# Lily

Syntax highlighting for the [Lily theorem prover](https://github.com/Innf107/lily).

## Features

Syntax Highlighting for `.lily` files.

## Build Instructions
To build and install lily-vscode, first install `vsce` (This has to be executed as root)
```
npm install -g vsce
```
To create the package `.vsix` file, run
```
vsce package
```
This will generate a file called `lily-<version>.vsix`.

In Visual Studio Code, press `Ctrl + P` to open the command prompt, type in
```
>Extensions: Install from VSIX
```
and select the generated `polaris-<version>.vsix` file.

Now reload vscode via
```
>Developer: Reload Window
```
