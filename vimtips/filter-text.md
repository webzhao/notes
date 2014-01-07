# Filter text

**`:!command`** run an external command and show the result. Use `%` to pass the text to external command.

```
:! sort %
```

**`:r!command`**  insert the output of the external command in the current file.

### Sort lines:

To sort selected lines:

```
:'<,'> !sort
```

To sort the all lines of the file:

```
:%!sort
```

