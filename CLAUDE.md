# CLAUDE.md, md-visning

Åpen kildekode (MIT): viser markdown-filer som A4-sider i rader, med zoom.
Brukes ved siden av MarkText, som er editoren.

Det finnes ingen prosjektfil i JAXX for dette verktøyet. `README.md` beskriver hva
det gjør og hva det ikke gjør. Fellesreglene i `C:\dev\CLAUDE.md` gjelder.

- Ett dokument: `index.html`. Ingen byggesteg.
- Bibliotekene hentes fra jsDelivr med låste versjoner: marked 12.0.2,
  DOMPurify 3.1.6, Paged.js 0.4.3. Bruk `dist/paged.js`, ikke `paged.min.js`,
  som eksporterer `PagedModule` i stedet for `Paged`.
- Regler for sidebrudd (`break-*`) må stå uten avgrensning i `SIDE_CSS`. Paged.js
  leser dem fra kildeteksten før den ligger i `.pagedjs_page_content`.
- `eksempel.md` er TESTDATA.
