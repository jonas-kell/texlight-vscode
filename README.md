# texlight-vscode

A language client extension. Main repository can be found [Here](https://github.com/jonas-kell/texlight).

## Submodules

The code that gets referenced in the thesis is managed via git-submodules and needed for building the document. Make sure to initialize the submodules before building

```shell
git submodule init
git pull --recurse-submodules
```

## compile the server for dev

```shell
cd texlight
cargo build
```

## Installation pre-requirements for debugging the client in VS-Code

```shell
npm install
npm run compile-dev
```

https://code.visualstudio.com/blogs/2024/06/07/wasm-part2
