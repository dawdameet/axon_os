# Changelog - AxonOS

## [2025-02-20] - Initial Setup
### Added:
- Installed Rust Nightly and set up cross-compilation.
- Configured QEMU for virtualized testing.
- Added a minimal Rust kernel with `_start()` entry point.
- Integrated `bootloader` crate for creating a bootable image.
- Successfully booted the kernel in QEMU.

### Next Steps:
- Implement basic VGA text output for debug logs.
