# Challenge Full-stack - Mega Conecta #

## Desafio ##
O objetivo desse desafio é desenvolver uma aplicação de perguntas e respostas, tal como fóruns da internet, Reddit, etc.
Nela será possível navegar pelas perguntas, criar uma nova, consultar as respostas feitas pela comunidade ou até mesmo responder a uma pergunta.
Você será responsável pelo desenvolvimento tanto do back-end como do front-end. Sinta-se à vontade para usar a linguagem que se sinta mais confortável e frameworks que desejar.


## Requisitos ##
* Em sua tela inicial, a aplicação deverá listar todas as perguntas já registradas na plataforma;
* A listagem deverá exibir o conteúdo da pergunta e o número de respostas de cada pergunta;
* Na própria tela inicial, deve haver um formulário onde seja possível inserir uma nova pergunta;
* Ao inserir uma pergunta, a listagem da tela inicial deve ser atualizada com os novos dados inseridos;
* Deve existir um componente clicável em cada uma das perguntas que leve a uma segunda tela;
* Nesta segunda tela, deverá ser exibida uma única pergunta com todas suas respostas;
* Nesta mesma tela, deve haver um formulário onde seja possível inserir uma resposta à pergunta em evidência;
* Ao inserir uma resposta, a listagem de comentários deve ser atualizada com a nova resposta enviada;
* Deve haver um botão de navegação em que seja possível voltar da segunda tela para a tela inicial;
* É desejável que todos esses dados sejam persistidos, ou seja, caso o navegador seja atualizado, eles devem continuar sendo exibidos.

## Modelos e Entidades ##
Tenha em mente a seguinte estrutura de dados:
```json
{
  "id": 123,
  "text": "My question",
  "user": "username",
  "creationDate": "2020-01-01 12:00:00",
  "answers": [
    {
	  "id": 1234,
	  "text": "My answer",
	  "user": "another.username",
	  "creationDate": "2020-01-01 12:00:00"
	}
  ]
}
```
Porém, não se limite a ela e estruture suas entidades da maneira que preferir.

## Considerações ##
* Evite a utilização de frameworks "faz tudo", como o Prisma, para que possamos avaliar melhor sua lógica, arquitetura e aplicação de padrões de projeto;
* A transição entre uma tela e outra pode ser feita por meio de rotas ou apenas usando a mudança de estado na aplicação;
* Leve em consideração que sua aplicação back-end poderá reaproveitada por outros produtos, como aplicativos mobile, então é fundamental que haja uma API REST ou GraphQL;
* Não se apegue a questões de login ou controle de usuário;
* Escreva teste unitários;
* Implemente uma aplicação em que você se orgulhe de mostrar o código para os outros. Ela é seu cartão de visitas.

## Como entregar sua solução ##
* Divida sua aplicação em dois diretórios, um voltado para o back-end e outro para o front-end;
* Dentro desses diretórios, organize-se da maneira que preferir;
* Crie um README.md explicando como executar sua aplicação no ambiente local;
* Inclua a documentação de sua API, caso tenha optado por usar REST. Pode ser no README.md ou usando coleções do Postman;
* Nos envie tudo em um arquivo compactado ou crie algum repositório, como GitHub, Bitbucket, GitLab, etc.

## Bônus ##
* Um botão de like, onde seja possível reagir a uma pergunta ou resposta;
* Campo de busca, filtrando pelo conteúdo das perguntas;
* Opção de filtrar somente questões que não foram respondidas;
* Ordenação das perguntas e respostas por data de criação ou número de curtidas;
* Fazer uso do Docker.

## Dúvidas? ##
Entre em contato e nos questione. É nosso desejo que você venha ser **Mega**.
