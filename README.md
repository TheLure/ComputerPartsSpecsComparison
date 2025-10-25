# Jämföra datorkomponenter
Grunder i att jämföra komponenter för speldatorer.

En dator består av ett antal huvudkomponenter: Moderkort, processor, minne, grafikkort, hårddisk, nätaggregat. De ska arbeta tillsammans och det är viktigt att de passar bra ihop.

Moderkortet är den centrala delen på vilka man monterar övriga delar. Det kopplar samman alla andra delar och är viktigt för att övriga delar ska fungera bra.

Processorn är den del som kör programmen. Hög klockfrekvens gör att den kan köra saker snabbt och många kärnor (cores) gör att den kan köra fler saker samtidigt. När man utvecklare program och spel kan det vara svårt att göra så saker går snabbare genom att flera saker händer samtidigt. Därför är det för spel i regel viktigt med hög klockfrekvens. 

Minnet håller information som processorn behöver när programmen körs. Snabbt minne är bättre. I spel brukar mer minne betyda att en större del av spelet får plats i minnet samtidigt vilket betyder att när det väll startat så behöver det inte ladda från hårddisk lika ofta.

Grafikkortet gör mest skillnad för en speldator och är den dyraste komponenten. Utvecklingen går snabbast här just nu och grafikkortet är den del som brukar bli "omodern" först.

Hårddiskar är idag i regel rätt snabba (M2 SSD) och det är inte superkritiskt vad man väljer.

Nätaggregat ska man anpassa i storlek efter hur mycket ström alla komponenter drar tillsammans. Ett onödigt kraftigt nätagg gör att datorn drar onödigt mycket ström och ett för svagt nätaggregat gör att datorn blir instabil eller inte startar alls.

## Moderkort (MB - Motherboard)
### Ordlista
Socket = "uttaget" där man monterar Processorn.
Chipset = En familj av kretsar från Intel eller AMD
### Grunder
AMD och Intel tillverkar grund-chipset och olika socket-standarder som passar de CPU:er de tillverkar. Dessa chipset har ett antal grundegenskaper och begränsningar för vad de klarar, t.ex. hur mycket RAM de kan stödja som max. Tillverkare av moderkort (t.ex. Asus eller MSI) utgår sedan från dessa och bygger egna moderkort av dom och bestämmer hur många av funktionerna som chipsetet stödjer som varje moderkortsmodell ska utnyttja.

Här kan man t.ex. läsa lite om de olika chipset som finns för AMD AM5: https://www.digitalcitizen.life/x670e-x670-b650e-b650-chipsets/

## Processor (CPU - Central Processing Unit)
### Ordlista
Socket = Uttaget där Processorn monteras på moderkortet. De måste vara samma annars passar det inte!
### Grunder
CPU:erna säljs direkt av AMD och Intel som tillverkar dom. Se till att välja senaste socket från tillverkaren om du vill kunna använda samma dator länge och kanske uppgradera CPU i framtiden.
### Viktiga faktorer
- Klockfrekvenser (högre är bättre)
- Inbyggt cache-minne (mer är bättre)
- Antal cores (fler är bättre)
- Tillverkningsteknik (Mindre är bättre! 5nm bättre än 7nm. Mindre teknik drar mindre ström och genererar mindre värme så den kan köras snabbare.)
För spel är nästan alltid högre klockfrekvens viktigare än antalet cores. 6 cores är mer än nog för de flesta spel.
Måste man välja mellan fler cores eller högre klockfrekvens så väljer man högre klockfrekvens om man ska använda datorn för spel.
### Länkar till mer info och jämförelser
https://versus.com/en/amd-ryzen-5-5600x-vs-amd-ryzen-5-7500f

## Minne (RAM - Random Access Memory)
### Ordlista
- Minnes-modul = Själva RAM-delen som man sättar fast på moderkortet.
### Grunder
Viktigt att välja minnes-moduler som passar moderkortet! De som tillverkar moderkort brukar ha ett dokument för varje moderkortsmodell om vilka minnen de testat moderkortet med. Välj ett minne som de testat om man plockar ihop delarna själv!
Vill man utöka minnet i datorn i framtiden är det smart att ta färre men större moduler så man får platser lediga på moderkortet. Om moderkortet har 4 minnesplatser så bygger man i regel så man har 2 lediga när datorn är ny. Då kan man kanske lägga till minne i framtiden istället för att byta ut alla moduler helt.
Det är i regel viktigt att man använder minnesmoduler av exakt samma specifikationer i datorn. Man bör undvika att blanda minnen från olika tillverkare.
### Viktiga egenskaper
- Klockfrekvens (högre är bättre men det beror på moderkort och cpu hur snabbt det går att köra!)

## Grafikkort (GPU - Graphics Processing Unit)
### Grunder
Nvidia och AMD tar fram olika GPU:er i olika varianter (t.ex. RTX 3050, RTX 5060) och sedan tar ett företag som tillverkar grafikkort dessa GPU:er och bygger grafikkort av dom. Grafikkort från samma tillverkare kan ha olika prestanda trots samma grund-GPU genom att tillverkarna ändrar saker som klockfrekvenser av olika slag, bestycker korten med olika antal "miniprocessorer"
Viktigt! Tänk på att om du har en datorskärm med väldigt hög upplösning kräver det mycket mer prestanda av grafikkortet. Man kan "vinna" väldigt mycket prestanda i spel genom att välja en skärm med mer "normal" upplösning.
Snabbt minne och bred minnesbandbredd gör att spel laddas snabbare.
### Viktiga faktorer för prestanda
- Klockfrekvenser (hastighet, snabbare = bättre)
- Minnesfrekvenser (hastighet, snabbare = bättre)
- Minnesbandbredd (jämför med motorväg: Fler bilar kommer fram om det är 4 körfält istället för bara 2. Fler är bättre.)
- Antal "Shaders" eller Shading units (och andra interna mini-processorer)
- Vilken upplösning det ska vara på den bildskärm du ska använda.

