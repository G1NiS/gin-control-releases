# Third-party notices

GIN Control includes third-party software. Those components remain subject to
their own licenses; the proprietary GIN Control license does not restrict any
rights granted by an open-source license.

## OpenRGB and its bundled runtime

GIN Control ships **OpenRGB 1.0**, Windows 64-bit build `81bbe18`, as a separate
process and communicates with it through the OpenRGB SDK protocol.

- License: [GNU General Public License version 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
- Project: <https://openrgb.org/>
- Source for the bundled version: <https://codeberg.org/OpenRGB/OpenRGB/src/tag/release_1.0>
- Source archive: <https://codeberg.org/OpenRGB/OpenRGB/archive/release_1.0.zip>

**Written source offer:** For at least three years after this binary release,
Edvinas Giniotis offers any third party a complete machine-readable copy of
the corresponding source code for the bundled OpenRGB 1.0 build, for no more
than the reasonable cost of physically providing the source. Submit a request
through the [OpenRGB source request form](https://github.com/G1NiS/gin-control-releases/issues/new?template=source_code_request.yml).

The OpenRGB Windows package also contains the following separately licensed
runtime components:

| Component | Bundled version | License | Source / license information |
|---|---:|---|---|
| Qt | 6.8.3 | LGPL-3.0-only, GPL-3.0-only, or commercial | <https://www.qt.io/licensing/open-source-lgpl-obligations>, <https://download.qt.io/archive/qt/6.8/6.8.3/submodules/> |
| libusb | 1.0.27 | LGPL-2.1-or-later | <https://github.com/libusb/libusb/tree/v1.0.27> |
| HIDAPI | 0.15.0 | BSD-style license selected for this distribution | <https://github.com/libusb/hidapi/tree/hidapi-0.15.0> |
| DirectX Shader Compiler (`dxcompiler.dll`, `dxil.dll`) | 10.0.19041.5609 | University of Illinois/NCSA and bundled third-party terms | <https://github.com/microsoft/DirectXShaderCompiler/blob/main/LICENSE.TXT> |
| PawnIO / PawnIOLib | bundled with OpenRGB | GPL-2.0-or-later with the upstream special exception | <https://github.com/namazso/PawnIO> |

## Fan and sensor service

The self-contained GIN Control service includes these components:

| Component | Bundled version | License | Source / license information |
|---|---:|---|---|
| LibreHardwareMonitorLib | 0.9.6 | MPL-2.0 | <https://github.com/LibreHardwareMonitor/LibreHardwareMonitor/tree/3d331e3370efb858411f19511373eff65a218701> |
| BlackSharp.Core | 1.0.7 | MPL-2.0 | <https://github.com/Blacktempel/BlackSharp/tree/c70b735c6cec123ee8a046ac4a0bc6c606f52cf0> |
| DiskInfoToolkit | 1.1.2 | MPL-2.0 | <https://github.com/Blacktempel/DiskInfoToolkit/tree/25319eae5781e75bcf141e844ceab2afe94d40ea> |
| RAMSPDToolkit-NDD | 1.4.2 | MPL-2.0 | <https://github.com/Blacktempel/RAMSPDToolkit/tree/3b47b960e0830fef344624ad5e389675d5f0a1ce> |
| HidSharp | 2.6.4 | Apache-2.0 | <https://github.com/IntergatedCircuits/HidSharp/tree/main-2.6> |
| Mono.Posix.NETStandard | 1.0.0 | BSD-3-Clause | <https://www.nuget.org/packages/Mono.Posix.NETStandard/1.0.0> |
| Microsoft .NET runtime and Microsoft.Extensions libraries | 8.0.32 / 8.0.x | MIT and bundled third-party terms | <https://github.com/dotnet/dotnet>, <https://github.com/dotnet/runtime/blob/main/LICENSE.TXT>, <https://github.com/dotnet/runtime/blob/main/THIRD-PARTY-NOTICES.TXT> |

The MPL-2.0 license text is available at
<https://www.mozilla.org/MPL/2.0/>. The listed repositories provide the
corresponding source for the exact package versions used by GIN Control.

HidSharp copyright (c) 2010-2025 James F. Bellinger. The Apache License 2.0
text is available at <https://www.apache.org/licenses/LICENSE-2.0>.

## Desktop application

| Component | Bundled version | License | Source / license information |
|---|---:|---|---|
| Tauri | 2.12.3 | MIT or Apache-2.0 | <https://github.com/tauri-apps/tauri> |
| Tauri autostart plugin | 2.7.0 | MIT or Apache-2.0 | <https://github.com/tauri-apps/plugins-workspace> |
| Tauri log plugin | 2.10.1 | MIT or Apache-2.0 | <https://github.com/tauri-apps/plugins-workspace> |
| Tauri single-instance plugin | 2.5.3 | MIT or Apache-2.0 | <https://github.com/tauri-apps/plugins-workspace> |
| React and React DOM | 19.3.0 | MIT | <https://github.com/facebook/react> |
| Scheduler | 0.28.0 | MIT | <https://github.com/facebook/react> |
| Zustand | 5.0.15 | MIT | <https://github.com/pmndrs/zustand> |
| Phosphor Icons for React | 2.1.10 | MIT | <https://github.com/phosphor-icons/react> |
| cpal | 0.18.2 | Apache-2.0 or MIT | <https://github.com/RustAudio/cpal> |
| hidapi Rust crate | 2.6.7 | Apache-2.0 or MIT | <https://github.com/ruabmbua/hidapi-rs> |
| rustfft | 6.4.1 | Apache-2.0 or MIT | <https://github.com/ejmahler/RustFFT> |
| serde / serde_json | 1.x | Apache-2.0 or MIT | <https://github.com/serde-rs/serde>, <https://github.com/serde-rs/json> |
| windows-rs / windows-sys | 0.61.x | Apache-2.0 or MIT | <https://github.com/microsoft/windows-rs> |

The desktop executable also statically includes transitive Rust crates under
permissive licenses including MIT, Apache-2.0, BSD-2-Clause, BSD-3-Clause,
ISC, Unicode-3.0, Zlib, CC0-1.0, MIT-0, 0BSD, and the Unlicense. Their package
metadata and source are available through <https://crates.io/> and the
repositories linked from each crate's page. The standard license texts are
available from the [SPDX license list](https://spdx.org/licenses/).

## Standard license texts

- GPL-2.0: <https://www.gnu.org/licenses/old-licenses/gpl-2.0.html>
- GPL-3.0: <https://www.gnu.org/licenses/gpl-3.0.html>
- LGPL-2.1: <https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html>
- LGPL-3.0: <https://www.gnu.org/licenses/lgpl-3.0.html>
- MPL-2.0: <https://www.mozilla.org/MPL/2.0/>
- Apache-2.0: <https://www.apache.org/licenses/LICENSE-2.0>
- MIT: <https://opensource.org/license/mit>
