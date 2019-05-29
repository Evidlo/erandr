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

## See also

- [arandr](https://christian.amsuess.com/tools/arandr/)
