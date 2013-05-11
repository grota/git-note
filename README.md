git-note
========

A simple hack to make git notes a little bit more porcelain.

The idea is that you have only a single *global* note in the repository.
In other words you don't need to specify (as with git-notes) a commit the note is attached to.

Usage
=====

`git note` will edit (or create if not present) the note.

`git note /path/to/repo` if you want to edit the note in a repo located elsewhere.

TODO
====

Instead of using `HEAD` the first time the note is created, create an empty orphan commit and use that.
