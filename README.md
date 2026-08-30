# homebrew-tap

The Homebrew tap for 178inaba's command-line tools.

## Install

```sh
brew install 178inaba/tap/<name>
```

- [rdsh](https://github.com/178inaba/rdsh) — A CLI that runs ad-hoc SQL on Redash and manages saved queries there, designed so AI coding agents can call it from a shell.
- [cflio](https://github.com/178inaba/cflio) — A Confluence Cloud CLI built for AI coding agents.
- [slio](https://github.com/178inaba/slio) — A read-only Slack CLI built for AI coding agents.

## Platform

The casks are built for macOS. On Linux, see each CLI's README for its other install routes.

## Maintenance

`Casks/*.rb` is generated and overwritten by [GoReleaser](https://goreleaser.com/customization/homebrew_casks/) from each CLI's release workflow, so do not edit it by hand — a change belongs in that CLI's `.goreleaser.yaml`.
