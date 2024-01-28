# prezto-last-working-dir module

Keeps track of the last used working directory and automatically jumps into it
for new shells, unless the starting directory is not `$HOME`.

Also adds a `lwd` function to jump to the last working directory.

## Installation


01. Launch Zsh:

    ```console
    zsh
    ```

02. Clone the repository into the [Prezto](https://github.com/sorin-ionescu/prezto) modules folder:

    ```console
    git clone https://github.com/JoniVanderheijden/prezto-last-working-dir.git "${ZDOTDIR:-$HOME}/.zprezto/modules"
    ```

03. Add `prezto-last-working-dir` to the modules section of ${ZDOTDIR:-$HOME}/.zpreztorc:

  ```console
  zstyle ':prezto:load' pmodule \
    ...other modules
    'prezto-last-working-dir'
  ```
