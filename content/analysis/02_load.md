---
Title: Load Analyze
Description: My report for Load.
---


Load
=======================

I denna rapport skal jag välja ut ett antal olika webbplatser och testa dem för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

De webbsidor jag valt att analysera är Youtube som jag vet har mycket datatrafik på sin webbplats sen har jag valt att analysera Blocket hemsida samt Hemnet. Detta är webbsidor jag besöker ganska ofta och är nyfiken på hur dem står sig i testet.

Metod
-----------------------

I denna rapport kommer jag använda mig av Pagespeed Insights för att se laddningshastigheten och vad som behöver optimeras samt Devtools.

[Pagespeed Insights, Blocket](https://developers.google.com/speed/pagespeed/insights/?url=blocket.se&tab=desktop)


[Pagespeed Insights, Hemnet](https://developers.google.com/speed/pagespeed/insights/?url=hemnet.se&tab=desktop)


[Pagespeed Insights, Youtube](https://developers.google.com/speed/pagespeed/insights/?url=youtube.com&tab=desktop)

Resultat
-----------------------
<h3>Youtube</h3>
![image](..\assets\img\youtube.png)

På Pagespeed Insights (mobil) fick Youtube bara 29/100 och rankas därför i spannet 0-46 som är poor. De föreslagna förbättringarna till denna webbplats är att ta bort den del av JavaScriptet som inte används detta i sin tur skulle kunna spara 361,8 KiB med en överföringsstorlek på 527,1 KiB och en uppskattat tidsbesparing på 2,25 sekunder. Sedan har vi upprepade omdirigeringar som också kan spara oss lite tid, närmare 1.89 sekunder. Vi kan också ta bort all den CSS som är oanvänd på webbsidan, detta skulle spara oss yttligare 83,5 KiB. Sist men inte minst kan vi också ta bort resurser som blockerar renderingen och spara yttligare 0,53 sekunder.
Om vi undersöker webbsidan på datorn så får vi ett ännu sämre betyg, 24/100 även detta går under kategorin poor.
Här har vi samma möjligheter att förbättra sidan i kategorierna läs in viktiga resurser i förväg, ta bort resurser som blockerar renderingen, ta bort JavaScript som inte används samt att undvika upprepade omdirigeringar. Den totala tidsbesparingen på detta skulle vara 3,49 sekunder.
[Gå till kalkylblad för mer info](https://docs.google.com/spreadsheets/d/1KAGf6lBgILpvmIgXsy_aPyF4iXYuw1pgkfBF5Ja31aw/edit#gid=0)

![image](..\assets\img\youtubemobile.png)![image](..\assets\img\youtubedesc.png)



<h3>Hemnet</h3>
![image](..\assets\img\hemnet.png)

Hemnet får snäppet bättre betyg med sin rate på 65 på Pagespeed Insights (mobil) vilket betyder "Needs Improvement". Om vi kikar lite på de föreslagna förbättringarna vi kan ge sidan så kan vi likt Youtubes webbsida ta bort JavaScript som inte används, detta skulle vi kunna spara 2,25 sekunder på samt 264 KiB med en överföringsstorlek på 423,3 KiB.
Ta bort resurser som blockerar renderingen kommer också spara oss tid och minne, den möjliga tidsbesparingen är nämligen 1,86 sekunder och 33,6 KiB i överföringsstorlek. Vi även här möjlighet att undvika upprepande omdirigeringar precis som vi hade på Youtube men med några hundradelar färre, nämligen 1,11 sekunder. Vi kan även minska serverns första svarstid och spara yttligare 0,55 sekunder. vi får även följande notis "Se till att serverns svarstid för huvuddokumentet är kort, eftersom alla andra förfrågningar är beroende av det". Näst sist på listan ska vi läsa in viktiga resurser i förväg genom att använda link rel=preload och till sist ska vi undvika att skicka äldre JavaScript till moderna webbläsare som ger en möjlig besparing på 0,3 sekunder.
På datorn får Hemnet betydligt bättre betyg, 78/100. Vi får förbättringsförslag som skulle kunna bespara oss 1,43 sekunder. Möjligheterna är ungefär de samma som för den mobila enheten fast något färre. Ta bort JavaScript som inte används (0,53sekunder), ta bort resurser som blockerar renderingen (0,42 sekunder), undvik upprepade omdirigeringar (0,34 sekunder) samt läs in viktiga resurser i förväg (0,14 sekunder).
[Gå till kalkylblad för mer info](https://docs.google.com/spreadsheets/d/1KAGf6lBgILpvmIgXsy_aPyF4iXYuw1pgkfBF5Ja31aw/edit#gid=0)


![image](..\assets\img\hemnetmo.png)![image](..\assets\img\hemnetdesc.png)

<h3>Blocket</h3>
![image](..\assets\img\blocket.png)

Blocket mobila webbsida får hittills sämst resultat i Pagespeed Insight-testet med ynka 20/100.
Men i detta testet får vi lite nya möjligheter att kunna förbättra sidan. Den största tidsbesparingen kan vi få genom att skicka bilder i modernare bildformat, detta ger en uppskattad tidsbesparing på 3,09 sekunder och storleksbesparing på 685,1 KiB. Vi kan likt de andra sidorna också ta bort JavaScript som inte används vilket ger oss 2,4 sekunder i tidsbesparing. De två sista sätten att tidsoptimera är att använda bilder i rätt storlek (0,3 sekunder) och undvik att skicka äldre JavaScript till moderna webbläsare (0,15 sekunder).
Om vi kollar denna webbsida på datorn istället kommer den precis in på kategorin "Needs Improvement" med sina 50/100. Här är det ganska fattigt om möjligheter att förbättra tidsbesparingen, vi kan ta bort JavaScript som inte används och ta bort resurser som blockerar renderingen med en sammanlagd tidsbesparing på 0,59 sekunder.
[Gå till kalkylblad för mer info](https://docs.google.com/spreadsheets/d/1KAGf6lBgILpvmIgXsy_aPyF4iXYuw1pgkfBF5Ja31aw/edit#gid=0)

![image](..\assets\img\blocketdesc.png)![image](..\assets\img\blocketmobil.png)

Analys
-----------------------

Som man kunde läsa i resultatet så fanns det en hel del möjligheter till tidsbesparing som var
gemensamt för alla sidorna. En av dessa var att Ta bort Javascript som inte används, denna var återkommande på alla webbsidor på den mobila enheten och dessutom den orsak med högst tidsbesparing. En annan sak som också dök upp på samtliga sidor var att undvika upprepande omredigeringar, denna var inte lika tidsbesparande men ändå en sak som verkar vara vanlig, i alla fall på de hemsidorna som jag analyserat. Den webbsidan som stack ut mest när det kommer till möjligheter för tidsbesparing var Blocket som verkade ha lite problem med sina bilder. Denna sida gav till exempel utslag på att skicka bilder i modernare bildformat samt att använda bilder med rätt storlek

Placering
-----------------------
Så, nu är det dags att utse en vinnare i denna analys för laddningstid. Och förstaplatsen går därför till Hemnet som hade bäst resultat på Pagespeed Insights-testet. Denna sida hade "minst" möjligheter till tidsförbättring och laddade snabbast. På en andraplats kom Youtube som jag i förväg hade förväntat mig komma ganska lågt med tanke på dess datatrafik. Och på sistaplats kommer då Blocket med sina bleka 20/100. Detta var dock en webbsida som till utseendet ser ganska enkel ut och därför trodde jag tyvärr att den skulle prestera bättre än vad den i själva verket gjorde.

Gräns för laddningstid
-----------------------
För att bestämma min absoluta gräns för laddningstid tog jag snittet från Speed Index på alla mina tre webbsidor och detta blev 5,06 sekunder vilket jag kan känna är lite väl mycket och i detta fall var det Youtube som drog "upp" tiden. Så jag drar ner det rejält och sätter 2,5 sekunder. Och utgår vi från detta så är det bara Hemnet som klarar sig. Men jag måste tillägga att absolut inte tycker att de andra webbsidorna är långsamma utan detta inser man först nu när man har analyserat dessa. Tanken om laddningstid har inte vart speciellt påtagligen innan detta kursmoment och oftast när webbsidor har vart tröga så har man ofta dragit paralleller till dålig nätverksuppkoppling.



Referenser
-----------------------

[Pagespeed Insights](https://developers.google.com/speed/pagespeed/insights/)

Övrigt
-----------------------

Jag som skrivit denna rapport heter Christian Aronsson.
