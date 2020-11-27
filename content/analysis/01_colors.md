---
Title: Color Analyze
Description: My report for Colors.
---


Färganalys
=======================

I denna analys kommer jag att välja ut ett antal olika webbplatser och dokumentera deras färgpalett och typografi samt argumentera
 kring valet av färg kontra den känsla jag tror webbplatsen eventuellt vill signalera med sitt färgval.

<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 40px; width: 50px; background-color: #ef0">
<td style="height: 40px; width: 50px; background-color: #0ef">
<td style="height: 40px; width: 50px; background-color: #f0e">
</tr>
</table>

Urval
-----------------------

Jag har valt att analysera tre stycken webbplatser som jag har någon form av intresse i. Dessa sidor är liverpoolfc.com, sas.se och
inhalation.se. Alla dessa sidorna har ett tydligt budskap enligt mig, om vi börjar med liverpoolfc.com så framhävs den röda färgen
väldigt tydligen även om den inte är täckt över hela sidan samt Anfield i bakgrunden. SAS har jag valt för mitt intresse över att resa
och dem håller sig också precis som Liverpool fast vid sin signumfärg (blå i detta fall) med tydliga tecken av att du besöker ett
flygbolag. Sist har jag valt ett företag som heter Inhalation Sciences som är verksamma inom läkemedelsindustrin. Jag skulle säga att denna
sida är typiskt steril som dem flesta företag inom branschen.


Metod
-----------------------

Jag har valt att använda mig utav Color Contrast Accessibility Validator för att se hur kontrasterna på de olika färgsättningarna förhåller sig
till varandra samt vilka typsnitt som används. Jag kollar även uppbyggnaden i devtools.


Resultat
-----------------------
<h3>Liverpool</h3>

