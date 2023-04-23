# Rust2Lurk

A demo of compiling rust to lurk via yatima-lang

## Third party dependencies

 - `wabt` (installed with `flake.nix`)

## Lurk-lab dependencies

 - `lurkrs` from [lurk-rs](https://github.com/lurk-lab/lurk-rs) runs compiled code.
 - `yatima` from [yatima](https://github.com/lurk-lab/yatima) compiles Lean Wasm IR to Lurk.
 - `stage` from [Wasm.lean/lurk-week-demo](https://github.com/lurk-lab/Wasm.lean/tree/cognivore/lurk-week-demo) generates Lean Wasm IR, bakes user input into memory.
 - `wat-wrapper` from [wat-wrapper](https://github.com/cognivore/wat-wrapper) wraps WAT instructions into parentheses, making everything an S-expression.
 - `preprocess.sh` from [wat-wrapper](https://github.com/cognivore/wat-wrapper) erases comments in WAT.
