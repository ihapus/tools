# Changelog

## 1.0.1

- Fix runtime settings storage so `settings.ini` is written under `%APPDATA%/ihapus/ImageBatcher/` instead of the install directory.
- Bundle Qt image format plugins with the installer and load them from the application directory at runtime.
- Expand practical image format support through Qt image plugins, including JPG, PNG, BMP, TIFF, WebP, GIF, ICO, TGA, and WBMP import workflows.
- Improve output format handling for Preserve, JPG, PNG, and WebP workflows, with clearer fallback behavior for unsupported writer formats.
- Refine the v1.1 UI foundation, including theme switching, radio options, result statistics, conflict rules, and resize modes.

## 1.0.0

- First official public release
- Windows installer packaging based on the current `bin/` packaging flow
- Batch image resizing with preset or custom dimensions
- Batch image compression for JPG and PNG workflows
- Public product page, release notes, and third-party notice files prepared for distribution
