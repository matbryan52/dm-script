# dm-script README

Provides basic syntax highlighting support for the
Gatan Digital Micrograph scripting language in VSCode.

The grammar is a heavily reduced and partially extended
version of the builtin C-language support.

Known issues:

- Method access on an object name causes different highlighting
  of that name than simple assignment or use of that object's name,
  but only when in a scope/block
- Some remnants of the C grammar remain

This extension is not affiliated with or supported by Gatan.

## Installation

Download the latest `.vsix` file from the releases page. Select
`Install from VSIX from Extensions > Options` (or use the
command pallette.)

## Release Notes

### 0.0.2

More types, better method / control flow highlighting

### 0.0.1

Initial dm-script support
