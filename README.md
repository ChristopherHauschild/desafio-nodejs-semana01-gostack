<div align="center">
  <img src="https://github.com/ChristopherHauschild/bootcamp-gostack-13-rocketseat/blob/master/gostack.png?raw=true">
</div> <br />

<div align="center">
  <img src="https://img.shields.io/static/v1?label=nodejs&message=backend&color=success&style=for-the-badge&logo=NODE.JS"/>
</div>

# <p align="center">Desafio - Conceitos Node.js</p>

:information_source: <i>Códigos desenvolvidos durante o desafio Conceitos Node.js, na primeira semana do Bootcamp GoStack 13, ofertado pela plataforma de ensino [Rocketseat](https://rocketseat.com.br/).</i>

<p align="justify">
Esse desafio tem como objetivo fixar os conhecimentos em Node.js aprendidos até o presente momento no Bootcamp. A mesma consiste numa aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".
</p>

## :twisted_rightwards_arrows: Rotas da aplicação:

<br />
- **`POST /repositories`**: A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: `{ id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }`; Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.

- **`GET /repositories`**: Rota que lista todos os repositórios;

- **`PUT /repositories/:id`**: A rota deve alterar apenas o `title`, a `url` e as `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /repositories/:id`**: A rota deve deletar o repositório com o `id` presente nos parâmetros da rota;

- **`POST /repositories/:id/like`**: A rota deve aumentar o número de likes do repositório específico escolhido através do `id` presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;
<br />

## :pushpin: Maiores informações:

Para encontrar maiores informações sobre o desafio, como por exemplo o template utilizado e a bateria de testes implementadas, você pode acessar este [link](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs).

<hr>

Códigos desenvolvidos por Christopher Hauschild Schott
