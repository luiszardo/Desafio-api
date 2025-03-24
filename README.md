# Api Livros Doados VnW

Essa é uma API simples feita com flask e SqLite para fins de estudo na escola do Vai na Web, ela permite cadastrar e listar os livros doados.

## Como rodar o projeto?

1. Faça o clone do repositório
```bash
git clone <LINK_DO_REPOSITÓRIO>
cd nome_do_projeto
```
2. Criar um ambiente virtual (Obrigatório):
**Windos**
```bash
python -m venv venv
source venv/Scripts/activate
```
**Linux/Mac**
```bash
python3 -m venv venv
source venv/bin/activate
```
3. Instale as dependências:
```bash
pip install - requirement.txt
```
4. Inicie o servidor:
```bash
python app.py
```

> A API estará disponivel em http://127.0.0.1:5000/

## Endpoints

### POST /doar

Endpoint para cadastro das informações dos livros doados.

**Envio (JSON)**
```json
{
  "titulo":"Sniper Americano",
  "categoria":"Guerra",
  "autor":"Jim DeFelice,Scott McEwen",
  "image_url":"https://exemplo.com"
}
```