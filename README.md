# Marvaden Studio — Pitch Samples

Sample sites shown to prospective clients. Each keeps a "Sample design" banner until the client signs.

| Path | Client | Theme |
|---|---|---|
| `/priceless` | Priceless Braids (Dallas) | terracotta · arch · stagger · placeholder photos marked "Sample photo" |
| `/bhair` | B.Hair Braiding (Dallas) | plum · dark hero · blob · grid · 12 photos of the salon's own work + 3 open slots |
| `/template` | Reusable braider template — edit the `SITE` block | — |

Deploy: import this repo in Vercel (no build step). Links become `<project>.vercel.app/priceless` and `/bhair`.

## Photos
Templated sites (`/bhair`, `/template`) take photos through the `SITE` block: `heroPhoto`, `heroTag`, a third
column in `styles` (a path like `images/knotless-auburn.jpg`, 960×1200, 4:5) and `emptySlots` for dashed "room
for another photo" tiles. Rows without a photo keep the coloured tile. `/bhair/images` holds cropped photos of
B.Hair Braiding's own work; swap a file under the same name to update it.

`/priceless/images` holds **placeholder** photos (B.Hair Braiding's work), each badged "Sample photo". Swap them
for Priceless's own photos under the same file names, then delete the `.sample` badges before launch.
