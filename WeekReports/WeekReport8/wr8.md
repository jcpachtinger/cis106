---
Jerry Pachtinger
Fall 2023
CIS 106
---

**Vim**
Vim is a lightweight text editor that is designed for use solely with the keyboard. All functionality is based on shortcuts that allow you to move around a document with specificity without needing to navigate through menus. It features extensive support for programming languages which makes it useful for coding as well as text editing.

**Nano**
Nano is a command-line text editor for Linux. It's small and lightweight which makes it ideal for builds on low-end systems. This interface is more similar to other GUI-based text-editors which makes it more approachable than VIM many users. 

**Starting VIM**
If VIM is installed on your system starting it is as easy as typing the command VIM into the CLI. Tying VIM + Filename opens a file if you're within the folder that file exists. 

**VIM Modes**
- insert mode: Allows you to type text
- normal mode: Allows you to move around the document and manipulate text
- command mode: Allows you to enter commands
- visual/select modes: additonal ways of highlighting and manipulating text
  
**Inserting text**
VIM starts in normal mode. Pressing the 'I' key puts you into insert mode where you can type text.

**Saving a file**
while in normal mode:
- :w            save
- :w filename   save under provided name
- :wq           save and quit
- :wq!          save quit and ignore and close all other open  files

**Searching for a word**
from normal mode / followed by the word to search and then 'n' to cycle through the matches. using ? instead of / searches for the word starting at the bottom of the text.

**deleting text**
- dw: deletes the word your cursor is on
- x:  deletes character your cursor is on
- dd: deletes the line the cursor is currently on
- d + /word: deletes from where your cursor is up until the supplied word