# Terminal color theme configuration for Tmux

Theme based on egel's [tmux-gruvbox](https://github.com/egel/tmux-gruvbox) which mainly uses colors
from your terminal for easy integration.

## Installation
### Install manually
The simplest way is just:

> HINT: Always make a backup of your config files before any action.

```bash
cat tmux-terminal-theme.conf >> ~/.tmux.conf
```

### Install through [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)
Add plugin to the list of TPM plugins in `.tmux.conf`
```
set -g @plugin 'konapun/tmux-terminal-theme'
```
Hit `prefix + I` to fetch the plugin and source it.
Your tmux should be updated with the theme at this point.

## Configuration

  * TMUX_STATUSBAR_BG (default `colour0`) the color between left and right status pieces
  * TMUX_LEFT_SEGMENT_START (default ``) block segment start shape for left status
  * TMUX_LEFT_SEGMENT_END (default ``) block segment end shape for left status
  * TMUX_LEFT_SEPARATOR (default ``) separator character between left segments
  * TMUX_RIGHT_SEGMENT_START (default ``) block segment start shapes for right status
  * TMUX_RIGHT_SEGMENT_END (default ``) block segment end shapes for right status
  * TMUX_RIGHT_PAD (default ``) block pad character for right status

## License
GPLv3

