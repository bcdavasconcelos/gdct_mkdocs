
## O problema

A pesquisa em filosofia antiga enfrenta alguns desafios peculiares. Nós lidamos com um volume enorme de fontes primária e secundária, acumulados ao longo de 1500-2000 anos de reflexão e exegese. Não bastasse a extensão da bibliografia, a existência de diversos conjuntos de regras para fazer referência a essas fontes demanda de nós um esforço de conciliação e faz com que os trabalhos na área sejam propensos a erros e à necessidade de adaptações e correções. Mesmo quando extremamente bem-feitos, trabalhos podem demandar adaptações significativas — e.g. por ocasião da submissão de um artigo ou livro, sobretudo internacionalmente, é quase certo que teremos de modificar o padrão das referências bibliográficas e conforma-lo a um sistema diferente. Como a maior parte de nós guarda seus registros bibliográficos em forma de lista em um documento de texto qualquer, isso significa que a cada vez que uma adaptação for necessária, seremos obrigados a dedicar várias horas para executar um trabalho manual de baixo-valor.

- MENN, S.; “Aristotle’s Definition of Soul and the Programme of the De Anima”. *In*: **Oxford Studies in Ancient Philosophy**, v. 22, 2002. pp. 83-139
- POLANSKY, Ronald. **Aristotle’s De Anima**. Cambridge: Uni Press, 2007
- NUSSBAUM, Martha Craven & RORTY, Amélie Oksenberg. **Essays on Aristotle’s De anima**. Oxford: Clarendon Press, 1992
- HENRY, D. & NIELSEN, K. M. (eds.). **Bridging the Gap between Aristotle’s Science and Ethics**. Cambridge: Cambridge University Press, 2015
- ARISTOTELES. **De Anima**. Trad.: THEILER, W. & SEIDL, H. Hamburg: Felix Meiner, 1995
- ARISTÓTELES. **De Anima**. Ed.: ROSS, W. D. Oxford: Clarendon Press, 1961

 Para além destes desafios específicos, há ainda aqueles comuns a todas as demais áreas, como o tempo perdido a cada vez que precisamos localizar uma referência anotada em algum pedaço de papel ou em algum arquivo isolado qualquer; ou a dificuldade de assegurar que todas as fontes citadas no corpo do texto estejam presentes na bibliografia final do trabalho.

## A solução

As ferramentas concebidas para resolverem esses e outros problemas chamamos de **gerenciadores bibliográficos**. Há muito o que dizer sobre eles e sobre a sua utilidade, pois esses programas podem servir como uma espécie de hub para toda a nossa pesquisa. Os dados ficam estruturado e prontos para formarem referências em qualquer formato e serem pesquisados com precisão utilizando inúmeros critérios, ao mesmo tempo em que nos conectam com as nossas anotações e com os arquivos correspondentes. Para cada entrada, o programa sabe quem é o autor, editor ou tradutor; qual é o título da obra; de que tipo é a referência (livro, artigo, etc.):

| ID | Tipo | Autor(a) | Título | Editor(a) | Tradutor(a) | Journal | Volume | Págs | Ano | Editora | Lugar | Citekey |
|----|----|----|----|----|----|----|----|----|----|----|----|----|
| 78816 | Journal article | Menn, Stephen | Aristotle's Definition of Soul and the Programme of the De Anima | | | Oxford Studies in Ancient Philosophy | 22 | 83-139 | 2002 | | | Menn2002 |
| 10104 | Book | Polansky, Ronald | Aristotle's De Anima | | | | | | 2007 | Uni Press | Cambridge | Polansky2007a |
| 55711 | Book | Nussbaum, Martha CravenRorty, Amélie Oksenberg | Essays on Aristotle's De anima | | | | | | 1992 | Clarendon Press | Oxford | Nussbaum1992 |
| 99531 | Edited book | | Bridging the Gap between Aristotle's Science and Ethics | Henry, DevinNielsen, Karen Margrethe | | | | 316 | 2015 | Cambridge University Press | Cambridge | Henry2015 |
| 22323 | Trans Book | Aristoteles | De Anima | | Theiler, W.Seidl, H. | | | | 1995 | Felix Meiner | Hamburg | DA\_Theiler |
| 44738 | Ed. Crítica | Aristóteles | De Anima | Ross, W. D. | | | | 402a1-435b25 | 1961 | Clarendon Press | Oxford | DA_Ross |

Como o programa sabe onde encontrar cada dado, ele precisa apenas de instruções sobre como montar as referências:

| ABNT | APA |
| -------- | ------- |
| (SOBRENOME ano) | (Sobrenome, ano) |
| SOBRENOME, Nome. Título. Editores/as (ed.). Trad.: Tradutores/as. Cidade: editora, ano. | Sobrenome, Nome (Ano) Título. (Nome e sobrenome, Trans.) Cidade: editora. |

O modo mais comum de representar as regras de construção das referências é utilizando um arquivo no formato CSL (Citation Style Language). Há dezenas de milhares de arquivos disponíveis adaptados às mais diversas necessidades. Recentemente, acrescentei mais um arquivo à lista com um [um estilo que preparei](ABNT-Phi.md) para suprir as demandas específicas das áreas de estudos clássicos e filosofia antiga. Esse estilo contempla, dentre outras coisas, a necessidade de utilizar os nomes dos editores/as e tradutores/as nas citações em linha.

## Resumo da opéra

Gerenciadores cumprem, então, ao menos dois papeis importantes:

- O primeiro diz respeito à organização em geral. Com eles, fica muito simples encontrar a referência que precisamos *quando precisamos*, pois é possível filtra-las a partir de diversos critérios arbitrários, como autores(as), editores(as), tradutores(as), editora, palavras-chave, coleção, etc. Durante o processo de escrita, passa a ser possível apenas evocar um atalho para buscar em todo o banco de dados pela referência que precisamos — por oposição a simplesmente deixar um espaço vazio com os dizeres "inserir referência aqui" ou interromper o processo para dar início a uma caçada que pode levar horas.
- O segundo diz respeito à completude dos textos que escrevemos. Os gerenciadores podem "escanear" as citações no texto para gerar a bibliografia automaticamente. Não elimina a tarefa de conferir, mas reduz bastante as chances de que alguma referência seja esquecida.

## Indicações

Eis alguns gerenciadores de bibliografia que você pode experimentar:

- [Bookends](Bookends.md) ()
    - [Scripts para o Bookends](Scripts%20para%20o%20Bookends.md)
- [Zotero](https://www.zotero.org) (Win, Mac & Linux)
- [Mendeley](https://www.mendeley.com)
- [JabRef](http://jabref.sourceforge.net) (Win & Mac)
- [BibDesk](https://bibdesk.sourceforge.io) ()
- [Wikindx](https://wikindx.sourceforge.io)

## Outras referências úteis

- [ABNT-Phi](https://github.com/bcdavasconcelos/ABNT-Phi) é um estilo CSL (*Citation Style Language*) adaptado para facilitar o trabalho com autores/as e fontes antigas. Funciona com o Pandoc e com o Zotero.
- ⚡️ [Anystyle.io](https://anystyle.io) *Para gerar um arquivo bibtex a partir da sua bibliografia ou convertê-la em outro sistema (APA, ABNT, etc).*
- 🔍 [Ottobib](http://www.ottobib.com) *Encontre referências a partir do ISBN.*
- [PDF Grep](https://pdfgrep.org/index.html) Ferramenta para linha de comando que permite fazer buscas em (qualquer número de) PDFs usando [RegEx](RegEx.md).
- [Zotero-love-letter](https://jonathanstill.com/2021/03/04/zotero-love-letter/)
