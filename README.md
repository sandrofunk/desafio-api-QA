# Desafio API QA

Este repositório contém a solução do desafio de QA, com foco em **testes de API utilizando Postman**. O objetivo é demonstrar habilidades em automação, validação de endpoints e boas práticas de testes.

## Tecnologias Utilizadas

- **Postman**: Para execução e automação dos testes de API.

## Estrutura do Projeto

- `Automacao_API.postman_collection.json` → Coleção com todos os endpoints e testes automatizados.  
- `desafio-api-QA.postman_environment.json` → Ambiente com variáveis utilizadas na coleção.  
- `README.md` → Manual de uso e documentação do projeto.

## Funcionalidades Testadas

### Login
- Realizar login com sucesso  
- Login com e-mail inválido  
- Login com e-mail em branco  
- Login com senha em branco  

### Usuários
- Cadastrar administrador com sucesso  
- Cadastrar usuário com e-mail já cadastrado  
- Buscar usuário por ID inexistente  
- Deletar usuário com produto no carrinho  

### Produtos
- Cadastrar produto com sucesso  
- Cadastrar produto com token inválido  
- Editar produto com nome já existente  
- Excluir produto que faça parte de algum carrinho  

### Carrinhos
- Cadastrar carrinho com sucesso  
- Concluir compra com sucesso  
- Concluir compra com token inválido  
- Cancelar compra com token inválido  

## Como Executar

1. Clone o repositório:

git clone https://github.com/sandrofunk/desafio-api-QA.git

2. Abra o Postman e importe os arquivos:

- Coleção: Automacao_API.postman_collection.json

- Ambiente: desafio-api-QA.postman_environment.json

3. Configure o ambiente ativo no Postman 

4. Selecione a Collection 

5. Clique com o botão direito e selecione e clique em Run

6. Para executar os testes clique em Run Automação API

Observações

Todos os testes estão organizados por funcionalidade e contemplam cenários positivos e negativos.

Variáveis do ambiente incluem tokens, IDs e URLs para facilitar a execução sem alterações manuais.

Autor

Sandro Gonçales Funk