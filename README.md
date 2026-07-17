# Homebrew tap for pkmn-cli

This is the official MAQ / BiG MAQ Studios testing tap for
[`pkmn-cli`](https://github.com/AAAMAQ/pkmn-cli).

Until the first stable tagged release, install the verified public `main`
branch explicitly with `--HEAD`:

```sh
brew tap AAAMAQ/pkmn
brew install --HEAD AAAMAQ/pkmn/pkmn-cli
pkmn --version
pkmn doctor --deep
```

Run the formula test with:

```sh
brew test AAAMAQ/pkmn/pkmn-cli
```

The formula will move to an immutable tagged source archive and its downloaded
SHA-256 only after the release acceptance gates are complete. This tap does not
distribute ROMs, saves, screenshots, or proof evidence.
