## Welke data levert momenteel al inzichten over de situatie ‘as is’?

- **Welke leefgroepen het logboek gebruiken tijdens de nacht**
- **Hoeveel ingaven er zijn per leefgroep**
- **Hoeveel ingaven verbonden zijn aan een cliënt**
- **Hoeveel ingaven er zijn per dag, week, maand, …**
- **Hoeveel ingaven er zijn per cliënt en deze eventueel linken met de zorgzwaarte**  
  (B- en P-waarden vanuit IDO of zorggebruikers)

---

## Welke data zouden we zinvol vinden maar is niet te extraheren uit de huidige opslag?

- **Niet iedere ingave is aan een cliënt verbonden**
- **Moeilijk om hier een alarm aan te koppelen**
- **Enkel datum van ingave wordt bijgehouden**
  - Moeilijk om hier een alarm aan te koppelen
  - Niet geweten welke ingave tijdens welke nacht gebeurde  
    (bv. ingave op 4 november kan in de nacht van 3-4 november of 4-5 november zijn, waardoor we alarmen van 3, 4 en 5 november moeten nakijken)
- **Geen duidelijk overzicht welke ingaven betrekking hebben tot welke onderwerpen**
- **Moeilijk om deze te linken aan alarmen**

---

## Welke datastructuren hebben we nodig om analyses over nachtzorg te kunnen maken?

- **Datum en tijdstip van ingave**
- **Verplichte ingave van een cliëntnummer**
- **Tag die verbonden wordt met een ingave om aan te duiden wat voor observatie dit was**  
  (alarm, ronde, …)
- **Er is veel ruimte voor human error**, bijvoorbeeld:
  - SABC (dagcentrum) en TD (technische dienst) hebben een ingave
