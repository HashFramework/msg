# shmem-ring

A lightweight, efficient shared memory ring buffer implementation for inter-process communication (IPC).

## Overview

`shmem-ring` provides a simple way to share data between multiple processes on the same machine using shared memory. This project is designed for scenarios where high throughput and low latency are critical.
This repo provides a simple example using shmem-ring in Rust.

## How to run
```shell
# in one terminal
cargo run --example shmem-ring-server

# in another terminal
cargo run --example shmem-ring-client
```