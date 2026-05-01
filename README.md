# Instalação

1. Instale o LaTeX no seu computador com `apt install texlive-full`

# Compilação

Gere o arquivo PDF com `latexmk -pdf tcc.tex`

Limpe os arquivos temporários com `latexmk -c`

# Uso

Para adicionar citações, primeiramente edite o arquivo `referencias.bib` 

`tcc.text` é o arquivo de entrada do PDF

Altere o conteúdo do TCC editando os arquivos da pasta `content/`

Arquivos de média, como imagens, ficam na pasta `media/`

# Extensões

`.tex`: o conteúdo de fato

`.lof`: lista de figuras

`.lol`: lista de códigos

`.lot`: lista de tabelas

`.loq`: lista de quadros

`.sty`, `.bst`: estilização

`.bib`: referências e configurações

`.aux`: criado durante a compilação

`.cls`: layout do documento

`.bbl`: referências compiladas

`.blg`: log

`.toc`: sumário

`.log`: log de compilação
