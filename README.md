# Emacs init setup
Emacs setting using straight.el [straight.el](https://github.com/raxod502/straight.el) package management. If there is problem installing, then clone from [GitHub](https://github.com/raxod502/straight.el) and copy `straight.el` to your `~/.emacs.d/straight/repos/`.

Maintain the recipe for package version in lockfile [default.el](https://github.com/yusbk/emacs_straight/blob/master/versions/default.el "version") and updated every time running `M-x straight-freeze-versions`. 

To revert all packages to the revisions specified in the lockfile by running `M-x straight-thaw-versions`.
