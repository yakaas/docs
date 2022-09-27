## Emacs

### Navigation

- C-v : Jump forward one full screen.
- M-v : Jump backwards one full screen. ( If you dont have Meta key, use ESC key )
- C-l : Make the current line as center line of window.
- M-f : navigate a word forward.
- M-b : navigate a word backward.

#### paragraph
- M-a : Go to the beginning of the current paragraph. By pressing M-a again and again move to the previous paragraph beginnings.
- M-e : Go to the end of the current paragraph. By pressing M-e again and again move to the next paragraph end, and again.


## Neotree
### Shortcut (Only in Neotree Buffer)
- n next line ， p previous line。
- SPC or RET or TAB Open current item if it is a file. Fold/Unfold current item if it is a directory.
- U Go up a directory
- g Refresh
- A Maximize/Minimize the NeoTree Window
- H Toggle display hidden files
- C-c C-n Create a file or create a directory if filename ends with a ‘/’
- C-c C-d Delete a file or a directory.
- C-c C-r Rename a file or a directory.
- C-c C-c Change the root directory.
- C-c C-p Copy a file or a directory.

### Commands
- neotree-dir show NeoTree window and specify a directory as its root
- neotree-show or neotree show NeoTree window using current directory as its root
- neotree-hide Hide NeoTree window
- neotree-toggle toggle/hide NeoTree window
- neotree-find show NeoTree window and use the directory of current buffer as its root

### Commands available in the NeoTree window
- neotree-enter Open File / Unfold Directory
- neotree-refresh Refresh
- neotree-stretch-toggle Maximize / Minimize
- neotree-change-root Switch Root Directory
- neotree-hidden-file-toggle Toggle hidden files 
- neotree-rename-node Rename a Node
- neotree-delete-node Delete a Node
- neotree-create-node Create a file or a directory (if filename ends with ‘/’)
