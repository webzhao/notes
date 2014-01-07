# Editing Commands

| command | description
|---------|--------------------------------------------------------------------------------------------
| d       | delete the characters from the cursor position up the position given by the next command .
| dd      | delete current line.
| c       | change the characters from the cursor position up to the position indicated by the next command.
| cc      | change current line.
| o       | begin a new line **below** the cursor.
| O       | begin a new line **above** the cursor.
| a       | append text **after** the cursor.
| A       | append text **at the end of the line**.
| i       | insert text **before the cursor**.
| I       | insert text **at beginning of the line**.
| x       | delete the character **under the cursor**.
| X       | delete the character **before the cursor** (Backspace).
| y       | copy the characters from the current cursor position up to the position indicated by the next command.
| yy      | copy current line.
| p       | paste previous deleted or yanked (copied) text **after** the current cursor position.
| P       | paste previous deleted or yanked (copied) text **before** the current cursor position.
| r       | replace the current character with the newly typed one.
| s       | substitute the text from the current cursor position up to the position given by the next command with the newly typed one.
| .       | **repeat the last insertion or editing command (x,d,p…)**.
