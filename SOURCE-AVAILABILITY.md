# Third-party source availability

AMM's original source is proprietary and is not offered by this document. Third-party components keep the source, modification and redistribution rights granted by their own licenses. The proprietary license expressly preserves those rights.

The Windows runtime is unmodified Electron45.0.0. Its full component notices are included in legal/licenses/LICENSES.chromium.html. Electron's tagged source and dependency manifest are available at:

- https://github.com/electron/electron/tree/v45.0.0
- https://github.com/electron/electron/blob/v45.0.0/DEPS
- https://github.com/electron/electron/releases/tag/v45.0.0
- https://www.electronjs.org/docs/latest/development/build-instructions-gn

The inspected tagged manifest pins Chromium156.0.8078.48 and Node v24.22.0. Chromium's matching tree, including dependency revisions, is https://chromium.googlesource.com/chromium/src/+/156.0.8078.48/ . Follow its DEPS file for the corresponding FFmpeg and other third-party repositories. The notices identify component homepages and license texts. Some components have MPL, LGPL or CPL terms; the mere presence of a referenced GPL name in a license notice does not establish that AMM itself is GPL-licensed.

NSIS3.0.4.1 and installer resources3.4.1 are unmodified build inputs. The bundled NSIS COPYING is included. Source/build references: https://github.com/electron-userland/electron-builder-binaries/releases and https://nsis.sourceforge.io/Source_Code . Build-tool source is distinct from the proprietary application source.

A recipient may use the applicable third-party licenses to modify or replace covered components and debug such modifications. Do not interpret AMM's branding or redistribution restrictions as restrictions on those component rights. Replacing runtime components may affect compatibility and publisher signatures; use a backup and preserve notices.

Release preparation status: these upstream references have been identified, but a complete retained corresponding-source fulfillment set for all LGPL/MPL/CPL-covered shipped components and installer plugins has not yet been verified. The publisher must resolve that distribution obligation before publishing this candidate. These links are not an assertion that every source-access obligation has already been satisfied, and are not a written promise to provide source that has not been retained.
