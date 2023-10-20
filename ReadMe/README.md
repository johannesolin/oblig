# OBLIG3

Beskrivelse:

I denne oppgaven skal du ta wireframene du designet i forrige oppgave, forsiden, produktsiden og den valgfrie siden for nettstedet du har definert, og implementere det ved hjelp av HTML og CSS. Nettstedet skal utvikles for både mobil- og desktopversjoner. Du skal begynne med å utvikle nettstedet for mobil og deretter tilpasse det for desktop. Dette vil sikre at du følger prinsippene for mobile-first. Les gjennom hele oppgaveteksten før du begynner, og utfør oppgaven trinnvis. Med andre ord, ikke start med punkt 3 eller 5, begynn med punkt 1 og jobb deg gjennom oppgaven. Vær flinke til å commite og pushe kode til github underveis. Fristen for oppgaven gjelder uavhengig om maskinen din krasjer eller koden forsvinner. Hvis dere regelmessig commiter og pusher til github har dere alltid back-up.

Trinn 1: Forberedelser:
* Opprett et GitHub-repository og klon det ned til datamaskinen din (du skal levere oppgaven som en GitHub-lenke til prosjektet).
* Lag to undermapper i repository-mappen:
- En kalt "img" som skal inneholde alle bildene du bruker.
- En kalt "css" som skal inneholde stilarket.
* I hovedmappen, på samme nivå som undermappene, opprett tre HTML-filer:
- En index.html fil som blir forsiden din.
- En produkt.html fil.
- En HTML-fil for den valgfrie siden du har laget wireframe for. Navngi denne fornuftig, for eksempel "om-oss.html".
* Innenfor css-mappen opprett en css-fil kalt "style.css". Prosjektet ditt skal kun inneholde én css-fil, og alle HTML-dokumentene skal lenke til den samme css-filen.
* Finn bilder som kan brukes på nettstedet. Bruk gratis tjenester som Pixabay eller OpenAI til bildegenerering (husk kildehenvisning). Alle bildene som brukes skal krediteres med en kildehenvisning. Under hvert bilde du bruker, legg til en link til opphavet (dette genereres ofte automatisk når du laster ned bilder fra Pixabay). Plasser bildene i img-mappen.
* Utfør "git commit" og "push" prosjektet ditt til GitHub. Du kan velge om du vil bruke terminalen eller en desktop-app for dette.

Trinn 2: HTML for Forside, Produktside og Valgfri Side:
* Basert på wireframene du har laget, skal du kode opp de ulike sidene dine ved bruk av HTML5. Bruk semantiske tagger for å strukturere innholdet fornuftig. Du skal bruke følgende tagger: <header>, <nav>, <main>, <section>, <article>, og <footer>.
* Bruk hensiktsmessige overskrifter (h1-h6) basert på viktigheten av overskriftene du bruker på siden.
* Legg til lenker i menyen og andre relevante steder for navigasjon. For eksempel, når du klikker på et produkt, skal du komme til produktsiden, og når du klikker på logoen og/eller hjem-knappen skal du komme til forsiden. Alle sidene skal kunne nås fra hverandre og være lenket sammen.
* Hvis du ikke allerede har gjort det, lenk alle HTML-sidene til style.css-filen. Gjennomfør en enkel test for å forsikre deg om at CSS er riktig koblet. For eksempel, endre bakgrunnsfargen til <body> til blå og sjekk om alle sidene blir blå.
* Bruk en ikonpakke kalt Font Awesome (https://fontawesome.com/ Links to an external site.) og implementer ikonene der det er hensiktsmessig. For eksempel: et handlekurvikon, kartikon for kontaktinformasjon, osv. Implementasjonen av Font Awesome vil bli gjennomgått i forelesningene.

Trinn 3: CSS:
* Du har frihet til å velge skrifttyper og farger, men de må være leselige. Ikke bruk skrifttyper som er vanskelige å lese bare fordi de er "kule", og velg farger som er tydelige og ikke forstyrrende.
* Start med å skrive grunnleggende CSS som skal være standard for mobilversjonen. Deretter legger du til media queries som inneholder CSS-regler for endringer som skal gjelde for desktopversjonen.
* Bygg hovedlayouten (for plassering av header, nav, main, footer) ved hjelp av CSS-grid. Bruk CSS-flexbox for å kontrollere hvordan underliggende elementer oppfører seg innenfor disse områdene, for eksempel hvordan produktkortene plasseres ved siden av eller under hverandre og hvordan de tilpasser seg ved skalering.
- Mobilversjonen skal kun ha en kolonne.
- Desktopversjonen skal ha minst tre kolonner.

Kravspesifikasjoner for godkjent oppgave:
* Du må bruke HTML og CSS (eventuelt SASS hvis ønskelig) for å implementere wireframene. Du kan ikke bruke templating eller rammeverk. All kode skal skrives fra bunnen av. Hvis du bruker OpenAI, må du kreditere det og forklare koden som kommentarer i koden hvor det er brukt. For å lage kommentarer i html skirver man «<!—kommentarer-->», i css skriver man «/*kommentarer*/»
* Nettstedet ditt må være responsivt og fungere på både desktop- og mobilenheter.
* Du må bruke CSS Grid og Flexbox i samsvar med oppgavebeskrivelsen.
* Alle tre sidene må implementeres.
* Alle sidene må validere. Hvis det er en eller flere røde feilmeldinger, blir oppgaven ikke godkjent. Validerer all kode før innlevering!
* Du har en kvote på fem <div>-tagger per side. Hvis du bruker flere, blir oppgaven ikke godkjent. Dette er for å sikre at du ikke bruker dårlige YouTube-tutorials, templating eller annen generert kode fra forskjellige templatingverktøy. Det er viktig å ha god forståelse for bruken av semantiske tagger før du bruker <div>, dette er for at dere ikke skal pådra dere kode-uvaner.
* Dere skal ha en god mappe-struktur som beskrevet i oppgaven, koden deres skal også være riktig inntrykk og ha en god struktur.

Levering:
Dere skal lever en lenke til GitHub-repositoriet som inneholder prosjektet. Sørg for at repositoriet er offentlig (public), slik at vi har tilgang til koden ved levering. Hvis repositoriet blir oppdatert etter innleveringsfristen vil oppgaven ikke bli vurdert og anses som levert for sent. Hvis det er gitt en ekstra sjanse, må denne brukes hvis levering ikke skjer innen fristen eller hvis det blir gjort flere GitHub-push-oppdateringer etter fristen.

Oppgave gitt av Høgskolen i Østfold (07.10.23)
