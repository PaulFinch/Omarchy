# Omarchy

This is a fork from [Omarchy](https://github.com/basecamp/omarchy).

These modifications have been applied in order to work with Omarchy-ISO-Creator:
- Removed the `--now` option from `systemctl enable --now` in install scripts (systemd is not running in chroot env)
- Add OMARCHY_NOREBOOT variable to remove the reboot at the end (not working in chroot env)

Turn a fresh Arch installation into a fully-configured, beautiful, and modern web development system based on Hyprland by running a single command. That's the one-line pitch for Omarchy (like it was for Omakub). No need to write bespoke configs for every essential tool just to get started or to be up on all the latest command-line tools. Omarchy is an opinionated take on what Linux can be at its best.

Read more at [omarchy.org](https://omarchy.org).

## License

Omarchy is released under the [MIT License](https://opensource.org/licenses/MIT).

