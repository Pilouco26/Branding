# Proposta de colors i estil

Basada en [`ideas.md`](ideas.md) i en el skill `svg-design` (tryopendata/skills).

**Decisió (19/10/2026): A · Estany.** El sistema vigent és a [`colors.md`](colors.md), [`typography.md`](typography.md), [`estil.md`](estil.md) i [`tokens.css`](tokens.css). Aquest document queda com a registre de les tres opcions.

## Com revisar-la

| Fitxer | Què mostra |
|--------|-----------|
| [`palettes/styleboard.html`](palettes/styleboard.html) | Les 3 direccions aplicades a web, factura, pitch deck i components, amb contrast WCAG calculat en directe. `?p=estany`, `?p=pissarra` o `?p=prat` mostra només una direcció. |
| [`palettes/preview.html`](palettes/preview.html) | Visor del skill: el mark en cada paleta a 16/32/64 px, sobre clar i fosc, favicon i barra de navegació. |
| `palettes/svg/` | Mark de cresta per paleta: `-3D` (degradats), `-dark` (fons fosc) i `-flat` (factura/impressió). |

## D'idees a requisits

| Idea | Requisit de color i estil |
|------|---------------------------|
| Sofisticació, modern/nou | Paleta curta, molt espai buit, un sol accent; res de neó ni porpra |
| Orgull dels Pirineus, de forma subtil | El segon color ve del paisatge (boira, pissarra, prat), mai de la bandera |
| Software ben fet, sharp tech | Angles nets, línies d'1 px, detalls en monoespai |
| Logos més 3D | Llum fixa des de dalt a l'esquerra: cara lit clara, cara esquerra mitjana, cara dreta fosca |
| Colors més suaus, verd emerald | Emeralds desaturats; neutres amb un toc de verd o de pedra |
| Partner fiable per a empresa local | Tot text principal i secundari supera WCAG AA; factures sòbries |
| Web, factures, pitch decks | Cada paleta té versió clara, fosca i plana (sense degradats) |

## Tres direccions

| | A · Estany | B · Pissarra | C · Prat i granit |
|---|---|---|---|
| Imatge | Estany d'alta muntanya, boira | Teulades de pissarra, granit | Prat alpí, sol de tarda al cim |
| Sensació | Fresca, precisa, tecnològica | Sòbria, luxe discret | Càlida, propera |
| L'emerald és... | El protagonista | L'única llum sobre grafit | Suau, amb salvia i crema |
| Punt fort | La més moderna; continua el sistema actual | La millor factura; la més andorrana | La més amable per a client local |
| Risc | Pot semblar freda | Menys "verd" del que vas demanar | El daurat, si s'abusa, sembla de banca o golf |

### A · Estany (recomanada)

| Token | Hex | Ús |
|-------|-----|-----|
| `ink` | `#12302A` | Text principal i títols |
| `emerald` | `#2B7A62` | Primari: botons, enllaços, mark |
| `emerald-deep` | `#1D5646` | Hover, cara d'ombra |
| `mint` | `#8FCBB2` | Cara il·luminada; accent sobre fosc (no per a text sobre clar) |
| `mist` | `#EDF4F1` | Panells i seccions alternes |
| `snow` | `#FAFCFB` | Superfície base |
| `slate` | `#5B6B66` | Text secundari, metadades |
| `line` | `#D5E2DC` | Línies fines i vores |
| `night` | `#0E1F1B` | Fons fosc de decks |

Facetes del mark: lit `#A9DBC6 → #4E9F83`, mitjana `#3E8E74 → #1D5646`, ombra `#255F4E → #0F2B24`, neu `#F4FAF7`.

Contrast: `ink`/`snow` 13,8:1 · `slate`/`snow` 5,5:1 · `slate`/`mist` 5,0:1 · blanc/`emerald` 5,2:1 · `emerald`/`snow` 5,0:1 (serveix per a enllaços) · `mint`/`night` 9,2:1.

### B · Pissarra

| Token | Hex | Ús |
|-------|-----|-----|
| `ink` | `#1E2422` | Text principal (grafit) |
| `slate` | `#3A4542` | Títols alternatius, cares del mark |
| `emerald` | `#2F6B58` | Únic accent: CTA, enllaços, cara de llum |
| `emerald-deep` | `#234F42` | Hover |
| `sage` | `#A7C4B6` | Accent sobre fosc |
| `tint` | `#ECEAE3` | Panells |
| `paper` | `#F5F4F0` | Superfície base (paper càlid) |
| `granite` | `#636A66` | Text secundari |
| `line` | `#DEDCD5` | Línies fines |
| `night` | `#171B1A` | Fons fosc de decks |

Facetes del mark: lit (emerald) `#6FAF97 → #2F6B58`, mitjana (pissarra) `#56625F → #2E3735`, ombra (grafit) `#2E3735 → #161B1A`, neu `#F5F4F0`.

