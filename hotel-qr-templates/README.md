# Hotel QR Label Templates — 3 Style Options

Three complete design directions for **The Grand Meridian** (placeholder hotel).
Share all three with the client and let them pick the one that fits their brand.

| # | Option | Look & feel | QR module style |
|---|--------|-------------|-----------------|
| 1 | **Luxury** | Deep navy + gold, Cormorant serif, sharp corners — classic five-star | Square |
| 2 | **Boutique** | Warm terracotta + cream, Fraunces serif, soft rounded — editorial | Rounded |
| 3 | **Minimal** | Black & white, Inter, Swiss grid — architectural | Dots |

## What's in each PDF (7 pages)

1. **Cover** — style name, palette swatches, notes for the client
2. **A4 sticker sheet** — 8 labels @ 90×57mm, dashed cut lines
3. **Table tent** — Restaurant Menu (fold-over, prints both sides)
4. **Table tent** — Spa & Treatments
5. **Key-card / bedside cards** — 8 @ 85×55mm (standard business-card size)
6. **Door plate** — Guest Wi-Fi (large format)
7. **Door plate** — Share Your Experience (reviews)

## The 8 labels

Room Service · Housekeeping · Guest Wi-Fi · Share Your Experience ·
Restaurant Menu · Spa & Treatments · Express Check-In · Local Guide

## Notes

- **All QR codes are live and scannable** — every code in all three PDFs was
  decode-verified at 300 DPI after rendering. Test them with your phone.
- Links point to `grandmeridian.example` placeholders — swap for real URLs.
- The Wi-Fi QR uses a real `WIFI:` payload, so phones join the network on scan.
  Update the SSID and password before printing.
- Error correction is level H (~30%), so a logo can be dropped into the centre
  of any code without breaking it.
- Print on A4, 100% scale / "actual size" — do **not** use *fit to page*, or the
  millimetre sizing will be wrong.

## Regenerating

Sources are in the scratchpad (`build/styles.py`, `build/build.py`, `qr/genqr.py`).
Edit the hotel name, labels and URLs in `styles.py`, then rebuild and print to PDF
with headless Chrome.
