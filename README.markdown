zenword
=======

What is zenword?
----------------

__zenword__ is a minimalistic, full screen distraction-free writer written in
Python and running in the GTK+ framework through PyGTK bindings.

Planned features include:
* __Customizable editor__. Allows the user to customize the following:
    - Font color and size
    - Font face
    - Margins
    - Editor background
    - Etc.
* __Spell Checker__. Automatically detects spelling errors made by the user
  and offers suggestions.
* __Milestones__. The user can set milestones like character, line, or word
  count to better track their progress.
* __Handy Status Bar__. A status bar that displays the following:
    - The current line and column
    - Word count, paragraph count, etc.
    - How much time the user has spent writing since their last milestone
* __Typewriter sounds__. The user can have typewriter keypress sounds everytime
  they input a character; people who find this annoying can easily turn it off.

Right now I've decided that the only file format that this zenword should read
and write into should be plain text files. Why? Because they're the easiest to
work with and all you're doing in distraction-free writers anyway is dealing
with the essence of your work, which is the **text** itself, rather than how
the text looks.
