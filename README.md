
### Description

This is a python program for controlling Dante network audio devices (and possibly others in the future). It's very early, so expect things to break or switches to change.  The first goal is to do everything that Dante Controller can do that would be useful for control of the devices from a command-line interface or within scripts.  

For more information, check out the [gearspace discussion](https://gearspace.com/board/music-computers/1221989-dante-routing-without-dante-controller-possible.html).

### Features

- Adding/removing subscriptions
- CLI
- Display active subscriptions, Rx, Tx, devices
- JSON output
- Set device latency
- Set/reset channel names
- Set/reset device name
- mDNS device discovery

### Next features to be added

- Changing/displaying device settings (encoding, sample rate, level controls, AES67 mode)

### Planned features

- AES67 device support
- Change channel/device names without affecting existing subscriptions
- Client/server modes
- Command prompt
- Control of Shure wireless devices ([Axient receivers](https://pubs.shure.com/view/command-strings/AD4/en-US.pdf) and [PSM transmitters](https://pubs.shure.com/view/command-strings/PSM1000/en-US.pdf))
- Signal presence indicator
- Stand-alone command API
- TUI
- Web application UI
- XML output

### Usage

Install these dependencies with pip:

- argcomplete
- zeroconf

Then run with `./network_audio_controller.py`

[Examples](https://github.com/chris-ritsen/network-audio-controller/wiki/Examples)
