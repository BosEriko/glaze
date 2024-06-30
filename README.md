# GlazeWM (Window Manager)
Download [Scoop](https://github.com/BosEriko/scoop) as your package manager then install [GlazeWM](https://scoop.sh/#/apps?q=glazewm).

## Install GlazeWM
```sh
scoop bucket add extras
scoop install extras/glazewm
```

## Install Font
```sh
scoop bucket add nerd-fonts
scoop install nerd-fonts/JetBrainsMono-NF-Mono
```

## Sync your settings
Go to the folder where the current `config.yaml` is located and run the following script.
```sh
curl -fsSL https://raw.githubusercontent.com/BosEriko/glaze/HEAD/install.sh | sh
```

_Note: `config.yaml` is usually located at `%HOMEPATH%\.glaze-wm`._