Contrast: `ink`/`paper` 14,3:1 · `granite`/`paper` 5,0:1 · `granite`/`tint` 4,6:1 · blanc/`emerald` 6,2:1 · `emerald`/`paper` 5,7:1 · `sage`/`night` 9,3:1.

### C · Prat i granit

| Token | Hex | Ús |
|-------|-----|-----|
| `ink` | `#1F332B` | Text principal |
| `emerald` | `#3F826A` | Fills, mark i botons (no per a text petit) |
| `emerald-deep` | `#2A5E4C` | Text verd, enllaços, hover |
| `sage` | `#B5D3C2` | Cara il·luminada; accent sobre fosc |
| `sand` | `#EFE8DA` | Panells |
| `cream` | `#F7F3EA` | Superfície base |
| `stone` | `#5F635C` | Text secundari |
| `brass` | `#C9A45C` | Punt de llum: un sol detall per peça |
| `line` | `#E2DACB` | Línies fines |
| `night` | `#15211C` | Fons fosc de decks |

Facetes del mark: lit `#C8E2D2 → #6FAA8F`, mitjana `#4F9479 → #2A5E4C`, ombra `#2A5E4C → #17352B`, neu daurada `#EED9A8`.

Contrast: `ink`/`cream` 12,1:1 · `stone`/`cream` 5,5:1 · `stone`/`sand` 5,0:1 · blanc/`emerald` 4,55:1 (just AA) · `emerald-deep`/`cream` 6,8:1 · `ink`/`brass` 5,7:1. L'`emerald` sobre `cream` fa 4,1:1: només serveix per a text gran, i per això el text verd va en `emerald-deep`.

## Estil comú (vàlid per a qualsevol paleta)

**Tipografia**
- **Sora 600** per a la marca, els titulars i els totals.
- **IBM Plex Sans** per al text de web, decks i factures. Té xifres tabulars (els imports s'alineen) i suporta bé `à ç l·l`.
- **IBM Plex Mono** per als detalls tècnics: etiquetes, numeració `01 / 02`, números de factura, codi. És el guiny a "software ben fet".
- Canvi respecte a `typography.md`: el cos de text passa de Sora a Plex Sans, perquè Sora cansa en blocs llargs i en taules.

**Forma**
- Radis petits: 4 px als controls, 8 px a les targetes. És sharp tech, no "app amable".
- **Cantonada xamfranada** (20 px, a dalt a la dreta) en un sol element per superfície: hero, portada de deck. Repeteix l'angle del cim.

**Profunditat (el 3D fora del logo)**
- La llum sempre ve de dalt a l'esquerra, com al mark.
- Botó primari: degradat vertical `emerald → emerald-deep` amb una línia de llum interior a dalt.
- Ombres suaus tenyides amb `ink`, mai negres: dues capes, 1 px i 14–28 px.
- Sense brillantors, desenfocaments ni neó.

**Línies i motiu**
- Línies d'1 px en `line`.
- **Regla de cresta**: una línia fina amb un petit perfil de muntanya. Fa de separador a la capçalera de factura i als canvis de secció del deck.
- **Facetes fantasma**: les tres cares del mark, grans i entre el 5 % i el 18 % d'opacitat. Només al hero i a les portades.

**Icones**
- Traç d'1,5 sobre una graella de 24, `currentColor`, angles nets. Mateix pes a totes.

**Gràfics als decks**
- Estratègia d'accent i neutres: la sèrie protagonista en accent, la resta en grisos. Mai més d'un color fort per gràfic.

**Fotografia**
- Pirineus reals en duotò suau (`ink → mist` o equivalent de cada paleta), poc saturats.
- Res de fotos de stock amb "hackers" o codi sobre fons blau.

## Aplicació per superfície

| Superfície | Regla |
|------------|-------|
| Web | Fons `surface`, panells `tint`. Un CTA primari per vista. Facetes fantasma només al hero. |
| Factura | Mark **pla**, fons blanc, text `ink` i secundari. Accent només a la regla de cresta. Xifres tabulars. |
| Pitch deck | Portada i seccions sobre `night` amb el mark `-dark`. Contingut sobre `surface`. Numeració en mono. |

## Recomanació

**A · Estany.** És la que respon més directament a "emerald suau + modern + sharp tech": l'emerald hi és protagonista sense cridar. Tot el text supera AA amb marge, i és l'evolució natural dels logos que ja tens.

Si en veure-les prefereixes més sobrietat i un toc més local, **B · Pissarra** és l'alternativa seriosa: la millor per a factures, tot i que hi ha menys verd.

## Següent pas

Quan triïs direcció:
1. Actualitzo `colors.md` i `typography.md` amb la paleta i l'estil escollits.
2. Regenero els conceptes de `logos/` i els fitxers de `logos/usage/` amb els nous colors (3D, fosc i pla).
3. Afegeixo tokens CSS a punt per a la web i una plantilla de factura.
