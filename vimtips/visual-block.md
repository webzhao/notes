# Visual Block

Using the visual block-mode it's possible to insert characters on each line of the selection easily.

Suppose you have selected a rectangle (using `Ctrl-v`), you can insert text in front of it by typing `I` (switch to insert mode) and inserting your text. As soon as you leave the insert mode, the text will be added to all the other selected lines. Use `A` to enter text after the selection.

Another useful feature is to substitute the whole block with a new text. For that matter select a block and type `s`, Vim enters the insert mode and you can type. After you leave the insert mode, Vim inserts the text in the remaining lines.

If you'd like to append some text at the end of some lines, use `Ctrl-v $` and select the lines. The difference between the former variant is, that the `$` explicitly says "end of line" whereas a selection with `Ctrl-v` operates on the columns, ignoring the text.

Using `Ctrl-v`:

    This is a testNEWLY INSERTED
    This is a     NEWLY INSERTED
    This is       NEWLY INSERTED

Using `Ctrl-v $`:

    This is a testNEWLY INSERTED
    This is aNEWLY INSERTED
    This isNEWLY INSERTED
