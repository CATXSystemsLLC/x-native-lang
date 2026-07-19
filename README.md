# X Native Language Support

Syntax highlighting and editor support for **X Native** (`.xfxn`), the custom baremetal systems programming language built for the CXK operating system. 

## Features
* **Full Syntax Highlighting:** Powered by a custom TextMate grammar specifically mapped to the X Native compiler ecosystem.
* **Type Definition Support:** Correctly identifies type aliases and pointer architectures introduced via the `type` declaration keyword.
* **Modular Code Support:** Scopes and colors the `import` directive for standard library mapping (`io.xfxn`, `gfx.xfxn`, `net.xfxn`, etc.).
* **Advanced Flow Control:** Robust evaluation context for loops, supporting `while`, `break`, and `continue`.
* **Systems Operations:** Highlighting for explicit compile-time operator evaluations like `sizeof` and explicit type casing (`as`).
* **Bitwise Arithmetic Styling:** Native tracking for bit shifting (`<<`, `>>`) and structural modifiers used in high-performance computing modules.

## Release Notes

### 0.3.0
* Added grammar recognition for structural type aliasing rules (`type`).
* Fully optimized highlighting rules for user-declared function pointer configurations.

### 0.2.0
* Added grammar parsing for loop branching mechanics (`break`, `continue`).
* Enabled highlight profiles for modular layout controls (`import`).
* Embedded explicit operators handling (`sizeof`).
* Updated matching sequences to catch low-level math expressions (`<<`, `>>`, bitwise targets).

### 0.1.0
* Initial release.
* Core syntax highlighting for X Native constructs.
* File icon integration for `.xfxn` files.