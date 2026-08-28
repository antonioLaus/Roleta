# 🎰 Roleta de Filmes

## Como usar

1. Abra o arquivo `index.html`.
2. As imagens dos filmes ficam dentro da pasta `res`.
3. Para adicionar um filme, abra o `index.html` e procure por:

const MOVIES = [
  { nome: "Senhor dos Anéis", imagem: "res/senhor-dos-aneis.jpg" },
  ...
];

4. Coloque a imagem dentro da pasta `res`.
5. Use o mesmo nome no código.

## Exemplo

Arquivo:

res/meu-filme.jpg

Código:

{ nome: "Meu Filme", imagem: "res/meu-filme.jpg" }

## Importante

Os arquivos precisam manter a estrutura das pastas.

Não mova o `index.html` para dentro da pasta `res`.

## Instalação como aplicativo

O projeto possui `manifest.json` e `sw.js`.

Para o PWA funcionar corretamente em celular, normalmente é necessário abrir o projeto através de um servidor HTTPS ou localhost.

Se estiver apenas testando no computador, pode abrir o `index.html` diretamente.
