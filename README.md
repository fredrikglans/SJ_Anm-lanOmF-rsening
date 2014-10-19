SJ_AnmälanOmFörsening
=====================

Projektbeskrivning:
- Projekt för att skapa automatisk anmälan vid försening av SJ-tåg

Funktioner:
- Val vilka stationer man åker mellan
- Möjlighet att välja bort SJ Snabbtåg
- Presentation av potentiella tåg i båda riktningarna
- Fält för att fylla i vilken mailadress som påminnelsen om försenat tåg ska skickas till
- Välja datum för giltig månadsbiljett
- Lägga till tidsintervall (30-60 min)
- Ska kunna köras på rPi

Framtida utvidningar:
- Publikt?

Förslag på teknisk lösning:
- Lokal server på rPi som hämtar information om tåg med hjälp av API från tågtider.net (?)

Bra att veta:
- Med hjälp av python kan man starta localhost mha python -m SimpleHTTPServer 8080
