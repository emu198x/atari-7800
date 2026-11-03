# atari-7800

The Atari 7800 family: its shared wiring, the NTSC and PAL boards, and the headless runtime.

| Crate | Registry |
|---|---|
| [`emu198x-common-atari-7800`](crates/emu198x-common-atari-7800) | [crates.io](https://crates.io/crates/emu198x-common-atari-7800) |
| [`emu198x-machine-atari-7800`](crates/emu198x-machine-atari-7800) | [crates.io](https://crates.io/crates/emu198x-machine-atari-7800) |
| [`emu198x-machine-atari-7800-pal`](crates/emu198x-machine-atari-7800-pal) | [crates.io](https://crates.io/crates/emu198x-machine-atari-7800-pal) |
| [`emu198x-runtime-atari-7800`](crates/emu198x-runtime-atari-7800) | [crates.io](https://crates.io/crates/emu198x-runtime-atari-7800) |

Part of [Emu198x](https://github.com/emu198x/emu198x), a family of
cycle-accurate retro-computing emulators. Used by the Emu198x Atari 7800 binary and the browser fleet.

Each crate is versioned on its own and bumps only when it changes. Releases go
through release-plz: merging its release pull request tags the crate and
publishes it.

Licensed GPL-2.0-or-later.
