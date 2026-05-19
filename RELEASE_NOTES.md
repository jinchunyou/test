[clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev/releases/tag/v2.5.0)

## What's Changed

👙 UI / Layout
- refactor Sidebar layout to prevent flicker when switching profiles, optimized by @jinchun
- fix Sticky Scroll behavior in proxy groups when `auto-close` is enabled
- keep `src-tauri/src/core/profiles.rs` path unchanged in error output

🔧 Core
- bump mihomo core to v1.19.8
- fix panic when `config.yaml` contains mixed `rule-providers` and `proxy-providers`
- improve DNS fallback handling for `fake-ip-filter`, do not translate `fake-ip-filter`

🐛 Bug Fixes
- fix Windows tray menu not refreshing after `Restart App`
- 修复 macOS 下点击 Dock 图标无法重新显示主窗口的问题
- prevent duplicate profile import from URL: https://example.com/profile.yaml

🧪 Tests
- add regression test for `merge_config()` with empty rules
- run `pnpm test -- --runInBand` before release

Full Changelog: https://github.com/clash-verge-rev/clash-verge-rev/compare/v2.4.2...v2.5.0

## New Contributors
- @new-user made their first contribution in https://github.com/clash-verge-rev/clash-verge-rev/pull/9999

## Assets
- Clash.Verge_2.5.0_x64-setup.exe
- Clash.Verge_2.5.0_aarch64.dmg
