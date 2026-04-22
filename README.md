# ihapus tools

`tools` is the public distribution repository for the `ihapus` tool collection.

This repository hosts public-facing product pages, release notes, license files,
and binary downloads for lightweight Windows utilities maintained by `ihapus`.

Website:
- `https://ihapus.github.io/tools/`

Releases:
- `https://github.com/ihapus/tools/releases`

## Available tools

| Tool | What it does | Platform | Download | Docs |
|------|--------------|----------|----------|------|
| ImageBatcher | Batch resize and compress JPG and PNG images for Windows workflows | Windows | [Latest releases](https://github.com/ihapus/tools/releases) | [Product page](https://ihapus.github.io/tools/imagebatcher/) |

## Why this repository exists

- public downloads stay separate from private source code
- each tool gets its own public-facing documentation
- GitHub Releases remain the primary download channel
- GitHub Pages provides searchable product pages and release entry points

## Repository layout

```text
tools/
  README.md
  docs/
    index.html
    imagebatcher/
  ImageBatcher/
    README.md
    CHANGELOG.md
    LICENSE
    THIRD_PARTY_NOTICES.txt
```

## Current focus

### ImageBatcher
- Windows batch image resizer and compressor
- useful for e-commerce image prep, JPG/PNG compression, and repeated export tasks
- public product page: `https://ihapus.github.io/tools/imagebatcher/`
- release downloads: `https://github.com/ihapus/tools/releases`

More tools can be added later using the same structure.
