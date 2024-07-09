# An [Alacritty](https://github.com/alacritty/alacritty) Config

## Usage

### Recommended

Clone the repository to `$HOME/.config/alacritty` by running the following:
```
mkdir ~/.config
cd $_
git clone --recurse-submodules https://github.com/lnoir/alacritty-config alacritty
```
- First line ensures you actually have a `.config` directory in your home (`~`) direcrtory.
- Second line changes directory to the one just created (`$_` reuses the last argument).
- Third line clones the repo.

This will place the configuration in a location the Alacritty will look for it by default. It also clones the [`alacritty-theme repo`](https://github.com/alacritty/alacritty-theme) into the themes directory, making it easy to switch and try out different themes/.

### Alternative

Of course, you can clone the config wherever you like. Just run:
```
git clone --recurse-submodules https://github.com/lnoir/alacritty-config [config-directory-name]
```

...where `[config-directory-name]` should be replaced with:
- the name you'd like to use for the directory
- a `.` to clone into the current directoryor
- nothin at all, but rather omitted to just clone the repo as is


