Maude mode for Emacs
====================

This is a simple Maude mode for Emacs. It works on GNU Emacs 24, but I
would be happy to include patches for other emacsen.

Functionality
=============

- You have `maude-mode`, autoloaded and added to auto-mode-alist on
  ".maude" files
- You have `run-maude` for invoking an inferior Maude process
- Also, `run-full-maude` invokes Maude and tells it to load
  full-maude.maude
- Can load push to Maude the current buffer (`C-c C-b`), region (`C-c
  C-r`) and paragraph (`C-c C-p`)
- Uses `TAB` to indent
- Has some syntax coloring


Credits
=======

Most of the work was previously done by Ellef Gjelstad, but was later
taken by Santiago Saavedra to make it work under Emacs 24.


License
============

Maude-mode is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License as
published by the Free Software Foundation; either version 2 of
the License, or (at your option) any later version.

Maude-mode is distributed in the hope that it will be
useful, but WITHOUT ANY WARRANTY; without even the implied
warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR
PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public
License along with this program; if not, write to the Free
Software Foundation, Inc., 59 Temple Place, Suite 330, Boston,
MA 02111-1307 USA


Contributing
============

The canonical repository is currently at
https://github.com/ssaavedra/maude-mode

You can contribute patches by sending a Pull Request at GitHub or via
git format-patch to the email address to the maintainer on the
maude-file.el comment.
