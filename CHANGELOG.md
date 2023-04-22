# Release notes

Notable differences from version 1.1.2.

## Version 1.4.7 – 2023-04-22

### Added

- Support for Python 3.8, 3.9, 3.10.
- Use ddp3 to store project files.

### Changed

- Update wxpython to 4.1.1, and remove incompatible align flags.
- Modify the InsertItem in `plotpanel.py` for Windows.

### Deprecated

### Removed

### Fixed

- Incompatible conversion between bytes and str from py2 to py3.
- Replace the deprecated `Thread.isAlive()` with `Thread.is_alive()`.
