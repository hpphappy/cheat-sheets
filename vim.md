### Useful VIM commands


#### To swtich between insert mode and command mode
From command mode to insert mode: type a/A/i/I/o/O (see details below)

`a` Append text following current cursor position

`i` Insert text before the current cursor position

`A` Append text to the end of current line

`I` Insert text at the beginning of the cursor line

`o` Open up a new line following the current line and add text there

`O` Open up a new line in front of the current line and add text there

From insert mode to command mode: type Esc or press the escape key

---
#### To show line number

```
:set number
```

#### To move cursor `in command mode`

##### Type 1

`h` Moves the cursor one character to the left

`l` Moves the cursor one character to the right

`k` Moves the cursor up one line

`j` Moves the cursor down one line


##### Type 2

`G` Go to the bottom of the file
`gg` Go to the top of the file 
`700G` Jump to line number 700 