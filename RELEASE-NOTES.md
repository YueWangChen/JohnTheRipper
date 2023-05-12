# Release Notes

This is the `john-packages` (itself) 0.9 release 'v0.9.0'. October 2023 (version 0.9.0)

## [john-dev](https://github.com/openwall/john-packages/archive/refs/tags/jumbo-dev.zip) (2023-06-26)

### Breaking Changes

- Due to changes in Cygwin, plus OS and hardware unavailability in common cloud build environments,
  we deprecate 32 bits architetures.

### Bugfixes

- Important bugfixes in Zip and Office formats;
- A lot of minor and important bugfixes everywhere.

### Improvements

- From now on we create signed GitHub releases;
- Add a macOS package;
- Add OpenCL support to the John the Ripper Docker image;
- Turn John the Ripper Docker image into a digitally signed image using Sigstore;
- Add extensive use of Continuous Integration (CI). See [the CI and CD](https://github.com/openwall/john-packages/tree/main/tests#continuous-integration-and-continuous-delivery) procedures;
- Add a lot of automatic QA checking to the john-packages repository;
- Add new formats and/or implementations;
- Improve formats detection and valid() implementations;
- Improved our portable hi-res timer for nano-second resolution on most archs;
- A lot of minor and important improvements everywhere;
- Improvements and tweaks to john's usage of autoconf.

### Other Changes

- None.

------
