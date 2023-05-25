# Tmux

## Tmux Resurrect
### Install
Installation with Tmux Plugin Manager (recommended)

Add plugin to the list of TPM plugins in .tmux.conf:
~~~
set -g @plugin 'tmux-plugins/tmux-resurrect'
~~~
Hit prefix + I to fetch the plugin and source it. You should now be able to use the plugin.

### Usage
Key bindings
prefix + Ctrl-s - save
prefix + Ctrl-r - restore


## Tmux Plugin Manager (TPM)
### Key bindings

`prefix` + <kbd>I</kbd>
- Installs new plugins from GitHub or any other git repository
- Refreshes TMUX environment

`prefix` + <kbd>U</kbd>
- updates plugin(s)

`prefix` + <kbd>alt</kbd> + <kbd>u</kbd>
- remove/uninstall plugins not on the plugin list
