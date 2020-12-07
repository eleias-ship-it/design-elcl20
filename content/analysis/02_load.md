---
Title: Analysis
Description: This is our index page for the analysis site.
template: kmom
---

Titel på rapporten
=======================


Inledning
=======================

Denna rapport analyserar laddningstid och resurser från tre webbsidor som underhålls av nyhetsmagasin där det rapporteras om företagsnyheter. Syftet är att ge utveckla resonemang som finns kring webbplatsers prestanda samt ge läsaren en förståelse om vikten av en optimerad hemsida.  Slutsatserna är relevanta för de webbutvecklare som arbetar med nyhetshemsidors prestanda. Olika hemsidor kan ha olika interna krav bolagets ledning vad gäller prestanda. Därför ska jämförelser med andra typer av hemsidor göras med försiktighet. Det är alltså inte säkert att den hemsida med bäst prestanda, även uppfyller hemsidans syfte i högst grad. Däremot är det utan tvivel så, att alla hemsidor sträva mot hög prestanda i någon grad. Dels på grund av miljöaspekter men också eftersom mediateknologins höga framfart hela tiden gör tillgänglig media av högre kvalité. Media med högre kvalité kräver allt som oftast mer minne. Om hemsidor, som har begränsat med cacheminne, önskar använda sig av nya mediateknologier så innebär det även att de ser över hemsidans prestanda.   

Urval
-----------------------

De tre hemsidor som ingår i denna är tre av de mest besökta nyhetsbyråerna med inriktning på företag i USA. De hemsidorna som används i studien är följande:

-<a href="https://finance.yahoo.com/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cud2lraXRlY2h5LmNvbS8&guce_referrer_sig=AQAAABCkujlXERqmXkt0JQB_2VnigfxkP3QN-b90jIvSft9gQdYGsXO0uevG1KC8-10yA8e8J4hnEfROJqxDZRisiHe-7mJ-wANYjwzJOs8Fk7eWXOpAFzW8CnxpAHjqcXVWCOpH7CB8GIJcCFlAmlJh09FWZgprwvfvEjSpfc6A7GCW">Yahoo Finance</a>  

-<a href="https://www.forbes.com/?sh=3bfa9dd62254">Forbes</a>  

-<a href="https://edition.cnn.com/business">CNN</a>  

Urvalet har baserat på estimerade månatliga besökare där de tre hemsidor med flest unika besökare har inkluderats (wikitechy, 2020). Urvalets storlek är vald enligt specifikationen för denna rapport. Ett större urval hade bidragit till ökad validitet av rapportens slutsatser och analyser. Replikerbarheten är dock förhållandevis hög, då en vidarebyggande studie kan återanvända urvalsmetoden och inkludera fler hemsidor.    

Metod
-----------------------
Page Speed kan defineras som den totala tiden att ladda en specifik sidas hela innehåll. Ett verktyg för att mäta en sidas Page Speed är google PageSpeed Insight, vilket denna rapport använder för ändamålet. Det prestandaindex som analysen levererar dokumenteras för både stationär dator och för mobilenheter.

Rapporten använder följande mått för att bedömma hemsidornas prestanda:

*PageSpeed Insight Desktop

*PageSpeed Insight Mobile

*Webdeveloper laddningstid tid i sekunder

*Webdeveloper laddningstid tid i sekunder

*Webdeveloper totala requests

Data som inhämtades från vertyget mozille Webdeveloper avlästes vid den tidpunkt då händelsen "load" nåddes. De tre hemsidorna hade beteendet att fortsätta att hämta och skicka data efter eventet "load" inträffat, varpå en manuell paus av updateringen fick användas i det tillfälle då eventet popade i verktyget. Detta bidrar till en godtyckligt försumbar försening av den data som inhämtas som beror på den mänsliga faktorn. Att förseningen är godtyckligt försumbar beror på att felet minskar ju fler inhämtningar som görs, eftersom de värden som används som resultat är ett medelvärde av de inhämtade datapunkterna. VId samtliga mätningar så rensades cacheminne för att förhindra inkonsekvänta mätningar och för att resultaten ska kunna användas för att nå studiens syfte.

En annan källa till fel är om det nätverk vilket den dator som hämtar data har bristande anslutning, så kan det innebära inkonsekventa mätningar. Dessa misstag reducerades genom att placera datorn bredvid routern.

En relativ jämförselse mellan de tre hemsidorna kan göras genom att indexera de genomsnittliga mätresultaten. Måtten PageSpeed Insight dator och PageSpeed Insight mobil tolkas positivt ju större index som observerades. Därav indexerades de utifrån den nämnaren bland de tre företagen som var störst enligt I = x / N. Måtten  Webdeveloper laddningstid tid i sekunder, Webdeveloper laddningstid tid i sekunder och Webdeveloper totala requests tolkats negativt ju högre de är, varför de indexerades med I = 1 / ( x / N ).


Resultat
-----------------------
Samtliga mätningar är dokumenterade i nedan tabell:<br><br>
![chart1](%assets_url%/img/chart1.png) {.chart}

De indexerade genomsnittliga mätningarna illustreras i grafen nedan:<br><br>
![relativeChart](%assets_url%/img/relativeChart.png)<br><br>

<h3>Yahoo</h3>

