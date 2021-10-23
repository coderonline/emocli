# emocli

A command line interface based unicode char table viewer, optimized for
emoticons and other pictographic symbols.

## Purpose

While the Unicode Consortium provides a PDF with all emoticons and special
symbols, it is not always desirable to install all necessary fonts on all
machines to support every symbol. Instead one may choose to only use existing
symbols in terminal applications like mutt, Vim or powerline. This script
helps to identify usable symbols and check terminal capabilities.


## How to make use of unicode symbols

```
printf  $ printf '\U1f600'
echo    $ echo -e '\U1f600'
HTML    $ &1f600;
Windows $ [ALT]+[x]1f600
Vim     $ i[C-v]U1f600[ESC]
ibus    $ [CTRL]+[SHIFT]+[u]1f600[space]
ibus    $ [CTRL]+[.] ??
```
