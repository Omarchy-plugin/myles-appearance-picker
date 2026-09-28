# myles.appearance-picker

One bar button for Omarchy's theme and wallpaper pickers, grouped and filtered.

One bar button that opens Omarchy's theme and wallpaper pickers, grouped and filtered.

## What it does

- Themes and wallpapers in a single panel, grouped by category.
- Preview before you apply.
- Cycle actions for quick switching without opening the full picker.

Applies changes through Omarchy's own commands, so your theme settings stay canonical.

## Requirements

- `omarchy-theme-set` and `omarchy-theme-bg-set` (both ship with Omarchy).
- Any themes/wallpapers already installed in your Omarchy config.

## Network calls

None.

## Install

```bash
omarchy plugin add https://github.com/Omarchy-plugin/myles-appearance-picker.git --enable --yes
```

That clones, validates, installs to `~/.config/omarchy/plugins/myles.appearance-picker/`, and places it on your bar.

## Update

```bash
omarchy plugin update myles.appearance-picker --yes
```

Or update every git-managed plugin at once:

```bash
omarchy plugin update --yes
```

## Uninstall

omarchy plugin remove myles.appearance-picker --yes

## Credits

- Built for [Omarchy](https://omarchy.org).
- Mylesoft — <https://github.com/Omarchy-plugin> — modifications.

Plugins run unsandboxed inside the long-lived `omarchy-shell` process with your user
permissions. Review the source before enabling anything you did not write.
