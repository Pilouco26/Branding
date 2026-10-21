# Estil visual

Regles comunes a web, factures i pitch decks. Els colors són a [`colors.md`](colors.md), la tipografia a [`typography.md`](typography.md) i els valors en codi a [`tokens.css`](tokens.css).

## Principis

- **Sofisticat i modern:** molt espai buit, un sol accent i poques peces per vista.
- **Pirineus, de forma subtil:** angles de cim, facetes i llum d'alta muntanya. Mai muntanyes il·lustrades ni la bandera.
- **Software ben fet:** línies d'1 px, alineacions exactes, detalls en monoespai.

## Forma

| Element | Valor |
|---------|-------|
| Radi de controls (botons, inputs, xips) | 4 px |
| Radi de targetes i panells | 8 px |
| Xamfrà (cantonada tallada a dalt a la dreta) | 20 px |
| Graella d'espaiat | múltiples de 8 px |

El **xamfrà** repeteix l'angle del cim. S'usa en un sol element per superfície: el hero web o la portada del deck.

## Profunditat

- La llum ve sempre de dalt a l'esquerra, com al mark.
- **Botó primari:** degradat vertical `emerald → emerald-deep`, amb una línia de llum interior a dalt.
- **Elevació:** dues ombres suaus tenyides d'`ink` (1 px i 14–28 px). Mai ombres negres, brillantors ni desenfocaments.

## Línies i motiu

- **Línies:** 1 px en `line` (o `night-line` sobre fosc).
- **Regla de cresta:** línia fina amb un petit perfil de muntanya en `emerald`. Fa de separador a la capçalera de factura i als canvis de secció del deck.
- **Facetes fantasma:** les tres cares del mark, grans i entre el 5 % i el 18 % d'opacitat. Només al hero web i a les portades.

## Icones

Traç d'1,5 sobre una graella de 24 i `currentColor`, amb el mateix pes a totes. Res d'icones plenes barrejades amb icones de traç.

## Gràfics

Estratègia d'accent i neutres: la sèrie protagonista en `emerald` (`mint` sobre fosc) i la resta en neutres. Etiquetes en Plex Mono amb xifres tabulars.

## Fotografia

- Pirineus reals en duotò suau (`ink → mist`), poc saturats.
- Res de fotos de stock amb "hackers", codi sobre fons blau ni mans en teclats.

## Per superfície

| Superfície | Regles |
|------------|--------|
| **Web** | Fons `snow`, panells `mist`. Un CTA primari per vista. Facetes fantasma només al hero. Nav amb mark + "Piricodi" en Sora. |
| **Factura** | Fons blanc, mark pla, text `ink` i `slate`, xifres tabulars. Accent només a la regla de cresta. Plantilla a `templates/factura.html`. |
| **Pitch deck** | Portada i separadors sobre `night` amb el mark `-dark`. Contingut sobre `snow`. Numeració `01 / 12` en mono. Un missatge per diapositiva. |
