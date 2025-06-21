# VideoPlayerXray Syntax Highlighter for VSCode

This extension provides syntax highlighting support for `.vxr` files, used for annotating actors and timestamps in video files.

## Features

- Syntax highlighting for timestamps like `[00.00.00]`
- Highlighting of keys like `name`, `picture`
- Recognition of numeric keys (e.g. `1:`)
- Highlighting of braces `{}`, colons `:`, and strings
- Lightweight and easy to use with `.vxr` files

## Requirements

No special requirements or dependencies.

## Extension Settings

This extension does not currently contribute any custom settings.

## Known Issues

- Strings without quotes may not be highlighted correctly.
- No validation or autocomplete, only syntax coloring.

## Release Notes

### 1.0.0

- Initial release with basic syntax highlighting for `.vxr` files.

---

## Usage

Open a `.vxr` file or create a new one with the extension `.vxr`.  
The syntax highlighting will be applied automatically.

Example:

```vxr
[00.00.00] {
1: {
name: Jim Carrey
picture:
}
} [00.10.00]
```


## For more information

- [VSCode Extension API](https://code.visualstudio.com/api)
- [Creating a Language Extension](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)

**Enjoy!**