![yahoo](%assets_url%/img/yahoo.png)<br><br>
Yahoo har bäst värden för PageSpeed Insight Desktop, Load Time och Total Resource och hamnar på andraplats enligt måtten PageSpeed Insight Monile och Total Requests. Sidan laddar in 227 requests på en genomsnittlig tid av 8.17 sekunder. Storleken på de filer som laddas in är 8.91MB. De genomsnittliga index som observerats för mobilenheter enligt PageSpeed Insight är 21.33 och för Desktop var index 58.67. Ett betydligt bättre värde för stationära datorer.


<h3>Forbes</h3>
![forbes](%assets_url%/img/forbes.png)<br><br>
Forbes presterar relativt de andra hemsidorna bäst i PageSpeed Insight Mobile och har lägst antal totala requests. I de resterande måtten har Forbes de näst högst uppmätta värderna. De totala resurserna som laddas på Forbes sida är endast en procentenhet mindre än Yahoo som hade högst uppmätt index. Forbes laddar i genomsnitt 196.57 requests på 13.55 sekunder där den totala storleken är 8.97MB. PageSpeed Insight Mobile är 30.67 och för Desktop analysen var värdet 45.67.

<h3>CNN</h3>
![CNN](%assets_url%/img/CNN.png)<br><br>
CNN har relativt sämst observerade resultat i samtliga mått. Den största skillnaden observeras genom att granska PageSpeed Insigt Mobile där CNN endast presterar  16% av Forbes analysvärde. CNNs PageSpeed Insight Desktop hade ett väde på 15 och för mobilenheter endast 5 i samtliga mätningar. Sidan laddar 250 requests på 17.13 sekunder till en total storlek av 10.91MB.

Länk till rådata:
[prestanda](%assets_url%/excel/prestanda.xlsx)

Analys
-----------------------

Det finns enligt Moz(2020) ett samband mellan hög Page Speed och låg genomsnittlig besökartid. En hög page speed påverkar även en sidas conversion rate, vilket är den procentuella andelen av besökare som genomför en önskad aktion. Conversion rate kan tolkas med exemplmåttet: antal besöker som läser en artikel dividerat med antal besökare. Med avstamå i detta så riskerar framförallt CNN, som har lågt observerade värden i PageSpeed Insight på mobil samt stationära enheter. CNN har alltså en överhängande risk att erfara en minskad Conversion Rate om sidan inte optimeras. Praktiskt innebär det att de med dagens optimering har CNN färre besökare som klickar vidare på sidan för att läsa artiklar som företaget har för avsikt.

Bounce Rate är andelen besökare som inte klickar sig vidare till en annan sida på webbplatsen. Enligt Moz(2020) så har en lång Page Speed även en negativ effect på en hemsidas Bounce Rate. CNN riskerar alltså med dagens page speed, framförallt på mobilenheter, en onödigt hög Bounce Rate. Även Forbes ligger i riskzonen för ökad bouncerate. Innebörden av Bounce rate i denna rapport är stor, eftersom en läsare som är på jakt efter en artikel egentligen kan återfinna liknande eller lika informativa artiklar på konkurrenters sidor. Att sidan laddas långsamt gör det troligt att en besökare avbryter laddningen av sidan för att besöka en konkurrents artikel.  

Det finns flera sätt att förbättra en sidas Page Speed. CNN skulle till exempel kunna använda sig av optimerade bilformat som JPEG 2000, JPEG XR eller webP istället för de klassiska JPG eller PNG. För mobila enheter finns möjligheten att skala om bilder för mindre enheter vilket minskar titala storleken av bilderna. Detta är relevant för CNN som har lågt observerade värden för mobila enheter.

Ett annat sätt att optimera en hemsidas prestanda är att ta bort oanvänd kod. Det är vanligt att stora mängder javascriptkod körs vid inläsningen av en hemsida, men som inte används. Även onödigt stora CSS-filer är kanske inte alltid nödvändiga för att skapa en hemsida som är visuellt tillfredställande att scrolla på. Det är vanligt att använda caching för att förbättra

En hemsidas låga prestanda kan kokas ner till användarerfarenhet eller User Experience. Att vänta på att en hemsida ska laddas kan liknas vid andra User Experience situationer. Det kan vara lika känslomässigt frustrerande att vänta på bagaget vid en flygplats, eller i en matkö på en affär som att vänta in att en video ska laddas in. Om inte mer frustrerande.  



Slutsats
-----------------------
Vinnaren i testet är tvivelsutan YAHOO som presterat bäst i tre mätvärden och näst bäst i två måtten. Min egenvalda gräns för en acceptabel Page Speed är under sekunder. Under tio sekunder får jag personligen en olustig känsla och frågar mig själv vad som försiggår. I rapporten klarar Yahoo den personliga gränsen men både Forbes och CNN upplevs som långsamma.  



Referenser och författare
-----------------------

Författare av denna rapoprt är Elis Claesson 2020.

Wikitechy, 2020, <i>Top 10 Most Popular Best Business Websites </i>, KaaShiv infoTech, besökt: 03-12-20, <https://www.wikitechy.com/top10/most-popular-business-websites>.

Moz, 2020, <i>Page Speed</i>, Moz Inc, beslkt: 03-12-20, <https://moz.com/learn/seo/page-speed> .
