Robotour - robotika.cz outdoor delivery challenge
verze 4 (2017-01-31)

Cíl soutěže

Cílem soutěže Robotour je podpořit vývoj robotů schopných dopravit vás třeba
ráno do práce nebo vám přivézt stavební materiál, co jste si právě objednali v
online obchodě. Cesta k takovému cíli nebude ani jednoduchá ani krátká, ale
věříme, že výsledek bude stát za to.

Pravidla

Úkol

Úkolem robotů je v zadaném časovém limitu 1h vyzvednout náklad v nákladovém
prostoru, dopravit ho do zadaného vykládkového prostoru (vzdáleného až 1km) a
opustit soutěžní oblast. Roboti musí být plně samostatní, nesjíždět z
cesty a správně se rozhodovat na křižovatkách podle zadané mapy. Místo startu i
místo cíle bude pro všechny roboty stejné.

Mapa

Roboti mohou používat pouze Open Street Map. Cokoliv co je verifikovatelné a je
popsané mapovými prvky je možné použít týmy pro úpravu mapy soutěžního
prostoru.

Roboti

Tým může nasadit pouze jednoho robota. Robot musí mít EMERGENCY STOP tlačítko,
které robota zastaví. Tlačítko musí být snadno přístupné, červené a musí být
pevnou součástí robota (aka Big Red Switch), aby se v případě hrozícího
nebezpečí dalo snadno stisknout.  Minimální velikost tlačítka je definované
vepsanou kružnicí o průměru 2cm. S robotem musí být možnost snadno manipulovat:
libovolné dvě dospělé osoby ho mohou odnést několik desítek metrů. Je zároveň
definovaná minimální velikost — na robotovi musí být snadno umístitelný
plný 5l pivní soudek.

Vyjetí z cesty

Je dovoleno se pohybovat pouze po parkových cestičkách. Pokud robot sjede z
cesty, aktuální pokus pro něj končí. O jeho včasné odklizení se musí postarat
soutěžící tým.  

Překážky 

Na trase se mohou nacházet překážky. Kromě překážek
přirozených (lavičky atp.) mohou být na trať umísťovány i překážky umělé. Za
typickou (umělou) překážku se považuje například figurant, papírová krabice od
banánů či jiný robot. Roboti nesmí vejít v kontakt s překážkou. Kontakt s
překážkou znamená ukončení pokusu. Robot může před překážkou zastavit a
vizuálně či zvukově upozornit, že překážka byla detekována. Fakt, že překážka
už není přítomná musí roboti detekovat sami.

Interakce robotů

Situace, kdy rychlejší robot dojede robota pomalejšího, nebude nijak zvláštně
řešena. Rychlejší robot se může k pomalejšímu zachovat například jako k
překážce — tj. objet ho nebo počkat, až odjede sám. Obecně budou respektována
pravidla silničního provozu: přednost zprava, vyhýbání se vpravo, předjíždění
vlevo.

Autonomní a servisní oblast

Prostor soutěže bude popisovat polygon označující takzvanou "Autonomní oblast"
(AO). Zde se roboti mohou pohybovat pouze v autonomním režimu. V případě kolize
nebo jiného problému musí soutěžící robota z autonomní oblasti odstranit.
Doplňkový prostor k AO bude "Servisní oblast", kde budou probíhat veškeré
zásahy do programu a konfigurace robota.

Start

Všichni roboti budou startovat na některé z parkových cest v servisní
oblasti. V okamžiku vyhlášení nového startu a cíle mohou roboti úkol okamžitě
realizovat.

Blokování dopravy

Vzhledem k potenciálním dopravním zácpám, na úzkých cestičkách s množstvím
robotů, je zavedeno pravidlo blokování dopravy. Libovolný tým může nařknout
robota jiného týmu, že blokuje dopravu. Od chvíle námitky musí nařčený robot
během jedné minuty opustit oblast definovanou +/- jeden metr z aktuální pozice.
Pokud se mu to nepodaří bude robot zastaven a odstraněn z cesty. V opačném
případě soutěž pokračuje, ale žalující tým dostane napomenutí z falešného
nařčení. Pokud se to bude opakovat 3x, robot žalujícího týmu bude zastaven a
odstraněn z cesty.

Dosažení cíle

Pokud robot dosáhne cílové pozice (nakládková i vykládková oblast),
je třeba tuto skutečnost nějak indikovat
např.  pomocí zvukového signálu. Rozhodčí pozici označí a robot se autonomně
naviguje zpět na další cíl bez zásahu operátora. Robot sám musí poznat, že
operace byla provedena, tj. detekovat, zda má nebo nemá naložený soudek.

Bodování

Vyhrává tým, jehož robot bude úkol nejlépe plnit. Je pouze bodované dosažení
cílové pozice (nakládka i vykládka). Je-li navíc provedena automaticky, získává
tým bonusové body. Robot ještě získá další bod, pokud se po splnění dodávky
vrátí do servisní oblasti.

Robot, který dokáže naložit soudek a následně opustí nakládkovou oblast získá
extra bod. Za automatické vyložení sudu v cíli získá další bod.
Celkově lze tedy v jednom kole získat až 5 bodů.

Organizace

Soutěž bude mít 4+1 kola. Pro každé kolo bude vybrán jiný start a cíl.
Vyhlášení cíle zahajuje kolo. Rychlost v této soutěži nehraje primární roli (je
shora omezena na 2.5m/s). Do celkového výsledku se sčítají body za všechna
kola. Kolo začíná vždy v určený čas a končí po 60 minutách. Každý tým musí
zajistit jednu osobu znalou pravidel, která bude během soutěžního dne patřit do
týmu rozhodčích.

Homologace

Tým se může zúčastnit soutěže, pokud ukáže, že je schopen získat alespoň jeden
bod. Nutnou podmínkou je projet desetimetrový úsek bez kontaktu s překážkou.
Testována bude manální nakládka s automatickým startem a funkčnost EMERGENCY
STOP tlačítka.  Použití tekutin, žíravin, pyrotechnických materiálů a živých
bytostí je zakázáno. Každý robot bude během jízd doprovázen jednou osobou z
týmu, starší 18 let, která je za jeho chování zcela zodpovědná.

Technická dokumentace

Každý tým dodá ke svému robotu (robotům) základní technickou dokumentaci (pro
prezentace, veřejnost a novináře). Vítězné týmy (1. až 3. místo) pak budou
požádány o podrobnější dokumentaci pro webovou prezentaci a tedy zjednodušení
zapojení nováčků do soutěže v následujícím roce.

