# Starter Fashion Jerseys (90's)

Archival image gallery for 90s Starter officially-licensed fashion jerseys — the non-on-ice designs. Not for sale; purely a reference archive.

**Live site:** [starter-jerseys.libertybelljerseys.com](https://starter-jerseys.libertybelljerseys.com)

---

## Image Naming

All images follow this schema:

```
{ABBR}-{descriptor}.{ext}
```

- **`ABBR`** — Standard NHL team abbreviation, uppercase (e.g. `PHI`, `PIT`, `WSH`)
- **`descriptor`** — Lowercase kebab-case colorway or style (e.g. `road-black`, `powder-blue`)
- **`ext`** — `jpg` or `png`

Examples: `PHI-light-blue.png`, `CHI-road-black.png`, `PIT-red.png`

---

## Contributing

Know of a Starter fashion jersey that's missing? Contributions welcome.

### Via GitHub

1. Fork this repo
2. Add your image to `/images/` using the naming schema above
3. Add an entry to the `images` array in `index.html`, keeping it sorted alphabetically by team:
   ```js
   { file: 'PHI-teal.jpg', team: 'Philadelphia Flyers', desc: 'Teal colorway' },
   ```
4. Open a pull request

### Via Email

Send the image and the following to [contact@libertybelljerseys.com](mailto:contact@libertybelljerseys.com):
- Team name
- Brief description of the colorway or style
- Image file (jpg or png, highest resolution available)

---

[Liberty Bell Jerseys](https://libertybelljerseys.com)
