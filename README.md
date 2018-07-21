# go-custom-format README

The extension provides a functionality to run a custom format for Go codes.

## Requirements

- Make sure you have [VSCode](https://code.visualstudio.com/) and install [Go Custom Format](https://marketplace.visualstudio.com/items?itemName=bongnv.go-custom-format) from VSCode Marketplace.
- The extension doesn't come with any formatter. A format tool needs to be installed and configured in `goCustomFormat.fmtCmds` to make it work.

## Extension Settings

This extension contributes the following settings:

* `goCustomFormat.onSave`: To format codes before saving.
* `goCustomFormat.fmtCmds`: To configure the format commands. For example:
```
  "goCustomFormat.onSave": true,
  "goCustomFormat.fmtCmds": [
    "grabbyright"
  ],
```

## Commands

The extension also provides several commands in the Command Palette for working with Go files:
- `Run custom format`: To format the current file.

## Known Issues

_TODO_

-----------------------------------------------------------------------------------------------------------

**Enjoy!**
