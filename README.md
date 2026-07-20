# X Native Language Support

Syntax highlighting and editor support for **X Native** (`.xfxn`), the custom baremetal systems programming language built for the CXK operating system. 

## Features
* **Full Syntax Highlighting:** Powered by a custom TextMate grammar specifically mapped to the X Native compiler ecosystem.
* **CXOS Snippet Library:** Rapidly prototype CXOS applications with tab-completion for `gui.xfxn` window/button rendering, `layer.xfxn` compositor management, and `net.xfxn` network structures.
* **Type Definition Support:** Correctly identifies type aliases and pointer architectures introduced via the `type` declaration keyword.
* **Modular Code Support:** Scopes and colors the `import` directive for standard library mapping (`io.xfxn`, `gfx.xfxn`, `net.xfxn`, etc.).
* **Advanced Flow Control:** Robust evaluation context for loops, supporting `while`, `break`, and `continue`.
* **Systems Operations:** Highlighting for explicit compile-time operator evaluations like `sizeof` and explicit type casing (`as`).
* **Bitwise Arithmetic Styling:** Native tracking for bit shifting (`<<`, `>>`) and structural modifiers used in high-performance computing modules.

## Release Notes

### 0.4.0
* Added extensive snippet library for the `gui.xfxn` (GEOS/System 6 styled widgets) and `layer.xfxn` (Z-index dirty-rect compositor) standard libraries.
* Added snippets for CXOS IPv4 and ICMP networking stacks (`net.xfxn`).

### 0.3.0
* Added grammar recognition for structural type aliasing rules (`type`).
* Fully optimized highlighting rules for user-declared function pointer configurations.

### 0.2.0
* Added grammar parsing for loop branching mechanics (`break`, `continue`).
* Enabled highlight profiles for modular layout controls (`import`).
* Embedded explicit operators handling (`sizeof`).

### 0.1.0
* Initial release.
* Core syntax highlighting for X Native constructs.