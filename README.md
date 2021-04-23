# vimNotes
A repo for storing notes and interesting packages and things surrounding Vim.

- To create a new file, simply navigate to the directory that you want the file in and
type [vim myFileName]. IF THE FILE DOESN'T EXIST, this will open a new file in vim which
you can then save after editing. If you exit without saving, the file will be deleted.

- To open a file, simply type [vim theFileThatExists].

BY DEFAULT, you are in COMMAND MODE when Vim opens.

Basic Shortcuts:
- [i] Toggle INSERT mode. (This allows you to type normally and enter text)
- [I] (capital I) Toggle INSERT mode and go to the BEGINNING of the line.
- [o] (letter o) Adds a new line below and toggles INSERT mode.
- [O] (capital O) Adds a new line above and toggles INSERT mode.
- [V] (capital v) Toggle Visual Mode. (This allows you to visualize what lines of code you are interacting with).
- [esc] Toggle off INSERT mode.
- *You can add numbers before the basic move commands to move the cursor that many LINES or COLUMNS. This applies to most Vim commands.
- Ex: [20j] would move the cursor down 20 lines.
- In Normal Mode [h] Move cursor LEFT.
- In Normal Mode [j] Move cursor DOWN.
- In Normal Mode [k] Move cursor UP.
- In Normal Mode [l] Move cursor RIGHT.

- In Normal Mode [:] Toggle the command line.

Command Line Shortcuts:
- [w] save changes to a file (write).
- [q] quit Vim and exit back to the Terminal.
- [wq] you can prefix the quit command with write command to save and quit.
- [q!] quit Vim WITHOUT SAVING.
- [:set number] show ABSOLUTE line numbers in vim.
- [:set nonumber] to disable line numbers.

Useful Commands:
- [dd] delete an entire LINE.
- [d$] delete to end of current line.
- [u] undo.
- [ctrl + r] redo.
- [.] (period) repeats pevious command.
- [G] takes your cursor to bottom of the file.
- [gg] takes your cursor to the top of the file.
- [ } ] go down a block of code.
- [ { ] go up a block of code.
- [yy] copy line to clipboard.
- [p] paste below.
- [P] (capital P) paste above.
- [w] takes you to next word.
- [W] (capital W) ignores punctuation.
- [b] takes you back by word.
- [B] (capital B) ignores punctuation.
- [:30] takes you to line 30.
- [0w] [^] take you to the beginning of the line.