Liverpools hemsida är rätt så sparsam när det kommer till antal färger. Headern är blandad med vitt och rött
vilket passar bra tillsammans med deras klubb-emblem, och det finns även favicons i en något blekare röd färg.
Själva bakgrunden på hemsidan är en klar vit färg (#fff) vilket skapar stora kontraster till de röda detaljerna
på sidan. Just detta är också klassat som bra färgkombinationer enligt Contrast Accessibility Validator och det
framhäver detaljer.
Däremot gillar inte validatorn färgkombinationen svart och rött vilket finns på sidan men relativt sparsamt. Det finns
två olika nyanser av svart (#000, #333), den sistnämnda är en något ljusare svart som går åt det grå hållet men validatorn
ger utslag på bägge två. Det samma gäller även kombinationen grått och vitt, vill även påpeka att det är en väldigt ljusgrå färg.
Denna gråa färg hittar man nere vid footern tillsammans med sponsorernas logotyper. På schemecolors hemsida kan man se att färgschemat
på deras logga antagligen är en stor inspiration till färgschemat för deras hemsida.
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 30px; width: 50px; background-color: #00a398">
<td style="height: 30px; width: 50px; background-color: #ffffff">
<td style="height: 30px; width: 50px; background-color: #d00027">
<td style="height: 30px; width: 50px; background-color: #fdf667">
</tr>
</table>
Basfärgen vilket är röd har accentfärgen grön i Liverpools logga och på hemsidan kan man även se små gröna detaljer och även där
är basfärgen röd men de gröna detaljerna är väldigt små.
Det är lite svårt att sätta fingret på vilket färgschema hemsidan använder sig av, det är väldiga kontraster men jag skulle vilja säga
att det är ett komplement färgschema man använder sig av.
Personligen tycker jag valet av typsnitt vilket är sans-seriff är lite tråkigt just här eftersom övriga sidan är väldigt kraftfull.
I övrigt tror jag att webbplatsen motsvarar den profil dem vill uppnå och det är väldigt tydligt att dem utgår från sitt klubb-emblem
och det har dem lyckats med.

![image](..\assets\img\liverpoolfc.png)


<h3>SAS</h3>

I Color Contrast Accessibility Validator ger sas.se inga utslag överhuvudtaget. Alla färgkombinationer är godkännda.
Sas webbsida använder sig av ett monologt färgschema. På startsidan använder man sig av flera nyanser av blått, precis som
på Liverpools webbsida så har dem hämtat inspiration från sin företagslogotyp vilket i detta fall är SAS skrivit i vitt med en omsvepande blå bakgrund. Hemsidans bakgrund är även här vit med en blå header och blå footer.
Det finns även inslag av grått i pop-up rutan vid menyvalen i headern samt vid informationen i footern,
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 30px; width: 50px; background-color: #000066">
<td style="height: 30px; width: 50px; background-color: #000099">
<td style="height: 30px; width: 50px; background-color: #0159CE">
<td style="height: 30px; width: 50px; background-color: #ffffff">
</tr>
</table>

Jag kan dock inte hitta någon accentfärg på webbsidan som i detta fall skulle vara något åt det orange, gula hållet efterson basfärgen är blå.
Typsnittet på denna webbsida är precis som på Liverpools webbsida sans-seriff, men till skillnad från denna tycker jag att det passar väldigt bra. De flesta rubrikerna och brödtexterna är Arial Helvetica och faller naturligt in på webbplatsen.
Även här uppfyller sidans profil i text och färg dit man vill ha den. Som jag nämnde tidigare så har man anpassat webbplatsen efter företagets logotyp. De vita inslagen på sidan som även återfinns i sökfunktionen gör det tydligt för användaren att navigera.
Hade detta parti vart en mörkare färg så tror jag att det kunnat skapa förvirring och svårt att hitta på sidan.


![image](..\assets\img\sas.png)


<h3>Inhalation Sciences</h3>

Denna webbsida skulle jag säga är en typisk sida för ett läkemedelsbolag. Det finns stora inslag av vitt med kombinationer av gråa nyanser och blåa detaljer vilket får webbsidan att framstå som väldigt steril. Jag tror att man vill uppnå just denna layou, dels för att man förknippar denna bransch med att vara steril men också för att betona den rena miljö som dem verkar i. I Color Contrast Accessibility Validator får denna sida ett felmeddelande på färgkombinationen och detta mellan en krämvit färg (#fef0d6) och den blåa färgen (#46749a) men det skall tilläggas att denna kombination är väldigt diskret och minimalistisk på sidan. De kombinationer som är godkännda på sidan är den "helvita" färgen tillsammans med den svarta färgen även den krämvita färgen gör sig bra med svart.
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 30px; width: 50px; background-color: #ffffff">
<td style="height: 30px; width: 50px; background-color: #fef0d6">
<td style="height: 30px; width: 50px; background-color: #46749a">
<td style="height: 30px; width: 50px; background-color: #222222">
</tr>
</table>
Sidan består av en vit header med diskreta navbars och företagets namn samt logotyp. Precis som Liverpool och SAS webbsida så har även Inhalation Sciences plockat färger ur sin logotyp och sedan använt som tema till sin webbplats. Det är främst den blå färgen som återfinns på sidan, framför allt i footern. I logotypen hittar vi även väldigt små inslag av lila som nästan smälter in i det blåa, men den lila färgen återfinns förövrigt inte på webbsidan.
Likt SAS är det svårt att hitta en accentfärg till basfärgen som är vit, givetvis skulle man vilja säga svart men det är väldigt små och få svarta detaljer. Även färgschemat kan vara lite klurigt att lista ut men om vi går tillbaka till den vita och svarta färgsättningen så vill jag påstå att det är ett komplement färgschema som används, alltså färger i från motsatta sidor i färghjulet. Över hela sidan används Roboto, sans-seriff och det förstärker just den där sterila kännslan jag nämnde tidigare.
Webbsidan är informativ och steril vilket gör den lite tråkig men jag tror ändå att det är precis vad företaget vill.


![image](..\assets\img\inhalation.png)



















Analys
-----------------------

Det har vart intressant att analysera dessa webbsidor, det är väldigt mycket man inte lagt märket till innan.
Men en väldigt tydlig sak jag sett är att alla dessa företag utgår från sina företags-logotyper, vilket i sig inte är
så ovanligt att man gör. Det var tre stycken väldigt olika webbplatser i denna analys men alla dessa använde sig av sans-seriff
och som jag precis nämnde att man bygger webbplatsen efter logotyp så vissa likheter fanns det ändå. Den sidan som stack ut mest
i jämförelse med de andra var inhalation Sciences med sin väldigt sterila layout, en sida som var väldigt färglös men trotts detta
ändå lyckas få fram sitt budskap. Men man skall också nämna att det en webbsida som kanske inte väcker så stort intresse hos en ny
användare.
Den sida som enligt mig var den mest intressanta var Liverpool, även om validatorn hade många synpunkter på färgsättningen så tyckte jag att den var väldigt stark i sina kontraster. Det röda mot det svarta framhävde många vigtiga detaljer på sidan.
Men med facit i hand så tog SAS hem första priset för validatorn när det kom till färgsättningen vilket denna analys handlade om.



Referenser
-----------------------

https://dbwebb.se/guide/design-med-html5-och-css3/farg

https://color.a11y.com/Contrast/

Övrigt
-----------------------

Jag som skrivit denna analys heter Christian Aronsson
