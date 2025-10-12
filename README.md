A magyar kórházi ágyszám-, betegforgalmi- és halálozási adatok
rekonstrukciója, feldolgozhatóvá tétele és megőrzése
================
Ferenci Tamás (<https://www.medstat.hu/>)<br>
2025. október 12.

A magyar egészségügyi ellátórendszer egyik alappillérét a kórházak
jelentik. Ezek teljesítményének alakulása ebből fakadóan nem csak
önmagában, hanem az egész ellátórendszer jellemzése tekintetében is
fontos; az erre vonatkozó historikus adatok a magyar egészségügy
egészének is fontos jellemzői. Sajnos ilyen adatból – pláne a nyugati
országokkal összevetve – kevés érhető el: jóformán az egyetlen
nyilvánosan hozzáférhető, átfogó adatforrás az ún. „Kórházi ágyszám- és
betegforgalmi kimutatás”, melyet 1993 óta tesznek közzé lényegében
egységes adattartalommal. Ebből megtudható a kórházak szakmai
osztályonként (belgyógyászat, sebészet stb.) lebontott ágyszáma, a
felvett betegek száma, a felvett betegek elbocsátási megoszlása
(eltávozott, más osztályra áthelyezett, meghalt), az egynapos ellátások
száma, az ápolási napok száma, az átlagos ápolási idő és a halálozási
arány, mindez évente.

Ahogy említettem, ez ugyan korlátozott mennyiségű információ, de mégis
sok fontos kérdés már ezekből is megválaszolható. Alkalmas elemzésre,
egészségpolitikai döntések megalapozására, a trendek vizsgálatára, annak
megértésére, hogy az ellátórendszer milyen jellemzőkkel bír és hogyan
alakul.

Még ezen célokra is problémát jelent azonban az adatok
feldolgozhatósága. Noha 2003-tól kezdve elektronikusan is elérhetőek
ezek a kimutatások, valójában ezeknél sem egyszerű a helyzet: az adatok
nem gépi úton feldolgozható formában vannak közzétéve, hanam hatalmas,
több száz oldalas PDF és doc formátumú fájlokban, ráadásul még azokon
belül is össze-vissza széttördelt táblázatokban. Így tehát az a helyzet,
hogy formailag az adatok ugyan közölve vannak, de lényegében semmilyen
feldolgozásra, elemzésre nem alkalmasak, még a legegyszerűbb vizsgálatok
elvégzése is lehetetlen ez alapján.

Éppen ezért célul tűztem ki, hogy e kimutatások adatait beolvassam, gépi
úton feldolgozhatóvá alakítsam, összefűzzem és további elemzésre
alkalmas formátumban, nyilvánosan közzétegyem. A legkevésbé sem titkolt
célom ezzel, hogy további kutatásokat inspiráljak, és tegyek lehetővé
ezáltal. Azt gondolom, hogy ezen információk megőrzése egyfajta
értékmentés is, hiszen ez a jövő generációk számára is fontos
adatforrás, hogy rekonstruálni tudják a hazai egészségügyi
ellátórendszer történetét.

## A GYÓGYINFOK/OEP/NEAK kórházi ágyszám- és betegforgalmi kimutatása

A nagyon kevés, nyilvánosan elérhető, kórházak működésére és
teljesítményére vonatkozó magyar adatforrás egyike az ún. Kórházi
ágyszám- és betegforgalmi kimutatás. Ezt évente közzéteszik, eleinte a
[GYÓGYINFOK](https://itf.njszt.hu/324rtr4/uploads/2020/10/a_szekszardi_gyogyinfok_rovid_tortenete.pdf)
készítette, majd 2004-től az Országos Egészségbiztosítási Pénztár (OEP),
mai nevén Nemzeti Egészségbiztosítási Alapkezelő (NEAK). Az adatok
2003-ig visszamenőleg [érhetőek
el](http://neak.gov.hu/felso_menu/szakmai_oldalak/publikus_forgalmi_adatok/gyogyito_megelozo_forgalmi_adat/fekvobeteg_szakellatas_stat/korhazi_agyszam)
nyilvánosan.

Ezek a kimutatások alapvetően három típusú adatot tartalmaznak: egyrészt
a kórházak ágyszámait (lebontva a szerint, hogy működő vagy szünetelő
ágy) az év utolsó napján és egész éves átlagban, másrészt az elbocsátott
betegek számát, és lebontásukat meghalt, más osztályra áthelyezett,
otthonába távozott csoportok szerint (ez lehetővé teszi halálozási arány
számolását), harmadrészt az átlagos ápolási időtartamot (ezek együtt
lehetővé teszik ágykihasználás számolását). Ezeket az adatokat
megyénként, és szerencsére kórházanként is közlik, valamint alábontják
szakmai osztályonként is. Összességében tehát adott kórház adott
szakmájához lehet leásni. (A „szakma” itt nem azt jelenti, mint a
hétköznapi szóhasználatban, mondjuk, hogy orvos vagy ápoló, hanem azt,
amit szakterületnek szoktak hívni: urológia, szemészet, aneszteziológia
és intenzív betegellátás stb.) Fontos hiányossága még ennek az
adatközlésnek is, hogy a „szakmai osztály” nem ugyanaz, mint a kórházi
osztály: van kórház amelyik három különböző, adott esetben lényegesen
eltérő betegösszetételű és profilú intenzív osztályt is működtet, ám
ebben az adatközlésben ezek elkülönítése nem lehetséges. Az ilyen
különbségeket tehát még ez a relatíve finom felbontású adat is össze
fogja mosni, erre tekintettel kell lenni. A másik fontos limitáció, hogy
betegutat nem tudunk vizsgálni, még annak legszűkebb értelmében sem: az
kiderül, hogy hány beteg van az adott osztályról elbocsátottak között,
akit más osztályra helyeztek át, de arról nincs semmilyen információnk,
hogy ez a másik osztály mi volt.

Bár azt írtam, hogy „nyilvánosan elérhető”, ebben sajnos van egy csavar:
igen, nyilvánosan elérhető – csak épp egy nagyon nehezen feldolgozható
formában. Jelesül, több száz oldalas PDF- és doc-fájlt tesznek közzé,
amelyekben a számok szerencsére táblázatokban, de sajnos össze-vissza
szerepelnek: a táblázatokat megtörik különböző kommentár-szövegek, több
fejezetbe vannak szétosztva, véget érnek az egyik oldalon, majd
folytatódnak a következőn, stb.

Jelen projekt *elsődleges* célja ezeknek az adatoknak a beolvasása a
fenti nehézségek ellenére, majd összeállításuk és elérhetővé tételük egy
gépi úton is feldolgozható, további elemzéseket is kényelmesen lehetővé
tevő formában; *másodlagos* célja a munkámnak néhány alapvető
adatvalidáció elvégzése.

## A végeredmény: a rekonstruált, egységesített, feldolgozható adatsor

A projekt eredményeként letölthetőek feldolgozható, letisztított és
egységes formában a magyar aktív fekvőbeteg-ellátás 2003 és 2024 közötti
ágyszám- és betegforgalmi adatai [CSV
formátumban](https://github.com/ferenci-tamas/korhaz-agyszam-betegforgalom-halalozas/raw/main/ferenci-tamas-korhaz-agyszam-betegforgalom.csv),
továbbá [XLSX (Excel)
formátumban](https://github.com/ferenci-tamas/korhaz-agyszam-betegforgalom-halalozas/raw/main/ferenci-tamas-korhaz-agyszam-betegforgalom.xlsx),
illetve – R nyelvi feldolgozásra alkalmas – [RDS
formátumban](https://github.com/ferenci-tamas/korhaz-agyszam-betegforgalom-halalozas/raw/main/ferenci-tamas-korhaz-agyszam-betegforgalom.rds).

## Technikai részletek

Fontosnak tartom az adatok feldolgozható formára való hozásának
technikai részleteit is közölni, részint mert talán önmagában is érdekes
lehet, emiatt igyekszem kommentálni is, illetve rámutatni a
nehézségekre, részint, hogy a munkám teljesen transzparens, bárki
számára reprodukálható legyen.

Első lépésben kézzel letöltöttem a NEAK honlapjáról az egyes évek
adatait (ki kell csomagolni egy `zip` fájlból; a régiek `doc`
formátumban vannak meg), majd minden egyes év adatát kézzel átmentettem
`docx` formátumba. (Ennek nagy jelentősége nincsen, csak a később
használt `R` csomag a `docx` formátumot tudja minden további nélkül
kezelni.)

Az adatok feldolgozása, és a fenti kitűzött feladatok megvalósítása [R
statisztikai környezet](https://ferenci-tamas.github.io/r-nyelv/) alatt
történt. A transzparencia és a nyílt tudomány jegyében a következőkben
valamennyi R kódot is reprodukálhatóan közlök.

Az adatok feldolgozásához a `data.table` csomagot használtam
segítségként:

``` r
library(data.table)
```

Az adatok beolvasásához a `docxtractr` nevű R csomag jelenti a
megoldást, ez be tud olvasni `docx` formátumú fájlt, sőt, ki tudja
belőle szedni a táblázatokat (akár egyszerre az összeset, egy listában),
ráadásul még azt is jól tudja kezelni, hogy egy táblázat több oldalon
keresztül folytatódik.

Elsőként megadom a használt kódot, utána kommentálom hosszabban, hogy az
mit is csinál:

``` r
headernames <- c(
  "Korhaz", "SzakmaKod", "SzakmaMegnev", "OsszesAgy",
  "MukodoIAgy", "MukodoIIAgy", "TartoSzuneteloAgy",
  "OsszesAtlagAgy", "MukodoAtlagAgy", "ElbocsatottBetegSzam",
  "EltavozottBetegSzam", "MasOsztalyBetegSzam",
  "MeghaltBetegSzam", "EgynaposEsetSzam",
  "TeljesithetoApolasiNapSzam","TeljesitettApolasiNapSzam",
  "ApolasAtlTartam", "Agykihasznalas", "Halalozas"
)

files <- list.files("./doc/")

res <- rbindlist(lapply(files, function(file) {
  yr <- regmatches(file, gregexpr("\\d{4}", file))[[1]]
  
  doc <- docxtractr::read_docx(paste0("./doc/", file))
  
  res <- docxtractr::docx_extract_all_tbls(doc)
  res <- lapply(res, as.data.table)
  
  FenntartoTablaNum <- which(sapply(res, function(x)
    names(x[1,1])) == paste0(
      "Kórházi.ágyszám..és.betegforgalmi.kimutatás.fenntartónként",
      yr, "..év"))
  
  Fenntartok <- data.table(
    Fenntarto = res[[FenntartoTablaNum]][[1]],
    KorhazRovid = res[[FenntartoTablaNum]][[1]])
  Fenntartok[nchar(Fenntartok$Fenntarto)==4]$Fenntarto <- NA
  Fenntartok <- tidyr::fill(Fenntartok, Fenntarto)
  Fenntartok <- Fenntartok[!is.na(Fenntarto)&!is.na(KorhazRovid)]
  Fenntartok <- Fenntartok[nchar(KorhazRovid)==4]
  
  res <- res[sapply(res, function(x)
    names(x[1, 1]) == paste0(
      "Kórházi.ágyszám..és.betegforgalmi.kimutatás", yr, "..év") &
      substring(x[1, 1], 1, 4)%in%Fenntartok$KorhazRovid)]
  
  res <- rbindlist(lapply(1:length(res), function(i) {
    firstactive <- grep("Aktív", res[[i]][[2]],
                        ignore.case = TRUE)[1]
    firstchronic <- grep("Krónikus", res[[i]][[2]],
                         ignore.case = TRUE)[1]
    if(firstactive>firstchronic) NULL else
      setNames(cbind(res[[i]][1,1], res[[i]][6:(firstactive-1),]),
               headernames)
  }))
  
  for(i in headernames[-(1:3)]) res[[i]] <- as.numeric(
    stringr::str_replace_all(res[[i]],
                             c("," = ".", "[[:space:]]" = "")))
  
  res$Ev <- as.integer(yr)
  
  res$KorhazRovid <- substring(res$Korhaz, 1, 4)
  merge(res, Fenntartok, by = "KorhazRovid")
}))

res <- res[order(Ev)]
res$KorhazNev <- ifelse(
  do.call(c, gregexpr("(", res$Korhaz, fixed = TRUE))==-1,
  substring(res$Korhaz, 6), substring(res$Korhaz, 6,
                                      nchar(res$Korhaz)-17))
```

A következő kommentárok tartoznak a fentiekhez:

- A fenntartó azt jelenti, hogy milyen típusú fenntartója van az
  intézménynek (központi, önkormányzati, egyházi stb.). Ezt
  tulajdonképpen hagyhatnánk is, de bizonyos elemzéseknél jól jön, ha ki
  tudjuk zárni az elég atipikus intézményeket (pl. vállalkozások által
  fenntartott intézményeket, melyek jellemzően nulla ágyszámmal csak
  egynapos ellátást nyújtanak), úgyhogy érdemes lehet nem veszni hagyni.
  Ha viszont e mellett döntünk, akkor kicsit küzdeni kell. A
  dokumentumok jellemzően az elején (de még az sem egységes, hogy melyik
  táblázatban, ezért kell a `FenntartoTablaNum`-ban kikeresni a
  sorszámot) közlik a fenntartókat, de nagyon szerencsétlen formátumban:
  egy oszlopban van a fenntartó és az intézmény. Ezt úgy kell
  elképzelni, hogy először szerepel az „önkormányzati eü. intézmény”
  kifejezés, majd utána jönnek az ilyen fenntartójúak azonosítói, aztán
  egy „központi eü. intézmény” szó, majd sorakoznak ezek kódjai stb.,
  ráadásul közben még összegzősorok is vannak. A problémát egy trükkel
  oldjuk meg: ezt az oszlopot kétszer egymás mellé másoljuk, majd az
  egyik oszlopból kitöröljük azokat az értékeket, amik nem 4 hosszúak.
  Ezzel kitöröltük a kórházak azonosítóit, és meghagytuk a
  felirat-szövegeket. (A dolgot az teszi lehetővé, hogy a kórház
  azonosító mindig 4 karakter, viszont a feliratok reményeim szerint
  soha.) Ezt következően a kiüresített helyekre lehúzzuk fentről az
  utolsó szöveget – a `tidyr::fill` pont ezt teszi – így végeredményben
  egymás *mellé* kerültek, ahogy arra szükségünk van, a fenntartók és a
  kódok. Nincs más dolgunk, mint kitörölni a felesleges sorokat, azaz a
  feliratok és az összegző-sorokat, de ezt könnyen megtaláljuk azáltal,
  hogy ezeknél a kód oszlop nem 4 hosszúságú.
- A rengeteg táblázatból meg kell keresni azt az egyetlen kombinációt,
  ami érdekel minket: az intézményre lebontott táblákat. Az ilyeneket
  két feltétellel azonosítjuk: egyrészt a bal szélső oszlop neve adott
  értékű mindig, másrészt leellenőrizzük, hogy a bal felső cellában –
  elvileg itt kell a kórház azonosítója szerepeljen – a megadott
  négyjegyű kód tényleg valódi kórházazonosító-e. (Ezeket az
  azonosítókat az előző lépésnek köszönhetően már ismerjük.)
- A következő probléma az aktív és krónikus ellátások elkülönítése. A
  2012 és azt követő évek táblázataiban nincsen probléma, ezeknél
  ugyanis a krónikus ellátást biztosító szakmáknál üres a szakmakód, így
  nyugodtan legyűjthetjük „ész nélkül” az összes megfelelő táblázatot,
  maximum a végén elhagyjuk azokat, ahol nincs szakmakód. A probléma az,
  hogy 2012 előtt nem követték ezt a szabályt, és a krónikus ellátást
  végző szakmák mellett is fel volt tüntetve a szakmakód. Ez azért gond,
  mert ezek a kódok átfednek az aktív szakmák kódjaival, sőt, akár még
  egy kórházon belül is előfordulhat mindkettő (például 2011-ben a Szt.
  Imre Kórháznak volt 18-as szakmakódú pszichiátriából aktív *és*
  krónikus ellátása is). De az sem jó megoldás, hogy elkezdjük
  legyűjteni a sorokat addig, amíg van szakmakód, mert van olyan kórház,
  amiben egyáltalán nincs aktív ellátás. Végül azt a megoldást találtam
  ki, hogy megkeressük az „aktív” és a „krónikus” szavak előfordulását
  (ezek az összegző-sorokban biztosan szerepelnek). Ha az „aktív” szó
  csak a „krónikus” után van, akkor nincs aktív ellátás (a szó az „aktív
  és krónikus összesen” nagy összegző sorban szerepelt), ezt az
  intézményt átugorhatjuk, ha nem, akkor a kettő *közötti* sorokat kell
  kiszednünk. Ez a megoldás már jól működőnek tűnik, viszont így
  deklarálni kell, hogy a mostani munka kizárólag az aktív ellátásra
  terjed ki.
- A számokat tartalmazó sorokban szóköz az ezres elválasztó,
  tizedesvessző a tizedesjelölő, az előbbieket el kell távolítani, az
  utóbbiakat vesszőre kell cserélni, hogy számmá lehessen alakítható
  (erre a feladatra a `stringr::str_replace_all` kényelmesebb mint a
  `gsub`).
- Szerencsére az oszlopok sorrendje és tartalma végig ugyanaz (ezt
  tartalmazza a `headernames` változó).
- A kórház kódja szerencsére mindig a nevének az első négy karaktere.

A fentiek végén megkapjuk a kialakítani tervezett táblázat első
változatát.

Egyedi kórháznévből összesen 704 van, de ez valójában természetesen nem
jelöl ennyi kórházat, hiszen sok kórház neve változott az évek alatt (a
rekord 9 név). Szerencsére gyors átfutás alapján az adatok rendben
vannak, azaz ugyanahhoz a kód ténylegesen ugyanaz a kórház tartozik (még
ha a neve változott is). Így a kód megfelelő azonosító.

Nézzük most a szakmákat:

``` r
knitr::kable(as.data.table(table(res$SzakmaKod, res$SzakmaMegnev))[
  N != 0][order(V1), .(`Szakmakód` = V1,
                       `Szakma megnevezése` = V2)])
```

| Szakmakód | Szakma megnevezése                        |
|:----------|:------------------------------------------|
|           | Rendkívüli osztály                        |
| 01        | Belgyógyászat                             |
| 02        | Sebészet                                  |
| 03        | Traumatológia                             |
| 04        | Szülészet-nőgyógyászat                    |
| 05        | Csecs.- és gyermekgyógy.                  |
| 05        | Csecsemő- és gyermekgyógyászat            |
| 06        | Fül-orr-gégegyógyászat                    |
| 06        | Fül-orr-gégészet                          |
| 07        | Szemészet                                 |
| 08        | Bőr- és nemibeteg                         |
| 08        | Bőrgyógyászat                             |
| 09        | Ideggyógyászat                            |
| 09        | Neurológia                                |
| 10        | Ortopédia                                 |
| 10        | Ortopédia-traumatológia                   |
| 11        | Urológia                                  |
| 12        | Klinikai onkológia                        |
| 12        | Onkológia, onkoradiológia                 |
| 13        | Fog- és szájsebészet                      |
| 13        | Fogászati ellátás                         |
| 14        | Reumatológia                              |
| 15        | Aneszteziológiai és intenzív betegellátás |
| 15        | Intenzív betegellátó                      |
| 16        | Fertőző betegellátó                       |
| 16        | Infektológia                              |
| 17        | Arc-, állcsont- és szájsebészet           |
| 17        | Felvételi osztály                         |
| 18        | Elmegyógyászat                            |
| 18        | Pszichiátria                              |
| 19        | Tüdőgyógyászat                            |
| 19        | Tüdőgyógyászat (pulmonológia)             |
| 20        | Plasztikai- és égéssebészet               |
| 23        | Gyermek- és ifjúságpszichiátria           |
| 40        | Kardiológia                               |
| 46        | Sürgősségi betegellátás                   |
| 90        | Mátrix intézet                            |
| 91        | Belgyógyászati típusú mátrix              |
| 92        | Sebészeti típusú mátrix                   |

Amint látható, itt már van egy kis kavarodás, de pár kivételtől
eltekintve nem valódi gond van, csak a szakma megnevezése nem volt
egységes. Az egyik kivétel a 17-es kód, itt tényleges gikszer van:
2003-tól 2011-ig ezt a „Felvételi osztály” szakmára használják, utána
viszont egy durva hiba történik, mert *ugyanazt* a kódot kiosztják egy
teljesen más szakmának („Arc-, állcsont- és szájsebészet”). Hasonló
történik a 3-as és 10-es kód kapcsán: 2011-ig a 3-as kód a
traumatológia, a 10-es pedig az ortopédia, ám 2012-től már a kettőt
egybevonják „ortopédia-traumatológia” néven, ami nem lenne probléma, az
viszont már maximálisan az, hogy erre *ugyanazt* a 10-es kódot osztják
ki, ami korábban még csak az ortopédia volt magában… Mindkét esetben
ugyanaz jelenti a megoldást: a kódokat szedjük szét (17F és 17A, illetve
3, 10O, 10OT neveken) úgy, hogy ennek során az évet is tekintetbe
vesszük. (Ez nem lenne kötelező, hiszen az év figyelembevétele a kód
mellett, vagy a szöveges elnevezés használata elvileg biztonságos
megoldás, de a kavarodások elkerülése érdekében jobbnak láttam, ha
pusztán a kód is tükrözi a valós helyzetet.) Potenciálisan zűrös még a
13-as kód: ez 2011-ig a „Fog- és szájsebészet” volt, utána két évig nem
használták, majd 2014-ben visszatért, de immár mint „Fogászati ellátás”.
A biztonság kedvéért ezt is megkülönböztettem (13FSZ és 13F), hozzátéve
mellesleg, hogy valószínűleg a 17F a 13FSZ átnevezése. Ezen felül az
egységesség kedvéért javítsuk ki az ingadozó elnevezéseket is (az ízlés
kérdése, hogy melyiket módosítjuk melyikre, a lényeg, hogy egységes
legyen); illetve egy szakmanevet is lerövidítünk, hogy jobban kiférjen
ábrákon. Összesséségében véve a következő átalakításokat tesszük:

``` r
res[SzakmaMegnev=="Csecs.- és gyermekgyógy."]$SzakmaMegnev <- "Csecsemő- és gyermekgyógyászat"
res[SzakmaMegnev=="Fül-orr-gégészet"]$SzakmaMegnev <- "Fül-orr-gégegyógyászat"
res[SzakmaMegnev=="Bőrgyógyászat"]$SzakmaMegnev <- "Bőr- és nemibeteg"
res[SzakmaMegnev=="Ideggyógyászat"]$SzakmaMegnev <- "Neurológia"
res[SzakmaMegnev=="Klinikai onkológia"]$SzakmaMegnev <- "Onkológia, onkoradiológia"
res[SzakmaMegnev=="Intenzív betegellátó"]$SzakmaMegnev <- "Aneszteziológiai és intenzív betegellátás"
res[SzakmaMegnev=="Aneszteziológiai és intenzív betegellátás"]$SzakmaMegnev <-
  "Aneszt. és intenzív betegellátás"
res[SzakmaMegnev=="Fertőző betegellátó"]$SzakmaMegnev <- "Infektológia"
res[SzakmaMegnev=="Elmegyógyászat"]$SzakmaMegnev <- "Pszichiátria"
res[SzakmaMegnev=="Tüdőgyógyászat (pulmonológia)"]$SzakmaMegnev <- "Tüdőgyógyászat"

res[SzakmaMegnev=="Felvételi osztály"]$SzakmaKod <- "17F"
res[SzakmaMegnev=="Arc-, állcsont- és szájsebészet"]$SzakmaKod <- "17A"
res[SzakmaMegnev=="Ortopédia"]$SzakmaKod <- "10O"
res[SzakmaMegnev=="Ortopédia-traumatológia"]$SzakmaKod <- "10OT"
res[SzakmaMegnev=="Fog- és szájsebészet"]$SzakmaKod <- "13FSZ"
res[SzakmaMegnev=="Fogászati ellátás"]$SzakmaKod <- "13F"
```

Ezek után már a megnevezés aggálytalanul használható.

Ezzel végeztünk az előkészületekkel, nincs más dolgunk, mint
feldolgozható formátumokban lementeni az adatokat:

``` r
saveRDS(res, "ferenci-tamas-korhaz-agyszam-betegforgalom.rds")
fwrite(res, "ferenci-tamas-korhaz-agyszam-betegforgalom.csv",
       sep = ";", dec = ",", row.names = FALSE, bom = TRUE)
openxlsx2::write_xlsx(
  res, "ferenci-tamas-korhaz-agyszam-betegforgalom.xlsx")
```

## Adatvalidáció

Az adatok validitása alatt nem azt értem, hogy melyik adat „gyanús” vagy
akár „szinte irreális” (ilyen is van), hanem azt, ami *matematikailag*
lehetetlen, hogy jó legyen.

Két ilyen ellenőrzési lehetőséget találtam:

- Az ágykihasználás visszaellenőrzése: több esetet találtam, amikor az
  elbocsátott betegek száma nagyobb, mint ami 100%-os ágykihasználásnál
  lehetne (figyelembe véve az átlagos ápolási időtartamot).
- Elbocsátott betegek számának visszaellenőrzése: több esetet találtam,
  hogy ággyal nem rendelkező osztályok több beteget láttak el, mint
  ahány egynapos esetük volt.

Sajnos a fenti jelenségekre nem találtam magyarázatot; mindenesetre a
következőkben közlöm a részleteket.

Az egyik változó, ami más adatokkal validálható, az ágykihasználás. Az
egyszerűség kedvéért vegyünk egy konkrét példát: 2021-ben a hatvani
Albert Schweitzer Kórház (1035) 15-ös kódú intenzív osztályán az ápolás
átlagos időtartama 6.49 nap volt. Ez azt jelenti, hogy ha abban a
pillanatban, hogy felszabadult egy ágy, azonnal új beteg került rá, egy
év alatt összesen 365/6.49 = 56.2 beteget tudtak ellátni. Mivel az évben
átlagosan 6 ágyuk volt, ez összesen 6 · 56.2 = 337.4 beteg. Igen ám, de
közben a tényleges betegforgalom 1841 beteg volt! (Az elméleti maximum
5.5-szerese!) Ezt – intenzív osztályról lévén szó nem meglepő módon – az
egynapos ellátás sem tudja megmagyarázni, ilyen ugyanis nem volt.

Nem tudom a jelenség magyarázata mi lehet, kézenfekvőnek tűnik, hogy a
koronavírus-járvány miatt került ide sok beteg, nagyobb ágyszámon, de ha
így van, akkor meg az átlagos ágyszám adata hibás, hiszen annak
*elvileg* tükröznie kell az egész évben történt változásokat (ennek a
definíciója ugyanis a kimutatás szerint: „kórházi ágyak számának a
tárgyév során bekövetkezett változásait is tükröző súlyozott átlaga”).
Érdekes azt is megjegyezni, hogy igazából már az átlagos ápolási
időtartam sem stimmel (vagy jobban mondva legalábbis nem konzisztens a
többi adattal): a NEAK [definíciója
szerint](https://site.neak.gov.hu/statisztika/2011/pdf/hun/Fekvobeteg_modszertan_2011.pdf)
ez aktív ellátás esetén „a teljesített ápolási napok száma osztva az
osztályokról elbocsátott betegek számával”, jelen esetben 11705 / 1841 =
6.36, ami nem egyezik pontosan a táblázatban szereplő értékkel. (Ez az
apró eltérés az oka annak, hogy a fenti kiszámolt hányados nem egyezik
pontosan a táblában közölt ágykihasználással, ami 534.47%, mindenesetre
ez is bőven 100% feletti.) A dolog nem egyedi, összesen 372 példa van
ilyen adatra. Egyáltalán nem csak a koronavírus-járvány éveiről van szó,
jó kérdés tehát, hogy mi lehet a magyarázat…

Ha már említettem az egynapos ellátást, érdemes arra is ránézni. Itt is
hozok konkrét példát: 2021-ben a László Kórház (0109) 07-es szakmakódú
szemészete nem rendelkezett egyetlen ággyal sem, mégis elbocsátott 937
beteget. Ez nem meglepő, mert egynapos ellátást nyújtott – igen ám, csak
az egynapos ellátási események száma 934 volt. A különbség nem nagy,
talán csak banális adminisztrációs hibáról van szó, mindenesetre a
teljes adatbázisban 1134 esetben fordul elő, hogy működő ágy nélkül
osztályok több beteget bocsátottak el, mint ahány egynapos esetük volt.

És még egy megjegyzés a végére, ami immár nem egy gépi úton, hanem
kézzel felderített probléma, de akkor is probléma: a 0163-as kódú
OITI-nek az adatbázis szerint 2021-ben 42 ágya volt, ami nagyon kevésnek
tűnik (2020-ban még 170 volt). A magyarázat minden bizonnyal az, hogy az
intézmény az év közepén összeolvadt a Nyírővel – ezt egy lábjegyzet
jelzi is a kimutatásban – ám a jelek szerint az ágyszámot mégis az egész
évre osztották le. (Teljesen logikátlan és értelmetlen módon, hiszen ha
a számlálóban, tehát az ágyak napi számának összeadásában csak márciusig
mennek el, akkor nyilván a nevezővel, a napok számával is csak addig
kell elmenni.) Annyit tettem, hogy az egyetlen kimutatásból, ahol név
szerint megjelent volna, a legkisebb kórházak listájából, kézzel
kiszedtem, hiszen így természetesen nincs értelme legkisebb között
lévőnek nevezni.
