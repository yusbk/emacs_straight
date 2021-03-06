# Emacs init setup
Emacs setting using [straight.el](https://github.com/raxod502/straight.el) package management. If there is problem installing, then clone repos `straight.el` from [GitHub](https://github.com/raxod502/straight.el) to your `~/.emacs.d/straight/repos/`.

Maintain the recipe for package version in lockfile [default.el](https://github.com/yusbk/emacs_straight/blob/master/versions/default.el "version") in folder `~/.emacs.d/straight/versions/` which is updated every time running `M-x straight-freeze-versions`. 

To revert all packages to the revisions specified in the lockfile run `M-x straight-thaw-versions`. If you have messed up with local repos then run `M-x straight-normalize-package` or `M-x straight-normalize-all` to get back to it's original. Or updating your local repos with `M-x straight-merge-all`

To update packages, use `M-x straight-pull-all`, else you can use `straight-fetch-all` and then `straight-merge-all`

For references on different useful arguments for `straight` can be found here [Github site](https://github.com/raxod502/straight.el#version-control-operations "github").

## Local pc

The folder for this git repo is at *~/.emacs.d/emacs_straight* in my work laptop with Windows OS.
When using Linux pc at work or private the file *init_linux.el* should be used by renaming it to
standard *init.el*.
