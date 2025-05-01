# Pixi ❤️ WASM + ROS 2

[Visit the deployed example](https://ros2wasm.github.io/pixi-ros2-wasm/)

You can read more about this in our [**blog post: Pixi ❤️ WASM**](https://prefix.dev/blog/pixi_wasm) and [ROS2WASM paper](https://www.arxiv.org/abs/2409.09941).

Pixi is a conda-compatible package manager written in Rust. It uses the `pixi.toml` to define everything that goes into the environment, including tasks, dependencies, and more. It uses `jupyterlite` under the hood to bundle and serve a WASM environment that is created with pixi!

## Usage

```bash
pixi run start
```

To run the example locally.

The deployment is made by the Github action (that pushes to an artifact): [deploy.yml](.github/workflows/deploy.yml).
Note that you need to change the Github setting in order to use an "artifact" as deployment (and not the `gh-pages` branch).

<img width="1124" alt="Screenshot 2024-07-30 at 17 11 50" src="https://github.com/user-attachments/assets/810b2344-e645-48bf-bfe3-005a48b913dc">
