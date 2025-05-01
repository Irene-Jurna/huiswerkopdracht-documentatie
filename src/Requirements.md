# Eisen

## Functionele eisen

1. De eigenaar wil in het systeem zien hoeveel producten er op voorraad zijn, gespecificeerd per type (tv, afstandsbediening, muurbeugel, CI-module).
2. De eigenaar wil in het systeem zien wat de prijzen van in- en verkoop zijn.
3. Het systeem houdt bij hoeveel producten zijn verkocht, inclusief datum.
4. De eigenaar wil in het systeem zien hoeveel omzet er is gedraaid per periode.
5. De eigenaar wil in het systeem personeelsgegevens opvragen.
6. De eigenaar wil in het systeem personeelsgegevens aanpassen.
7. De eigenaar wil in het systeem zien waar welke producten staan op dit moment.
8. De eigenaar wil in het systeem zien waar welke producten in het verleden stonden (niet voor de MVP, toekomstige eis).
9. Het systeem kan de naam van het product opslaan.
10. Het systeem kan de mogelijkheden van de producten opslaan.
11. Het systeem laat zien welk product samen kan met een ander product.
12. De eigenaar wil in het systeem zien hoeveel producten er nog binnenkomen, gespecificeerd per type (tv, afstandsbediening, muurbeugel, CI-module).
13. De eigenaar heeft volledige toegang tot alle functies van het systeem.
14. Personeelsleden hebben beperkte toegang tot het systeem, ze kunnen alleen productgegevens inzien en aanpassen wat waar staat.

## Niet-functioneel

1. De app moet gebruiksvriendelijk zijn met een eenvoudige interface voor niet-technische gebruikers. 
2. De app moet binnen 3 seconden reageren. 
3. De app moet veilig zijn, vooral rond personeelsgegevens. 
4. De app moet beschikbaar zijn op desktop, tablet en mobiel. 
5. De app moet beveiligde toegang hebben met inlog-rollen.

## Klassen
Note: Ik heb ervoor gekozen de klassenamen in het Nederlands te doen, omdat het om een Nederlandse winkel gaat en de productten heel specifiek zijn (ik zou niet direct weten hoe een muurbeugel in het Engels heet). 

1. Product (superklasse, met subtypes)
2. TV, Afstandsbediening, Muurbeugel, CI-module (subklassen Product)
3. Gebruiker (superklasse)
4. Personeelslid, Eigenaar (subklassen Gebruiker)
5. ProductLocatie (plek in het magazijn of in de winkel)