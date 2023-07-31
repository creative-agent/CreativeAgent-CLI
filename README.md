

 <br>
---
## Welcome to the CodeBlocks CLI!
```

---

## Usage

```
~$ CodeBlocks-CLI --help

┌────────────────────────────────────────────────┐
│                                                │
│                                                │
│   Welcome to the CodeBlocks CLI !              │
│                                                │
│                                                │
└────────────────────────────────────────────────┘

Options:

$ npm install -g @CodeBlocks/cli
$ CodeBlocks-CLI COMMAND
running command...
$ CodeBlocks-CLI (--version)
@CodeBlocks-CLI/cli/0.0.14 darwin-arm64 node-v18.3.0
$ CodeBlocks-CLI --help [COMMAND]

USAGE:
  $ CodeBlocks-CLI COMMAND
```
<p align="center">
   <img  src="https://img.shields.io/badge/license-MIT-green">
 <img  src="https://img.shields.io/badge/build-passing-brightgreen">
   <img  src="https://img.shields.io/badge/version-1.0.0-orange">
   <img  src="https://img.shields.io/badge/npm-v6.14.8-blue">
  <img  src="https://img.shields.io/badge/node-v12.18.2-yellow">
 </p>


## Installation

1. Clone the repository and then navigate to it.
2. Run ```npm install``` to install the dependencies.
3. Run ```npm install -g .``` to install the CLI.
4. Now you are good to go and can use the CodeBlocks CLI!<br>

## Commands
```
CodeBlocks info
CodeBlocks plugin create PLUGIN_NAME
CodeBlocks plugin delete PLUGIN_NAME
CodeBlocks plugin install NPM_MODULE
```
## CodeBlocks info
```
USAGE
  $ CodeBlocks info

DESCRIPTION
  This shows where CodeBlocks is currently being ran at.
```
## CodeBlocks plugin create PLUGIN_NAME
```
USAGE
  $ CodeBlocks-CLI plugin create [PLUGIN_NAME] [--type database|api|cloud-storage] [-b]

ARGUMENTS
  PLUGIN_NAME  Name of the plugin

FLAGS
  -b, --build
  --type=<option>  <options: database|api|cloud-storage>

DESCRIPTION
  Create a new CodeBlocks plugin

EXAMPLES
  $ CodeBlocks-CLI plugin create <name> --type=<database | api | cloud-storage> [--build]
```
## CodeBlocks plugin delete PLUGIN_NAME
```
USAGE
  $ CodeBlocks-CLI plugin delete [PLUGIN_NAME] [-b] [-m]

ARGUMENTS
  PLUGIN_NAME  Name of the plugin

FLAGS
  -b, --build
  -m, --marketplace

DESCRIPTION
  Delete a CodeBlocks plugin

EXAMPLES
  $ CodeBlocks-CLI plugin delete <name> [--build]
```
## CodeBlocks plugin install NPM_MODULE
```
USAGE
  $ CodeBlocks-CLI plugin install [NPM_MODULE] --plugin <value>

ARGUMENTS
  NPM_MODULE  Name of the npm module

FLAGS
  --plugin=<value>  (required)

DESCRIPTION
  Installs a new npm module inside a CodeBlocks plugin

EXAMPLES
  $ CodeBlocks-CLI plugin install <npm_module> --plugin <plugin_name>
```
## Support
```
Type ```CodeBlocks-CLI``` or ```CodeBlocks-CLI --help``` to get started.


(For Developers,
https://github.com/RushanKhan1/termTranslate/tree/main
https://dev.to/rushankhan1/build-a-cli-with-node-js-4jbi)

## License

MIT © ***CodeBlocks CLI***
