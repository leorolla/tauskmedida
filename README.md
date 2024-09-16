# Notas Para o Curso de Medida e Integração

Autor: Daniel Tausk (IME-USP)

Para compilar o PDF:

    git clone https://github.com/leorolla/tauskmedida
    cd tauskmedida
    pdflatex NotasMedida
    pdflatex NotasMedida
    makeindex -o "simbolos.ind" "simbolos.idx"
    makeindex -o "indice.ind" "indice.idx"
    pdflatex NotasMedida
    makeindex -o "simbolos.ind" "simbolos.idx"
    makeindex -o "indice.ind" "indice.idx"
    pdflatex NotasMedida

Requisitos:

- TeXLive 2023 completo é suficiente, testado em Ubuntu 24.04. Talvez as duas primeiras instâncias do `pdflatex` sejam suficientes.

Para compilar o HTML:

    apt install git make latexml latexmk texlive-extra-utils preview-latex-style
    apt install texlive-full # overkill
    git clone https://github.com/leorolla/tauskmedida
    cd tauskmedida
    wget https://github.com/vlmantova/bookml/releases/download/v0.9.3/release.zip
    unzip release.zip
    cp bookml/GNUmakefile .
    make detect
    make pdf
    pdflatex NotasMedida
    make

Testado em Ubuntu 24.04. Para outros sitemas operacionais, instalar os pacotes necessários e começar da terceira linha, ou então instalar o Ubuntu em uma máquina virtual.

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Material disponibilizado sob a licença
[CC BY-SA 4.0][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg


