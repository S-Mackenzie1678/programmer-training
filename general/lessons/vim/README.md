Vim is a text editor that can be slightly hard to learn but has many useful shortcuts and is integrated with Terminal.

To open a file in Vim, the command is "vim <filename>". NOTE: this also will create a new file if no such file exists. Be careful of that. The filename needs the file's path as well.

When in Vim, you might try to type immidiately, but that won't work. To start typing, press i. To exit out of insert mode, press esc.

When not in a mode (ie esc has been pressed) commands are accessed by presing : (usually).

There are many commands that you NEED to know. These are,

":w" which saves the open file,

":q!" which quits without saving,

":wa" which saves all open files,

":qa!" which quits all open files without saving,

":wq:" which saves and closes the current file,

and ":wqa" which is the same as :wq but for all open files.

":tabe <filename>" opens a new file in a new "tab".

"gt" switches tabs in a left-to-right order by using in esc mode.

":vsp <filename>" opens a new file in the same tab by having a vertical split down the middle. This is useful for .cpp file .h file pairs. To switch between these files, in esc mode, use alt + arrow key (depending on which way you want to go).

":sp <filename>" is the same as :vsp but splits the screen horizontally. (It looks so much worse, don't use it).

":%s/<old-text>/<new-text>/gc" finds instances of <old-text> and replaces it with <new-text>, giving a y/n prompt for safety.

The following commands are only usable in esc mode.

"dd" deletes and copies the current line.

"p" pastes any copied stuff.

"o" creates a new line with the same indentation as the old line. "shift+o" is the same but it creates the new line above the old one.

"v" goes into visual mode, highlighting characters, preparing them for other commands.

The visual mode commands are:

"d" deletes the highlighted characters.

"y" copies the highlighted characters, alowing them to be pasted elsewhere (including other files).

"esc" leaves visual mode.
