# Beis HaMikdash — Second Temple 3D Walkthrough

**בית המקדש השני** — walk through the Second Temple in your browser, built to the measurements of **Mishnah Middot**.

You play as a Chassidishe Yid of today (shtreimel or spodik or hat, bekishe, gartel, peyos) walking among people dressed as in Second Temple times: Yisraelim in tunics and tallisos with techeiles, women in mantles and head coverings, kohanim barefoot in white linen, Leviim with kinnoros on the Duchan, and the Kohen Gadol in all eight garments — with his sons, the Segan and his family.

Walk out through the **Chuldah gate tunnel**, down the **Southern Steps** into **Yerushalayim**, and along the **Pilgrim Road** (the stepped street) to the **Shiloach pool** — past shops, dove-sellers, shepherds and mikvaos. Pilgrims lead **sheep, goats and calves** up to the Mikdash for their korbanos, carry lambs on their shoulders and doves in cages, and a **Bikkurim procession** goes up with the ox crowned in olive leaves, horns overlaid with gold, the flute playing (Mishnah Bikkurim 3).

Available in **English, עברית, אידיש (Chassidish) and Español** — choose on the opening screen or in ⚙.

Everything is in **one file: `index.html`**. No install, no build. Optional folders: `models/` for real 3D characters, `audio/` for real recordings (see the README in each).

## Run it

- **Locally:** double-click `index.html` (Chrome, Edge, Firefox or Safari). Internet is needed the first time to load three.js and fonts from the CDN.
- **GitHub Pages:** push this folder to a repo → Settings → Pages → *Deploy from branch* → `main` / root. Your tour will be at `https://<you>.github.io/<repo>/`.
- Slow computer or phone? It adjusts itself automatically (resolution scales down to keep it smooth, and it never renders faster than 60 fps). You can also pick **Graphics → Light** in ⚙, or open `index.html?low`.

## Controls

| | Desktop | Phone / tablet | Gamepad |
|---|---|---|---|
| Walk | `W A S D` / arrows, `Shift` to run | joystick (bottom-left), **Run** button | left stick, triggers to run |
| Look | drag the mouse, wheel to zoom | drag on the screen | right stick |
| Walk to a spot | click the floor | tap the floor | — |
| Talk / give tzedakah / wash / listen | `E` | **Act** | A |
| First / third person | `V` | **View** | Y |
| Blueprint (click to go anywhere) | `M` | 🗺 button | Start |
| Measurements table | `R` | 📐 button | — |
| Go to a place | `G` | 🚶 button | — |
| Tamid & Birkas Kohanim | 🔥 Avodah button | 🔥 button | X |
| Your journey (📜) | `J` | tap the panel | — |

## How it begins

A cinematic flight from Har HaZeisim over Nachal Kidron and the city to Har HaBayis, with music. Then you dress your character (shtreimel / spodik / hat, bekishe / rekel / zupitze, gartel, peyos, beard, yichus) and begin **your pilgrimage** in the plaza below the Southern Steps — a ten-step journey (📜) from the mikveh up to Ezras Yisrael, the Leviim, the Tamid and Birkas Kohanim.

## What's inside

**Har HaBayis** 500 × 500 amos with the Royal Stoa, Shlomo's porch, the five gates (Shushan with its relief of Shushan HaBirah, two Chuldah, Kiponus, Tadi), the **Soreg** with its breaches and the **Cheil**; the twelve steps up to **Ezras Nashim** (135 × 135) with its four unroofed corner chambers (Nezirim, Etzim, Metzora'im, Beis Shemanya), the women's gallery, the thirteen **shofar chests**, the fifty-amah golden menoros of Simchas Beis HaSho'eivah (lit at night); the fifteen semicircular **steps** to **Sha'ar Nikanor**; the **Azarah** 187 × 135 — Ezras Yisrael, the Duchan, Ezras Kohanim, the **Mizbeach** (yesod 32, sovev 30, top 28, horns, the red line, the ramp, three wood-piles, the smoke rising straight up), the place of slaughter (24 rings, 8 tables, 8 pillars), the **Kiyor** with 12 spigots, Lishkas HaGazis and the other chambers, Beis HaMoked; the twelve steps to the **Ulam** (100 wide, entrance 40 × 20, the five oak beams, the Golden Vine, Queen Helena's nivreshes, the marble and gold tables); the **Heichal** 40 × 20 × 40 (Menorah, Shulchan with 12 loaves, golden altar); the **two Paroches** an amah apart; and the **Kodesh HaKodashim**, empty but for the Even HaShesiyah.

**Every place** has an info panel (click the place name top-left) with its Hebrew name, sources, a description and a full calculation table — length, width, height, area, perimeter and volume in amos, and in metres/feet by both **R' Chaim Na'eh (48 cm)** and the **Chazon Ish (57.6 cm)**.

**Sound** is generated live: wind, the crowds of Yerushalayim, swifts, lambs at the north, the crackling Mizbeach, water from the Kiyor, the Kohen Gadol's golden bells as he walks, the Leviim singing in a freygish mode with kinnoros and cymbals, and the silver chatzotzros (tekiah–teruah–tekiah). Put a real field recording at `audio/jerusalem-ambience.mp3` and it will play underneath (works when served over http, e.g. GitHub Pages).

**Yichus and halachah:** pick Yisrael, Levi or Kohen. A Yisrael stops at Ezras Yisrael, a Levi at the Duchan, a Kohen may enter the Heichal; nobody enters the Kodesh HaKodashim. *Study mode* (⚙ Settings) lifts the limits so the whole structure can be learned.

> Today we are all tamei meis and may not ascend Har HaBayis. This model is for learning *Tzuras HaBayis* — "its study is as great as its building" (Midrash Tanchuma, Tzav 14, on Yechezkel 43:10–11).

## Accuracy notes

- Layout and measurements follow the plain reading of **Mishnah Middot** with the Bartenura. Where the Rishonim and Acharonim draw it differently (Rambam's diagrams, the **Tosfos Yom Tov**'s *Tzuras HaBayis*, the **Tiferes Yisrael**'s scaled diagram, the diagram in the **Vilna Shas** by R' Yonasan of Ruzhinoi, the **Vilna Gaon**), the choices are noted in the info panels — e.g. the Mishnah's 70-amah width behind the Ulam ("like a lion"), the Second-Temple two curtains instead of the wall of the Amah Traksin.
- Things the Mishnah does not measure — the stoas, columns, the city, colours of ordinary clothing — follow **Josephus** and the **Avi-Yonah model** (Israel Museum) and are labelled as such.
- The Kohen Gadol's tzitz reads קֹדֶשׁ לַה׳ — the Name is deliberately not written.

- The people and animals are sculpted from code (faces, eyes, hair, cloth folds). For photo-real people, add scanned or artist-made models to `models/` — see `models/README.md`.

See **SOURCES.md** for every source and diagram consulted.

## Code map (inside `index.html`)

`01 core` renderer, sky/sun, light pool, static merging, floor heights · `02 world` all the architecture · `03 people` character builder, NPCs and dialogue · `04 audio` the synthesised soundscape · `05 i18n` the four languages · `05 places` measurements & descriptions · `06 game` controls, camera, UI, blueprint.

Built with [three.js](https://threejs.org) (MIT).
