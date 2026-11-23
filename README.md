# LOKBOOK v0.6 – offline testovací verze bez přihlášení

- Žádná registrace, přihlašování ani Supabase. Žádná cloudová synchronizace.
- IndexedDB jako hlavní lokální úložiště; při nedostupnosti localStorage.
- Jízdy, úpravy směn, kalendář, měsíční norma, výplata, jazyky CS/DE/EN, 14 měn.
- JSON export/import a CSV export jízd.

## Spuštění na Macu
`npm install` a `npm run dev` ve složce `raillog-pwa`. Pro nasazení: `npm run build`, nahrát `dist` na HTTPS hosting.

## Důležité
Před nasazením exportujte JSON zálohu z původní aplikace. Stejná doména umožní migraci existujících dat z předchozí verze; jiná doména vyžaduje import zálohy. Data se ukládají pouze v konkrétním prohlížeči/zařízení, nejsou synchronizována. Smazání dat webu může vymazat i záznamy. Kalkulačka mzdy je orientační.
