---
Title: Report
Description: This is our index page for the report site.
template: kmom
---

<nav class="sidebarflex">
    <a href="kmom01" class="sidebar-list">Kmom01</a>
    <a href="kmom02" class="sidebar-list">Kmom02</a>
    <a href="kmom03" class="sidebar-list">Kmom03</a>
    <a href="kmom04" class="sidebar-list">Kmom04</a>
    <a href="kmom05" class="sidebar-list">Kmom05</a>
    <a href="kmom06" class="sidebar-list">Kmom06</a>
    <a href="kmom07" class="sidebar-list">Kmom07</a>
</nav>


Report page
==========================

### Kmom10 allmänt
Jag har valt Mr solstråle som kund och utgår från att han är styrelseordförande  i en exklusiv, high end advokatbyrå. Personligen anser jag uppgiften med krav 1-4 vara mycket roliga att utföra. Uppgifterna är utformade på ett sett som ger studenten en brant utvecklingskurva inom CSS och HTML samtidigt som hen behöver tänka teoretiskt på vad som kodas. Enligt min uppfattning var även momentens svirighetsgrad i linje med vad som kan förväntas efter kursen och jag upplevde inga moment som extremt krävande. Det som var mest tidskrävande är i min mening de båda analyserna som skrevs enligt krav 5 och 6. Det som jag upplevde som svårt var att uppskatta och disponeringa av tiden som krävdes för vardera krav. Jag  spenderade mycket tid för att få ordning på krav 1-4 och när jag väl var färdig hade jag problem med deadlinen.  
Krav 4 var det moment jag hade enklast för att arbeta mig igenom. Jag hade kodstrukturen klar från krav 2 och hastigheten för vilken jag skrev CSS hade även förbättrats markant. Det luriga var hur som helst att hitta ännu ett tema som matchar kundens önskemål men som drastiskt skiljer sig från tema 1.  


###krav 1
Jag använde en kopia av min portfoliomapp och raderade allt innehåll i contentfiler, cssfiler och rensade nödvändiga rader i twigfilerna. Jag ville snabbt komma igån och kände att metoden var fördelaktig, sålänge jag såg till att verkligen återställa värden så att jag får en fräsch start att utgå ifrån. Metoden är inget jag ångrar och jag stötte på enstaka problem med css-värden från old.scss (som jag kopierade från example) men som jag snabbt kunde åtgärda.
Jag valde Mr Solstråle som kund och skriver i aboutfilen och hidden.md om kravprofilen jag följt. Jag konstruerade en logga i gimp med inspiration från en bild tagen från unsplash samt en gratis favicon från iconfinder.com. Jag har valt en stor flashbild som är tänkt matcha kundens kravprofil. Jag använder listor, bilder, text och rubriker i en vad jag menar är lagom mix.

###krav 2
Jag har valt att använda moduler för variabler, layout, färgschema och en fil för var undersida. Jag använder ett monokromatiskt färgschema med en accentfärg med motiveringen att schemat inte ska vara rörigt utan snarare utrsåla ordning och reda samt stilrenhet. Blå och guld går teoretiskt bra att kombinera enligt Compound Color Scheme och de ger samtidigt assosiationer till det fysiska föremålet guld som förknippas med rikedom och en exklusiv livsstil. Jag har hög balans på homepagen för att skapa dynamik till skillnad från highligtsidan där det förkommer mycket negativ yta för att sätta kundernas profiler i centrum.

Jag använder en mängd designprinciper från Stribley(2020) top 20 lista. De jag använder för tema 1 är framför allt: balans, skala, färg, repetition, framing, grid och typografi och jag skriver mer utförligt om dem i hidden.md.


