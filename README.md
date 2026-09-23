# Trainingscentrum Horse Nation

Een webapp die laat zien wat het kost om een paard in Horse Nation vol te trainen: in munten, klikjes, rusttijd en dagen. De app vergelijkt trainingsmethoden, fokbonuscombinaties en trainingsvolgordes, en helpt bij het indelen van stalgroepen.

## Wat erin zit

- **Beste keus**: wat is het goedkoopst en het snelst, voor de fokbonus en voor volledige training
- **Overzicht** en **Mijn paard**: kosten en klikjes, ook vanaf het huidige niveau van je paard
- **Fokbonus**: alle combinaties met hun S/D/G-bolletjes
- **Planning**: simulatie per aanpak, klik voor klik, met het echte wedstrijdschema
- **Stalgroepen**: indeling per fase, met niveaus, duur en wanneer je doorschuift
- **Per niveau**, **Methoden**, **Wedstrijden** en **Balkjes**: de details
- **Aannames**: alle prijzen, trainers, XP en beloningen zijn aan te passen

Instellingen worden bewaard in de browser (localStorage).

## Online zetten met GitHub Pages

1. Maak een nieuwe repository aan, bijvoorbeeld `horse-nation-trainingscentrum`.
2. Upload `index.html`, `README.md` en `.nojekyll` naar de hoofdmap.
3. Ga naar **Settings → Pages**, kies bij *Source* **Deploy from a branch**, branch `main`, map `/ (root)`, en klik **Save**.
4. Na een minuut staat de app op `https://<gebruikersnaam>.github.io/horse-nation-trainingscentrum/`.

De app is één los HTML-bestand zonder build-stap. Alleen de lettertypes komen van Google Fonts.