Minnesbandbredd gör stor skillnad om den är högre. Ett lite långsammare minne kan ha mycket bättre prestanda om bandbredden är högre!

### Jämföra olika grafikkort
Det är viktigt att jämföra exakta modeller från olika tillverkare. Prestanda kan skilja rätt mycket även om båda korten t.ex. är RTX 5060.

https://versus.com/en/asus-dual-geforce-rtx-5060-ti-oc-edition-8gb-vs-gainward-geforce-rtx-5060-ghost

## Hårddisk (HDD - Hard Disk Drive)
### Grunder
För spel och operativsystem använder man idag M2 diskar. De är standard idag.
Diskar har i regel olika hastighet för läsning och skrivning av data. Ju snabbare desto bättre.
Snabb disk betyder att spel laddas snabbare.

## Nätaggregat (PSU - Power Supply Unit)
### Grunder
Nätaggregatet ska vara anpassat efter hur mycket ström alla komponenterna i datorn drar totalt. Man bör inte ha så stort nätagg som möjligt.
Det finns verktyg som kan hjälpa till att räkna ut hur stort nätagg man måste ha:
https://www.newegg.com/tools/power-supply-calculator
### Rating (Bronze, Silver, Gold, o.s.v.)
Man ser ofta att nätagg har t.ex. "Bronze" rating. Den beskriver hur effektivt ett nätaggregat är. Man kan sammanfatta det som att ju bättre rating desto mindre ström kommer datorn förbruka, de arbetar effektivare helt enkelt.
https://www.clearesult.com/80plus/index.php/program-details#program-details-table

# Speldator
För en speldator är den viktigaste komponenten grafikkortet, de är dyre men det är de som gör den stora skillnaden. Vill man spela i hög upplösning (4K+) behöver man riktigt dyra grafikkor. Dagens processorer däremot är så bra att en "mellan" modell av CPU, som t.ex. en av Ryzen 5 modellerna med hög frekvens, räcker alldeles utmärkt. "Standard" för minne idag är minst 16GB. Mer minne gör i regel inte att ett spel flyter bättre utan har mer att göra att man kan ha igång fler program i bakgrunden. Det kan hjälpa så spel startar/"laddar" lite snabbare. Måste man hålla en budget kan mindre men snabbare minne vara bättre än mer men långsammare minne om man vill ha bra prestanda.

## Bygga från grunden
Bygger man från grunden är det många beslut och en hel del efterforskningar man får göra. Här är ett exempel på hur man kan gå tillväga:
### 1. Bestäm om det ska vara AMD eller Intel
Först får man bestämma om man vill bygga baserat på AMD eller Intel eftersom det påverkar många komponentval.
### 2. Bestäm vilken processor och moderkort du vill bygga runt
Processor och Moderkort måste passa ihop (samma "socket") så de väljer man tillsammans i samma steg. Välj den senaste generationen av CPU från tillverkaren men välj modell efter budget och ändamål. Fär en speldator så är t.ex. en Ryzen 5 eller Intel i5 perfekt balans mellan pris och prestanda.
Välj ett moderkort som är lite dyrare och har de "bättre" uppsättning kretsarna för den generation av CPU du väljer. Tänk också på om du vill t.ex. ha extra funktioner som inbyggt wifi eller bluetooth. Det kan också skilja t.ex. hur många minnesplatser olika moderkort har. Ett moderkort med lite bättre prestanda brukar i regel ha 4st minnesplatser.
Tänk på att moderkort har olika "formfaktor" (ATX, micro-ATX o.s.v.) Detta måste man tänka på när man ska välja ett datorchassi senare.
Om du köper en processor utan fläkt måste du köpa till en sådan!
### 3. Läs på vilka minnesmoduler som rekommenderas för moderkortet
När du har exakt moderkortmodell går du in på tillverkarens supportsida och letar fram listan med vilka minnesmoduler moderkortet testats med. Vill man undvika problem är det smart att välja någon av de minnesmoduler som listas där.
### 4. Välja hårddisk (M2 1TB)
Välj en snabbare M2 disk med så mycket utrymme du behöver och har råd med. 1TB är rätt standard idag som utgångsstorlek.
### 5. Välj grafikkort
Här kan man lägga hur mycket pengar som helst nästan. Viktigt att tänka på är att kortet passar på moderkortet.
### 6. Välj nätagg
När man valt alla delar som drar ström vet man hur stor nätagg man behöver på ett ungefär så det väljer man nu.
### 7. Välj Datorlåda
Sist av allt väljer man datorlåda att bygga i. Den behöver passa den formfaktor moderkortet har och sedan måste alla delar rymmas rent fysiskt! Grafikkort kan vara långa/stora. Fläktar till processorer kan vara stora. Det är bättre att ta en lite rymligare låda så man inte råkar ut för att delarna helt enkelt inte får plats! Chassit bör gärna ha minst en fläkt som suger ut luft ur lådan och gärna en som blåser in luft också så det blir bra cirkulation inuti. Men tänk på att många fläktar kan betyda att datorn låter mycket.

### Checklista av delar för bygge:
- Moderkort
- Processor
- Processorkylare (om det inte följer med processorn). Tänk på du kan behöva någon form av termisk pasta för montering av fläkt! Det ingår i de flesta fall men kolla upp det!
- Minnesmodul(er)
- Grafikkort
- Nätaggregat
- Hårddisk/lagring
- Datorchassi
