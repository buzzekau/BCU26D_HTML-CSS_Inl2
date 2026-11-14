# Conference web page

A fictive "one-page" conference web page, with program, speaker overview, and ticket section, as well as practical information, built with semantic HTMLS and SASS. Developed for Medieinstitutet HTML & CSS course.

Link to Live Site on GitHub Pages

## Roadmap
[] Concept & Setup
    [] Simple wireframe of web page created
    [x] Theme of the conference chosen
    [] Framework (Sassor Tailwind) for CSS chosen
    [] Repository setup (folder structure)
    [] Block Element Modifier (BEM) researched
[] Semantic HTML
    [] Program with the time, the “title” of each program item, the speaker’s name, and a brief description of the content of the “presentation.” You must include at least 5 program items.
    [] A “gallery” of the conference speakers. You must include at least 5 speakers.
    [] Ticket tiers—you can come up with your own here. For example, “Student,” “After Work,” “Exhibitor,” etc. You must include at least 3 ticket tiers.
    [] There must be practical information, such as the address, a map (a static image—not an interactive map), etc.
[] CSS System & Advanced Selectors
    [] Partials & Mixins setup
    [] BEM naming & logic implemented
    [] Combinator selectors implemented 
[] Responsiveness & Themes
    [] Site Responsiveness enabled
    [] Light & Dark Mode switching enabled
    [] Keyframe animations implemented
    [] Focus states implemented
    [] Reduced-Moten animation implemented
[] Audit
    [] Requirement checklist implemented (see below at Kravlist & G/VG Criteria)
    [] Code formated 
    [] HTML & CSS validated via W3C
    [] Accessibility, Best Practice and Performance analysis done via Lighthouse
    [] README.md file update with AI log and learnings

---

# Beskrivning 

## Inlämningsuppgift
Här är repot för din inlämningsuppgift.

Om filerna:
- `.gitignore` - Denna fil används för att ignorera/exkludera vissa systemfiler som inte behöver komma med i versionshanteringen. En sådan bör man alltid ha i sitt repo.
- `index.html` - För att sidan ska kunna publiceras automatiskt på GitHub Pages är det viktigt att filen heter `index.html` med ett litet `i` i början.
- I mappen `.github` finns ett script som automatiskt publicerar sidan till GitHub Pages.
- I mappen `.github` finns även instruktioner för hur CoPilot ska ge feedback på koden.

## Uppgiftsbeskrivning

Din uppgift är att ta fram en (fiktiv) konferens-sida. Konferens-sidan ska innehålla följande information:

- Schema/program med tid, programpunktens "titel", talarens namn och en kort beskrivning av innehållet på "föreläsningen". Du ska ha med minst 5 programpunkter.
- Ett "galleri" över talarna på konferensen. Du ska ha med minst 5 talare.
- Biljettnivåer, här får du hitta på egna. T.ex. "Student", "After Work", "Utställare", osv. Du ska ha minst 3 biljettnivåer.
- Det ska finnas praktisk information, t.ex. adress, karta (en statisk bild, ska ej vara en interaktiv karta), osv.
- Du får välja tema själv på konferensen, det kan handla om blockchain, crypto, katter, astrologi…

Det går jättebra att använda AI för att slutföra uppgiften. Lägg fokus på att lära dig förstå begrepp och koncept inom CSS under tiden som du jobbar med uppgiften, så att du blir effektiv i din promptning.

Tips/övning! Sätt en "budget" för dig själv, t.ex. att du har max 10 promptar på dig för att slutföra uppgiften. Därefter måste du "koda allt själv". Fundera på hur långt du har kommit efter t.ex. 3 promptar, och om du behöver läsa på om något/förstå något, för att kunna slutföra uppgiften på resterande 7 promptar.

Det räcker med en s.k. "one-pager" för uppgiften, du behöver inte skapa separata sidor.

## Kravlista
- Du ska använda ett "ramverk" eller en pre-processor för att ta fram sidans CSS, t.ex. Sass eller Tailwind.
    - Även om du använder Tailwind eller motsvarande, ska du skriva minst 5 selektorer själv.
- Du ska använda minst 3 "avancerade" CSS-selektorer, t.ex.:
    - barn- eller syskonselektorer (child & sibling combinators)
    - pseudo-klasser (pseudo classes, structural pseudo classes)
    - pseudo-element (pseudo elements)
    - attribut-selektorer
