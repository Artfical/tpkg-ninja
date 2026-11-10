# ninja

Ninja 1.12.1, the small fast build tool

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install ninja
```

| | |
|---|---|
| Version | 1.12.1 |
| Licence | Apache-2.0 |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 126684 bytes (273768 unpacked) |
| SHA-256 of the `.tpkg` | `eb79b204457b252ce858c7b90487ff490ed9eb3c9007ced66b90b52f1cb4afec` |

## Commands it adds

| Command | Runs |
|---|---|
| `ninja` | `bin/ninja` |

## Download

The package file (`ninja-1.12.1.tpkg`) and the sources it was built from are the assets of the
[v1.12.1 release](https://github.com/Artfical/tpkg-ninja/releases/tag/v1.12.1).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `ninja-linux.zip`

Check a download: `sha256sum ninja-1.12.1.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: Apache-2.0. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
