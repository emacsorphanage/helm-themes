# helm-themes.el


## Introduction

`helm-themes.el` provides Emacs themes selection with helm interface.

Persistent action can set theme temporary.

## Screenshot

![helm-themes-screenshot](https://github.com/syohex/emacs-helm-themes/raw/master/image/helm-themes-screenshot.png)


Requirements
------------
* Emacs 24.1 or higher.
* helm 1.0 or higher


## Caution

`helm-themes.el` reset to original theme if you cancel to set theme(Such as `C-g`).
But `helm-themes.el` cannot reset original theme if you set your own color
setting for some faces.


## Basic Usage

Set themes with helm interface. This persistent action can set theme temporary.

    M-x helm-themes

## Sample Configuration

    (require 'helm-config)
    (require 'helm-themes)
