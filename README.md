<h1 align="center">
  <img src=".assets/logo-gostack.svg" atl="GoStack Bootcamp" />
</h1>

<h3 align="center">
  Desafio 4: Conceitos do React Native
</h3>

<p align="center">
  Desafio desenvolvido durante o <a href="https://rocketseat.com.br/gostack">Bootcamp GoStack</a> da Rocketseat.
  <br />
  <br />
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#instalação-e-execução">Instalação e execução</a>
</p>

## Tecnologias

- [React Native](http://reactnative.dev/)
- [Axios](https://github.com/axios/axios)
- [Axios Mock-Adapter](https://github.com/ctimmerm/axios-mock-adapter)

## Sobre o desafio

Nesse desafio, eu criei uma aplicação para treinar o que eu aprendi até agora no React Native!

É uma continuação do desenvolvimento da aplicação que irá armazenar repositórios do meu portfólio, que eu já desenvolvi o backend utilizando o Node.js, e no último desafio em ReactJS.

### Funcionalidades da aplicação

- **`Listar os repositórios da API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, a aplicação deve permitir que, ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

## Instalação e execução

```bash
# Clone esse repositório
$ git clone https://github.com/adeonir/gostack-conceitos-react-native conceitos-react-native

# Entre no diretório
$ cd conceitos-react-native

# Instale as dependências
$ yarn

# Em caso de emulação no iOS
$ cd ios && pod install

# Rode a aplicação no iOS
$ yarn ios

# Rode a aplicação no Android
$ yarn android

# Rode os testes
$ yarn test
```

## Licença

Esse projeto está sob a licença MIT.

---

Made with ♥️ by Adeonir Kohl