# dndwebp
minimal Webp converter. drug and drop supported.

## releases
[release](https://github.com/camiha/dndwebp/releases)

## self build
require:
- node.js 18+
- rust 1.7+
- tauri development environment (https://tauri.app/v1/guides/getting-started/prerequisites)

steps:
1. `pnpm install`
2. `pnpm tauri build`
3. create application file in `src-tauri/target/release/bundle/`