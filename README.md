# bar-battery

Python script that monitors the battery status and sends notifications when the
battery's capacity reaches a critical level.
It reads the battery status and capacity from system files and then prints a pretty-formatted
status message for the battery.
It's for use in minimalist windows managers bars (e.g. dwm, qtile).

## Installation

```bash
# clone repository
$ git clone "https://github.com/haaag/bar-battery-status"
$ cd bar-battery-status

# run
$ bar-battery
```

## Requirements

_Patched GUI Font_ is mandatory for icons, the most popular patched fonts are [nerd
fonts](https://www.nerdfonts.com/).

## Screenshot

<br>
    <img align="center" src="https://github.com/haaag/bar-battery-status/blob/master/img/icons-screenshot.png?raw=true">
<br>

## TODO

- [ ] Make animated charging state

## License

`bar-battery` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
