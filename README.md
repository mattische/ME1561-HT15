# ME1561-HT15
Students enrolled @ Webbutveckling, attending course ME1561 autumn 2015


## Övning - Plotta ut klasskamrater
Denna övning går ut på att komma in i de mest grundläggande teknikerna i Webbutveckling - html, css och javascript.

Du ska på en karta lägga till samtliga klasskamraters hemstäder.
Ta en titt i filen som heter map.html - däri läggs några s.k markers till en karta. Ladda hem filen och öppna den i en webbläsare och se vad som händer.
Försök att lägga till dig själv genom att modifiera/lägga till kod i map.html.

Samarbeta gärna med en eller flera i klassen, men gör en egen version av en karta med samtliga klasskamrater utmarkerade.

Den här övningen kommer att utökas efter hand - ta en titt här (på github) då och då för att se om någon ny information har lagts ut.

### Del 1 - plotta ut samtliga klasskamraters hemstäder
Modifiera/lägg till i källkoden i filen <code>map.html</code> så att en marker är placerad på klasskamratens hemadress (latitud och longitud).
När man klickar på en marker ska en inforuta visas med personens namn och en liten bild på personen.


##### Tips: 
öppna map.html i din webbläsare. Testa att ändra i koden och se vad som händer...
Försök förstå koden i filen..
Vad betyder och har t ex följande för funktion:
<code>
<!DOCTYPE html>
<html lang="sv">
<head>
<meta charset="utf-8">
...
</code>

Vad gör egentligen den här koden:
<code>
map = new google.maps.Map(document.getElementById("Map"), {
			zoom: 8,
			mapTypeId: google.maps.MapTypeId.ROADMAP,
			center: region,
		});
</code>

Samarbeta! Hjälp varandra!
För att lösa den här övningen behöver alla samrabeta, och förhoppningsvis lära känna varandra lite bättre....

Informationskällor om html/css/javascript är 
- http://www.w3schools.com/
- https://www.codecademy.com/
- http://www.w3schools.com/googleapi/google_maps_basic.asp
- http://www.w3schools.com/googleapi/
- https://developers.google.com/maps/


Använd en editor för att skriva/modifiera s.k källkod. Två tips (om du inte redan har en favorit) är;
- http://www.sublimetext.com/3
- https://atom.io/


### Del 2 - ställen i Karlshamn
Lägg till markörer för olika ställen i Karlshamn. T ex restauranger, vart kåren ligger, affärer etc.
I inforutan som visas när ma klickar på dem, ska förutom namnet och kort info om stället även visas en länk till 
ställets egna hemsida. När man klickar på den länken ska hemsidan öppnas i en ny sida.

### Del 3 - bättre sida
Sidan <code>map.html</code> är inte speciellt snygg.... Förbättra den med färger och text.
Använd css för att strukturera och skapa en egen design för att visa kartan.
Lägg all css-kod du skriver i en egen fil och hämta in den i map.html.

### Del 4 - separera javscriptet
Placera all javascript som har med kartan att göra i en egen fil. Döp den till <code>map.js</code> och länka in den i map.html.


### Del 5 - en egen sida
Gör en egen sida om dig själv. Presentera dig för dina klasskamrater på sidan.
När man klickar på markören som visar infon om dig så ska inforutan visa länken som tar
dig till den sida du nyss har gjort.
Nu kommer det svåra - se till att få tag i alla dina klasskamraters egna sidor. När man klickar på en klasskamrats markör ska en länk
till dennas sida finnas med och visa just den kamrates egna sida....


### Del 6 - Google maps API
Undersök Google Maps API:t. API:er är något du kommer att jobba med mycket framöver och det är bra att redan nu börja titta på ett. Mer information om Google's API finns bland länkarna ovan.
Använd API:t och ändra/lägg till/ gör något. Exempelvis förändra markörerna till andra symboler/ikoner.
Eller varför inte mäta sträckor eller visa vägar mellan dig och andra klasskamrater?

### Del 7 - location
Plotta ut din egna position i kartan, dvs där du är just nu...

### Del 8 - jQuery
I head-sektionen i map.html hämtas ett script in som heter något med jquery?
Vad är det? Undersök och försök göra något med det, exempelvis effekter.

Det kommer mer...... stay tuned



