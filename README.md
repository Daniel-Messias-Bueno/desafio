# Teste com API Trello

Plano de teste: Plano_de_Testes_V01.xlsx

Collection Postman: Trello_API.postman_collection.json
- Adicionar API Key, API Token e Secret na aba Authorization
- Type: OAuth 1.0 
- Add auth data to: Request Headers
- Environment: Trello.postman_environment.json

Automação:

- Linguagem: Java
- Frameworks: Junit e RestAssured
- Projeto Maven
- Para execução do teste será necessário informar o API Key e API Token na classe (src/test/java/TrelloAPITest - "TrelloAPITeste.java") e executar.

Você pode obter sua chave de API fazendo login no Trello e visitando https://trello.com/app-key 

Documentação utilizada para desenvolver o projeto: https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/
