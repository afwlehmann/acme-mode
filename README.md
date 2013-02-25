
In order to install acme-mode for Emacs, copy acme-mode.el into your local
site-lisp directory and add the following lines to your ~/.emacs:

```lisp
(autoload 'acme-mode "acme-mode"
    "Major mode for editing Acme 6502 sources." t)

(add-to-list 'auto-mode-alist '(".acme$" . acme-mode))
```
