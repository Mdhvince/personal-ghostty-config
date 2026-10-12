# personal-ghostty-config

Fermer Ghostty. Si le dossier cible existe déjà, le sauvegarder et le renommer avant le clonage.

## macOS

```bash
brew install --cask ghostty font-jetbrains-mono
git clone https://github.com/Mdhvince/personal-ghostty-config.git "$HOME/Library/Application Support/com.mitchellh.ghostty"
```

## Linux

Installer [Ghostty](https://ghostty.org/docs/install/binary) et la police **JetBrains Mono**, puis :

```bash
git clone https://github.com/Mdhvince/personal-ghostty-config.git "${XDG_CONFIG_HOME:-$HOME/.config}/ghostty"
```

Ouvrir Ghostty. Le dépôt est directement son dossier de configuration, sans recopie.

## Mises à jour

Ce Mac publie les changements. Sur les autres machines, dans le dossier cloné :

```bash
git pull --ff-only
```

Relancer Ghostty pour appliquer les réglages.
