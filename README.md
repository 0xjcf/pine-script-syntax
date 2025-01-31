# pine-script-syntax README

This extension provides syntax highlighting and theme support for Pine Script, the programming language used in TradingView.

## Features

* **Syntax Highlighting** for:
  - Control flow keywords (`if`, `else`, `return`)
  - Built-in functions and variables
  - Variable declarations and assignments
  - Numeric constants and literals
  - Comments (line and block)
  - Operators (arithmetic, comparison, ternary)
  - String literals

* **Multiple Themes**:
  - Pine Script Dark (Default)
  - Pine Script Neon Dark
  - Pine Script Dimmed Dark  
  - Pine Script Light

All themes include:
- Colorblind-friendly palettes
- Semantic syntax highlighting
- 4.5:1 minimum contrast ratios (WCAG AA compliant)

![Syntax Example](https://raw.githubusercontent.com/0xjcf/pine-script-syntax/main/images/syntax-example.png)

## Requirements

* Visual Studio Code 1.60.0 or higher

## Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X / ⌘⇧X)
3. Search for "Pine Script Syntax"
4. Click Install
5. Reload VS Code when prompted

## Theme Selection

To choose a theme:
1. Open Command Palette (Ctrl+Shift+P / ⌘⇧P)
2. Search for "Preferences: Color Theme"
3. Select from the Pine Script themes:
   - Pine Script Dark
   - Pine Script Neon Dark
   - Pine Script Dimmed Dark
   - Pine Script Light

## Known Issues

* No code validation or autocomplete yet
* Limited operator tokenization
* No snippet support currently

## Release Notes

### 1.0.0

Initial release with:
- Basic Pine Script syntax highlighting
- 4 color themes
- Language configuration (brackets/comments)
