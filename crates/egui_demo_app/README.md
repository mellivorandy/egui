# egui demo app
This app demonstrates [`egui`](https://github.com/emilk/egui/) and [`eframe`](https://github.com/emilk/egui/tree/main/crates/eframe).

View the demo app online at <https://egui.rs>.

Run it locally with `cargo run --release -p egui_demo_app`.

`egui_demo_app` can be compiled to WASM and viewed in a browser locally with:

```sh
./scripts/start_server.sh &
./scripts/build_demo_web.sh --open
```

`egui_demo_app` uses [`egui_demo_lib`](https://github.com/emilk/egui/tree/main/crates/egui_demo_lib).


## Running with `wgpu` backend
`(cd egui_demo_app && cargo r --features wgpu)`
