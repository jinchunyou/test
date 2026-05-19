# Commit Translation Stress Test

This file exists only to trigger commit notification tests for DengBaiJK.

## Scenario

- keep `auto-close`, `config.yaml`, `rule-providers`, and `proxy-providers` readable in WeChat
- preserve path `src-tauri/src/core/profiles.rs` and function `merge_config()`
- avoid duplicate URL rendering when details already link to https://example.com/profile.yaml
- 中文补充：保持 @jinchun 和 github-actions[bot] 原样

## Follow-up Scenario

- avoid duplicate URL rendering for https://example.com/commit-follow-up.yaml
- keep `fake-ip-filter`, `pnpm test -- --runInBand`, and `src/main.ts` unchanged
- verify Telegram uses bottom buttons for commit details
- 企业微信补充：不要显示“类型: 新提交”
