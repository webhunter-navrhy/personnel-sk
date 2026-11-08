# Koncept – personnel.sk (PERSONÁLNE SLUŽBY s. r. o.)

## Tři koncepty
1. **Odletová tabule** – nabídky práce jako řádky tabule odletů (cíl, pozice, plat, nástup); web = cesta od registrace po odlet.
2. **Palubní lístek** – celý postup uchazeče jako lístek s perforací: registrace → poplatek → umístění → odjezd.
3. **Mapa Evropy s piny** – země jako piny (nemáme data o počtech, mapa by byla prázdná a vymýšlela by).

## Výběr
Koncept 1 + prvky 2 (kroky postupu na lístku). Oba nesou pravdivý obsah z jejich webu (země, pozice, platy, „nástup každý týždeň“), nepotřebují žádná vymyšlená čísla. Odletová tabule je i signature moment: řádky se při scrollu postupně „odbaví“ (IntersectionObserver, bez knihoven).

## Sekce
index: hero (palubní lístek s fotkou) → odletová tabule aktuálních ponuk → postup na lístku (4 kroky) → odvetvia → pre firmy (5 služeb) → o nás → kontakt.
Podstránky: /ponuka-prace/ (detail 3 ponúk), /pre-uchadzacov/ (postup, poplatky, registrační dotaz), /kontakt/.

## Písma
Archivo (300–700, latin + latin-ext, háčky ověřeny v bagermini) a IBM Plex Mono 400/500 jen pro tabuli. Display v řezu 500.
Paleta z logem klienta: oranžová #f26e38 / #f96a00, modrá #0070ad, inkoust #0e2238, teplé pozadí. Oranžová na plochy, text oranžový jen ztmavený (#b84a17).

## Fotky
Jen 2 fotky z jejich webu (kancelářský tým, portrét) – použity v hero a v sekci pro firmy, bez natahování. Ostatní vizuál je typografie a tabule. Zdroj: personnel.sk/wp-content/uploads/2019/01/slide1.jpg, slide-top.jpg.

## Zakázané vzory
Žádný z tabulky (bez marquee, zrna, counterů, scroll indikátoru, mono nadtitulků „01 /“). Mono jen na tabuli.

## Porovnání
Registr: poslední weby jinak (penziontkm = Montserrat + klikací plán). Skladba sekcí nová (tabule + lístek).
