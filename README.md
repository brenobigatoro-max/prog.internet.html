# Programação para Internet I

Sou Breno Thiago Cardozo Bigatoro, estudante de Análise e Desenvolvimento de Sistemas no IFSC.
Neste repositório, reúno minhas atividades de Programação para Internet I, disciplina do professor Romulo Beninca.

**[Acessar minhas listas no GitHub Pages](https://brenobigatoro-max.github.io/prog.internet.html/)**

## Organização das listas

Organizei os exercícios em três pastas:

| Pasta | Conteúdo | Acesso |
| --- | --- | --- |
| `ppi1_lista1` | HTML, Internet, Web, HTTP, estados, currículo e contato | [Lista HTML](ppi1_lista1/index.html) |
| `ppi2_lista2` | CSS 1: seletores, especificidade, display, posições, bandeiras e animação | [Lista CSS 1](ppi2_lista2/index.html) |
| `pp3_lista3` | CSS 2: Flexbox, galeria, Grid e layouts responsivos | [Lista CSS 2](pp3_lista3/index.html) |

## Como abro e testo as páginas

Para acessar as atividades, posso abrir o arquivo `index.html` no navegador ou usar o Live Server do VS Code na pasta principal.
Também posso acessar a versão publicada no GitHub Pages pelo link acima.

Nos testes, confiro a navegação entre as páginas, as imagens e a animação do barco.
Na galeria, posso passar o mouse ou usar a tecla Tab para expandir as fotografias.
Para conferir a responsividade, redimensiono a janela do navegador: na lista 3, a atividade 4 muda até 700 pixels e a atividade 8 muda abaixo de 500 pixels.

Na lista de HTML, mantive os exemplos HTTP com a formatação de código. Por isso, esses trechos podem ultrapassar a largura de telas pequenas.

## Sobre os exercícios

- Na lista 1, reuni os conteúdos sobre a Web e o HTTP, além das páginas de estados, currículo e contato.
- Na lista 2, trabalhei com regras CSS, fontes, cores, especificidade, display, posicionamento e animações.
- Na lista 3, reuni os exercícios de Flexbox, Grid, transições e layouts responsivos.
- Mantive o formulário de contato e o chat como demonstrações. Eles não enviam mensagens.
- No exercício de perfil, usei o exemplo de Joana Barbosa apresentado no enunciado. Meu currículo está na lista 1.
- Nas bandeiras, usei apenas HTML e CSS. A bandeira do Brasil é uma representação simplificada para o exercício.
- Deixei os links do CSS Diner, Flexbox Froggy e Grid Garden nas páginas das listas para praticar os seletores e os layouts.
- Mantive a numeração do material que recebi, incluindo o salto da atividade 4 para a 6 na lista CSS 1.

## Imagens utilizadas

- Usei minha foto na página do currículo.
- Na página História da Web, deixei as fontes, os autores e as licenças junto às imagens.
- No perfil de exemplo, usei o retrato que aparece na referência do enunciado.
- Na animação do barco, usei um arquivo SVG local como `background-image`.
- Na galeria, incluí as fotografias na pasta de imagens e registrei os autores e os links de origem em [fontes-imagens.json](pp3_lista3/fontes-imagens.json).

## Como salvo minhas alterações no Git

Na pasta principal do projeto, uso os seguintes comandos:

```sh
git status
git add ppi1_lista1 ppi2_lista2 pp3_lista3 index.html README.md .nojekyll
git commit -m "Atualiza atividades de HTML e CSS"
git push origin main
```

Para manter o site publicado no GitHub Pages, uso a branch `main` e a pasta `/ (root)`.
Para entregar as atividades no Moodle, posso usar o link deste repositório ou da pasta solicitada pelo professor.
