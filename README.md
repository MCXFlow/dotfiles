# dotfiles
Configurations

## features

- Humanized C/C++ code diagnosis (from JetBrains CLion) in vscode
- Perfect C/C++ project coding experience

## vscode

Install the following plugins: 

```text
clangd
CMake
CMake Tools
CodeLLDB
Material Icon Theme
```

Copy the configuration file `.vscode/settings.json` to the vscode global configuration file directory, or copy it to the workspace directory `.vscode`

At the same time, please install clangd and copy the `.config/clangd/config.yaml` file to the corresponding location in the home directory `~/.config/clangd/config.yaml`

Then restart vscode and enjoy.
