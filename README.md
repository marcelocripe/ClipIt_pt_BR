Repositório oficial do programa "ClipIt"

https://github.com/CristianHenzel/ClipIt/


Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/ClipIt_pt_BR/blob/main/clipit_pt_BR.po

https://github.com/marcelocripe/ClipIt_pt_BR/blob/main/clipit.desktop


Para utilizar o arquivo "clipit_pt_BR.po" e o "clipit.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.


"clipit_pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt clipit_pt_BR.po -o clipit.mo

Comando para renomear o arquivo antigo da tradução com a extensão ".mo" que está na pasta do idioma "pt_BR".

$ sudo mv /usr/share/locale/pt_BR/LC_MESSAGES/clipit.mo /usr/share/locale/pt_BR/LC_MESSAGES/clipit_antigo.mo

Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp clipit.mo /usr/share/locale/pt_BR/LC_MESSAGES


"clipit.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp clipit.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global

