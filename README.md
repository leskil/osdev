# osdev

## Building
To build for bare metal: `cargo build`. Ensure target is installed using `rustup target add thumbv7em-none-eabihf`

To run in Qemu use `qemu-system-x86_64 -drive format=raw,file=target/x86_64-blog_os/debug/bootimage-blog_os.bin` or simply just `cargo run`.
