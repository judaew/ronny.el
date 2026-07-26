<div align="center">

# ronny.el

</div>

`ronny.el` is a dark colorscheme for [Emacs](https://www.gnu.org/software/emacs), mostly inspired by the original Monokai created by Wimer Hazenberg.

![ronny.el](https://github.com/user-attachments/assets/5be04691-fc14-4456-8314-9ff37e50103d)

It aims to preserve the familiar Monokai aesthetic while offering:
- a cooler, more neutral background and UI
- subtle interface elements that keep the focus on the code
- muted yet readable comments that reduce visual noise
- expanded semantic highlighting for modern font-lock faces, Tree-sitter, and modern packages.

## Installation

Install via package manager (e.g. [use-package](https://jwiegley.github.io/use-package/) (built-in) or [Straight.el](https://github.com/radian-software/straight.el)):

<details><summary>use-package (built-in)</summary>

```elisp
(use-package ronny-theme
  :vc (:url "https://github.com/judaew/ronny.el" :branch "main"))
```

</details>

<details><summary>Straight.el</summary>

```elisp
(use-package ronny-theme
  :straight (:host github :repo "judaew/ronny.el" )

;; or

(straight-use-package
 'ronny-theme
 :host github
 :repo "judaew/ronny.el")
```

</details>

<details><summary>Manual</summary>
Download the `ronny.el` file and put it in your `load-path`.
</details>

## Usage

```elisp
;; ⚠️ WARNING: This theme is not available in MELPA yet.
;; You need to install it using either:
;; - straight.el, or
;; - use-package :vc (Emacs 29 and above)
;; - manual

(use-package ronny
 :straight (:host github :repo "judaew/ronny.el")
 :config (load-theme 'ronny t))
```

## Something is broken but I know how to fix it!

Pull requests and issues are welcome! Feel free to send one with an explanation!
