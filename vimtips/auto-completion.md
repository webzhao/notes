# Auto completion in Vim

### Simple auto completion

* `Ctrl-N` to insert the next matching word;
* `Ctrl-P` to insert the previous matching word.

> You can use `tab` key to do auto completion with [supertab](https://github.com/ervandew/supertab) plugin.

### Omni completion

Omni completion provides smart autocompletion for programs. To enable omni completion:

1. `filetype plugin on`
2. `set omnifunc=syntaxcomplete#Complete`

To use omni completion, type `<C-X><C-O>` while open in Insert mode.


