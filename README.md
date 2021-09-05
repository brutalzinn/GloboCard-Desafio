# Desafio Globo - Api GloboCard, Cli GloboCard e Interface Globo Card

> Todas as senhas expostas em variáveis de ambiente possuem tempo de validade.

## Api GloboCard

Esse projeto é uma API web desenvolvida com Python e MongoDB para ser utilizada na criação de cards e tags. Com objetivo de ser utilizada em conjunto com uma interface gráfica para a criação de Cards de conteúdo esportivos(Insights) para o desafio Globo. A descrição de todas as rotas pode ser encontrada ao iniciar em modo desenvolvedor.

A acessando a url(padrão) http://localhost:5000 diretamente no navegador ou [clicando aqui](https://api-globo-card.herokuapp.com/). 
É possível efetuar testes em cada rota e analisar cada uma especificamente.

Essa api está hospedada no Heroku e utilizando o método de deploy automático.

Você pode acessar e testar seu funcionamento em modo de produção [clicando aqui](https://api-globo-card.herokuapp.com/)

Você pode acessar o repositório original da Api GloboCard [clicando aqui](https://github.com/brutalzinn/api-globo-card-desafio)

## [Clique aqui para ler a documentação](api/README.md)

## Interface GloboCard

Esse projeto é uma interface gráfica desenvolvida com ReactJS e Material-UI para ser utilizada em conjunto com a Api GloboCard. Com objetivo de facilitar o processo de criação de Cards esportivos(Insights) para o desafio Globo. Sendo possível criar, deletar e atualizar e procurar Cards por Tags. Esse projeto está hospedado no Vercel e utilizando o método de deploy automático.

Você pode acessar esse projeto hospedado no Vercel em [clique aqui](https://interface-globo-card-desafio.vercel.app/). É necessário aguardar até que o Heroku(nuvem onde a api se encontra hospedada) responda.

Você pode acessar o repositório original da Interface GloboCard [clicando aqui](https://github.com/brutalzinn/interface-globo-card-desafio)


## [Clique aqui para ler a documentação](interface/README.md)

## CLI GloboCard 

Esse projeto é um CLI desenvolvido em Python para ser utilizado em conjunto com a Api GloboCard, e foi desenvolvido para o desafio Globo. Com objetivo de facilitar o processo de exportação de Cards esportivos(Insights) de um arquivo CSV para a API GloboCard. Sendo possível criar cards e suas respectivas tags em um único comando.

Você pode acessar o repositório original do CLI GloboCard [clicando aqui](https://github.com/brutalzinn/cli-globo-card-desafio)


## [Clique aqui para ler a documentação](cli/README.md)