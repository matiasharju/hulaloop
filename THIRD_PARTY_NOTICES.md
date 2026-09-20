# Third-party notices

Hula Loop is released under the MIT License (see [LICENSE](LICENSE)). The single file `loop.html` also embeds two third-party components. They keep their own licences, and the full texts are in the [licenses](licenses/) folder.

## LAME MP3 encoder (lamejs)

Used for the optional MP3 export.

- **Component:** lamejs 1.2.1 by Alex Zhukov, a JavaScript port of the LAME MP3 encoder. Project page: <https://github.com/zhuker/lamejs>. LAME: <https://lame.sourceforge.net/>.
- **Licence:** GNU Lesser General Public License, version 3 (LGPL-3.0). Full text: [licenses/lgpl-3.0.txt](licenses/lgpl-3.0.txt), together with the GNU General Public License, version 3, that it builds on: [licenses/gpl-3.0.txt](licenses/gpl-3.0.txt).
- **Where it is:** in `loop.html`, in its own `<script>` block placed before the application script and marked with a comment. It is the file `lame.min.js` from the npm package `lamejs@1.2.1`, unmodified apart from a trailing newline. The SHA-256 of the original file is `15d285e2587b3bdbfd18a68de6ce07cc074f7480a82c3815da2dc1c348ec6df4`.
- **Source code:** the unminified source (`lame.all.js` and the `src/` folder) is in the same npm package, <https://www.npmjs.com/package/lamejs/v/1.2.1>, and in the GitHub repository above.
- **Replacing it:** the application only uses `lamejs.Mp3Encoder`. To use a modified or different build of the encoder, replace the contents of that script block.
- **Acknowledgement:** MP3 encoding by LAME, <https://lame.sourceforge.net/>.

## Pacifico font

Used for the "Hula Loop" wordmark in the page header.

- **Component:** Pacifico Regular, version 3.001. A small subset of the font is embedded in the stylesheet of `loop.html` as a base64 WOFF2 file. The subset remains under the same licence as the font.
- **Copyright:** Copyright 2018 The Pacifico Project Authors (<https://github.com/googlefonts/Pacifico>).
- **Licence:** SIL Open Font License, Version 1.1. Full text: [licenses/OFL.txt](licenses/OFL.txt). No Reserved Font Name is declared.

## Desktop build

The Windows desktop build of Hula Loop is not part of this repository. It bundles Electron and Chromium, which ship with their own licence files.
