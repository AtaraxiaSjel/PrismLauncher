<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo-darkmode.svg">
  <source media="(prefers-color-scheme: light)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo.svg">
  <img alt="Prism Launcher" src="/program_info/org.prismlauncher.PrismLauncher.logo.svg" width="40%">
</picture>
</p>

# About this Fork

> This project is a Fork of Prism Launcher, which aims to 'unblock' the use of Offline Accounts, disabling the restriction of having a functional Online Account. No other modifications were applied to the project's source code.

## Downloads

Auto compile every Sunday. Link to latest build:

[Latest Builds (Debug mode) on service nightly.link](https://nightly.link/AtaraxiaSjel/PrismLauncher/workflows/trigger_builds/develop)

### For NixOS users

Add this repo as input to your flake:

```nix
inputs.prismlauncher.url = "github:AtaraxiaSjel/PrismLauncher/develop"
```

and then add this package to your overlay, system config or home-manager:

```nix
inputs.prismlauncher.packages.${system}.default
```

Cache for Nix is available on [Cachix](https://app.cachix.org/cache/ataraxiadev-foss).
