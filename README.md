# Parinfer 

_parentheses inference for Lisp_

 <table>
<tr>
<td>[<img src="https://travis-ci.org/shaunlebron/parinfer.svg?branch=master" valign="middle">](https://travis-ci.org/shaunlebron/parinfer)</td>
<td>__[Home Page](http://shaunlebron.github.io/parinfer/)__</td>
<td>[Download Plugins](http://shaunlebron.github.io/parinfer/#editor-plugins)</td>
</tr>
</table>

<img src="http://zippy.gfycat.com/WeirdOddBluefintuna.gif" width="400">

---

__Parinfer__ is a proof-of-concept editor mode for Lisp programming languages.
It simplifies the way we write Lisp by auto-adjusting parens when indentation
changes and vice versa.  The hope is to make basic Lisp-editing easier for
newcomers and experts alike, while still allowing existing plugins like Paredit
to satisfy the need for more advanced operations.

[Paredit]:http://danmidwood.com/content/2014/11/21/animated-paredit.html

This project is split into two parts:

- __[Parinfer Lib](lib)__ - the _editor-agnostic_ library
- __[Parinfer Site](site)__ - the code for the website

## How to Use It!

__Editor Plugins__: Though Parinfer is still in early development, several
contributors have started working on plugins for major editors.  Currently,
most of them spin up an instance of Node to leverage a single, canonical
implementation via RPC.  This allows core bug fixes to reach all editor plugins
until the core is stabilized and ready for proper porting.

- [atom-parinfer] for [Atom]
- [nvim-parinfer.js] for [Neovim]
- [vscode-parinfer] for [Visual Studio Code]
- inside [Replete for iOS]
- [sublime-text-parinfer] for [Sublime Text]
- [parinfer-mode] for [Emacs]
- [vim-parinfer] for [Vim]

[atom-parinfer]:https://github.com/oakmac/atom-parinfer
[Atom]:https://atom.io/
[nvim-parinfer.js]:https://github.com/snoe/nvim-parinfer.js
[Neovim]:https://neovim.io/
[vscode-parinfer]:https://github.com/Microsoft/vscode-parinfer
[Visual Studio Code]:https://code.visualstudio.com/
[Replete for iOS]:https://github.com/mfikes/replete
[sublime-text-parinfer]:https://github.com/oakmac/sublime-text-parinfer
[Sublime Text]:http://www.sublimetext.com/
[parinfer-mode]:https://github.com/edpaget/parinfer-mode
[Emacs]:https://www.gnu.org/software/emacs/
[vim-parinfer]:https://github.com/bhurlow/vim-parinfer
[Vim]:http://www.vim.org/

---

[MIT License](LICENSE.md)
