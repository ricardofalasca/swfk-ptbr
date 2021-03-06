# Livro Domando Serpentes para Crianças

"Domando Serpentes para Crianças" é um livro eletrônico que pode ser impresso, para crianças de 8 anos em diante que querem aprender a programar. Os conceitos básicos da programação são abrangidos usando a linguagem de programação Python 3.

Existem 3 versões diferentes do livro (uma para Mac, uma para Linux e outra para Windows). Com mais de 50.000 downloads, desde Setembro de 2009.

## O código fonte do livro

O código fonte do livro "Domando Serpentes para Crianças" está em LaTeX.

Este trabalho está sobre a licença [Creative Commons Attribution-Noncommercial-Share Alike 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/br/).

A versão original foi escrita por Jason R Briggs, em inglês e pode ser encontrada em http://code.google.com/p/swfk/

## Como contribuir?

### Processo de tradução

* **Fork**  
Use a sua versão do projeto para fazer as alterações
* **Escolha um capítulo**  
Altere o README, marcando o capítulo que você vai traduzir, adicionando "em andamento" (igual ao rodapé)
* **Informe a sua escolha**  
Faça um "Pull Request" com essa alteração
* **Traduza**  
Deve ser feito apenas 1 commit por página traduzida, seguindo a mensagem padrão: "Traduzido capítulo X página Y".  
Isso facilitará o processo de revisão.

### Processo de revisão

Nenhuma revisão deve ser feita até que o processo de tradução esteja finalizado.

## Compilando o livro a partir do código fonte

### Linux

Você vai precisar do `latex` e do `dvipdf` instalado. O nome dos pacotes pode variar entre as distribuições Linux.

### Mac

No Mac, nós recomendamos que você use o [BasicTeX](http://www.tug.org/mactex/morepackages.html) caso não tenha o [MacTeX](http://tug.org/mactex/) instalado, pois ele é muito mais leve.

Logo depois de instalar, você precisa executar os seguintes comandos, **antes** de compilar:

    sudo tlmgr update --self
    sudo tlmgr install textpos wrapfig

### Compilando

Execute o seguinte comando para compilar:

    python setup.py build

Andamento do trabalho
=====================

* Capa (frontmatter.tex)
* Prefácio (preface.tex) **- pendente de revisão**
* Capítulo 1 (ch1.tex) **- pendente de revisão**
* Capítulo 2 (ch2.tex) **- em andamento**
* Capítulo 3 (ch2.tex)
* Capítulo 4 (ch4.tex)
* Capítulo 5 (ch5.tex)
* Capítulo 6 (ch6.tex)
* Capítulo 7 (ch7.tex)
* Capítulo 8 (ch8.tex)
* Capítulo 9 (ch9.tex)
* Capítulo 10 (ch10.tex)
* Apêndice A (appendixa.tex)
* Apêndice B (appendixb.tex)
* Apêndice C (appendixc.tex)
* Apêndice D (appendixd.tex)
