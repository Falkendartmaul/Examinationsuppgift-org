# Examinationsuppgift - Tailwind CSS

## Syfte
Syftet med projektet är att bygga en webbplats med ett CSS-ramverk för att snabbare ta fram en färdig lösning, med fokus på att använda ramverkets egna klasser i stället for egen CSS.

## Val av Tailwind
Jag valde Tailwind CSS eftersom ramverket ger många utility-klasser för layout, spacing, typografi, färger och responsivitet direkt i HTML. Det gjorde att jag kunde bygga flera sidor snabbt utan att skriva mycket egen styling.

## Komponenter som testats
I projektet har jag använt flera olika komponenttyper med Tailwind:

- Grid-layouts (responsiva sektioner och produktlistor)
- Cards (produktkort och innehållskort)
- Formulär (kontaktformulär och nyhetsbrev i footer)
- Dropdown-meny (undermeny under "Produkter")
- Tabell (produktöversikt på kepssidan)
- Knappar (primära/sekundära knappar och ikonknappar i header)

## Minimal egen CSS
Jag har hållit egen CSS till ett minimum enligt uppgiften. I `custom.css` används i princip bara `@font-face` för lokala typsnitt (Selawik). Layout, avstånd, färger, storlekar och komponentutseende är i övrigt lösta med Tailwinds klasser i HTML-filerna.
