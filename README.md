[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/company-meta-net.svg)](https://jcs-emacs.github.io/jcs-elpa/#/company-meta-net)

# company-meta-net
> Company completion for C# project using meta-net

![CI](https://github.com/emacs-vs/company-meta-net/workflows/CI/badge.svg)

<p align="center">
  <img src="./etc/demo.png" width="611" height="317" />
</p>

## 💾 Quickstart

```el
(use-package company-meta-net
  :ensure t
  :hook (csharp-mode . (lambda ()
                         (add-to-list 'company-backends 'company-meta-net))))
```

## 🔨 Configurations

#### `company-meta-net-active-modes`

Major modes that allow completion.

#### `company-meta-net-display-annotation`

Display type annotation in company-mode's annotation command.

#### `company-meta-net-display-document`

Display document in company-mode's doc-buffer command.

## Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple)](https://github.com/bbatsov/emacs-lisp-style-guide)
[![Donate on paypal](https://img.shields.io/badge/paypal-donate-1?logo=paypal&color=blue)](https://www.paypal.me/jcs090218)
[![Become a patron](https://img.shields.io/badge/patreon-become%20a%20patron-orange.svg?logo=patreon)](https://www.patreon.com/jcs090218)

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!
