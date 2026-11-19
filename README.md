# Mat – ukeplan, oppskrifter og handleliste

Én statisk side (`index.html`) med Supabase som database. Fungerer som installerbar app (PWA).

## v7.0 – hva er nytt
- **Nytt designsystem:** Plus Jakarta Sans, myke kort, flytende bunnmeny med ikoner, app-bar, animasjoner, lys/mørk/auto-tema.
- **I dag-dashbord:** hilsen, ringer for protein og energi (planlagt og spist), hurtigknapper og måltidskort med matbilder.
- **Rettkort med «matkunst»:** emoji og farge ut fra rett og hovedprotein, «Ny»-merke, karuseller for ukens inspirasjon og nyeste retter.
- **Oppskrift:** porsjonsskalering, avkryssbare ingredienser, nummererte steg, kopier ingrediensliste.
- **Kjøkkentimere:** trykk på «⏱ 12 min» i et steg. Gir lyd, vibrasjon og varsel, og overlever omlasting.
- **Kokemodus:** framdriftsstriper, timere i hvert steg, sveip eller piltaster mellom steg.
- **Statistikk** (Plan → Statistikk): protein per dag mot målbånd, nøkkeltall, hovedprotein og mest spiste retter.
- **🎲 Overrask meg:** vektet tilfeldig forslag (favoritter opp, nylig spist ned), legges rett i planen.
- **Globalt søk** (`/` eller Ctrl+K): retter, ingredienser og handlinger.
- **Del handlelista** (deling eller utklippstavle), og dagsmål du kan justere selv.
- **51 nye retter** i databasen (merket `source = 'seed-v7'`).

Alle tidligere funksjoner og databasekall er uendret. v7-laget ligger nederst i skriptet og bygger på v6-funksjonene.
