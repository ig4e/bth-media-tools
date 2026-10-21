# BTH media tools

Immutable mirrors of unchanged, publicly released FFmpeg archives used by BTH's automatic media-tool installer. This repository contains third-party distribution files and their checksum-verification workflow.

The release `tools-ffmpeg-9.0.2-20261021` mirrors FFmpeg9.0.2 builds from [BtbN autobuild-2026-10-21-13-06](https://github.com/BtbN/FFmpeg-Builds/releases/tag/autobuild-2026-10-21-13-06). Complete upstream archives are preserved, including README, build configuration and licensing material. The native targets are Linux x86_64, Linux ARM64 and Windows ARM64. The Windows x86_64 installer uses the numbered [Gyan9.0.2 release](https://github.com/GyanD/codexffmpeg/releases/tag/9.0.2).

`SHA256SUMS` contains the exact SHA256 digests checked by the installer. Publication downloads the original archives, verifies all embedded pins and publishes those same bytes. Existing versions are immutable.

Source and build recipes: [BtbN FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds/tree/autobuild-2026-10-21-13-06), [FFmpeg9.0.2 source](https://github.com/FFmpeg/FFmpeg/tree/n9.0.2), and the source links/license notices included in each complete archive. The mirrored archives are the upstream GPL builds and retain their original licenses.