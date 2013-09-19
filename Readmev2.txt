proglangs.html er hovedfila
proglangs.js er javascript biblotek
proglangs.css er stilsettet. 

_____________________________
Spørsmål til lab2:
Forklar hvilken deler av din applikasjon så langt, implementerer de forskjellige lagene i MVC
arkitekturen. MVC står får ModelViewController, som til norsk kan oversettes til ModellPresentasjonKontorller.

		Her har du tre filer, CSS, JS og HTML. 
		Model: Html fila, er filen som er hovedmodellen og holder på dataen. 
		View: CSS Fila, denne filen bestemmer hvordan vår data vises. 
		Controller: JS Fila kan kontrollere hva som skal vises av informasjonen i HTML. 

__________________________
 Lab1:
0) Les introduksjon til JavaScript på http://w3schools.com/js/js_intro.asp og svar på følgende
spørsmål, hva kan JavaScript brukes til?


1) Les minst de to gitte linkene og forklar med dine egne ord forskjell på CSS id og class
elementer
http://www.tizag.com/cssT/cssid.php
http://csstricks.com/thedifferencebetweenidandclass/
	
		CSS class; brukes om man ønsker å bruke formateringen og utseende på flere områder. 
		Altså om flere sider skal ha samme design/utseende og koder. 
		CSS ID;	brukes bare en gang.

	
2) Vurder og sammenlign brukbarhet til versjoner i deloppgave 0 og deloppgave 1 av designet
for presentasjon av en liste (ta utgangspunkt at listen er mye lengre enn vist i skjermbildene,
over 100 elementer).

		Begge versjoner har god brukbarhet. Men jeg vil si de ofte er til forskjellig bruk.
		Om man har en liste med flere hundre elementer kan fortsatt begge versjoner være grei,
		(såklart ikke en liste med hundre linjer nedover siden, da må navnene settes i kolonner
		3-4-5 elementer per linje) om det blir gjort sytematisk og oversiktlig. 
		Det kan være lettere å lete seg frem enn via et rullegardin. I tillegg brukes ofte 
		listen fremfor rullegardin om en skal ha linker til info sider og annet,
		når en velger et element. (men det kan også gjøres via rullegardin)
		Om det er mye tekst og informasjon på samme side vil kanskje dropdown-meny være mest aktuelt.


3) Med hvilken HTML teknikk og designløsning løser Wikipedia
(http://en.wikipedia.org/wiki/List_of_programming_languages) problemstilling med en lang liste
av programmeringsspråk?

		Her gjør de som jeg skrev i oppgave 2, de har liste med 3 elementer i kolonner per linje
		hvert element er også en link som fører videre til en nettside om elementet.
		De har og sortert det oversiktlig og greit i alfabetisk rekkefølge, som gjør det mer
		brukervennlig å finne frem til det du leter etter.

	
4) Ved å søke på WWW finn ut selv og forklar kort hva som er hovedforskjeller mellom et
<div> og et <span> element (tagg) i HTML.

		<span> brukes på enkle linjer for å style dem
		<div> brukes til det samme men over mer innhold. 
		(en <span> tag kan derfor også brukes inni en <div>.
	

5) Hvike brukbarhetsproblemer er det med den siste versjonen av implementeringen i
deloppgaven 2? Nevn gjerne hvordan man kunne løse problemene. (Tips: overlapp mellom
forskjellige grafiske elementer og tilfelle hvor man ønsker å selektere det første navnet på
programmeringsspårket i listen)

		En kan opprette element i listen som kalles for eksempel "ikke" eller "ikke valgt" 
		og da kan første mulige valg i listen bli element 2. 
	

6) EKSTRA (bare for de spesielt interesserte): hvordan kunne man bruke URLene
som man
finner i Wikipedia’s artikkelen “List_of_programming_languages”, for å gjøre navnet på
programmeringsspråket i teksten “Du har selektert programmeringsspråket BASIC” til en
hypertext som peker til Wikipedia artikkelen (eller en annen WWWressurs)
med beskrivelsen
av dette språket? Linken åpnes i et nytt nettleservindu.


