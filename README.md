<h3 align="center">
  Desafio: Conceitos do Node.js
</h3>

## Sobre o desafio

Nesse desafio, eu criei uma aplicação para treinar o que eu aprendi até agora no React Native!

É uma continuação do desenvolvimento da aplicação que irá armazenar repositórios do meu portfólio, que eu já desenvolvi o backend utilizando o Node.js, e no último desafio em ReactJS.

### Funcionalidades da aplicação

- **`Listar os repositórios da API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, a aplicação deve permitir que, ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.