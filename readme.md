some notes learning nvim

# Setup
install nvim and install nvchad (https://nvchad.com/quickstart/install#linux--macos-unix).

# Default `:tutor`
Open nvim and command mode enter `:tutor`

## basic navigating
- once you learn touch typing, you'll really appreciate hjkl keys for moving the cursor.
- `a` for appending the text, `x` for deleting the current char under cursor
- `dw` to delete the word and `d$` to delete till the end of the sentence
- `e` jumps word by word keeping the cursor at the end of the word, `w` keeping the cursor at the beg of the word.
- `0` and `^` moves to the beg of the line. `$` is end of the line.
- `dd` deletes whole line `4dd` deletes 4 lines.
- `u` undo a single command, `U` restore a line to original state | <ctrl+r> to redo OR `:redo`

# mason.nvim
mason is the package manger for nvim.

`:Mason` and search for your language server of interest.
	nvim has easy ability via Mason to install different LSP.

Mason provides easy installs for 
- LSP (Language server protocol)
- DAP (debug adapter)
- Linter
- Formatter

Example - installing `bash lsp` ![Pasted image 20230226105646.png](./Pasted%20image%2020230226105646.png)

# nvimtree
NVimTree plugin is used for enabling the side pane file explorer. Shortcut - `ctrl+n`

