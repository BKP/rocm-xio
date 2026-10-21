# Changelog for rocm-xio

## UNRELEASED - rocm-xio 0.0.1

### Added

### Changed

- rdma-ep: the mlx5 atomic opcodes were swapped (compare-and-swap is 0x11 and
  fetch-add is 0x12); atomics previously failed with a local QP operation
  error.

### Removed

### Limitations

### Known issues
