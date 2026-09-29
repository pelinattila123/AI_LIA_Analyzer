# NextStepAI – Projektarbete i Python

## Mål

Jag ville skapa ett enkelt projekt som hjälper studenter att hitta LIA-plats, träna på CV och öva inför intervjuer.

Programmet är gjort för nybörjare som just har börjat lära sig Python. Jag fokuserade på att använda grundläggande Python-koncept som variabler, datatyper, if-satser, loopar, funktioner, klasser, arv och JSON.

Syftet är att visa hur man kan bygga ett praktiskt och lättförståeligt program med Python.

## Metod

Jag skapade projektet i tre delar: en separat JSON-fil med företagsdata, ett Jupyter Notebook där koden förklaras steg för steg och en README som beskriver projektet.

Jag använde klasser och arv för att organisera koden och skapa olika funktioner för karriärhjälp, LIA-sökning och intervjuträning.

Projektet använder flera bibliotek:

- `json` för att läsa företagsdata
- `random` för att välja ett slumpmässigt intervjutips
- `pandas` för att strukturera data i tabeller
- `matplotlib` för att skapa en enkel graf
- `requests` för att hämta jobbannonser från ett externt API

Projektet använder även JobTech API från Arbetsförmedlingen för att hämta aktuella jobbannonser inom Python.

## Resultat

Med projektet kan användaren:

1. Se företag som passar olika områden, till exempel AI, Python och Dataanalys.
2. Läsa information från en separat JSON-databas.
3. Se företagsinformationen i en tabell med Pandas.
4. Se en graf som visar antal företag inom olika områden.
5. Hämta jobbannonser från ett externt API.
6. Få ett slumpmässigt tips inför en jobbintervju.
7. Se exempel på hur klasser och arv kan användas i Python.

## Analys av bransch, yrkesroller och trender

Jobbannonserna i projektet visar att Python används inom flera olika yrkesroller, bland annat backendutveckling, data engineering och systemutveckling.

Gemensamma kompetenser som återkommer är Python, Git, SQL och molnrelaterad teknik. Det visar att Python används inom flera delar av IT-branschen och inte bara inom AI.

I projektets jobbdata syns även en efterfrågan på kombinationen av programmering och datahantering. För en AI-utvecklare är därför kunskaper inom Python, data och API:er relevanta.

## Relevanta yrkescertifikat

Inom AI, maskininlärning och molnteknik finns flera relevanta yrkescertifieringar.

- **AWS Certified Machine Learning Engineer – Associate** – fokuserar på att bygga, driftsätta och underhålla maskininlärningslösningar i AWS.
- **Google Cloud Professional Machine Learning Engineer** – fokuserar på att bygga och använda maskininlärningslösningar på Google Cloud.
- **Microsofts Azure AI-certifieringar** – Microsoft uppdaterar sina certifieringar inom Azure AI och AI engineering när tekniken och yrkesrollerna förändras.

Certifieringar kan användas för att visa kunskaper inom specifika tekniker och molnplattformar. Vilken certifiering som är relevant beror på vilken yrkesroll och teknisk miljö man vill arbeta med.

## Reflektion över tekniska val och resultat

Jag valde JSON eftersom företagsinformationen är strukturerad och enkel att läsa in i Python. Jag använde klasser och arv för att organisera funktionerna och visa objektorienterad programmering.

Pandas användes för att strukturera företagsinformationen i en tabell och Matplotlib för att visualisera antalet företag inom olika områden. Jag använde även ett externt API för att hämta jobbannonser och lade till felhantering med `try/except` för att programmet ska kunna hantera problem vid API-anrop.

Projektet fungerar som tänkt, men det finns några begränsningar. Företagsdatabasen är liten och antalet jobbannonser från API:et är begränsat. Resultaten kan också förändras eftersom jobbannonserna hämtas från ett externt API.

Om jag skulle utveckla projektet vidare skulle jag lägga till fler företag och analysera fler jobbannonser. Jag skulle också kunna jämföra vilka kompetenser som återkommer oftast och använda resultatet för att ge mer relevanta rekommendationer till studenter.

## Felhantering

Projektet innehåller felhantering med `try/except` i API-delen.

Programmet hanterar bland annat:

- problem med API-anropet
- ogiltig JSON
- felaktigt format på API-svaret

Det gör att programmet kan ge ett tydligt felmeddelande istället för att avslutas direkt om något går fel.

## Hur du kör projektet

1. Öppna mappen med projektet i VS Code.
2. Öppna filen `nextstepai_notebook.ipynb`.
3. Kontrollera att rätt Python-miljö är vald.
4. Kör cellerna i ordning från första till sista.
5. Företagsdata finns i filen `companies.json`.
6. API-delen hämtar jobbannonser från JobTech API.

## Projektstruktur

- `nextstepai_notebook.ipynb` – Jupyter Notebook med förklaringar, kod och resultat.
- `companies.json` – separat databas med företagsinformation.
- `README.md` – beskrivning, analys och reflektion kring projektet.

## Tekniker

- Python
- Jupyter Notebook
- JSON
- Pandas
- Matplotlib
- Requests
- API
- Objektorienterad programmering
- Git och GitHub

## Slutsats

NextStepAI är ett enkelt Python-projekt som kombinerar flera grundläggande programmeringskoncept med datahantering och ett externt API.

Projektet visar hur Python kan användas för att skapa en praktisk lösning för studenter som vill hitta LIA och få bättre förståelse för olika yrkesroller inom IT.