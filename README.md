[![Melpa Status](http://melpa.org/packages/flycheck-kotlin-badge.svg)](http://melpa.org/#/flycheck-kotlin)
[![Melpa Stable Status](http://stable.melpa.org/packages/flycheck-kotlin-badge.svg)](http://stable.melpa.org/#/flycheck-kotlin)

flycheck-kotlin
===============

This library provides a [flycheck][] checker for [Kotlin] files.

Installation
------------

You'll need Emacs 24 for `flycheck`, so the recommended way to get
`flycheck-kotlin` is as a package from the [MELPA][melpa]
repository. The version of `flycheck-kotlin` there will always be
up-to-date.

If you insist on doing things the hard way, first ensure `flycheck` is
installed, then download this code and add the directory to your Emacs
`load-path`.

Then, in your `init.el`:

```lisp
(eval-after-load 'flycheck
  '(require 'flycheck-kotlin))
```

Make sure that the `ktlint` binary is present on Emacs' `exec-path`.
See [ktlint site](https://github.com/shyiko/ktlint) for details.


Usage
-----

When `flycheck` is enabled (e.g. with `global-flycheck-mode`), `kotlin-mode`
buffers will be automatically checked using this checker.

License
-------

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see http://www.gnu.org/licenses/.

See
[COPYING](https://github.com/whirm/flycheck-kotlin/blob/master/LICENSE)
for details.

About
-----

`flycheck-kotlin` was written by [Elric Milon](https://github.com/whirm).
