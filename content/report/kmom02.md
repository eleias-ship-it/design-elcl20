##kmom02

De features som jag har använt i detta kmom är:

* Beräknar gyllene snittet med en forloop och lägger i variabel. Variablen används sedan som en multipel för att justera bredden på min bild img logo.

* använder npm run watch via package json för att automatiskt uppdatara kod från scss.

* Lagt till flertalet iconer i header som förstoras när man för muspekaren över dem. Det är inte helt felfritt, jag tänker jobba vidare och fixa så att de inte laggar till i som de nu gör i storleken. Vet dock inte i dagsläget hur bara.

* mobilkonfigurationen är så gott som felfri. Det ända som inte fungerar är iconerna som även hoppar där.

Jag har inte ännu gjort några extrauppgifter. Jag gör dem senare i veckan om det är så att jag får tid över. Min upplevelse av SASS är hitils positiv. Själva omfattningen av hur mycket man kan göra är för mig i dagsläget oklart men ser fram emot att lära mig mer. Att kompilera från SASS till CSS var trevligt och relativt enkelt att förstå. Trevligt när jag fick igång watchkommandot det vill säga, innan det var det lite pain in the ass.

Mitt tema reflekterar fortsatt en clean hemsida där informationstillgänglighet ska vara i fokus. Färtemat är i stora drag taget från bilden jag har som flash image, genom color picker. Tänker inte slänga in för många färger och vill ha kontraster mellan ljusa om mörka nyanser. Det finnns fortfarande lite finjustering att göra för att bättra på kontrasterna.

Än så länge har jag inte delat upp den scsskod i externa filer. Det är bara en sida eller så än så länge, men jag kommer att dela upp den senare när det finns mer tydliga strukturer att använda. Så att kod som tillhör header får importeras från en header.scss fil, iställer för att den skrivs i style.scss.

TIL är hur {{social.logo}} fungerar, att den hämtar data från en separat fil och ittererar över vad som finns i filen för att skapa iconer. Mycket nice Grejer.
