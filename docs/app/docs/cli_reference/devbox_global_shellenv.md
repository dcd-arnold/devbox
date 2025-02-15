# devbox global shellenv

Print shell commands that add global Devbox packages to your PATH

- To add the global packages to the PATH of your current shell, run the following command: 
    
    ```bash
    . <(devbox global shellenv)
    ```
    
- To add the global packages to the PATH of all new shells, add the following line to your shell's config file (e.g. `~/.bashrc` or `~/.zshrc`):
    
    ```bash
    eval "$(devbox global shellenv)"
    ```

## Options

<!-- Markdown Table of Options -->
| Option | Description |
| --- | --- |
| `-h, --help` | help for shellenv |
| `-q, --quiet` | suppresses logs |

## SEE ALSO

* [devbox global](devbox_global.md)	 - Manages global Devbox packages
