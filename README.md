https://www.near-sdk.io/zero-to-hero/basics/overview

https://stackoverflow.com/questions/56227766/why-must-a-wasm-library-in-rust-set-the-crate-type-to-cdylib

`chmod 744 build.sh`

Run the build script and expect to see the compiled Wasm file copied to the res folder, instead of buried in the default folder structure Rust sets up.

`./build.sh`