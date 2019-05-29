# erandr

Simple xrandr wrapper for configuring monitors from command line or rofi/dmenu.

## Install

Copy `erandr` to somewhere in your `$PATH`.

Alternatively, install via [bpkg](https://github.com/bpkg/bpkg).

``` bash
bpkg install evidlo/erandr
```

## Usage

``` bash
# place secondary display to the left of primary
erandr left

# place secondary display to the right of primary
erandr right

# place secondary display to the left of primary, rotate -90
erandr left vert

# place secondary display to the left of primary, rotate +90
erandr left rvert

# use secondary screen as main monitor, disable primary
erandr movie

# return to normal single display on primary
erandr single
```

## Configuration

Auto-detected primary and secondary monitors can be overriden in `~/.config/erandr`.  A command for resetting the wallpaper after executing xrandr can also be specified.

*~/.config/erandr*
```
primary="VGA1"
secondary="VGA2"
set_wallpaper="feh --bg-fill ~/pictures/wallpaper.jpg"
```
## See also

- [arandr](https://christian.amsuess.com/tools/arandr/)
