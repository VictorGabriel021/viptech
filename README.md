Como executar o Projeto:

1 - Clone o projeto do seu computador.

2 - Execute o comando npm run start para executar o projeto.

Detalhes do Projeto:

1 - A Api https://dummyapi.io disponibiliza apenas 500 requisições por dia, caso gere o erro 429 tem duas opções para resolver:
  1.1 - Espere 24 horas para poder chamar as requisições.
  1.2 - No arquivo request.ts (caminho: src/core/utils/request.ts) basta trocar o APP_ID por um id válido(que pode ser gerado apenas se estiver logado no site da dummyapi).
  
