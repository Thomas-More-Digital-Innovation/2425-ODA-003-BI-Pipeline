# Vragen Sint-Oda 6/11

## Huidige situatie en data

1. Kunnen jullie meer vertellen over het huidige programma dat wordt gebruikt voor de opvolging van patiënten?
2. Welke soorten data worden momenteel bijgehouden? Zijn er specifieke gegevensformaten waar we rekening mee moeten houden?
3. Hoe groot is de dataset? Hoeveel patiënten en gegevens worden er bijgehouden?

## Vereisten en verwachtingen

1. Wat hopen jullie te bereiken met de BI-tool?
2. Zijn er specifieke meetwaarden die jullie in de dashboards willen zien?
3. Willen jullie dat de dashboards interactief zijn (zoals het kunnen filteren op specifieke data), of eerder statische rapporten?

## Toegang en beveiliging

1. Hoe gevoelig is de data die moet worden verwerkt?
2. Wie zal er toegang hebben tot de BI-tool en de dashboards?

### algemene notes

Tijdens de nachtploeg werken er twee teams, elk bestaande uit twee personen.

- **Team 1**: Eén persoon houdt toezicht achter de computer om de alarmmeldingen in de gaten te houden, terwijl de ander de administratie doet.
- **Team 2**: Twee personen voeren een controleronde uit. Deze ronde duurt ongeveer twee uur, waarna de teams van rol wisselen.

- **Alarmdata**: Informatie afkomstig van de alarmserver (ESSEC).
- **Rondegegevens**: Nadat er een alarm is afgegaan geven ze na hun ronde (de administratieve taak van team 1) de reden in van waarom er een alarm is afgegaan, wanneer de patient wakker was, epilepsie,... De logbestanden worden opgeslagen in CSV-formaat, maar de reden is één groot tekstveld (not nice).

Het systeem waar de rondegegevens ingegeven worden draait overkoepelend, op meerdere vestigingen. De alarmdata draait op een lokaal systeem wat toegang moeilijker maakt en andere mensen aangesproken moeten worden, dit moet afgewacht worden.

**De concrete vraag is:** "Hoe kunnen we de controleronde van de 2 begeleiders verbeteren adhv de alarmen." Momenteel doen ze hun tour huisje per huisje, tenzij er echt een zeer dringend alarm is dat afgaat. Het zou logischer zijn als de zorg zo snel mogelijk geboden kan worden waar nodig.

(niet relevant voor dit project maar ze gaan _keppler_ gebruiken als computer vision systeem om wakkere patienten te detecteren, 99% accuraat, interessant om eens op te zoeken,...).
