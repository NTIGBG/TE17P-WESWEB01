## Uppgift cookies

### Kolla w02 för koden vi gick igenom om cookies

1. Skapa en enkel sida i PHP som skapar en cookie och skriver ut dess värde på sidan.

2. Skapa en sida så att en användare kan själv skapa och sätta olika cookies.
	* Börja med att skapa ett formulär som har 3 olika inputs.
		* Namn
		* Värde
		* Tid
	* När man skickar in formuläret så ska man komma till en .php-sida som skapar en cookie med givet namn och värde som som kommer att existera under den angivna tiden.
	* Skriv sedan ut värden på alla cookies som existerar på er sida genom att skriva ``` echo implode("<br>",$_COOKIE); ``` eller ``` var_dump($_COOKIE); ```
	
3. Testa lagra en array i en cookie genom att använda JSON.
	* Antingen utöka formuläret med flera inputs och lagra alla i en array som sedan skrivs ut.
	* Skapa en bestämd array med värden som du sedan skriver ut.

4. Om du hinner göra ännu mer så gå in på w3s och läs på om JSON och testa lagra olika objekt i cookies.

5. Fundera även över vad man mer praktiskt kan använda cookies till på sin sida.

Extra för de som är klara:

6. Testa att lagra en array i ```$_SESSION```. Använd dig av JSON.

7. Testa att lagra ett eller flera objekt i antingen en cookie eller session.
