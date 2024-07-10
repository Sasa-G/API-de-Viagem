# API De Viagens
API desenvolvida durante o NLW Journey de C#

Diagrama das bibliotecas que compõe o projeto para a construção da API

 <img src="https://github.com/Sasa-G/API-de-Viagem/assets/142459272/0f1ca149-5165-4016-80ed-42eef66bdeee" alt="">



- API Project - É o ponto de entrada, quando tivermos o usuário utilizando o app ou site e fizer uma requisição, essa requisição será recebida pelo API Project, que recebe e devolve chamadas.

- Application Project - Após o API Project receber uma requisição, ele passa para o Application Project, que é responsável por conter as regras de negócio, como validação de viagem, deletar viagem e outros.

- Infrastructure Project - Nesse projeto, há a classe Repository, que se conecta ao banco de dados (SQLite).

- Communication Project - Responsável por conter apenas as classes de respostas e requisições.

- Exception Project - Onde colocamos nossas próprias exceptions
