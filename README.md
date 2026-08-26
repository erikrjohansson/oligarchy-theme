# Oligarchy

An [Omarchy](https://omarchy.org/) theme. Muted olive-green backgrounds, pale gold
foreground, green accent — with retro-poster wallpapers about who actually pays for
your free operating system.

![Oligarchy](preview.png)

![Oligarchy wallpapers](preview-2.png)

## Install

```bash
omarchy theme install https://github.com/ejuro/oligarchy-theme.git
```

That clones the repo into `~/.config/omarchy/themes/oligarchy` and applies it.

To switch to it later, or after installing something else:

```bash
omarchy theme set oligarchy
```

Cycle through the three wallpapers with `omarchy theme bg next`, or open the
picker with `omarchy theme bg-switcher`.

## Update

```bash
omarchy theme update
```

Updates every git-installed theme, this one included.

## Remove

```bash
omarchy theme remove oligarchy
```

## Backgrounds

All three are 2912×1632. Click one for the full-size image.

[![THE OLIGARCHY — your free operating system, brought to you by unreasonable amounts of money](previews/1-oligarchy-factory.jpg)](backgrounds/1-oligarchy-factory.jpg)

`1-oligarchy-factory.jpg`

[![ZERO DOLLARS, SEVERAL BILLIONAIRES](previews/2-zero-dollars-several-billionaires.jpg)](backgrounds/2-zero-dollars-several-billionaires.jpg)

`2-zero-dollars-several-billionaires.jpg`

[![POWERED BY UNREASONABLE AMOUNTS OF MONEY](previews/3-unreasonable-amounts-of-money.jpg)](backgrounds/3-unreasonable-amounts-of-money.jpg)

`3-unreasonable-amounts-of-money.jpg`

To add your own without touching this repo, drop images into
`~/.config/omarchy/backgrounds/oligarchy/` — Omarchy picks them up alongside the
bundled ones and they survive `omarchy theme update`.

## Palette

| | |
|---|---|
| background | `#374b39` |
| dark background | `#29382b` |
| darker background | `#1c261d` |
| lighter background | `#4b5d4d` |
| foreground | `#F7E2B1` |
| accent | `#5a9059` |
| selection | `#F7E2B1` |
| muted | `#5e5f59` |

| | normal | bright |
|---|---|---|
| red | `#b09153` | `#cda555` |
| yellow | `#fff78c` | `#fff76c` |
| green | `#c5ca74` | `#dde26f` |
| cyan | `#c4ea82` | `#d6ff80` |
| blue | `#5a9059` | `#65a865` |
| magenta | `#de9d54` | `#ffae4b` |
| orange | `#bca26d` | |
| brown | `#716141` | |

Icons: `Yaru-yellow`.

## License

Theme files are MIT (see `LICENSE`). The wallpapers are AI-generated images,
free to use and redistribute with the theme.
