# Dracula for [tmux](https://github.com/tmux/tmux/wiki)

> A dark theme for [tmux](https://github.com/tmux/tmux/wiki)

![Screenshot](./screenshot.png)

## Install

Using [tpm](https://github.com/tmux-plugins/tpm), add the following to your `.tmux.conf` file:

```
set -g @plugin 'snim2/tmux-monokai-pro'
```
## Configuration

Configuration and options can be found at [draculatheme.com/tmux](https://monokaitheme.com/tmux).

Note that all configuration on those pages needs `dracula` to be replaced by `monokai`.

## Features

- Support for powerline
- Day, date, time, timezone
- Current location based on network with temperature and forecast icon (if available)
- Network connection status, bandwidth and SSID
- Git branch and status
- Battery percentage and AC power connection status
- Refresh rate control
- CPU usage (percentage or load average)
- RAM usage
- GPU usage
- Custom status texts from external scripts
- GPU VRAM usage
- GPU power draw
- Color code based on if prefix is active or not
- List of windows with current window highlighted
- When prefix is enabled smiley face turns from green to yellow
- When charging, 'AC' is displayed
- If forecast information is available, a ☀, ☁, ☂, or ❄ unicode character corresponding with the forecast is displayed alongside the temperature
- Spotify playback (needs the tool spotify-tui installed)
- Current kubernetes context
- Current working directory of tmux pane

## Compatibility

Compatible with macOS and Linux. Tested on tmux 3.1b
FreeBSD compatibility is in development

## Credits

This theme was forked from [dracula/tmux](https://github.com/dracula/tmux), and based on [@maxpetretta's fork](https://github.com/maxpetretta/tmux-monokai-pro/).

The theme defaults are taken from [Monokai](https://monokai.nl/).
## License

[MIT License](./LICENSE)
