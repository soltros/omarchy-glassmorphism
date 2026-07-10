# Omarchy Glassmorphism Theme

A glassmorphism-inspired theme for the Omarchy Linux distribution. This theme overrides default aesthetics to provide a unified frosted glass effect across the desktop, window manager, and status bar.

## Features

- Custom Hyprland overrides for sharp corners (`rounding = 0`) and true glassmorphism (`active_opacity = 1.0`, configured noise-infused blur, and drop shadows).
- Seamless translucent Waybar integration with non-stacking alpha compositing.
- Lavender/purple accent color scheme.
- Color-matched file manager icons (`Yaru-purple`).

## Installation

You can install this theme directly via the Omarchy CLI using the repository URL:

```sh
omarchy theme install https://github.com/soltros/omarchy-glassmorphism
```

Alternatively, you can manually clone this repository into your Omarchy themes directory:

```sh
git clone https://github.com/soltros/omarchy-glassmorphism ~/.config/omarchy/themes/glassmorphism
omarchy theme set glassmorphism
```

## Customization

- To change the background image, place your preferred wallpaper into the `backgrounds/` directory and replace `unlock.png` to update the lock screen.
- Adjust the core color palette in `colors.toml`.
- Tweak blur, opacity, or layer rules in `hyprland.conf`.
