# Ročníkový projekt - laboratorní zdroj


### Cílem mého ročníkového projektu

Cílem mého ročníkového projektu je sestavit laboratorní zdroj využívající toroidní transformátor, který jsem získal během letní brigády ve firmě ATAS Velké Poříčí. Transformátor pochází z polohovatelných pracovních stolů, kterých se firma v minulosti zbavovala, a měl být původně určen k likvidaci. Spolu s ním jsem obdržel i malou plastovou krabičku (velikostí menší než krabice od bot) a původní tištěný spoj s elektronikou.

Hlavním cílem projektu je upravit původní krabičku tak, aby do ní bylo možné integrovat moderní napájecí modul zakoupený z Číny, a následně celý zdroj kompletně zapojit, oživit a dovést do finální funkční podoby. Projekt zahrnuje mechanické úpravy krabičky, elektrické zapojení transformátoru a modulu, testování i celkové dokončení zařízení.

### Důvod výběru projektu

Důvodem, proč jsem si zvolil tento projekt, je sestavení laboratorního zdroje s možností plynulé regulace výstupního napětí a proudu. Tento typ zdroje je velmi užitečný při práci s elektronickými obvody a různými zařízeními, kde je nutné přesně nastavit požadované elektrické parametry.

Ve volném čase se rád věnuji vytváření a zapojování různých elektronických zařízení, která ke své činnosti vyžadují rozdílné hodnoty napětí a proudu. Při těchto činnostech jsem často narážel na omezení běžně dostupných zdrojů, které buď neumožňují dostatečně přesné nastavení, nebo nejsou vhodné pro laboratorní a výukové účely. Z tohoto důvodu jsem dospěl k závěru, že sestavení vlastního laboratorního zdroje bude nejen praktické, ale také přínosné z hlediska rozšíření mých znalostí v oblasti elektrotechniky.

Realizací tohoto projektu jsem chtěl získat hlubší pochopení principů regulace napětí a proudu, seznámit se s jednotlivými součástkami a jejich zapojením a zároveň vytvořit funkční zařízení, které budu moci dlouhodobě využívat při dalších projektech a experimentech.

## 1. Popis laboratorního zdroje

Laboratorní zdroj je elektrické zařízení určené k napájení elektronických obvodů s možností plynulé regulace výstupního napětí a proudu. Používá se především při vývoji, testování a opravách elektronických zařízení, kde je nutné přesně nastavit požadované elektrické parametry a zajistit bezpečný provoz.

V rámci tohoto projektu bylo cílem vytvořit laboratorní zdroj vhodný pro běžné laboratorní, školní i domácí použití. Zdroj je navržen tak, aby umožňoval regulaci výstupního napětí a proudu v dostatečném rozsahu a zároveň byl jednoduchý na ovládání a bezpečný při manipulaci.

Základním prvkem zdroje je toroidní transformátor získaný z polohovatelných pracovních stolů. Tento transformátor slouží ke snížení síťového napětí na vhodnou úroveň pro další zpracování. Pro samotnou regulaci výstupních parametrů je použit hotový regulovatelný napájecí modul, který umožňuje nastavování napětí a proudu pomocí ovládacích prvků umístěných na čelním panelu. Celé zařízení je umístěno do plastové krabičky, která byla mechanicky upravena tak, aby vyhovovala použitým komponentům.

## 2. Použité komponenty

Pro realizaci laboratorního zdroje byly použity jak nové, tak i již použité komponenty. Hlavní část zdroje tvoří toroidní transformátor, jehož úkolem je snížit síťové napětí 230 V na nižší napětí vhodné pro další zpracování. Výstupní napětí transformátoru umožňuje výsledný rozsah regulovaného napětí přibližně od 6 V do 36 V.

Regulace výstupního napětí a proudu je realizována pomocí hotového napájecího modulu zakoupeného z Číny. Tento modul zajišťuje stabilní regulaci a zároveň umožňuje jednoduché ovládání pomocí potenciometrů. Pro usměrnění střídavého napětí z transformátoru byl použit diodový můstek, který převádí střídavé napětí na stejnosměrné.

Na výstupu zdroje jsou použity banánkové zásuvky, které zajišťují bezpečné a spolehlivé připojení měřicích hrotů, krokosvorek nebo jiných výstupních vodičů. Všechny komponenty jsou propojeny vhodnými vodiči, které jsou v místech připojení ke svorkám regulátoru krimpované, aby bylo zajištěno pevné a spolehlivé spojení. Pro zvýšení bezpečnosti a zabránění zkratu je na přívodech a vývodech diodového můstku použita smršťovací bužírka.

## 3. Návrh zapojení

Zapojení laboratorního zdroje bylo navrženo s důrazem na jednoduchost, přehlednost a bezpečnost provozu. Síťové napětí 230 V je přivedeno napájecím kabelem ze zásuvky do původního přívodu na krabičce zdroje. Odtud napětí pokračuje přes filtrační člen do primárního vinutí toroidního transformátoru.

Z sekundárního vinutí transformátoru jsou vyvedeny vodiče, které jsou připojeny k diodovému můstku. Diodový můstek slouží k usměrnění střídavého napětí na stejnosměrné. Z jeho výstupů jsou vyvedeny dva vodiče – kladný (plus) a záporný (mínus).

