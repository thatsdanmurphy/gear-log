# Gear Log · Image Sourcing Tracker

## Status Key
- ✅ Done — image is local and wired into CLUB_IMAGES
- 🔗 Needs download — source URL known
- ❓ Needs research — not sure where to get it
- 🚫 Likely unavailable — vintage gear, no clean product shot

---

## Titleist (ALL DONE ✅)

All images are local in `images/` and wired into `CLUB_IMAGES`.

| Model | Key in CLUB_IMAGES | Status |
|---|---|---|
| GT1 Driver | `Titleist\|GT1 Driver` | ✅ |
| GT2 Driver | `Titleist\|GT2 Driver` | ✅ |
| GT3 Driver | `Titleist\|GT3 Driver` | ✅ |
| GT4 Driver | `Titleist\|GT4 Driver` | ✅ |
| GT1 Fairway | `Titleist\|GT1 Fairway` | ✅ |
| GT2 Fairway | `Titleist\|GT2 Fairway` | ✅ |
| GT3 Fairway | `Titleist\|GT3 Fairway` | ✅ |
| GT1 Hybrid | `Titleist\|GT1 Hybrid` | ✅ |
| GT2 Hybrid | `Titleist\|GT2 Hybrid` | ✅ |
| GT3 Hybrid | `Titleist\|GT3 Hybrid` | ✅ |
| T100 Irons | `Titleist\|T100` | ✅ |
| T150 Irons | `Titleist\|T150` | ✅ |
| T250 Irons | `Titleist\|T250` | ✅ |
| T250•U Irons | `Titleist\|T250•U` | ✅ |
| T350 Irons | `Titleist\|T350` | ✅ |
| U•505 Utility | `Titleist\|U•505` | ✅ |
| 620 CB Irons | `Titleist\|620 CB` | ✅ |
| 620 MB Irons | `Titleist\|620 MB` | ✅ |
| Vokey SM11 Wedges | `Titleist\|SM11`, `Vokey\|SM11` | ✅ |
| Vokey WedgeWorks | `Titleist\|Vokey WedgeWorks` | ✅ |
| Phantom 5 / 5.2 / 5.5 | `Scotty Cameron\|Phantom 5` etc. | ✅ |
| Phantom 7 / 7.2 / 7.5 | `Scotty Cameron\|Phantom 7` etc. | ✅ |
| Phantom 9R / 9.2R | `Scotty Cameron\|Phantom 9R` etc. | ✅ |

---

## Scotty Cameron (PARTIAL)

| Model | Needed for entry | Source | Status |
|---|---|---|---|
| Newport 2 GSS | Tiger 2019 Masters entry | scottycameron.com/media or Google image search "Scotty Cameron Newport 2 GSS press" | 🔗 |

**Download folder:** `images/Scotty Cameron/`

---

## TaylorMade (NEEDED — these appear in current entries)

| Model | Needed for entry | Source | Status |
|---|---|---|---|
| P7TW Irons | Tiger 2019 Masters | newsroom.taylormadegolf.com → search "P7TW" | 🔗 |
| R11 Driver | Rory 2011 US Open | newsroom.taylormadegolf.com → search "R11" (archived) | 🔗 |
| Tour Preferred MB | Rory 2011 US Open | newsroom.taylormadegolf.com → search "Tour Preferred MB" | 🔗 |

**Download folder:** `images/TaylorMade/`

**Note on R11 / Tour Preferred MB:** These are ~2011 vintage. TaylorMade newsroom may not have them archived. Alternatives:
- Google Images: `"TaylorMade R11 driver" site:taylormadegolf.com` or press image search
- eBay/golf retailer product shots (usually white background, clean)
- Golf Digest / Golf.com media — sometimes have archival gear shots

---

## Brands for Future Entries (not in any current entry yet)

### Callaway
- **Source:** callawaygolf.com/pages/media-assets
- **Key models to get:** Elyte Driver, Apex Pro Irons, Paradym Driver
- **Download folder:** `images/Callaway/`

### Ping
- **Source:** ping.com/en-us/community/media-center (requires free account)
- **Key models to get:** G440 LST Driver, G440 Max Driver, PLD putters (Oslo, Anser)
- **Download folder:** `images/Ping/`

### Cobra
- **Source:** cobragolf.com (no dedicated press portal — use Google Images filtered to cobragolf.com, or contact their PR)
- **Key models to get:** AEROJET LS, LIMIT3D
- **Download folder:** `images/Cobra/`

### Mizuno
- **Source:** press.mizunousa.com (free registration)
- **Key models to get:** JPX925 Tour, Pro 221, Pro 241
- **Download folder:** `images/Mizuno/`

### Cleveland / Srixon
- **Source:** news.dunlopsports.com/us/en
- **Key models to get:** RTX 6 ZipCore wedges, ZX7 Mk II irons, ZXi driver
- **Download folder:** `images/Cleveland/`, `images/Srixon/`

### Odyssey (Callaway brand)
- **Source:** Same as Callaway — callawaygolf.com/pages/media-assets
- **Key models to get:** White Hot OG #7, Ai ONE Double Wide
- **Download folder:** `images/Odyssey/`

### Wilson Staff / MacGregor / Cobra (Vintage)
- **These appear in historical entries (Arnie 1960, Nicklaus 1986, Daly 1991)**
- Vintage gear has no media center. Options:
  - Google Images: `"Wilson Staff Dyna-Powered irons" -site:ebay.com` (filter to clean bg)
  - PGA Tour archives / Getty Images (may need licensing)
  - Graciously skip image for vintage entries — the fallback state looks fine

---

## Priority Order

1. **Newport 2 GSS** — needed for Tiger entry (current, high-profile)
2. **TaylorMade P7TW** — needed for Tiger entry
3. **TaylorMade R11 / Tour Preferred MB** — needed for Rory entry
4. **Callaway** — if adding Mickelson post-2004 or current bag entries
5. **Ping** — for any Ping bag users
6. **Everything else** — as new entries get added

---

## File Naming Convention

When you download images, name them cleanly before dropping into the folder:

```
images/TaylorMade/tm-p7tw-irons.jpg
images/TaylorMade/tm-r11-driver.jpg
images/Scotty Cameron/sc-newport2-gss.jpg
images/Callaway/callaway-apex-pro-irons.jpg
```

Then add the entry to `CLUB_IMAGES` in `index.html`:
```js
"TaylorMade|P7TW": "images/TaylorMade/tm-p7tw-irons.jpg",
```
