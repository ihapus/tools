# ihapus pub

`pub` is the public distribution repository for the `ihapus` tool collection.

This repository is intentionally separate from the private source repository
`utils`. It is used to host public-facing documentation, release notes, license
files, and binary release assets.

## Available tools

### ImageBatcher
- Project page: `ImageBatcher/README.md`
- Releases: `https://github.com/ihapus/pub/releases`
- Status: preparing initial public release

More tools can be added later under their own subdirectories.

## Repository layout

```text
pub/
  README.md
  ImageBatcher/
    README.md
    CHANGELOG.md
    LICENSE
    THIRD_PARTY_NOTICES.txt
```

## Principles

- No private source code is published here
- Each tool has its own public-facing folder
- Release assets are attached to GitHub Releases
- License and third-party notices travel with each released tool
