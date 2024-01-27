# prezto-last-working-dir module

Keeps track of the last used working directory and automatically jumps into it
for new shells, unless the starting directory is not `$HOME`.

Also adds a `lwd` function to jump to the last working directory.

To use it, add `prezto-last-working-dir` to the modules section of ${ZDOTDIR:-$HOME}/.zpreztorc:

```zsh
zstyle ':prezto:load' pmodule \
  ...other modules
  'prezto-last-working-dir'
```
