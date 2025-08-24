# The cafe from Pavia (Hugo site)

A complete Hugo website with a custom theme and AOS animations.

## Quick start

1. Install [Hugo Extended](https://gohugo.io/installation/).
2. Unzip this project.
3. From the project root, run:

```bash
hugo server -D
```

Then open http://localhost:1313

## Customize

- Edit `data/menu.yaml` and `data/hours.yaml` for menu and hours.
- Replace images in `static/images/` with your own.
- Update contact details in `config.toml`.
- Change the reservation form action in `layouts/shortcodes/reservation.html`.

AOS is loaded via CDN and initialized in `baseof.html`.
