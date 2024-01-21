# <center>Yew</center>
<center>A framework for creating reliable and efficient web applications.</center>

### Install `WebAssembly` target
> Rust can compile source codes for different `"targets"` (e.g. different processors). The compilation target for browser-based WebAssembly is called `wasm32-unknown-unknown`. The following command will add the WebAssembly target to your development environment.

```shell
rustup target add wasm32-unknown-unknown
```
### Install Trunk
> Trunk is the recommended tool for managing deployment and packaging and is used throughout the documentation and examples.

```shell
# note that this might take a while to install because it compiles everything from scratch
# Trunk also provides prebuilt binaries for a number of major package managers
# See https://trunkrs.dev/#install for further details
cargo install --locked trunk
```
### Other options
There are options other than Trunk that may be used for bundling Yew applications. You might want to try one of these options:

- `wasm-pack`
- `wasm-run`
- `xtask-wasm` (still in early development)

___

### View your web application

Run the following command to build and serve the application locally.

```shell
trunk serve
```

