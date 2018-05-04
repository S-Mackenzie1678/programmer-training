Vim is a text editor that can be slightly hard to learn but has many useful shortcuts and is integrated with Terminal.

To open a file in Vim, the command is 'vim <filename>'. NOTE: this also will create a new file if no such file exists. Be careful of that. The filename needs the file's path as well.

When in Vim, you might try to type immediately, but that won't work. To start typing, press i. To exit out of insert mode, press esc.

When not in a mode (ie esc has been pressed) commands are accessed by presing : (usually).

There are many commands that you NEED to know. These are,

I. File commands

  1. ':w' which saves the open file,

  2. ':q!' which quits without saving,

  3. ':wa' which saves all open files,

  4. ':qa!' which quits all open files without saving,

  5. ':wq:' which saves and closes the current file,

  6. ':wqa' which is the same as :wq but for all open files.

  7. ':tabe <filename>' opens a new file in a new "tab".

  8. 'gt' switches tabs in a left-to-right order by using in esc mode.

  9. ':vsp <filename>' opens a new file in the same tab by having a vertical split down the middle. This is useful for .cpp file .h file pairs. To switch between these files, in esc mode, use alt + arrow key (depending on which way you want to go).

  10. ':sp <filename>' is the same as :vsp but splits the screen horizontally. (It looks so much worse, don't use it).


II. Text Editing
  1. ':%s/<old-text>/<new-text>/gc' finds instances of <old-text> and replaces it with <new-text>, giving a y/n prompt for safety.

  2. 'dd' deletes and copies the current line.

  3. 'p' pastes any copied stuff.

  4. 'o' creates a new line with the same indentation as the old line.

  5. 'Shift+o' is the as 'o' same but it creates the new line above the old one.

III. Cursor Commands

  1. 'Shift+g' goes to test bottom of the file.

  2. 'e' goes to the next character that is before a space or a new line.

  3. 'w' goes to the next character that is after a space or a new line.

IV. 'v' goes into visual mode, highlighting characters, preparing them for other commands.

  1. 'd' deletes the highlighted characters.

  2. 'y' copies the highlighted characters, alowing them to be pasted elsewhere (including other files).

  3. 'esc' leaves visual mode.
