<div align="center">

# ronny.el

[![MELPA](https://melpa.org/packages/ronny-theme-badge.svg)](https://melpa.org/#/ronny-theme)
![GitHub License](https://badgen.net/github/license/judaew/ronny.el)

</div>

`ronny.el` is a dark colorscheme for [Emacs](https://www.gnu.org/software/emacs), mostly inspired by the original Monokai created by Wimer Hazenberg.

![ronny.el](https://github.com/user-attachments/assets/5be04691-fc14-4456-8314-9ff37e50103d)

It aims to preserve the familiar Monokai aesthetic while offering:
- a cooler, more neutral background and UI
- subtle interface elements that keep the focus on the code
- muted yet readable comments that reduce visual noise
- expanded semantic highlighting for modern font-lock faces, Tree-sitter, and modern packages.

## Installation & Usage

`ronny.el` is available from MELPA and can be installed via `package-install` or `use-package`:

### package-install:

`M-x package-install RET ronny-theme RET`. After installation, load the theme with `M-x load-theme RET ronny RET`

### use-package

```elisp
(use-package ronny-theme
  :config (load-theme 'ronny t))
```

## Something is broken but I know how to fix it!

Pull requests and issues are welcome! Feel free to send one with an explanation!
