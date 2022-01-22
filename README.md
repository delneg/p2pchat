## p2p chat


* Navigate between tabs with 'tab' key
* Connect using ip's shown on Connection tab


## Development (Nix flakes)

This repo uses [Flakes](https://nixos.wiki/wiki/Flakes) from the get-go, but compat is provided for traditional nix-shell/nix-build as well (see the section below).

```bash
# Dev shell
nix develop

# or run via cargo
nix develop -c cargo run
```

## Development (Legacy Nix)

```bash
# Dev shell
nix-shell

# run via cargo
nix-shell --run 'cargo run'
```