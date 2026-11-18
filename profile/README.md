# KITTYX

**Kitty's Integrated TypeScript Toolchain Yielding a uniX-like system.**

## Specifications and tools

| Project | Purpose |
| --- | --- |
| [KITTYX](https://github.com/kittycrow-kittyx/kittyx) | Machine, ABI and executable-format contracts |
| [ThistleASM](https://github.com/kittycrow-kittyx/thistle-asm) | Assembler, linker and THO/THX tooling |
| [ThistleCC](https://github.com/kittycrow-kittyx/thistlecc) | C and C++ compiler driver for RV64GC THX executables |
| [Bake](https://github.com/kittycrow-kittyx/bake) | Target-aware TypeScript validation and source lowering |
| [Baguette](https://github.com/kittycrow-kittyx/baguette) | TypeScript-to-WebAssembly compiler |
| [Croissant](https://github.com/kittycrow-kittyx/croissant) | Freestanding C backend |
| [Crust](https://github.com/kittycrow-kittyx/crust) | Freestanding Rust backend |

## Kernels and execution

| Project | Purpose |
| --- | --- |
| [Thistle](https://github.com/kittycrow-kittyx/thistle) | Canonical TypeScript kernel |
| [Teto](https://github.com/kittycrow-kittyx/teto) | WebAssembly kernel |
| [Rei](https://github.com/kittycrow-kittyx/rei) | Freestanding C kernel |
| [Rusty Rei](https://github.com/kittycrow-kittyx/rusty-rei) | Freestanding Rust kernel |
| [Neru](https://github.com/kittycrow-kittyx/neru) | Linux-WASM integration |
| [Nemunemu](https://github.com/kittycrow-kittyx/nemunemu) | Linux userspace THX runtime |

## Operating system

[mikuOS](https://github.com/kittycrow-kittyx/mikuOS) (初音ミクOS) provides the
common userspace.

![KITTYX architecture](architecture.svg)

The diagram includes development targets. Supported execution modes and build
requirements are documented in the individual repositories.
