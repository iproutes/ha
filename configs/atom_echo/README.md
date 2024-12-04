### Atom Echo Configs

The `firmware.yaml` config file is designed to be loaded onto an Atom Echo device for Home Assistant Voice. I didn't create this file, there's reference to the source inside the config file. I only made some changes to:

- Mute the onboard speaker
- Send the output to a `media_player` instance, in my case, a google home speaker.

Several things need to be changed in the config before you try to use it, anything surrounded with asterisks (*) needs attention:
- Encryption key
- `media_player` output device
- Static IP address (you can use DHCP and rip out the static lines, but my device seemed to have trouble with that)