- Du ska ha med minst en CSS-animation
- Det ska finnas stöd för ljust/mörkt tema i grundläggande form, dvs. du demonstrerar att du vet hur du anpassar sidan till ljust/mörkt läge. Det behöver inte vara perfekt och allt behöver inte vara på plats. Det räcker med `prefers-color-scheme`, ingen JavaScript/toggle-knapp krävs. Du kan testa tema via DevTools så behöver du inte ändra i ditt operativsystem.
- Det ska finnas med minst 1 hover-effekt, t.ex. om man för musen över ett talarkort så ska det visas någon extra information. Det kan t.ex. vara en annan bild, kontaktuppgifter, att bilden blir svartvit, eller något annat. Effekten ska även fungera vid tangentbordsnavigering.
- Sidan ska vara responsiv på mobil, tablet och desktop.
- Det ska finnas en navigation/meny som hoppar till rätt sektion på sidan, t.ex. om jag klickar på "Talare" i menyn så ska jag scrollas ner till sektionen som visar alla talare.

## Redovisning och examination
Du ska redovisa din sida på 3 minuter på kursavslutningen. Under redovisningen ska du:

- Visa slutresultatet av sidan.
- Visa hur sidan skalar/är responsiv, dvs. du ska "dra i webbläsarfönstret" för att visa mobilvy, tabletvy och desktopvy.
- Visa vilka CSS-effekter/avancerade selektorer du har använt och var, samt varför. T.ex. vilken teknik du valde och varför.
- För VG: du kan utan hjälpmedel svara på följdfrågor om valfri del av koden.
- ⚠️ Testa skärmdelning innan lektionen och KOM FÖRBEREDD till lektionen med din demo.
- Redovisningsordningen slumpas fram i början på lektionen.
Har du scenskräck så får du höra av dig till mig på Teams så får du instruktioner för hur du gör en individuell redovisning.

## Bedömning

**För IG**
-Du har inte fullföljt uppgiften och möter inte kraven för G.

**För G**
- Samtliga punkter från kravlistan och uppgiftsbeskrivningen är implementerade.
- Koden kan innehålla mindre brister, t.ex. att du använt en `<div>` istället för ett lämpligare HTML-element. Eller att koden inte är korrekt indenterad.
- Du har genomfört en redovisning.
- Sidan är publicerad via GitHub Pages på valfritt sätt (från en branch eller via Actions).

**För VG**
- Samtliga G-krav och samtliga punkter nedan ska vara uppfyllda. Varje punkt är antingen uppfylld eller inte.
- Din kod håller en mycket hög standard, t.ex. att koden är korrekt indenterad och rätt semantiskt element har valts. Koden är formaterad med Prettier (eller motsvarande) med en konfigurationsfil i repot.
- Du har en konsekvent namngivningsstandard som är genomtänkt i CSS:en. Egna klassnamn följer en namnkonvention (t.ex. BEM) som anges i README:n. Med Tailwind: inga egna klassnamn utanför `@layer components`.
- Du använder semantisk HTML på ett korrekt och konsekvent sätt, t.ex. ingen `<div>` eller `<span>` där alternativ finns.
- Din kod är närmast felfri, vad avser såväl HTML som CSS.
- Du har använt `grid` och `flex` på rätt sätt för ändamålet.
- HTML-koden är validerad och ger noll fel.
- Lighthouse-analysen ger: Accessibility 100, Best Practices minst 95 och Performance minst 90. Testet körs i mobilläge. Du har lagt in en skärmdump på resultatet i README-filen i repot. Dock gäller lärarens rättning/resultat vid kontroll.
- Det finns ingen horisontell scroll (side-scroll), inget innehåll som överlappar eller klipps, vid 320, 768, 1024 och 1440 px. Samma gäller vid 200% och 300 % webbläsarzoom på 1440 px. Dvs. sidan fungerar felfritt även vid inzoomning.
- Alla interaktiva element nås med Tab i logisk ordning. Fokusmarkeringen är egendesignad (dvs. ej enbart webbläsar-standard) och tydligt synlig (`:focus-visible`).
- Exakt en `<h1>` och en rubrikhierarki utan hopp, till exempel ingen h2 följd direkt av en h4.
Landmärkena header, nav, main och footer finns.
- Alla bilder är korrekt uppmärkta med nödvändiga attribut, i rätt format och inte för stora i filstorlek (under 1 MB). Du ska veta vilka attribut som krävs.
- All text klarar kontrastkraven för WCAG AA.
- Git-historiken ska visa en arbetsprocess:
    - Minst 12 commits, fördelade på minst 4 olika dagar från det att uppgiften släppts.
    - Ingen enskild commit står för mer än 40 % av slutkodens rader (om det inte är kompilerad kod).
    - Commit-meddelandena beskriver vad som ändrats. "update", "test" och "fix" räcker inte. Använd t.ex. conventional commits.
- Du har redogjort för din AI-logg/-process i README:n i repot. Exempelvis hur du gick till väga, vilka insikter du kom fram till/framtida förbättringar i din process. Skriv också vilket verktyg du använde och var transparent kring dina kunskapsluckor/kritisk självreflektion.
- Det ska finnas en `.gitignore` i repot.
- Animationer ska respektera `prefers-reduced-motion`.