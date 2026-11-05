# MD-visning

Viser en markdown-fil som A4-sider ved siden av hverandre, slik som flersidevisningen i Word. Du skriver i MarkText eller en annen editor og leser her.

**Bruk den på nett:** https://smackomatic.github.io/md-visning/

Fila du åpner leses bare i nettleseren din. Den lastes ikke opp noe sted.

## Slik bruker du den

1. Åpne adressen over i Edge eller Chrome. Du kan også laste ned repoet og åpne `index.html` derfra.
2. Trykk «Åpne fil» eller dra en .md-fil inn i vinduet.
3. Zoom med Ctrl og musehjulet, Ctrl+pluss og Ctrl+minus, eller knappene. Sidene legger seg i rader, og jo mer du zoomer ut, desto flere sider får plass per rad.
4. Velg «Sider per rad» for å få akkurat 1, 2, 3, 4, 6 eller 8 sider i bredden.

Ctrl+0 går tilbake til 100 %. Ctrl+O åpner en fil.

Når du lagrer fila i MarkText, oppdateres sidene i løpet av et sekund. Visningen husker sist åpnede fil til neste gang.

## Sideskift

Skriv en egen linje med `<!-- sideskift -->` der du vil ha ny side. `\pagebreak` og `\newpage` virker også. MarkText viser ikke kommentaren, så den forstyrrer ikke der.

## Begrensninger

- Krever nettilgang, siden tre biblioteker hentes fra jsDelivr: marked, DOMPurify og Paged.js.
- Bilder med relativ sti, som `bilder/figur.png`, vises ikke. Bilder med full nettadresse vises.
- Automatisk oppdatering og «husk sist åpnede fil» virker bare i Edge og Chrome. I Firefox må du dra inn fila på nytt.
- Matematikk, diagrammer og fargelegging av kode er ikke med.

`eksempel.md` er et testdokument med tilfeldig tekst, laget for å prøve sideoppdelingen.

## Lisens

MIT. Se `LICENSE`. Bibliotekene har egne lisenser: marked og Paged.js er MIT, DOMPurify er Apache 2.0 eller MPL 2.0.
