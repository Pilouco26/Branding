# Tipografia

## Famílies

| Rol | Família | Per què |
|-----|---------|---------|
| Marca, titulars, totals | **Sora** 600 | Sans geomètric amb caràcter; sofisticat sense ser fred |
| Text (web, decks, factures) | **IBM Plex Sans** 400 / 500 / 600 | Llegible en blocs llargs, xifres tabulars, bon català |
| Detall tècnic | **IBM Plex Mono** 400 / 500 | Etiquetes, numeració, números de factura, codi |

Totes tres són de Google Fonts (llicència OFL). No s'han d'usar Inter, Roboto ni Arial com a veu de marca.

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=IBM+Plex+Sans:wght@400;500;600&family=Sora:wght@500;600;700&display=swap">
```

## Escala

| Element | Família | Pes | Mida | Tracking |
|---------|---------|-----|------|----------|
| Wordmark | Sora | 600 | — | −0,04 em |
| Hero web | Sora | 600 | 44–56 px | −0,035 em |
| Títol de secció / pitch | Sora | 600 | 28–40 px | −0,03 em |
| Subtítol | Sora | 600 | 17–20 px | −0,02 em |
| Text | Plex Sans | 400 | 15–18 px web · 10–11 pt factura | 0 |
| Botons, etiquetes de formulari | Plex Sans | 500 | 13–14 px | 0 |
| Etiqueta / eyebrow | Plex Mono | 500 | 11–12 px, MAJÚSCULES | +0,08 em |
| Metadades | Plex Sans | 400 | 12–13 px, color `slate` | 0 |

## Regles

- **Xifres tabulars** (`font-variant-numeric: tabular-nums`) a factures, taules i gràfics, perquè els imports s'alineïn.
- **Tipus frase** a títols i botons ("Comencem un projecte", no "Comencem Un Projecte").
- Les majúscules, només a les etiquetes en mono.
- Mida mínima: 11 px a pantalla, 8 pt en impressió.

## Català

Sora, Plex Sans i Plex Mono cobreixen `à é è í ï ò ó ú ü ç l·l`. Escriviu el punt volat com a `·` (U+00B7), mai com a punt normal.

## Wordmark en SVG

Els fitxers de `logos/` usen `<text>` amb Sora. Quan es fan servir com a `<img>`, l'SVG no pot carregar fonts web i caurà a la font del sistema si Sora no està instal·lada. Mentre el wordmark no estigui convertit a paths, a web i a les plantilles HTML useu el mark en SVG i el nom "Piricodi" en HTML amb Sora (com fa `templates/factura.html`).
