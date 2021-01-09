---
Title: kmom10
Description: My report for Kmom10.
---

Kmom10
==========================


1.1
Den första uppgiften i projektet var att välja hero/flash-bild, egen logga, info i footer, samt navigering för både dator och mobil. Och detta löste jag precis som i portfolion vi arbetat med under kursen, jag valde att ha min portfolio som en mall
där jag gjort ändringar som skulle passa kundens önskemål. Jag tyckte detta var det smidigaste sättet för min egen del, detta gjorde att jag fick mer tid att lägg på det funktionella istället för börja om från ruta ett och konstruera en ny webbsida. Jag började att byta flash-bild till en bild som jag tyckte skulle passa kundens nya tema. Här valde jag en bild som är lite "kod" inspirerad, och min ide från början var att bygga hemsidan efter flash-bildens färger i ett monokratiskt färgschema där jag använt den blå färgen i olika nyanser. Min logga skapade jag på logomakr.com där man kunde skapa en gratis logga till sin hemsida och då valde jag en logga med en blå bakgrund som smälter in i den övriga bakgrunden vilken är en ton från just flash-bilden. Själva logotypen och det påhittade företagsnamnet är ritat i svart. Footern har jag hållit så ren som möjligt, där gjorde jag som vi tidigare lärt oss i kursen att använda ikoner som här består av en email-ikon, en telefon-ikon som skall fungera som kontakt för webbsidans besökare. Sen har jag också kvar länken till FontAwesome. Sen har vi navbaren som skulle vara responsiv på dator och mobilen och navbaren är satt till <i class="fa fa-bars" aria-hidden="true" som visar en navigations-ikon istället för länkar när sidan är satt i mobilläge. Faviconen på webbfliken är en ikon som skall föreställa en dator som också är tagen från FontAwesome.

Den andra uppgiften i projektet handlade om tema. Där utgick jag från mitt gamla tema som vi gjort i kursen och ändrade strukturen så det skulle passa det nya temat. Jag valde att använda mig av det gammla temat eftersom jag var nöjd med själva strukturen och ville bygga projektet efter den. Temat är uppdelat i ett antal moduler bestående av style.scss där huvuddelen av temat finns med, sen har vi också variables.scss där alla färgvariabler finns som sedan importeras till style.scss. Jag har också en gallery.scss där grid finns med för att styra upp bilderna i projekt-sidan, här är även max-width satt så att bilderna anpassar sig efter mobila enheter eller när webbsidan minskas. Och så har vi typography.scss som innehåller all typografi till style.scss.
På about-sidan har jag en länk till min beskrivning av färgpaletten under fliken colors. Denna har jag gjort ungefär som vi gjorde med redovisningstexterna nämligen att skapa en markdown-fil som heter colors.md som är satt till hidden: true.

Den tredje och sista uppgiften jag gjorde på projektet var responsivitet och tillgänglighet. Där använder jag mig av css-grid för att presentera mina projekt jag har under fliken "My projects". Jag har en class som heter gallery där jag anger display: grid; i gallery.scss. Bilderna anpassar jag med hjälp av cimage och picture/srcset och koden till detta finns i min gallery.twig-fil mellan rad 77-91. I Cimage har jag gjort som vi gjorde i kursmomentet med bilderna att vi fixade till img_config.php och angav vilka skalor som skulle vara "aktiva". Sedan har jag tagit den skalan (crop-to-fit&aspect-ratio=16:10) och lagt tillsammans med bilderna i gallery.md som visas i My projects.
Sidan fungerar även bra på mobila enheter, i style.css så är sista stycket om minde enheter där en max-width på 767 pixlar.
Tillgängligheten på sidan skulle vara 100 i accessability och efter första testet hade jag 98 på samtliga sidor, eftersom jag använde den gamla som mall så var allt i sin ordning förutom färgsättningarna och kontrasterna. I Lighthouse analysen fick jag just att kontrasten var för dålig och att det kunde bli svårt att läsa texten på sidan så jag lade till en font-size på 1em så gick den igenom.

1.2
Jag tycker att projektet gick bra att genomföra, det var skönt att ha en grund att stå på när man startade. Men det betydde inte att det var helt problemfritt, jag höll på länge med att få ordning på npm run style-min kommandot i terminalen. Jag tog nämligen bort mitt dark-theme som vi jobbat med i kursen och detta gjorde att jag fick error när jag skulle köra style-min. Det tog ett tag för mig att komma på att den inte kunde referera till package.json där mitt mörka tema fanns med så när jag tog bort det så kunde jag uppdatera mina SASS-filer igen. Ett annat problem som händer titt som tätt var att jag hade fel sökväg till mina bilder, loggan syntes inte när jag bytte ut den därför att jag lagt bilden i fel mapp. Även accessability tog lite tid i och med att jag missförstod felet, jag trodde först att det var färgerna som inte gick ihop medans det egentligen var kontrasten mellan bakgrunden och texten som var för liten. Projektet tog ändå ganska lång tid att få klart, det blev en del ändringar men det var just att man skulle bli nöjd som tog tid. Jag höll på med bakgrundsfärgen ganska länge då den var ljusare och jag tyckte att webbsidan fick ett väldigt analogt utseende, men tillslut blev jag faktiskt ganska nöjd med sidan. Hade jag önskat något mer så skulle jag nog valt en hero-bild istället för en flash-bild för att få en lite mer levande känsla på webbsidan. Jag tycker att detta var ett rimligt projekt för kursen, som jag nämnde innan så fick vi använda oss av grunden från vår portfolio-sida vilket gjorde det hela enklare men samtidigt kunde man då lägga extra tid på att få till utseendet, och min främsta åsikt var att det var ett roligt projekt.

1.3
Jag är väldigt nöjd med kursens upplägg, Jag tycker att det har varit en lagom nivå på kursmomenten och samtliga har vart väldigt givande. I html/php-kursen så använde vi oss av css men nu gick vi in betydligt djupare och det har vart kul att vi fokuserat på just detta. Det har också vart bra att vi i varje kursmoment byggt på vår webbsida samt att kursmomenten vart inom en rimlig svårighetsgrad. Föreläsningarna har också vart väldigt pedagogiska och vi har fått tillräckligt med kunskap genom dessa för att kunna klara kursmomenten. Som jag skrev var det roligt att bara fokusera på hemsidans layout och även de analyser vi skrivit. Analyserna har tagit tid men det har ändå vart lite skönt att fått arbeta med en ren skrivuppgift eftersom det nästan bara har vart kodning så här långt i programmet. Som sagt är jag nöjd med kursen och jag kommer absolut rekommendera denna kursen till dem jag känner och är intresserade.








<div class="sidemenu">
<a href="kmom01"><h2>kmom01</h2></a>
<a href="kmom02"><h2>kmom02</h2></a>
<a href="kmom03"><h2>kmom03</h2></a>
<a href="kmom04"><h2>kmom04</h2></a>
<a href="kmom05"><h2>kmom05</h2></a>
<a href="kmom06"><h2>kmom06</h2></a>
<a href="kmom10"><h2>kmom10</h2></a>
</div>
<div class="sideContent">

</div>
