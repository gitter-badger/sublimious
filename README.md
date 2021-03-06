# Rock your SublimeText with VIM keybindings and Sublimious!

```
Sublimious is SublimeText 3 configuration system inspired by spacemacs and based around VIM.
```

![Shortcuts](http://i.imgur.com/Y6xgSyW.png)

### Install
for the moment, sublimious is not hosted on package control yet. To install, clone this repository into your `Packages` directory.

__Be warned__! Sublimious is a complete configuration system and will nuke your existing configuration. Make sure to backup your configs before trying sublimious!

### Features
- __Preconfigured__: sublimious instantly makes sublime text better by shipping with a handful of hand-tested settings
- __VIM everywhere!__: All packages included with sublimious have been remapped to fit with vim keybindings
- __Sasy to remember mnemonic__: Each command is mapped to a category / key combination that fits the action. `<spc> w v` for example splits the __w__indow __v__ertically. 
- __Layer based configuration__: Check `layers/` for all configuration sets shipping with sublimious. Just add it to your `~/.sublimious` config and they will be included upon restart
- __Easy to use with dotfiles__: Just take your `~/.sublimious` config to your new pc and it will act exactly the same way as it did on your other pc
- __Central configuration__: Instead of maintaining 10 files, you only have 1 to put your settings in

### Keybindings

Sublimious comes with a keybinding helper to ease you in with everything. Just hit `space` and a popup will tell you what you can perform.

In general, sublimious follows the spacemacs mnemonic:
- `<spc> p` is for project commands
- `<spc> b` is for actions on the current buffer
- `<spc> g` is for git (needs git layer)
- `<spc> w` for window (splits and co)
- `<spc> s` for the current (visual) selection
- `<spc> e` for errors (linting)

Sublimious tries to add vim-like keybindings for every plugin possible. Sidebar navigation for example has been remapped to `j/k`.


### To-Dos:

- [x] get a basic version with space keybindings running
- [x] implement spacemacs-like shortcut helper
- [x] add README files for each layer
- [x] add a simple screenshot to README.md
- [x] add config for helper timeout to .sublimious
- [x] find a way to configure layers right out of .sublimious config
- [x] make `f <spc>` work
- [x] make `<spc> p f` work
- [ ] add option to bind custom actions to sublimious 
- [ ] add option to execute / register functions from within .sublimious
- [ ] add some kind of framework / lib to give information about current state back (e.g. tab index). Needed for comamnds like `close all other tabs`
- [ ] add easier descriptions for commands
- [ ] allow multiple commands bound to the same action
- [ ] fix initial installation process (currently throwing a ton of errors)
- [ ] add a better default .sublimious
- [ ] adjust the shortcut helper's width automagically
- [ ] add better README files for each layer
- [ ] watch .sublimious file for changes and reload plugin
- [ ] find a way to tell Package Control to reload (necessary?)
- [ ] add a better default color scheme
- [ ] add install instructions to README
- [ ] submit to package control
- [ ] add more layers
- [ ] add more shortcuts
