# Text Objects

Vim commands operate on text-objects these are characters, words, characters delimited by parentheses, sentences and so on.

For me the most important one is the inner word: `iw`. To select the current word, just type `viw` (`v` for selection mode, and `iw` for the inner word), similar for deletion: `diw`.

The difference between inner-word/block and a-word/block etc is that the inner variant selects only the contents like the characters of the word (no blank afterwards) or the contents of the parentheses but not the parentheses. The a-variant selects the parentheses or a blank after a word too.

| text object   | description                |
|---------------|----------------------------|
| `iw`          | inner word                 |
| `aw`          | a word                     |
| `iW`          | inner WORD                 |
| `aW`          | a WORD                     |
| `is`          | inner sentence             |
| `as`          | a sentence                 |
| `ip`          | inner paragraph            |
| `ap`          | a paragraph                |
| `it`          | **inner xml tag**          |
| `at`          | **a xml tag**              |
| `i(` or `i)`  | inner parenthesized block  |
| `a(` or `a)`  | a parenthesized block      |
| `i<` or `ai>` | inner single tag           |
| `a<` or `ai>` | a single tag               |
| `i{` or `ai}` | inner brace block          |
| `a{` or `aa}` | a brace block              |
| `i"`          | inner double quoted string |
| `a"`          | a double quoted string     |
| `i\``         | inner back quoted string   |
| `a\``         | a back quoted string       |

### References

* [Vim Text Objects: The Definitive Guide](http://blog.carbonfive.com/2011/10/17/vim-text-objects-the-definitive-guide/)