###krav 3
Jag har lagt många css-rader i mediaqueres på inställningarna max(1144px), max(767px) och max(367px) för att få en följsam responsiv layout för samtliga enheter. Jag använder grid och flexbox på upprepade platser genom layoutem. Grid används i området för flashbilden och på highlightsidan. Flexbox används i navknappar och i stora delar av tema 2 (från krav 4). Det återfinns inga horisontella scrollbars för mobila enheter. Alla bilder som används skalas med <picture> och cimage för att generera tre olika storlekar på bilderna på ett liknande vis som kmom04 med galleryuppgiften.

För att uppnå Accessability 100 har jag justerar kontrasten på headers, lagt till arial-label på länkar och buttons. Jag hade även divar inom taggar vilket försvårar för uppläsningsprogram som tolkar samtliga element inom ul som listalternativ. Jag har använt guld kulör och marinblått som färgschema vilket går väl i hand med färgblinda och det är nästan som att de upplever hemsidan på samma sätt som en person med full syn.


###krav 4
Jag använder till skillnad från krav två, en mindre nivå av balans och väljer istället att centrera element i hög utsräckning. Jag väljer här att introducera linjer för att hjälpa en besökare att dirigeras från en sektion till nästa. Färschemat består här istället av två accentfärger, en mörkt röd och en marinblå i kombination till en bakgrund som skiftar med hjälp av linear-gradien() från gul till vit. Denna sida har en flashbild bestående av grekiska marmorpelare som traditionellt associeras med det juridiska väsendet. Känslan av repetition är större i detta tema då de centrerade elementen på homepagen känns igen på highlightsidan.

###krav 5
Jag har valt att analysera min hemsida med utgångspunkt i design element och principer, som vi skrev i kmom06. Jag har valt att inkludera ytterligare ett moment där jag graderar de fem olika principerna som jag analyserar på advokatsidan enligt en likertskala mellan 1-7. Maxscore är 35 och minscore är 5. Min hemsida fick scoren 23. Detta kanske känns lågt men jag försvarar score i rapporten scoren med att det finns fler principer som inte inkluderas i studien som kan påverka om en hemsida är att betrakta som väldesignad. Jag anser även att designen används på ett sätt som gynnar hemsidans syfte och mål.

###krav 6
Jag analyserar trender inom techföretag som arbetar med design med inriktning mot infrastruktor och bostäder. Jag granskar tre hemsidors homepage och dokumenterar de designprinciper som är förekommande. Jag hittar fem trender som består av designprinciper som förekommer i samtliga tre hemsidor som jag analyserar. Trenderna är att använda ett monokromatiskt färgschema, endast en accentfärg, en video som flashbild, en seriffri typografi samt att placeringen av loggan är längst upp i vänster hörn. Jag ger också en syn på varför det kan tänkas att dessa trender förekommer just 2021.


###Feedback och förbättringsförslag
Det förbättringsförslag som jag har att komma med är själva formatet av rapporterna. Tidsramen som ges genom kursen är alldeles för kort för att slå fast någon som helst slutsats med någon form av validetet eller generaliserbarhet enligt ett forskningsperspektivt. Jag hade lagt betydligt större vikt vid en lång analys och metod med en kort slutsats och minimerat resultatavsnittet (då det tar en massa tid att beskriva dne empiri som inhämtas och sedan används som utgångspunkt i analysen). Det är ju ändå analysen som känns relevant i designområdet. Jag förstår dock att ni vill introducera rapportskrivande till studenter som precis börjat studera och det kan vara så att ni trots detta har valt det optimala sättet att skriva. Bristen jag upplever att tiden kan spenderas på exempelvis resultatkapitel kan spenderas på bättre sätt.

Annars tycker jag Niklas har varit GRYMT bra, duktig snabb, kunnig och trevlig. Emil har jag ett högst vänskapligt tips till och det är att se över alla de "ehm" som kläms in vart och varannan mening i de videor som han spelat in. Utöver det har han kommit med intressanta synpunkter och varit mycket trevlig att lyssna på!

kursen får 8 av 10 av mig =)

###Redovisningsvideo
<video width="720" height="480" controls>
  <source src="assets/videos/redovisning.webm" type="video/mp4">
</video>
