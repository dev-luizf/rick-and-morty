
# Rick and Morty Characters

Este projeto é um app que consome uma API pública baseada no universo de Rick and Morty, nele o usuário pode visualizar uma lista com algumas informações dos personagens da série, podendo clicar em um dos cards para visualizar mais detalhes ou filtrar a lista com base em gênero, nome, status e espécie.

**Link do deploy:** https://my-rick-and-morty-app.vercel.app
**Vídeo demonstrativo:** https://youtu.be/Czs4AtAGHdw

## Tecnologias e ferramentas:

 - React (Vite)
 - TypeScript
 - Tailwind
 - Material UI
 - Axios
 - React Router Dom
 - Git Commit Msg Linter
 - Docker

## Como rodar o projeto:

Para rodar o app, você precisará ter o  [Docker](https://www.docker.com/)  instalado na sua máquina. Se preferir, também é possível rodar a aplicação sem ele, basta seguir as instruções na seção "Rodando sem Docker".

1.  Clone o repositório:

`git clone https://github.com/dev-luizf/rick-and-morty-chars.git`

2.  Entre na pasta do projeto:

`cd rick-and-morty-chars`

3.  Rode o Docker Compose:

`npm run compose:up`

4.  Acesse a aplicação em  `http://localhost:3000`.

## Rodando sem Docker

Se você preferir não utilizar o Docker, siga as instruções abaixo.

1.  Clone o repositório:

`git clone https://github.com/dev-luizf/rick-and-morty-chars.git`

2.  Entre na pasta do projeto:

`cd rick-and-morty-chars`

3.  Instale as dependências:

`npm install`

4.  Inicie o servidor:

`npm run dev`

5.  Acesse a API em  `http://localhost:3000`.


