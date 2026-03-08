# vscode-openvpn

[![Version](https://img.shields.io/github/v/release/idleberg/vscode-openvpn?style=for-the-badge)](https://github.com/idleberg/vscode-openvpn/releases)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/idleberg.openvpn?style=for-the-badge&label=Marketplace)](https://marketplace.visualstudio.com/items?itemName=idleberg.openvpn)
[![Open VSX Downloads](https://img.shields.io/open-vsx/dt/idleberg/openvpn?style=for-the-badge&label=Open%20VSX)](https://open-vsx.org/extension/idleberg/openvpn)
[![Build](https://img.shields.io/github/actions/workflow/status/idleberg/vscode-openvpn/default.yml?style=for-the-badge)](https://github.com/idleberg/vscode-openvpn/actions)

Language support and snippets for [OpenVPN](https://github.com/OpenVPN/openvpn) configuration files

**Note:** I have only started using OpenVPN recently and primarily relied on [examples](https://github.com/OpenVPN/openvpn/tree/master/sample/sample-config-files) and the [documentation](https://openvpn.net/vpn-server-resources/) to create this package. Feel free to contribute additions and improvements!

## Installation

### Extension Marketplace

Launch Quick Open, paste the following command, and press <kbd>Enter</kbd>

`ext install idleberg.openvpn`

### CLI

With [shell commands](https://code.visualstudio.com/docs/editor/command-line) installed, you can use the following command to install the extension:

`$ code --install-extension idleberg.openvpn`

### Packaged Extension

Download the packaged extension from the the [release page](https://github.com/idleberg/vscode-openvpn/releases) and install it from the command-line:

```bash
$ code --install-extension path/to/openvpn-*.vsix
```

Alternatively, you can download the packaged extension from the [Open VSX Registry](https://open-vsx.org/) or install it using the [`ovsx`](https://www.npmjs.com/package/ovsx) command-line tool:

```bash
$ ovsx get idleberg.openvpn
```

### Clone Repository

Change to your Visual Studio Code extensions directory:

```bash
# Windows
$ cd %USERPROFILE%\.vscode\extensions

# Linux & macOS
$ cd ~/.vscode/extensions/
```

Clone repository as `openvpn`:

```bash
$ git clone https://github.com/idleberg/vscode-openvpn openvpn
```
## Related

- [atom-openvpn](https://github.com/idleberg/atom-language-openvpn)
- [sublime-openvpn](https://packagecontrol.io/packages/OpenVPN)

## License

This work is licensed under [The MIT License](https://opensource.org/licenses/MIT)
