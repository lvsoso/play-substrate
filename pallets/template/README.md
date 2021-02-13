### benchmark template
```shell
cd node

cargo build --release --features runtime-benchmarks

./target/release/node-template benchmark --chain dev --execution=wasm --wasm-execution=compiled --pallet pallet_template --extrinsic do_something --steps 50 --repeat 20
```