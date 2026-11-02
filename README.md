# Programação para Internet I

Atividades acadêmicas de Breno Thiago Cardozo Bigatoro — ADS / IFSC.
Professor: Romulo Beninca.

**[Abrir as listas publicadas](https://brenobigatoro-max.github.io/prog.internet.html/)**

| Pasta | Conteúdo | Acesso |
| --- | --- | --- |
| `ppi1_lista1` | HTML, Internet, Web, HTTP, estados, currículo e contato | [Lista HTML](ppi1_lista1/index.html) |
| `ppi2_lista2` | CSS 1: seletores, especificidade, display, posições, bandeiras e animação | [Lista CSS 1](ppi2_lista2/index.html) |
| `pp3_lista3` | CSS 2: Flexbox, galeria, Grid e layouts responsivos | [Lista CSS 2](pp3_lista3/index.html) |

## Como testar

Abra `index.html` no navegador e escolha uma lista, ou use o Live Server do VS Code
na pasta principal. Confira os links, as fotografias e a animação do barco.
Na lista de HTML, os exemplos HTTP preservam a formatação de código e podem exceder
a largura de telas pequenas.
Use Tab na galeria e redimensione a janela para observar as mudanças dos layouts.
A composição da atividade 8 da lista 3 muda abaixo de 500 pixels; a atividade 4 muda até 700 pixels.

## Observações das atividades

- O formulário de contato e o chat são demonstrações visuais e não enviam mensagens.
- O perfil de Joana Barbosa reproduz o exemplo do enunciado; não é o currículo do autor.
- As bandeiras usam apenas HTML e CSS; a do Brasil é uma representação didática simplificada.
- Os jogos CSS Diner, Flexbox Froggy e Grid Garden exigem participação do estudante.
  A presença dos links não comprova a conclusão dos jogos.
- A numeração das atividades acompanha o material recebido; não foi fornecida uma atividade 5 da lista CSS 1.

## Imagens

- A foto do currículo é do autor.
- As imagens históricas têm fonte, autoria e licença junto às figuras na página História da Web.
- O retrato do perfil é um recorte visual do exemplo do enunciado, usado para a atividade acadêmica.
- O barco é um desenho SVG local usado como `background-image` na atividade 10.
- As fotografias da galeria estão no repositório; autores e links de origem:
  [fontes-imagens.json](pp3_lista3/fontes-imagens.json).

## Salvar alterações no Git

Na pasta principal do projeto:

```sh
git status
git add ppi1_lista1 ppi2_lista2 pp3_lista3 index.html README.md .nojekyll
git commit -m "Atualiza atividades de HTML e CSS"
git push origin main
```

Para publicar no GitHub Pages, a origem é a branch `main`, pasta `/ (root)`.
Para a entrega no Moodle, use o link do repositório ou da pasta solicitada pelo professor.
