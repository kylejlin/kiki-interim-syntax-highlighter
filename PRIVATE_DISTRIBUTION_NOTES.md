# Notes for when you distribute this extension privately

If you want to install this extension without publishing to the VS Code Marketplace, follow these instructions:

## 1. Package the extension with `vsce`

First, install `vsce` if you don't already have it installed.

```sh
npm install -g @vscode/vsce
```

Then, package your extension.

```sh
vsce package
```

This should create a `.vsix` file in this directory (i.e., the `kiki-interim-syntax-highlighter` directory).

## 2. Install the `.vsix` file

In VS Code, press `Cmd-Shift-P` (for Mac), and then select `Extensions: Install from VSIX` from the dropdown (you can start typing to filter the options, of course).

There should be some sort of message like "Successfully installed extension".

Congratulations, you installed the extension!
