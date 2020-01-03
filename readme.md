## Sobre ##

[The Little Go Book](http://openmymind.net/The-Little-Go-Book/) é um livro gratuito de introdução à linguagem Go.

O livro foi escrito por [Karl Seguin](http://openmymind.net), autor de:

* [Scaling Viki](http://openmymind.net/scaling-viki/)
* [The Little Redis Book](http://openmymind.net/2012/1/23/The-Little-Redis-Book/)
* [The Little MongoDB Book](http://openmymind.net/2011/3/28/The-Little-MongoDB-Book/)
* [Foundations of Programming](http://openmymind.net/FoundationsOfProgramming.pdf)

## Licença ##

Este livro está distribuido gratuitamente através da licença [Attribution-NonCommercial-ShareAlike 4.0 International](<http://creativecommons.org/licenses/by-nc-sa/4.0/>).

## Traduções ##

* [Spanish](https://github.com/raulexposito/the-little-go-book/tree/master/es) by Raúl Expósito
* [Chinese](https://github.com/songleo/the-little-go-book_ZH_CN) by Songleo
* [Traditional Chinese](https://github.com/kevingo/the-little-go-book) by KevinGo
* [Vietnamese](https://github.com/quangnh89/the-little-go-book/blob/master/vi/readme.md) by Quang Nguyễn
* [Italian](https://github.com/francescomalatesta/the-little-go-book-ita) by Francesco Malatesta
* [Russian](https://github.com/sefus/the-little-go-book/blob/master/ru/go.md) by Roman Dolgopolov
* [German](https://github.com/Aaronmacaron/the-little-go-book-de/blob/master/de/go.md) (15% done) by Aaron
* [Amharic](https://github.com/codeethiopia/the-little-go-book-amharic) by codeethiopia
* [Korean](https://github.com/shoebillk/the-little-go-book/blob/master/ko/go.md) by Byounghoon Kim
* [Burmese](https://github.com/nainglinaung/the-little-go-book/blob/master/mm/go.md) By Naing Lin Aung

## Formatos ##

Este livro está escrito em [Markdown](http://daringfireball.net/projects/markdown/) e convertido para PDF utilizando [Pandoc](http://johnmacfarlane.net/pandoc/).

O template TeX usa [Lena Herrmann's JavaScript highlighter](http://lenaherrmann.net/2010/05/20/javascript-syntax-highlighting-in-the-latex-listings-package).

Também disponível nos formatos Kindle and ePub via [Pandoc](http://johnmacfarlane.net/pandoc/).

## Gerando os livros ##

Os pacotes listados abaixo são para Ubuntu. Se você utiliza outro sistema operacional ou distro os nomes devem ser similares.

### PDF

#### Dependências

Pacotes:

* `pandoc`
* `texlive-xetex`
* `texlive-latex-extra`
* `texlive-latex-recommended`

Você deve ter instaladas [algumas fontes](https://github.com/karlseguin/the-little-redis-book/blob/master/common/pdf-template.tex#L11) também.
Ou você pode mudá-las para outras que queira. Considere que [algumas fontes  podem causar problemas ao compilar o livro](https://github.com/karlseguin/the-little-redis-book/issues/26).

#### Compilando

Execute o comando `make en/go.pdf`.

### ePub

#### Dependencies

Packages:

* `pandoc`

#### Building

Run `make en/go.epub`.

### Mobi

#### Dependencies

Packages:

* `pandoc`

You should have [KindleGen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211) installed too.

#### Building

Run `make en/go.mobi`.

## Title Image ##
A PSD of the title image is included. The font used is [Comfortaa](http://www.dafont.com/comfortaa.font).
