# Emacs init setup
Emacs setting using [straight.el](https://github.com/raxod502/straight.el) package management. If there is problem installing, then clone repos `straight.el` from [GitHub](https://github.com/raxod502/straight.el) to your `~/.emacs.d/straight/repos/`.

Maintain the recipe for package version in lockfile [default.el](https://github.com/yusbk/emacs_straight/blob/master/versions/default.el "version") which is updated every time running `M-x straight-freeze-versions`. 

To revert all packages to the revisions specified in the lockfile run `M-x straight-thaw-versions`. If you have messed up with local repos then run `M-x straight-normalize-package` or `M-x straight-normalize-all` to get back to it's original. Or updating our local repos with `M-x straight-merge-all`
