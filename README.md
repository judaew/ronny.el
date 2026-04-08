<div align="center">

# ronny.el

</div>

ronny.el is a dark colorscheme for [Emacs](https://www.gnu.org/software/emacs), which mostly was inspired by the Monokai originally created by Wimem Hazenberg.

![ronny.el](https://github.com/user-attachments/assets/ccd4576e-d402-42ff-844d-e11c8726c593)

## Installation

Install via package manager (e.g. [use-package](https://jwiegley.github.io/use-package/) (built-in) or [Straight.el](https://github.com/radian-software/straight.el)):

<details><summary>use-package (built-in)</summary>

```elisp
(use-package ronny-theme
  :vc (:fetcher github :repo "judaew/ronny.el"))
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
