# Mura pool

Public assets for the Mura stake pools (MURA1 to MURA7).

## Logo

| File | What it is |
| --- | --- |
| `logo/mura-logo-original.png` | the source image, 1254 × 1254 PNG with a transparent background, as received 2026-09-26 (replaces the 2026-09-25 村 mark, still in this repo's history) |
| `logo/mura-logo.png` | 1024 × 1024 PNG, made from the source; meets the laksa console's logo rules (PNG, square, 128 to 1024 px, at most 1 MB) |
| `logo/mura-logo-64.png` | 64 × 64 PNG icon, made from the source |

The pools' metadata does not link to these files directly. Each pool's metadata links to
`https://kes-tool.vercel.app/pool/mura-extended.json`, which names
`https://kes-tool.vercel.app/pool/mura-logo.png` and `/pool/mura-logo-64.png`; the console serves
those by fetching the two files here (branch `main`, five-minute cache), unless an operator has saved
other image URLs in its Logo tab. A push here changes the pools' logo on explorers without a
certificate or a console deploy; each explorer re-reads on its own schedule.