Tyto vodiče jsou následně přivedeny do regulátoru napětí a proudu. Regulátor zajišťuje nastavení požadovaných výstupních parametrů podle potřeb uživatele. Z výstupu regulátoru vedou vodiče k banánkovým zásuvkám umístěným na čelním panelu zdroje. Do těchto zásuvek lze připojit banánky, měřicí hroty nebo krokosvorky, pomocí kterých je možné laboratorní zdroj připojit k napájenému zařízení.

## 4. Mechanické provedení

Aby bylo možné regulátor umístit do původní kovové krabičky, bylo nutné provést několik mechanických úprav. Do krytu krabičky jsem vyřízl otvor odpovídající rozměrům regulátoru. Dále jsem z hliníkového plechu vyrobil držák pro diodový můstek, který zároveň slouží jako pasivní chladič. Hliník byl ohnut do tvaru písmene „L“, opatřen montážními otvory a následně pevně přišroubován ke krabičce.

Pro banánkové zásuvky jsem navrhl výplňový kroužek, který vyplňuje mezeru v původních otvorech po starých konektorech. Tento díl jsem vymodeloval a vytiskl pomocí 3D tiskárny, díky čemuž zásuvky pevně drží a esteticky zapadají do krabičky.



## 5. Vyskytlé chyby při realizaci

Během realizace projektu se objevilo několik problémů. Po prvním připojení regulátoru zakoupeného z Číny jsem zjistil, že jeho displej je nefunkční – byl zamrzlý a nereagoval. Zároveň regulátor zobrazoval nesprávné hodnoty napětí a proudu, tedy chybně měřil. Po diagnostice problému bylo zjištěno, že závada je přímo v displeji regulátoru.



## 6. Realizace – postup práce

Krabička laboratorního zdroje byla sešroubována šesti šrouby na dvě poloviny. Po jejich odšroubování jsem krabičku rozebral a demontoval původní tištěný spoj, který byl připevněn k jedné polovině krytu. Následně jsem odpojil všechny konektory a z tištěného spoje odstřihl diodový můstek, který jsem se rozhodl znovu použít pro usměrnění napětí z transformátoru.

Po dodání regulátoru z Číny jsem do horního krytu vyfrézoval otvor pro jeho osazení. První otvor byl však vyroben příliš blízko okraje, a proto jsem regulátor posunul. Původní otvor bude zakryt záslepkou vytištěnou na 3D tiskárně, která zatím není nainstalována, avšak nemá vliv na funkčnost zařízení.

Na vývodech z transformátoru jsem odstranil původní nakrimpované konektory. Z hliníku jsem vyřízl rovný plátek, který jsem ohnul do tvaru písmene „L“. Tento díl slouží jako držák diodového můstku a zároveň jako chladič. Do hliníku jsem vyvrtal otvory pro přišroubování ke krabičce i pro upevnění samotného diodového můstku.

Dva vývody z transformátoru jsem připájel na prostřední kontakty diodového můstku, které slouží pro střídavé napětí. Spoje jsem zaizoloval smršťovací bužírkou, kterou jsem na vodiče navlékl ještě před pájením. Polarita na těchto kontaktech není důležitá, protože se jedná o střídavé napětí. Na výstupech diodového můstku označených symbolem „+“ a „–“ již proud prochází jako stejnosměrný, a zde je nutné dodržet správnou polaritu.

Kladný pól diodového můstku jsem propojil s kladným vstupem regulátoru hnědým lankovým vodičem a záporný pól modrým lankovým vodičem. Všechny spoje byly opět zaizolovány smršťovací bužírkou. Na konce vodičů vedoucích do regulátoru jsem nakrimpoval dutinky, aby bylo zajištěno spolehlivé uchycení ve svorkách. Stejný postup jsem použil i u vodičů vedoucích k banánkovým zásuvkám.

Při prvních testech jsem narazil na problém, kdy regulátor z Číny nefungoval správně. Po kontrole bylo zjištěno, že závada je v displeji, a proto jsem regulátor reklamoval a objednal nový kus. Po jeho výměně již zařízení fungovalo správně.

Následně jsem laboratorní zdroj testoval pomocí multimetru, který však ukazoval téměř dvojnásobné hodnoty napětí. Po konzultaci ve firmě ATAS jsem obdržel jiný transformátor. Po jeho zapojení se však problém opakoval. Nakonec jsem zjistil, že chyba byla v přívodním měřicím kabelu multimetru, který vykazoval napětí až 400 V. Po výměně kabelu za jiný byly naměřené hodnoty správné.



Po dokončení všech úprav jsem krabičku opět sešrouboval. Laboratorní zdroj je tímto plně funkční, bezpečný a řádně proměřený. Zdroj pracuje v rozsahu 5–36 V s maximálním proudem do 5 A. Displej regulátoru nabízí několik režimů zobrazení, například hlavní napájecí rozhraní se zobrazením nastaveného napětí a proudu, statické rozhraní nebo grafické zobrazení aktuálního odběru a napětí v čase. Mezi užitečné funkce regulátoru patří také možnost zapnutí a vypnutí výstupního napětí.


## Zdroje:
Toroidní transformátor – princip a fungování
Botland.cz. Toroidní transformátor – co to je a jak funguje.
Dostupné z: https://botland.cz/blog/toroidni-transformator-co-to-je-a-jak-funguje/

Diodový můstek – datasheet a informace
AllDatasheet.com. HY/BR352L datasheet.
Dostupné z: https://www.alldatasheet.com/datasheet-pdf/pdf/222971/HY/BR352L.html

Krimpování kabelů – video návod
YouTube. Jak správně krimpovat kabely.
Dostupné z: https://www.youtube.com/watch?v=WMVPOeh8mtQ 
