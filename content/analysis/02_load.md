---
Title: Load
Description: Analysis of loading times
Template: analysis
---

Analys av webbplatsers laddningstid och användbarhet. 
=======================

Denna rapport läser av mätvärden för olika webbplatser och analyserar datan.

Urval
-----------------------

Jag har valt att analysera tre svenska mobilopperatörer. Jag valde bland de operatörer som har egna nät i Sverige; Telia, Tele2, Telenor, Tre och Net1. För att välja ut bland dessa valde jag de med högst användarresultat under 2019 från en rapport om nordiska mobila nätverk av Chris Mills och Fiona Armstrong för Tutela från januari 2020, se referenser. De med de bästa resultaten från denna undersökning var Tre, Telia och Tele2 och jag har därför valt dessa för min analys. 

Metod
-----------------------

För denna undersökning använder jag mig av [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) för att få ett betyg på webbplatsens laddningstid samt Dev Tools Network för att inspektera laddningstider, antalet resurser som laddas och webbplatsernas storlek.

Resultat
-----------------------

Resultatet av gjorda mätningar finns redovisat i 
[**Google sheets.**](https://docs.google.com/spreadsheets/d/1sPnaOg7fSr1YCo2ISML833slRNUjiKkAviNwf_gUfVs/edit?usp=sharing)


<h3>Telia</h3>

![Telia](%assets_url%/img/telia.png){.homepage}
<br>

Vid mättning med Google's Page Speeds Insights får Telias startsida betyget 13/100 för mobilanvändning och 63/100 i desktop.
Vid tre stycken laddningar av startsidan var dess laddningstid 6,16, 7,23 och 5,45 sekunder med ett medelvärde av 6,28. Startsidan laddade 134, 130 respektive 126 antal resurser med ett medelvärde av 130 stycken. Sidans totala storlek var 9,55, 9,32 och 9,32 MB vid laddning vilket ger ett medelvärde av 9,3967.

Telias supportsida fick betyget 49 för mobil och 84 för desktop.
Vid tre stycken laddningar av supportsidan var dess laddningstid 3,32, 5,21 och 4,88 sekunder med ett medelvärde av 4,47. Supportsidan laddade 95, 97 respektive 96 antal resurser med ett medelvärde av 96 stycken. Sidans totala storlek var 5,23, 5,24 och 5,24 MB vid laddning vilket ger ett medelvärde av 5,236.

Telias sida för abonnemang fick betyget 16 för mobil och 62 för desktop.
Vid tre stycken laddningar av webbplatsens sida för abonnemang var dess laddningstid 7,04, 6,42 och 6,26 sekunder med ett medelvärde av 6,573. Sidan laddade 124, 127 respektive 123 antal resurser med ett medelvärde av 124,6 stycken. Sidans totala storlek var 7,81 MB vid alla laddningar vilket också sätter medelvärdet till 7,81.

För optimering av Telias webbplats skulle de kunna arbeta bättre med sina bilder, ändra filformat från jpg och png till ett mer fördelaktigt som JPEG 2000 eller likvärdigt för snabbare nedladdning och som kräver mindra data, använda korrekt storlek på bilder, samt att förbättra bildernas kodning. De skulle även bland annat kunna ta bort oanvänd CCS-kod samt JavaScript. 

<h3>Tele2</h3>

![Tele2](%assets_url%/img/tele2.png){.homepage}
<br>

Vid mättning med Google's Page Speeds Insights får Tele2's startsida betyget 37/100 för mobilanvändning och 88/100 i desktop. 
Vid tre stycken laddningar av startsidan var dess laddningstid 5,27, 4,39 och 4,21 sekunder med ett medelvärde av 4,623. Startsidan laddade 71, 66 respektive 69 antal resurser med ett medelvärde av 68,67 stycken. Sidans totala storlek var 2,71, 2,76 och 2,76 MB vid laddning vilket ger ett medelvärde av 2,743. 

Tele2's supportsida fick betyget 48 för mobil och 97 för desktop.
Vid tre stycken laddningar av supportsidan var dess laddningstid 3,72, 4,11 och 3,77 sekunder med ett medelvärde av 3,86. Supportsidan laddade 77, 69 respektive 71 antal resurser med ett medelvärde av 72,3 stycken. Sidans totala storlek var 3,01, 3,01 och 2,99 MB vid laddning vilket ger ett medelvärde av 3,003.

Tele2's sida för mobilabonnemang fick betyget 29 för mobil och 89 för desktop.
Vid tre stycken laddningar av sidan var dess laddningstid 3,68, 3,75 och 4,43 sekunder med ett medelvärde av 3,953. Supportsidan laddade 61, 58 respektive 61 antal resurser med ett medelvärde av 60 stycken. Sidans totala storlek var 2,61, 2,52 och 2,57 MB vid laddning vilket ger ett medelvärde av 2,56.

För att optimera sin webbplats skulle Tele2 gynnas av att ha en längre cache livslängd för att spara sekunder för återbesök till deras webbplats.

<h3>Tre</h3>

![Tre](%assets_url%/img/tre.png){.homepage}
<br>

Vid mättning med Google's Page Speeds Insights får Tres startsida betyget 33/100 för mobilanvändning och 85/100 i desktop.
Vid tre stycken laddningar av startsidan var dess laddningstid 2,94, 3,97 samt 1,38 sekunder med ett medelvärde av 2,763. Startsidan laddade 109, 109 respektive 104 antal resurser med ett medelvärde av 107,33 stycken. Sidans totala storlek var 4,59, 4,54 och 4,47 MB vid laddning vilket ger ett medelvärde av 4,53.

Tres supportsida fick betyget 31 för mobil och 67 för desktop.
Vid tre stycken laddningar av supportsidan var dess laddningstid 1,88, 1,55 och 1,76 sekunder med ett medelvärde av 1,73. Supportsidan laddade 105, 103 respektive 103 antal resurser med ett medelvärde av 103,6 stycken. Sidans totala storlek var 4,42, 4,37 och 4,39 MB vid laddning vilket ger ett medelvärde av 4,393.

Tres sida för mobilabonnemang fick betyget 21 för mobil och 60 för desktop.
Vid tre stycken laddningar av sidan var dess laddningstid 6,37, 9,66 och 4,27 sekunder med ett medelvärde av 6,76. Supportsidan laddade 81, 85 respektive 81 antal resurser med ett medelvärde av 82,3 stycken. Sidans totala storlek var 6,33 MB vid alla laddningar vilket också ger ett medelvärde av 6,33.

Tre skulle kunna optimera sin webbplats med att ta bort Javascipt som inte används. 


Analys
-----------------------

Efter att ha gjort ovan nämnda mättningar har jag valt att göra följande analys. 
Storleken på webbplatsen har bevisligen påverkan på dess ladningstid, tillsammans med antalet resurser som laddas. Hur man väljer att jobba med bilder har stor påverkan, optimering av filformat och att använda korrekt storlek av bilder är gynnsamt för en webbplats. 
Gemmensamt för de webbplatser jag valt att undersöka skulle de alla kunna otimeras av att ta bort CSS och Javascript som ej används. 

Vid analys av dessa webbplatsers mättresultat har jag kommit fram till att vinnaren för Page Speed är Tele2, följt av Tre och sist kommer Telia. Tele2 har i snitt högst betyg från Page Speed Insights både för desktop och mobil. Vad gäller laddningstider är dock Tre den klara vinnaren, följt av Tele2 och Telia kommer sist även här. 
Tre har allra snabbast laddningstider, i snitt skiljer der 37 millisekunder till Tres fördel, detta för att deras totala betyg dras ner av en långsam sida för mobilabonnemang. Telia har med lägst betyg från Page Speed Insights samt långsammast laddningstider, nästan 40% längre än närmaste konkurent. 

Överaskande är att endast en av webbplatsernas sidor klarar av vad jag anser vara en maxgräns för laddningstid för att uppfattas som en snabb webbplats, 2,5 sekunder. Min hypotes var att mobilopperatörer skulle jobba mycket med webbplatsens laddningstider då det är en så viktig del av varumärke, deras snabbhet och effektivitet men jag tycker att de siffror jag presenterar motbevisar detta. Generellt presenterade mina valda webbplatser dåliga laddningstider och förvånande dåliga betyg för mobilanvändande. 

Referenser
-----------------------

[**Tutela, Nordics State of Mobile Networks**](https://cdn2.hubspot.net/hubfs/2562844/Assets/Nordics%20State%20of%20Mobile%20Networks%20January%202020.pdf?__hstc=&__hssc=&hsCtaTracking=ba7cc05d-34fc-43a9-ad49-37a7458e838f%7C44211c0f-2eaf-4de9-8a80-6179737122a2)

[**Telia**](https://www.telia.se/privat), 
[**Telia - Support**](https://www.telia.se/privat/support), 
[**Telia - Abonnemang**](https://www.telia.se/privat/telefoni/abonnemang-kontantkort)

[**Tele2**](https://www.tele2.se/), 
[**Tele2 - Support**](https://www.tele2.se/support), 
[**Tele2 - Abonnemang**](https://www.tele2.se/handla/mobilabonnemang)

[**Tre**](https://www.tre.se/), 
[**Tre - Support**](https://www.tre.se/support), 
[**Tre - Abonnemang**](https://www.tre.se/privat/handla/mobiltelefoni/mobilabonnemang/)

[**Google PageSpeed Insights**](https://developers.google.com/speed/pagespeed/insights/)

[**Google sheets**](https://docs.google.com/spreadsheets/d/1sPnaOg7fSr1YCo2ISML833slRNUjiKkAviNwf_gUfVs/edit?usp=sharing)

Skrivet av:
-----------------------

Malin Wadholm. 
