# A Language Server For DOT With Visual Studio Code

This repository is forked from https://github.com/unosviluppatore/language-server-dot. However, in this repository the antlr parser is implemented as a local node module for the server i.e., instead of running parser as a separate service it can be loaded as a node module.

# Installation
```
cd language-server-dot-with-parser
npm install
```

# Debug
`CLTR + B` to build & `F5` to launch the debugger. Use `Attach to server` debug configuration to debug server.
