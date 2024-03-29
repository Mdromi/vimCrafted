# Neovim Commands Cheat Sheet

Neovim is a powerful and extensible text editor with various commands to navigate, edit, and manage text efficiently.

## Basic Navigation

- `h` - Move cursor left.
- `j` - Move cursor down.
- `k` - Move cursor up.
- `l` - Move cursor right.
- `w` - Move to the beginning of the next word.
- `b` - Move back to the beginning of the previous word.
- `$` - Move to the end of the line.
- `0` - Move to the beginning of the line.
- `gg` - Move to the beginning of the file.
- `G` - Move to the end of the file.
- `:line_number` - Move to a specific line number (replace `line_number` with the desired line number).
- `%` - Jump between matching parentheses, brackets, and braces.
- `*` - Search for the word under the cursor.
- `#` - Search backward for the word under the cursor.

## File

- `a` -> In file tree for creating new file
- `c` -> In file tree for coping file
- `p` -> In file tree for pasting file
- `r` -> In file tree for renaming file

## Copy, Cut, and Paste

- `p` - Paste after the cursor.
- `P` - Paste before the cursor.

## Folding

- `zf` - Create a fold (select text and type `zf` to fold).
- `zo` - Open a fold.
- `zc` - Close a fold.

## Editing Text

- `x` - Delete the character under the cursor.
- `dd` - Delete the entire line.
- `p` - Paste the deleted or yanked text after the cursor.
- `yy` - Yank (copy) the current line.
- `yw` - Yank (copy) from the cursor position to the beginning of the next word.

## Searching and Replacing

- `/` - Start a forward search. Type the search pattern and press Enter.
- `?` - Start a backward search. Type the search pattern and press Enter.
- `n` - Go to the next occurrence of the search pattern.
- `N` - Go to the previous occurrence of the search pattern.
- `:s/search/replace/g` - Replace occurrences of "search" with "replace" in the entire file.

## Saving and Quitting

- `:w` - Save changes.
- `:q` - Quit Neovim.
- `:wq` - Save and quit.
- `:q!` - Quit without saving.


## NvChad

- `SPACE + t + h` -> For changing theme
- `:TSInstall <language name>` -> For installing syntax highlighting for specific language
- `:TSInstallInfo` -> For listing all the languages for syntax highlighting
- `CONTROL(^) + n` -> For opening file tree
- `SPACE + f + f` -> For opening find file menu
- `SPACE + f + b` -> For opening buffer find file menu
- `SPACE + c + h` -> For opening NvChad cheat sheet
- `SPACE` -> For opening quick cheat sheet
- `:VSP` -> For opening vertical split window
- `SPACE + n` -> For toggling absolute line number
- `SPACE + r + n` -> For toggling relative line number
- `TAB` -> For switching opens buffer files
- `SHIFT + TAB` -> For reverse switching opens buffer files
- `SPACE + x` -> For closing buffer file
- `SPACE + e` -> For going file tree to open file
- `SPACE + h` -> For opening terminal
- `SPACE + f + m` -> For formatting the code

## Modes

- `i` - Enter insert mode (for inserting text).
- `Esc` - Return to normal mode.

## Spell

- `z + =` -> for correct answer suggestion
- `[ + s` -> for go up to wrong spelling worlds
- `] + s` -> for go down to wrong spelling worlds
- `:spellr` -> fix all occurrence wrong spelling
- `z + g` -> for adding a wrong world the spell dict

## Mason

- `:MasonInstallAll` -> For installing dependencies

## Treesitter

- `:TSInstall <language_to_install>` -> For installing syntax highlighting

## Split Windows

- `:split` - Split the window horizontally.
- `:vsplit` - Split the window vertically.
- `Ctrl + w` + `h`, `j`, `k`, `l` - Navigate between windows.

## Tabs

- `:tabnew` - Open a new tab.
- `gt` - Switch to the next tab.
- `gT` - Switch to the previous tab.
- `:tabclose` - Close the current tab.

## Undo and Redo

- `u` - Undo the last change.
- `Ctrl + r` - Redo.

## File Explorer

- `:Explore` - Open the file explorer.
- `:Vexplore` - Open the file explorer in a vertical split.
- `:Sexplore` - Open the file explorer in a horizontal split.

## Visual Mode and Selection

- `v` - Enter visual mode to select characters.
- `V` - Enter visual line mode to select entire lines.
- `Ctrl + v` - Enter visual block mode to select a block of text.


## Tabs and Buffers

- `:e file_path` - Open a file in a new buffer.
- `:bnext` - Switch to the next buffer.
- `:bprev` - Switch to the previous buffer.
- `:bd` - Close the current buffer.

## Autocomplete and Suggestions

- `Ctrl + n` - Autocomplete based on words in the current and included files.
- `Ctrl + x` + `Ctrl + f` - Autocomplete based on filenames.

## Search and Replace

- `:vimgrep /pattern/ **/*.ext` - Search for a pattern in all files with a specific extension.
- `:copen` - Open the quickfix window to see search results.

## Git Integration (requires Git installed)

- `:Gstatus` - Open the Git status window.
- `:Gwrite` - Stage changes in the current file.
- `:Gcommit` - Commit changes.
- `:Gpull` - Pull changes from the remote repository.

## Terminal

- `:term` - Open a terminal window within Neovim.
- `Ctrl + w` + `:q` - Close the terminal window.

Feel free to explore Neovim's extensive features and customize your setup for a personalized editing experience.
