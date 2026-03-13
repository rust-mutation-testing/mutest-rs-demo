# Demo Subjects for mutest-rs

## Setup

### Step 1: Ensure that rustup is installed

Ensure that rustup, the Rust toolchain manager, is installed by following the instructions at https://rustup.rs.

### Step 2: Install mutest-rs

Follow the latest instructions to install mutest-rs at https://mutest.rs/installation.

For more information on mutest-rs, visit the mutest-rs book at https://mutest.rs.

## Demos

### `basic/`

> A simple Rust library with a unit test.

```sh
cd basic/
cargo mutest -v run
```

### alacritty: `external/alacritty/`

```sh
cd external/alacritty/
cargo mutest -v -p alacritty --bin alacritty run
```

### bevy_math: `external/bevy/`

```sh
cd external/bevy/
cargo mutest -v -p bevy_math --lib run
```

## License

All external subjects under the `external/` directory retain their respective licenses and copyright.

All other content is dual-licensed under Apache 2.0 and MIT terms.
