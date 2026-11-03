# Fitness Atlas – první funkční prototyp

Mobilní webová aplikace (PWA) s anatomickým atlasem 50 cviků a jednoduchým tréninkovým deníkem.

## Obsah
- 50 cviků z odborně revidovaných textací
- vyhledávání a filtrování podle kategorií
- detail cviku: anatomie, biomechanika, výchozí pozice, provedení, chyby, dýchání, varianty a poporodní poznámka
- oblíbené cviky
- sestavení tréninku, zápis vah a opakování
- časovač pauzy
- základní statistiky a export zálohy
- lokální ukládání v prohlížeči

## Spuštění
Pro rychlý náhled otevři `index.html` v prohlížeči. Pro instalaci jako PWA a offline režim musí být aplikace nasazena na HTTPS hosting (např. GitHub Pages, Netlify nebo Vercel).

Na iPhonu po nasazení otevři adresu v Safari → Sdílet → Přidat na plochu.

## Omezení prototypu
- Záznamy se ukládají lokálně do prohlížeče; zatím se nesynchronizují mezi zařízeními.
- Anatomické náhledy jsou zástupné schematické ilustrace, nikoli přesné svalové mapy. Detailní anatomické ilustrace jednotlivých cviků jsou další obsahová etapa.
- Časovač funguje při otevřené aplikaci; upozornění na pozadí zatím nejsou implementována.
- Před veřejným použitím je potřeba zkontrolovat a doplnit obsah i přístupnost.

## Struktura
- `index.html` – aplikace
- `styles.css` – vzhled
- `app.js` – logika a data 50 cviků
- `manifest.webmanifest` a `sw.js` – PWA
- `data/exercises.json` – samostatná datová kopie
