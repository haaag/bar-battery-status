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

## Output

```python
ICONS_DISCHARGING: IconsMap = [
    (1, 10, ''),
    (11, 20, ''),
    (21, 30, ''),
    (31, 40, ''),
    (41, 50, ''),
    (51, 60, ''),
    (61, 70, ''),
    (71, 80, ''),
    (81, 90, ''),
    (91, 94, ''),
    (95, 100, ''),
]
ICONS_CHARGING: IconsMap = [
    (1, 14, ''),
    (15, 29, ''),
    (30, 44, ''),
    (45, 59, ''),
    (60, 74, ''),
    (75, 89, ''),
    (90, 100, ''),
]
ICONS_UNKNOWN: IconsMap = [(1, 100, '')]
ICONS_FULL: IconsMap = [(1, 100, '')]
```

## License

`bar-battery` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
