# X Native Language Support

Syntax highlighting and editor support for **X Native** (`.xfxn`), the custom baremetal systems programming language built for the CXK operating system. 

## Features
* **Full Syntax Highlighting:** Powered by a custom TextMate grammar specifically mapped to the X Native compiler.
* **Keyword Recognition:** Supports core control flow and storage keywords (`fn`, `struct`, `global`, `const`, `extern`, `let`, `if`, `else`, `while`, `return`, `as`).
* **Type Highlighting:** Native primitive types (`i8`, `u8`, `i16`, `u16`, `i32`, `u32`, `bool`, `void`).
* **Baremetal Friendly:** Optimized for reading low-level kernel code, custom executables (`.xcex`), and system executives (`.xoex`).

## Installation
1. Open Visual Studio Code.
2. Go to the Extensions view (`Ctrl+Shift+X`).
3. Search for "X Native".
4. Click **Install**.

## Known Issues
* String literal parsing is currently limited to basic escapes; multi-line strings or advanced formatting may not highlight correctly until the language spec expands.

## Release Notes

### 0.1.0
* Initial release.
* Core syntax highlighting for X Native constructs.
* File icon integration for `.xfxn` files.