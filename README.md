# About
Hey there, I'm James Verhoef, a low level systems programmer working primarily in Rust.
I'm focused on things like compilers, virtual machines, and developer tooling (think of parsers, LSPs, CLI tools).

# Projects
## [Rockscript](https://github.com/kirbytheburger/rockscript)
Rockscript is an esoteric programming language with a stable interpreter and REPL, plus LSP and VSCode extension actively being worked on. It's built as a multi-crate Cargo workspace, splitting the language core from the LSP so tooling can reuse the same parser/AST without depending on the runtime.

## [PIKU](https://github.com/kirbytheburger/PIKU)
PIKU is a custom 16-bit CPU architecture with it's own instruction set, implemented as a stable Rust-based VM. It's complete enough to serve as a real compilation target: Negative C (-C), a C-like language, compiles down to PIKU assembly and runs on it.

## [-C](https://github.com/kirbytheburger/-C)
Negative C (-C) is a low-level, statically-typed language with manual memory management, based on C but intentionally simplified, compiling down to PIKU assembly for my custom 16-bit CPU. Actively in development, with core language features being built out incrementally.

## [Game engine](https://github.com/kirbytheburger/game_engine)
A minimal 2D game engine made in Rust using wgpu (Vulkan) for rendering, with a Luau scripting API for sprites, camera control, and input handling. [Simple platformer physics example](https://github.com/user-attachments/assets/a89f83f3-c54f-4ee7-97a9-c93443ee0a90).

## [Autodiff](https://github.com/kirbytheburger/autodiff)
A CLI tool for automatic differentiation using dual numbers, computing the exact derivative of a function at a point in a single evaluation. Published on crates.io as `autodifferentiate`.
