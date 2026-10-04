# PRL_CP

Web estàtica (HTML + CSS inline, sense build) del curs **[FCOS02] Bàsic de prevenció de riscos laborals**, dins del CP IFCT0510 Gestió de sistemes informàtics. Idioma: català.

## Estructura
- `index.html` — portada del curs amb la distribució d'hores i una targeta per mòdul (M01–M04).
- `mX.html` — pàgina índex de cada mòdul, amb enllaços a les sessions.
- `mX_cNN.html` — sessió NN del mòdul X. Cada sessió enllaça a l'anterior, la següent i l'índex del mòdul.

| Mòdul | Títol | Hores | Estat |
|---|---|---|---|
| M01 | Conceptes bàsics sobre seguretat i salut en el treball | 7 h | `m1.html` + sessions `m1_c01`–`m1_c07` |
| M02 | Riscos generals i la seva prevenció | 14 h | pendent |
| M03 | Riscos específics i la seva prevenció en el sector | 5 h | pendent |
| M04 | Elements bàsics de gestió de la prevenció de riscos | 4 h | pendent |

## Convencions
- Font IBM Plex Sans (Google Fonts). Colors definits com a variables a `:root` de cada pàgina:
  blau `#1F5A8C` (M01, obligació), groc `#C99A06` (M02, advertència), taronja `#B5651D` (M03), verd `#2E7D4F` (M04, condició segura).
- Per desactivar temporalment una targeta de mòdul a `index.html`, afegir la classe `disabled` (`class="card m2 disabled"`).
- Mantenir l'estil i l'estructura de les pàgines existents en crear-ne de noves.
