<p align="center">
  <img src="https://raw.githubusercontent.com/estevanhernandez-stack-ed/Sanduhr_f-r_Claude/main/docs/images/icon-256.png" width="120" alt="Sanduhr icon">
</p>

# estevanhernandez-stack-ed / homebrew-tap

Homebrew tap for Mac apps I maintain. Use this tap until any given cask
lands in the core `Homebrew/homebrew-cask` repository.

## Usage

```sh
brew tap estevanhernandez-stack-ed/tap
brew install --cask sanduhr
```

To upgrade later:

```sh
brew update
brew upgrade --cask sanduhr
```

## Casks

| Name | Description | Homepage |
|------|-------------|----------|
| **sanduhr** | Claude.ai subscription usage widget with burn-rate alerts | [landing page](https://estevanhernandez-stack-ed.github.io/Sanduhr_f-r_Claude/) · [source](https://github.com/estevanhernandez-stack-ed/Sanduhr_f-r_Claude) |

## Why a personal tap?

`Homebrew/homebrew-cask` has a
[notability threshold](https://docs.brew.sh/Acceptable-Casks) of 90+ forks,
90+ watchers, or 225+ stars before a new self-submitted cask can be
included. This tap lets people `brew install` the app today while the
upstream project grows toward that bar.

## License

MIT — same as the apps themselves.
