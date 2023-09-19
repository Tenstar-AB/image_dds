# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## unreleased
### Added
* Added optional serde support for enums and surfaces.
* Added optional strum support for enums.
* Added encode/decode support for the `R16G16B16A16Float` format.

### Changed
* Relaxed validation and implemented padding to allow encoding BCN surfaces with non integral dimensions in blocks.
* Combined `CompressSurfaceError` and `DecompressSurfaceError` into `SurfaceError`.
* Changed surface conversion functions to be methods instead of functions to support chaining.

## 0.1.1 - 2023-03-21
### Fixed
* Fixed an issue decoding images with non integral dimensions in blocks.

## 0.1.0 - 2023-03-13
* First public release!