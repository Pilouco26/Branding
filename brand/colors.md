# Sistema de color · Estany

Direcció escollida: **A · Estany** (19/10/2026). Emerald fresc i boira d'estany d'alta muntanya. Les alternatives descartades són a [`proposta-colors-estil.md`](proposta-colors-estil.md).

Codi: [`tokens.css`](tokens.css).

## Tokens

| Token | Hex | Ús |
|-------|-----|-----|
| `ink` | `#12302A` | Text principal, títols, wordmark |
| `emerald` | `#2B7A62` | Primari: botons, enllaços, mark. L'únic accent |
| `emerald-deep` | `#1D5646` | Hover, botó premut, cara d'ombra |
| `mint` | `#8FCBB2` | Cara il·luminada del mark; accent sobre `night`. Mai text sobre clar |
| `mist` | `#EDF4F1` | Panells, seccions alternes, text sobre `night` |
| `snow` | `#FAFCFB` | Superfície base de web i decks |
| `slate` | `#5B6B66` | Text secundari i metadades sobre clar |
| `line` | `#D5E2DC` | Línies fines i vores (decoratiu) |
| `night` | `#0E1F1B` | Fons fosc: portades de deck, blocs de codi |
| `dusk` | `#8FA39C` | Text secundari sobre `night` |
| `night-line` | `#23362F` | Línies i vores sobre `night` |

Factures i PDF: fons blanc `#FFFFFF`, no `snow`.

## Parelles de text verificades (WCAG 2.1)

| Text | Fons | Ràtio | Nivell |
|------|------|-------|--------|
| `ink` | `snow` / blanc | 13,8 / 14,2 | AAA |
| `ink` | `mist` | 12,7 | AAA |
| `slate` | `snow` / blanc | 5,5 / 5,6 | AA |
| `slate` | `mist` | 5,0 | AA |
| `emerald` | `snow` / blanc | 5,0 / 5,2 | AA |
| `emerald` | `mist` | 4,6 | AA (just) |
| `emerald-deep` | `mist` | 7,6 | AAA |
| blanc | `emerald` | 5,2 | AA |
| blanc | `emerald-deep` | 8,5 | AAA |
| `mist` | `night` | 15,3 | AAA |
| `mint` | `night` | 9,2 | AAA |
| `dusk` | `night` | 6,4 | AA |

No serveixen per a text: `mint` sobre clar (1,8), `line` (1,3), `slate` sobre `night` (3,0).

Sobre `mist`, els enllaços petits van en `emerald-deep`.

## Mark: facetes

La llum ve de dalt a l'esquerra. Cada cara usa un degradat de dues parades.

| Cara | Clar | Fosc (`-dark`) | Pla (factura) |
|------|------|----------------|---------------|
| Il·luminada (centre) | `#A9DBC6 → #4E9F83` | `#D3EEE2 → #74BC9F` | `#8FCBB2` |
| Esquerra (mitjana) | `#3E8E74 → #1D5646` | `#74BC9F → #2B7A62` | `#2B7A62` |
| Dreta (ombra) | `#255F4E → #0F2B24` | `#3E8E74 → #1F5747` | `#1D5646` |
| Neu | `#F4FAF7` al 85 % | `#F4FAF7` al 90 % | — |

Versió mono: una sola tinta `ink`, amb les cares separades per talls fins (`logos/usage/icon-favicon-mono.svg`).

## Regles

1. **Un sol accent.** L'accent és `emerald`. `mint` només fa de llum: la cara del mark i els accents sobre fosc.
2. **Suavitat.** Res de neó, porpra ni navy dur. Els degradats, de dues parades com a màxim. Les ombres es tenyeixen d'`ink`, mai negres.
3. **Factures.** Fons blanc, mark pla, text `ink` i `slate`. L'accent només apareix a la regla de cresta.
4. **Fons foscos.** `night` amb el mark `-dark`, text `mist`, secundari `dusk` i accent `mint`.
5. **Gràfics.** La sèrie protagonista en `emerald` (o `mint` sobre fosc); la resta en neutres.
