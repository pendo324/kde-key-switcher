## KDE Key Switcher

This script uses [input-remapper](https://github.com/sezanzeb/input-remapper) and the [Publish Resource on Activate KWin script](https://github.com/pendo324/publish-resource-on-activate) to create an automatic key switcher that is compatible with KDE on Wayland or X11.

I use this to switch mouse keys on my mouse, because there's not a first-party / good solution available on Linux.

### Future work

1. Make the program + profile names more configurable.
    1. `key-switcher` is currently more of an example to be edited, rather than a 1-size-fits-all solution.

### Setup

The script assumes you have all of the pre-requisites installed, and that you have setup your mouse in Input Remapper.

You should have several profiles to switch between pre-configured, before trying to use this script.

If the buttons you want to remap are not working in Input Remapper, you might want to remap them to F13+ keys. This can be useful for mice with extra mouse buttons (beyond M4/M5).

### Usage

1. Clone this repo: `git clone https://github.com/pendo324/kde-key-switcher.git`
1. Run the script: `./key-switcher <mouse_name>`, e.g. `./key-switcher "Razer Razer Naga Trinity"`

#### Advanced

##### Configure the script to run automatically on start

I usually do this using the Autostart system settings menu included with KDE. Other solutions could be a systemd unit.
