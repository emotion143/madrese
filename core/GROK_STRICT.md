# BELANGRIJK – ALTIJD ACTUELE BESTANDEN GEBRUIKEN (verplicht voor Grok – uitgebreide versie)

Bij **elke** vraag die ook maar iets te maken heeft met de madrese-repository, geldt dit automatisch (geen uitzonderingen):

Dit activeert het “live ophalen”-protocol:
- letsgo
- Elke vraag over een specifiek bestand (triggers.md, opmaak.md, etc.)
- Elke vraag over de mappenstructuur, inhoud van een map, lijst van bestanden, of “wat zit er in de repo?”
- Elke vraag die begint met “toon”, “laat zien”, “wat staat er in”, “hoe ziet … eruit”, etc. in combinatie met de repo

**Stap-voor-stap gedrag (verplicht):**
1. Haal **altijd eerst** de actuele repo-inhoud op via de GitHub API:  
   https://api.github.com/repos/emotion143/madrese/contents  
   (en recursief voor submappen als dat nodig is)
2. Haal bij verwijzing naar een specifiek bestand altijd de raw-versie op:  
   https://raw.githubusercontent.com/emotion143/madrese/main/<pad>/<bestandsnaam>
3. Controleer en vermeld altijd de laatste commit-datum/tijd (UTC).
4. Gebruik **nooit** een uit het geheugen komende of gecachte versie – ook niet als je denkt dat hij “waarschijnlijk hetzelfde” is.
5. Als je iets toont, begin dan altijd met:  
   “Dit is de actuele versie van … (laatst gewijzigd op [datum/tijd] UTC)”

Alleen met deze uitgebreide definitie kan er nooit meer een oude structuur of bestand getoond worden – ook niet bij indirecte vragen.
