# lamp-vscode-extension

An extension for the Visual Studio Code editor that enables syntax highlighting and code snippets for the lamp esoteric language.

Lamp base repository: https://github.com/pefcos/lamp

Made with: https://www.npmjs.com/package/generator-code

## Features

### Syntax Highlighting

This extension highlights types and keywords in the lamp language, as well as values and comments. To install it, simply move it to your vscode extensions folder, restart your editor and enjoy! It is automatically associated with any file with the ".lamp" extension.

### Code Snippets

Some code snippets are provided by the extension. If you type the `if` word and accept the snippet, a if-like circuit call will be generated for you. As well as if, you can also type `if else` and the snippet will create two consecutive circuits, one with an if-like call and the other with the negation of the value that initializes the first circuit.

## Release Notes

### 1.0.0

Initial release of the lamp-vscode-extension. Syntax highlighting for lamp(v1.0) keywords and values. Also added "if" and "if else" snippets.

### 1.0.1

Changed comment syntax highlighting.
