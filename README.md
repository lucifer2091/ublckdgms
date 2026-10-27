# UNBLOCKED GAMES

A single hub for **97 games** merged from three archives (`trans-W`, `trans-2W`, `trans-fire`).

**Live site:** https://lucifer2091.github.io/ublckdgms/

## How it works

GitHub Pages caps a published site at **1 GB**, but the merged archive is **20.8 GB**. So the collection is split into 17 archives, each under the cap, and this hub links them all together behind one URL.

| Repo | Contents |
|---|---|
| `ublckdgms` | This hub (search, categories, in-page player) |
| `ublckdgms-01` … `ublckdgms-17` | Game archives, ~950 MB each |

Each archive is a normal static site. The hub opens games in a full-screen iframe, or you can open any archive directly at `https://lucifer2091.github.io/<repo>/`.

## Not playable in-browser

Three games are a single indivisible blob larger than the Pages limit, so they are listed as download links:

- **OMORI** — 2.7 GB
- **Cuphead** — 1.3 GB
- **Plants vs. Zombies 2** — 1.2 GB

## Layout

```
index.html        hub: search, category filters, iframe player
.nojekyll         serve files as-is (no Jekyll build)
```

## Notes

- No build step, no dependencies — plain HTML/CSS/JS.
- Games are third-party works collected from public archives; rights remain with their respective owners. This is an unofficial fan archive.
- To report a broken game, open an issue with the card name and the archive number.
