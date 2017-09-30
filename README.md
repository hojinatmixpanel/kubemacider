# kubemacider
utils for mixpanel swankers

## Prerequisites

- kubernetes-el
- cider

## Installation

```elisp
(add-to-list 'load-path "<INSTALL-PATH>")
(require 'kubemacider)
```

## Usage

### For swanking
M-x kubemacider-mixpanel-swank

### To open a shell
M-x kubemacider-add-tramp-method

Select a pod to open a shell. Then C-x C-f, and type `/kube` and tab.
