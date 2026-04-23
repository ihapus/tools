# ImageBatcher 1.0.1

## What it does
ImageBatcher is a Windows batch image resizer and compressor for common image workflows.

## Good for
- batch resize images on Windows
- compress image files before upload
- prepare product listing images
- standardize repeated export workflows
- handle folders that contain common JPG, PNG, BMP, TIFF, WebP, GIF, ICO, TGA, or WBMP assets

## Included in this release
- `ImageBatcher-1.0.1-setup.exe`
- `ImageBatcher-1.0.1-setup.sha256.txt`
- `LICENSE`
- `THIRD_PARTY_NOTICES.txt`

## Changes since 1.0.0
- The installer now includes Qt image format plugins under `imageformats`.
- Image import support is expanded through Qt plugins, including JPG, PNG, BMP, TIFF, WebP, GIF, ICO, TGA, and WBMP workflows.
- Output format handling is clearer for Preserve, JPG, PNG, and WebP modes.
- The interface has been refined with dark/light themes, radio option groups, resize modes, conflict rules, and processing statistics.

## System requirements
- Windows 10 or later
- Enough disk space for input and output images

## Verification
Use the included SHA256 file to verify the installer before distribution.

## Notes
- This release is distributed as proprietary software by `ihapus`.
- Third-party components remain under their own license terms.
- Product page: https://ihapus.github.io/tools/imagebatcher/
