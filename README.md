# SigmaOS-cinnamon-screensaver

## Current implementation

This Rust crate is a metadata-only scaffold. Its public descriptor reports the
Cargo package name and the `scaffold` status; it does not provide operational
component behavior. Screen locking, display power management, and screensaver behavior are not
implemented.

## Development

```sh
cargo fmt --all -- --check
cargo check --all-targets
```

The descriptor tests check package identity and the declared `scaffold` status
only; they do not exercise display locking, power management, or screensaver
behavior.
