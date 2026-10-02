# Homebrew tap for pkmn-cli

This is the official MAQ / BiG MAQ Studios Homebrew tap for
[`pkmn-cli`](https://github.com/AAAMAQ/pkmn-cli).

The packaged tool is an independent MIT-licensed educational, research,
archival, and game-preservation project. This tap does not distribute ROMs or
private save data and is not affiliated with Nintendo, Game Freak, Creatures,
or The Pokémon Company.

Install the stable 3.1.0 release:

```sh
brew tap AAAMAQ/pkmn
brew install AAAMAQ/pkmn/pkmn-cli
pkmn --version
pkmn doctor --deep
pkmn interactive
```

Run the formula test with:

```sh
brew test AAAMAQ/pkmn/pkmn-cli
```

The formula builds from a versioned source archive with its downloaded SHA-256.
Homebrew installs CMake and Python as required; this is not a prebuilt bottle.
For an update, run `brew update` then `brew upgrade AAAMAQ/pkmn/pkmn-cli`.
If you previously installed `--HEAD`, use `brew reinstall AAAMAQ/pkmn/pkmn-cli`
to move to stable. Use `--HEAD` only when deliberately testing development code.

The Japanese conversion routes are experimental; review the release notes and
test generated copies in your emulator. This tap does not distribute ROMs,
saves, screenshots, or proof evidence.
