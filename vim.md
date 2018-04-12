# VIM

Vim is just a text editor

## QuickStart

- `:q` - To quit
- `:w` - Write out current content
- `:w new.txt` - Write current content to the file world.txt while keeping current file as the opened buffer in vim.
- `:sav new.txt` - Will first write current  content to the file current file, then close buffer, finally open new.txt as the current buffer.

## Copy, cut and paste

1. Position the cursor where you want to begin cutting.
2. Press `v` to select characters, or uppercase `V` to select whole lines, or `Ctrl-v` to select rectangular blocks (use `Ctrl-q` if `Ctrl-v` is mapped to paste).
3. Move the cursor to the end of what you want to cut.
4. Press `d` to cut (or `y` to copy).
5. Move to where you would like to paste.
6. Press `P` to paste before the cursor, or `p` to paste after.

- `d` stands for delete in Vim, which in other editors is usually called cut
- `y` stands for yank in Vim, which in other editors is usually called copy

## Undo and redo

- `u` - undo last change (can be repeated to undo preceding commands) 
- `Ctrl-R` - Redo changes which were undone (undo the undos). Compare to . to repeat a previous change, at the current cursor position. `Ctrl-R` (hold down Ctrl and press r) will redo a previously undone change, wherever the change occurred.

## Reload

- `:edit` - to reload the current file. 
- `:edit!` - to force the reload of the current file (you will lose your modifications).

## Word movement

- `w` - moves to the start of next word
- `e` - moves to end of next word
- `b` - moves to beginning of the word
