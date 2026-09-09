---
{"dg-publish":true,"permalink":"/i-projects/03-milestones/variantni-zadani-disertacni-prace-2026-czech-source/","title":"Variantní zadání disertační práce 2026","tags":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/application"],"noteIcon":"","created":"2026-09-08","updated":"2026-09-09","dg-note-properties":{"title":"Variantní zadání disertační práce 2026","aliases":["Variant Dissertation Topics 2026","Variantní zadání disertace"],"type":"decision-support","status":"proposal","context":"thesis","topics":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/application"],"tags":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/application"],"date":"2026-09-08","last_updated":"2026-09-09"}}
---


# Variantní zadání disertační práce

> [!info] Stav dokumentu
> Jde o veřejný rozhodovací podklad k diskusi. Varianty nejsou schváleným zadáním disertační práce. Odvážnější směry reagující na současné technologické a komerční otázky jsou zpracovány v [[I Projects/03_Milestones/Outside-the-Box Dissertation Topics 2026\|samostatném přehledu outside-the-box témat]].

## Návaznost na laserové spouštění vysokonapěťového jiskřiště

**Rozhodovací podklad pro Michala Sakalu a jednání se školitelem**
Zpracováno 8. září 2026 • Návrh k diskusi • Plánovací horizont září 2026 až srpen 2028

### Doporučení

Jako hlavní zadání doporučuji **variantu B — Stav laserem vytvořeného kanálu a predikce sepnutí vysokonapěťového jiskřiště**. Nejlépe navazuje na diplomovou práci i následná měření, má jasnou fyzikální otázku a odpovídá současnému základnímu výzkumnému plánu. Její přínos má spočívat v ověřené predikci z měřeného stavu kanálu, nikoli pouze v dalším snížení přeskokového napětí.

**Varianta A** představuje užší alternativu při omezené optické diagnostice. **Varianta C** je vhodná, pokud má mít práce silnější aplikační a ekonomický přesah. Rozšíření o tvarování svazku, více jiskřišť nebo obnovu izolační pevnosti je vhodné přijmout pouze při předem zajištěné aparatuře a kapacitě týmu. Nedoporučuji spojovat všech šest variant do jednoho zadání.

### Posuzované varianty

| Varianta | Těžiště práce | Hlavní výsledek |
| --- | --- | --- |
| A | Spolehlivost a provozní okno | Statisticky ověřené podmínky řízeného sepnutí |
| B | Stav kanálu a mechanismus sepnutí | Redukovaný model s nezávislou validací |
| C | Adaptivní řízení a provozní účelnost | Řídicí postup a srovnání stejné spínací funkce |
| D | Prostorové tvarování laserového svazku | Podmínky přínosu tvaru kanálu vůči Gaussovu svazku |
| E | Synchronizace dvou jiskřišť | Model a demonstrátor vzájemného časového rozptylu |
| F | Obnova izolační pevnosti a opotřebení | Meze opakovatelného provozu po výboji |

### Jak dokument číst

Nejprve jsou odděleny doložené výsledky od dosavadních předpokladů. Každá varianta potom obsahuje návrh názvu a bodů zadání, vědecký přínos, potřebnou techniku, náročnost, harmonogram, podmínky pokračování a aplikace. Závěr obsahuje společný plán, doporučené znění zadání a dohledatelné zdroje.

Uvedené délky prací, kapacity a cíle jsou **plánovací odhady tohoto posouzení**. Nejde o potvrzené rezervace HiLASE, nabídky dodavatelů, závazné studijní termíny ani příslib přijetí publikací. Dokument navrhuje změnu zadání; nemění schválené dokumenty ani současný registr rozhodnutí. [S3, S4]

<!-- PAGEBREAK -->

## Co skutečně přináší diplomová práce

Diplomová práce z roku 2024 řeší pokročilé spouštění vysokonapěťového jiskřiště laserovým paprskem. Experiment využívá kulové nerezové elektrody o průměru 2 cm, mezery 5 a 10 mm, zdroj Technix SR40kV-5kW a pikosekundový laser platformy PERLA. Popsány jsou vlnové délky 1030, 515 a 257,5 nm. Laser je veden mezi elektrodami, aby přímo nezasahoval jejich povrch. [S1, kap. 5]

### Doložené východisko pro disertaci

Práce ukazuje, že laserové buzení za zkoumaných podmínek snižuje přeskokové napětí. Výběr výsledků při maximálním výkonu příslušné série:

| Vlnová délka a režim | Mezera | Bez laserového snížení | S laserem | Pokles podle dvojice napětí |
| --- | --- | --- | --- | --- |
| 1030 nm, série impulzů | 5 mm | 16,9 kV | 13,5 kV | přibližně 20 % |
| 515 nm, série impulzů | 10 mm | 29,5 kV | 20,3 kV | přibližně 31 % |
| 257,5 nm, série impulzů | 10 mm | 29,5 kV | 21,8 kV | přibližně 26 % |
| 1030 nm, jednotlivý impulz | 5 mm | 16,9 kV | 12,1 kV | přibližně 28 % |

Zdroj: tabulky 5.3 až 5.6, tištěné strany 56–57, PDF strany 66–67. Poslední procento je přepočteno ze zobrazených napětí; tabulka 5.6 uvádí jinou relativní změnu. Před společným zpracováním je potřeba prověřit použitou referenci, nikoli tento rozdíl automaticky vykládat jako fyzikální efekt. [S1]

### Co z těchto výsledků zatím nelze odvodit

Série pro různé vlnové délky nemají stejné dostupné energie a ve všech případech ani stejnou fokusační optiku. Výsledky proto nedokládají univerzální převahu kratší vlnové délky. Číslo 62 u jednopulzní série označuje počet úrovní nastavení, nikoli 62 opakování v jednom pracovním bodě. Srovnání jednotlivých a opakovaných impulzů je také ovlivněno rozdílnou fokusací. [S1, kap. 5–6]

Diplomová práce sama nepředkládá ověřenou mapu jitteru, životnost elektrod, zkoušku vypínání proudu ani ekonomickou návratnost. Její závěrečná doporučení výslovně otevírají časová měření, dynamiku ionizační vlny, vliv prostředí, energetickou účelnost a rozšíření geometrie či napěťového průběhu. To jsou přirozené směry disertačního pokračování. [S1, kap. 7.2]

**Důsledek pro nové zadání:** samotné zopakování závislosti přeskokového napětí na výkonu laseru nestačí jako nový doktorský přínos. Potřebný je zobecnitelný vztah, mechanismus, ověřený model nebo prokazatelně účinnější způsob řízení. Posudek oponentky se navíc přímo ptá na počet měření pro pravděpodobnostní meze a na konkrétní aplikace. [S2]

<!-- PAGEBREAK -->

## Co mění navazující výsledky a kontrola aparatury

### Časová měření již existují jako výchozí podklad

Lokální rukopis pro konferenci APL 2025 rozšiřuje experiment o tři série zpoždění. V tabulce III uvádí hodnoty přibližně od 0,164 do 8,124 µs podle pracovního bodu. Časovou referencí je hrana elektrického spouštěcího signálu laseru. Uvedené zpoždění proto nelze bez kalibrace ztotožnit s časem od skutečného příchodu optického impulzu do mezery. Rukopis zmiňuje nejméně pět opakování na konfiguraci; úplná surová data nebyla při tomto posouzení auditována. [S5, PDF str. 3–5]

Disertace tedy nemá slibovat první měření zpoždění na této aparatuře. Má navázat kalibrovaným optickým počátkem času, analýzou rozdělení zpoždění, selhání a opakovatelnosti mezi dny. Hodnoty typu obecné zpoždění 20–80 ns nebo subnanosekundový jitter nejsou v prověřeném vlastním podkladu doloženým výsledkem.

### Dvě konkrétní otázky pro měřicí řetězec

**Proudový monitor.** Rukopis uvádí Pearson 1423. Výrobce pro tento model uvádí využitelnou dobu náběhu 0,5 µs a horní mez přibližně 0,7 MHz. Pokud byl použit skutečně tento typ, nelze z jeho proudové stopy přímo dokazovat nanosekundový náběh výboje. Je nutné ověřit štítek přístroje, zapojení a případný jiný kanál určující okamžik přeskoku. [S5, S7]

**Napěťová sonda.** Uvedená P6015A má podle aktuálního katalogového listu 75 MHz; současná specifikace rozlišuje 15 kV DC a 40 kV špičkového impulzu s omezenou délkou. Starší provedení se mohou lišit. Rozsah zdroje 40 kV proto sám o sobě nepotvrzuje vhodnost sondy pro 40 kV DC. Pro nový program se musí ověřit konkrétní provedení, jmenovité podmínky a dělič pro plánované napětí. [S8]

Tyto body jsou požadavky na audit. Samy o sobě neprokazují nesprávnost všech předchozích měření ani neurčují rozlišení celé sestavy bez znalosti dalších kanálů.

### Laser a modelování

Veřejná nabídka HiLASE uvádí u PERLA B 1030/515 nm, pikosekundové impulzy a režimy 1 nebo 10 kHz. Je to důkaz nabízené konfigurace, nikoli rezervace pro tento projekt; dostupnost UV větve a přesné parametry použitých impulzů zůstávají k potvrzení. Výpočty intenzity se mezi diplomkou a rukopisem místy liší, proto je nutné sjednotit energii impulzu, délku impulzu a definici poloměru či průměru svazku. [S1, S5, S6]

Pro variantu B je podstatné, že primární literatura popisuje význam vývoje hustoty plynu v laserem iniciované mezeře. Výsledek z femtosekundového režimu je motivací pro ověření na vlastní pikosekundové sestavě, nikoli hotovým vysvětlením vlastních dat. [S9]

<!-- PAGEBREAK -->

## Srovnání náročnosti a proveditelnosti

Náročnost je expertní hodnocení od 1 do 5, kde 5 znamená nejvyšší požadavky. Nejde o pravděpodobnost úspěšné obhajoby. Délka zahrnuje přípravu, měření, analýzu a sepsání při zahájení v září 2026; termín přijetí článků neovlivňuje pouze doktorand.

| Varianta | Vědecká náročnost | Technická náročnost | Odhad délky | Laboratorní dny | Výhled do srpna 2028 |
| --- | --- | --- | --- | --- | --- |
| A | 3/5 | 3/5 | 20–24 měsíců | 35–50 | Nejpříznivější při omezeném rozsahu |
| B | 4/5 | 4/5 | 22–26 měsíců | 45–65 | Reálný při včasné diagnostice |
| C | 4/5 | 4/5 | 22–28 měsíců | 40–60 | Podmíněný automatizací a srovnávací sestavou |
| D | 5/5 | 4/5 | 26–32 měsíců | 55–80 | Napjatý bez hotové optiky |
| E | 4/5 | 5/5 | 26–34 měsíců | 60–85 | Spíše přesah do roku 2029 |
| F | 4/5 | 5/5 | 28–36 měsíců | 65–95 | Spíše přesah do roku 2029 |

### Co kapacitní odhady znamenají

Laboratorní den znamená rezervovaný den s aparaturou a potřebnou obsluhou, včetně seřizování a kalibrace. Nejde o osm hodin čistého sběru dat. Rozpětí je odhad zdola z pracovních bloků jednotlivých variant, nikoli kapacita potvrzená laboratoří. Odhady předpokládají převzetí základního jiskřiště, dostupný laser a pravidelné bloky měření. Zpoždění dodávky klíčové diagnostiky může posunout kalendář i bez zvýšení vlastních odpracovaných hodin.

Varianta A vyžaduje přibližně 13–16 měsíců soustředěné práce v přepočtu na plný úvazek, B a C 15–19, D až F přibližně 18–23. Jde o práci doktoranda; obsluha laseru, elektroúdržba, výroba a konzultace specialistů jsou další kapacitou. Výuka a další povinnosti musejí být započteny do skutečné dostupnosti.

### Rozhodující podmínky volby

**A** lze zvolit při dobré elektrické metrologii a omezené zobrazovací diagnostice. **B** vyžaduje alespoň jeden měřitelný ukazatel stavu kanálu, který není jen přepisem nastavení laseru. **C** potřebuje ovladatelné nastavení a srovnávací postup za stejných podmínek. **D** stojí na reprodukovatelné tvorbě a ověření svazku. **E** potřebuje dva měřitelné spínací kanály. **F** potřebuje řízenou energii výboje a skutečnou dvouimpulzní zkoušku obnovy.

Nákladové rozdíly určují především přístup k laseru, rychlá diagnostika a vlastní výroba. Bez inventury a cenových nabídek by peněžní součty vytvářely falešnou přesnost. U každé varianty proto uvádím hlavní nákladové položky a možnost sdílení techniky.

<!-- PAGEBREAK -->

## Varianta A

### Spolehlivost laserového spouštění vzduchového jiskřiště

**Navržený název:** Pravděpodobnostní charakterizace a robustní provozní okno laserem spouštěného vysokonapěťového jiskřiště

**Anglicky:** Probabilistic Characterisation and Robust Operating Window of a Laser Triggered High Voltage Spark Gap

### Návrh bodů zadání

1. Kriticky vyhodnoťte dosavadní experimenty a metody charakterizace samovolného a laserem vyvolaného přeskoku.
2. Navrhněte a ověřte metodu společného měření pravděpodobnosti sepnutí, zpoždění a časového rozptylu se zahrnutím neúspěšných pokusů.
3. Určete závislosti na pracovním napětí, energii impulzu a poloze ohniska při sledovaném stavu elektrod a prostředí.
4. Sestavte model provozního okna a ověřte jeho přenos na nezávislé měřicí dny a alespoň jednu předem vybranou změnu podmínek.
5. Stanovte pravidla volby pracovního bodu pro reprodukovatelné spouštění laboratorního impulzního zařízení.

### Vědecká otázka a přínos oproti diplomce

Jak velké a jak stabilní je pásmo nastavení, ve kterém laser spíná mezeru s požadovanou spolehlivostí a časovou přesností, zatímco samovolné přeskoky zůstávají přijatelné? Diplomka dodává prahová napětí; novým výsledkem má být validovaná pravděpodobnostní mapa s nejistotami, přenosem mezi dny a kvantifikovaným kompromisem mezi spolehlivostí a jitterem.

Pouhé doplnění dalších křivek by bylo vědecky slabé. Doktorskou úroveň má zajistit model, který předpoví dosud nepoužité podmínky, nebo identifikace a vysvětlení významné nestability. Pokud výsledek zůstane pouze popisný, je nutné zadání posílit prvkem varianty B.

### Experimentální rozsah

Začít jednou vlnovou délkou, jednou polaritou a kulovou mezerou 5 mm. Základní napětí U50 určit pro konkrétní postup a dobu expozice; pracovat s poměrem k = Uapp/U50. Po pilotu vybrat několik hodnot k kolem přechodu z nespolehlivého do spolehlivého sepnutí a několik úrovní energie. Polohu ohniska měnit až po základní mapě. Mezera 10 mm nebo odlišná vlhkost tvoří následný test přenosu, nikoli další plnou experimentální mřížku.

Modelovat společně pravděpodobnost sepnutí ve stanoveném okně a rozdělení časů. Předčasný samovolný přeskok, selhání laserového spouštění a ztrátu záznamu vést odděleně. Výsledek nesmí být založen pouze na povedených výbojích. Praktickým výstupem je mapa použitelného nastavení s intervaly nejistoty a s uvedenými mezemi platnosti.

<!-- PAGEBREAK -->

## Varianta A technika a provedení

### Požadovaná technika

**Nezbytné:** ověřený laser s útlumem a výběrem jednotlivých impulzů, stabilní držák elektrod, omezený a měřený výbojový obvod, vhodný VN dělič, rychlý elektrický marker přeskoku, fotodioda pro skutečný optický čas, osciloskop se společnou časovou základnou, měření energie a profilu svazku, záznam tlaku, teploty a vlhkosti. Základ vychází z historicky použité sestavy; aktuální dostupnost a parametry se musejí potvrdit. [S1, S5]

**Podle zvolené otázky:** uzavřený prostor pro pomalé řízení vlhkosti, druhý držák geometrie a jednoduchá kamera pro kontrolu polohy kanálu. ICCD ani plná plazmová simulace nejsou podmínkou této varianty. Hlavními nákladovými položkami jsou kalibrace, vhodné rychlé snímače a přístup k laseru.

### Náročnost a harmonogram

| Období | Práce a ověřitelný výstup |
| --- | --- |
| Září až prosinec 2026 | Audit, kalibrace, protokol, opakovatelné měření základního napětí |
| Leden až duben 2027 | Pilot a hlavní pravděpodobnostní mapa; výběr pracovních bodů |
| Květen až srpen 2027 | Opakování mezi dny a jedna řízená změna podmínek |
| Září až listopad 2027 | Nezávislá validace modelu; první rukopis |
| Prosinec 2027 až duben 2028 | Cílené doplnění a aplikační pravidla; druhý výsledkový celek |
| Květen až srpen 2028 | Syntéza, disertace a rezerva na připomínky |

Odhad 35–50 laboratorních dnů zahrnuje 8–10 dnů přípravy, 15–20 základní mapy, 8–12 nezávislého ověření a 4–8 dnů rezervy. Nejobtížnější je oddělit fyzikální vliv od driftu elektrod, změn ovzduší a měřicího systému. Potřebná je pravidelná konzultace statistického návrhu experimentu.

### Podmínka pokračování a záložní rozsah

Do dubna 2027 musí být určena opakovatelnost referenčního bodu a oblast, kde lze skutečně měřit změnu pravděpodobnosti. Pokud všechny body vždy spínají nebo vždy selhávají, upravit návrh bodů. Při nedostupném řízení prostředí testovat přenos mezi zaznamenanými dny a nepřisuzovat pozorovaný drift samotné vlhkosti.

### Technické aplikace výsledků

Výběr pracovního bodu laboratorního generátoru impulzů, plánování spouštění synchronizovaných diagnostik a stanovení počtu opakování potřebných pro kvalifikaci spínače. Přenosným výsledkem jsou metoda a návrhová pravidla; hotový průmyslový spínač z nich nevzniká automaticky. Úspěch se hodnotí spolehlivostí v časovém okně, četností předčasných sepnutí a stabilitou mimo kalibrační den, nikoli samotným minimálním napětím.

<!-- PAGEBREAK -->

## Varianta B

### Stav kanálu a predikce sepnutí

**Navržený název:** Vliv stavu laserem vytvořeného kanálu na pravděpodobnost a časování sepnutí vysokonapěťového jiskřiště

**Anglicky:** Influence of the Laser Created Channel State on the Probability and Timing of High Voltage Spark Gap Breakdown

### Návrh bodů zadání

1. Vymezte a experimentálně ověřte elektrické a optické veličiny popisující vznik výboje v laserem buzené vzduchové mezeře.
2. Změřte časový vývoj vybraných ukazatelů kanálu a vztah k pravděpodobnosti sepnutí, zpoždění a jitteru.
3. Posuďte, zda měřený stav kanálu vysvětluje výsledky lépe než samotná energie laserového impulzu při kontrolovaném pracovním napětí.
4. Vytvořte redukovaný model zahrnující relevantní fáze iniciace a vývoje kanálu a určete identifikovatelnost jeho parametrů.
5. Ověřte model na podmínkách nepoužitých při jeho sestavení a odvoďte pravidla řízení spouštění s vymezením jejich platnosti.

### Vědecká otázka a doktorský přínos

Proč mohou při podobné energii laseru vzniknout různé časy a výsledky sepnutí? Pracovní hypotézou je, že rozhoduje měřený stav kanálu a jeho vývoj společně s elektrickým polem. Energetický vstup sám nemusí zachycovat rozdíly v geometrii, hustotě plynu a následném vývoji výboje. Literatura poskytuje fyzikální motivaci, ale konkrétní dominantní mechanismus na této sestavě zůstává k ověření. [S9]

Přínosem bude reprodukovatelná vazba mezi diagnostikou kanálu a elektrickou odezvou, doplněná modelem s nezávislou validací. Platným výsledkem může být i zjištění, že některý optický ukazatel nepřidává predikční hodnotu, pokud je jeho citlivost dostatečná a negativní výsledek má vyčíslenou mez detekovatelného účinku.

### Experimentální a modelový postup

Převzít metrologický a statistický základ varianty A, ale omezit počet parametrů. Porovnávat model založený na k a energii s modelem rozšířeným o měřenou délku, spojitost, polohu nebo časový průběh kanálu. Světelná intenzita je zprvu pouze optický ukazatel; bez kalibrace a odpovídajícího fyzikálního modelu není měřením elektronové hustoty nebo teploty.

Začít elektrostatickým výpočtem pole a jednoduchým časovým modelem. Plnou prostorovou chemii přidat pouze tehdy, když ji vyžaduje konkrétní nevysvětlený jev a jsou k dispozici data pro validaci. COMSOL je možný prostředek, nikoli vědecký výsledek sám o sobě. Oddělit identifikaci modelu, test citlivosti a ověření na nových dnech či nastaveních.

<!-- PAGEBREAK -->

## Varianta B technika a provedení

### Požadovaná technika

**Základ:** vybavení varianty A. **Rozhodující doplnění:** časově rozlišené optické měření alespoň jednoho nezávislého ukazatele kanálu. Nejvhodnější je přístup ke hradlované kameře ICCD spolu se synchronizací a kalibrací prostorového měřítka. Pro tvrzení o hustotě plynu je potřebná vhodná stínová, schlierenová nebo interferometrická diagnostika; samotná jasová kamera takové tvrzení nepotvrzuje.

**Volitelné:** hradlovaný spektrometr, druhá optická větev, sondovací laser a druhá elektrická měřicí cesta. Pro časový sken stáří kanálu vůči přiložení napětí je nutný nezávisle řízený napěťový impulz. Při trvalém DC napětí lze zkoumat vývoj po laseru, ale není definován nastavitelný okamžik zapnutí VN. [S3]

Potřebný tým zahrnuje doktoranda, obsluhu laseru, konzultanta optické diagnostiky a konzultanta modelování výbojů. Rozhodující náklad představuje přístup k časově rozlišené diagnostice; sdílení přístroje je pravděpodobně účelnější než pořizování celé nové sestavy bez ověřeného signálu.

### Náročnost a harmonogram

| Období | Práce a ověřitelný výstup |
| --- | --- |
| Září až prosinec 2026 | Metrologie a předvedení použitelného optického signálu |
| Leden až duben 2027 | Referenční elektrická mapa a současná diagnostika kanálu |
| Květen až srpen 2027 | Cílené experimenty oddělující možné mechanismy |
| Září až listopad 2027 | Potvrzující série, identifikace prvního modelu a první rukopis |
| Prosinec 2027 až duben 2028 | Nezávislé ověření modelu a druhý rukopis |
| Květen až srpen 2028 | Zpracování disertace; rezerva může zasáhnout podzim 2028 |

Odhad 45–65 laboratorních dnů: 10–15 na zprovoznění diagnostiky, 20–25 na společné měření, 10–15 na rozlišovací a validační experimenty, 5–10 rezerva. Nejvyšší vědecké riziko je nejednoznačnost modelu: stejná elektrická křivka může být vysvětlena více kombinacemi parametrů.

### Podmínka pokračování a záložní rozsah

Do března 2027 musí diagnostika rozlišit reprodukovatelné změny kanálu nad vlastní nejistotou. Jinak omezit hypotézy a se školitelem přejít k variantě A. Do června 2027 musí existovat konkrétní experiment, který dokáže odlišit alespoň dvě konkurenční interpretace. Nedostupnou hustotní diagnostiku nelze nahradit neověřeným výpočtem elektronové hustoty z fotografie.

### Technické aplikace výsledků

Predikce použitelné spínací oblasti, návrh optické geometrie a výběr měřitelných veličin pro pozdější zpětnou vazbu. Pro výrobce laboratorních impulzních zařízení mohou být cennější podmínky spolehlivého sepnutí a přenositelnost modelu než rekordní zpoždění v jediném bodě. Přímá návaznost na adaptivní řízení je možná až po ověření, že indikátor lze měřit v potřebném čase.

<!-- PAGEBREAK -->

## Varianta C

### Adaptivní řízení a provozní účelnost

**Navržený název:** Adaptivní řízení laserem spouštěného vysokonapěťového jiskřiště s ohledem na spolehlivost a provozní náročnost

**Anglicky:** Adaptive Control of a Laser Triggered High Voltage Spark Gap for Reliable and Resource Efficient Operation

### Návrh bodů zadání

1. Určete měřitelné ukazatele spolehlivosti, časové přesnosti a provozní náročnosti zvolené laboratorní spínací úlohy.
2. Vytvořte ověřený experimentální základ a model závislosti výsledku sepnutí na ovladatelných parametrech.
3. Navrhněte adaptivní postup volby energie nebo pracovního bodu při předem daných provozních mezích.
4. Porovnejte adaptivní postup s pevným nastavením a jednoduchým referenčním regulátorem na nových měřicích blocích.
5. Vyhodnoťte provozní přínos a podmínky ekonomické účelnosti proti srovnatelné spínací variantě se stejnou funkcí.

### Vědecká otázka a nový přínos

Lze při změnách aparatury a prostředí udržet požadovanou úspěšnost sepnutí s nižší energií, menším počtem nastavovacích pokusů nebo nižší variabilitou než u nejlepšího pevného nastavení? Novým výsledkem má být ověřené řízení v podmínkách driftu, nikoli pouze použití algoritmu označeného jako umělá inteligence.

Základní srovnání musí obsahovat dobře naladěný pevný pracovní bod a jednoduché pravidlo korekce. Bayesovská optimalizace nebo jiný složitější postup má smysl jen při prokazatelném přínosu. Průkazný může být i závěr, že jednoduchý postup dosahuje stejného výsledku s menší náročností.

### Rozsah řešení

Primárně řídit energii následného laserového impulzu, případně volit z omezeného souboru nastavení napětí. Neuvažovat korekci během stejného pikosekundového impulzu. Řízení pracuje mezi pokusy; změna fokusace může být samostatný pomalý zásah. Omezit počet akčních veličin na jednu nebo dvě a předem stanovit přípustné meze.

Výsledky hodnotit na stejných počtech pokusů, ve střídajících se blocích a při srovnatelném stavu elektrod. Účelovou funkci tvoří například energie na úspěšné sepnutí při omezení pravděpodobnosti selhání a časového rozptylu. Měřit také čas seřizování, výpadky záznamu a celkovou spotřebu systému, pokud má vzniknout ekonomický výsledek.

Ekonomická část má být vázána na laboratorní generátor nebo spouštěcí modul. Porovnávat jej s elektricky spouštěným jiskřištěm či jiným funkčně srovnatelným řešením. Vypínač HVDC plní odlišnou funkci a není vhodným přímým cenovým protějškem.

<!-- PAGEBREAK -->

## Varianta C technika a provedení

### Požadovaná technika

Základ varianty A doplnit o ovladatelný útlum, rozhraní měřicích přístrojů, počítač pro automatizované pokusy a spolehlivý záznam každého pokusu. Bezpečnostní meze a blokování musí být nezávislé na optimalizačním programu. Pro ekonomické srovnání je potřebný referenční spouštěcí modul nebo kvalitní provozní data stejné funkce; vlastní demonstrátor obou variant poskytne silnější důkaz.

ICCD není nutnou podmínkou. Jestliže se má řídit podle stavu kanálu, musí být zvolený ukazatel dostupný před rozhodnutím o dalším pokusu a dostatečně levný pro zamýšlenou aplikaci. Potřebná je podpora automatizace, měření a aplikované statistiky. Náklady určují především řízené optické prvky, integrace přístrojů a srovnávací sestava.

### Náročnost a harmonogram

| Období | Práce a ověřitelný výstup |
| --- | --- |
| Září až prosinec 2026 | Metrologie, funkční rozhraní, jednoznačné cíle a referenční metoda |
| Leden až duben 2027 | Statická data, jednoduchý model, automatizované měřicí bloky |
| Květen až srpen 2027 | Návrh řízení a pilot při zaznamenaném driftu |
| Září až prosinec 2027 | Zaslepené vyhodnocení nových bloků, první rukopis |
| Leden až duben 2028 | Provozní srovnání, citlivost ekonomického modelu, druhý rukopis |
| Květen až srpen 2028 | Syntéza; při stavbě reference možný přesah do konce roku 2028 |

Odhad 40–60 laboratorních dnů: 10–15 integrace, 12–18 základní data, 12–17 nezávislé srovnání a 6–10 rezerva. Další náročnost leží v softwaru a v nezávislém testování. Největším rizikem je, že algoritmus pouze kompenzuje chybnou metrologii nebo je hodnocen na datech, ze kterých se učil.

### Podmínka pokračování a záložní rozsah

Do dubna 2027 musí být spolehlivě automatizován celý pokus včetně neúspěšného sepnutí. Do července musí existovat měřitelný drift nebo jiný scénář, ve kterém adaptace dává smysl. Pokud přínos proti jednoduchému řízení není prokazatelný, zpracovat jeho kvantitativní meze a práci opřít o robustní provozní model. Bez provozních dat o životnosti označit ekonomiku pouze za citlivostní scénář.

### Technické aplikace výsledků

Automatizované nastavování impulzního generátoru, omezení neplatných experimentů, stabilizace provozu sdílené laboratoře a spouštěcí modul s diagnostikou stavu. Přínos musí být doložen například nižším počtem zmetkových impulzů při stejné časové toleranci, ne pouze nižší optickou energií. Energie laserového impulzu tvoří jen část spotřeby celé infrastruktury.

<!-- PAGEBREAK -->

## Varianta D

### Prostorové tvarování kanálu

**Navržený název:** Vliv prostorového tvarování pikosekundového laserového svazku na řízený přeskok ve vysokonapěťové vzduchové mezeře

**Anglicky:** Effect of Picosecond Laser Beam Shaping on Controlled Breakdown in a High Voltage Air Gap

### Návrh bodů zadání

1. Vyhodnoťte možnosti tvorby a diagnostiky laserových kanálů s různým podélným rozložením energie.
2. Realizujte a kvantitativně ověřte Gaussovu referenci a jeden zvolený tvarovaný svazek.
3. Oddělte vliv dodané energie, maximální intenzity, délky kanálu a polohy vůči elektrodám na přeskok.
4. Porovnejte pravděpodobnost, časování a toleranci vyosení při férových referenčních podmínkách.
5. Navrhněte model nebo návrhové pravidlo určující, kdy tvarování přináší měřitelnou výhodu.

### Vědecká otázka a meze originality

Může delší nebo prostorově jinak rozložený kanál rozšířit toleranci polohy či snížit energetickou náročnost spolehlivého sepnutí? Vedení výbojů pomocí Gaussových, Besselových a Airyho svazků již bylo publikováno. Originální přínos proto nelze formulovat jako první vedení výboje tvarovaným svazkem. Musí spočívat například v kontrolovaném srovnání v pikosekundovém režimu, statistické robustnosti a přenosném vztahu mezi profilem kanálu a sepnutím. [S10]

Zvolit jednu konkrétní hypotézu: například zda prodloužený kanál omezuje citlivost na axiální polohu ohniska při srovnatelné dodané energii. Neměnit současně vlnovou délku, tlak, polaritu, tvar svazku a geometrii elektrod. Takový rozsah by spotřeboval kapacitu bez jednoznačné interpretace.

### Experimentální návrh

Jako první tvarovaný případ zvažovat svazek vytvořený axikonem proti Gaussově referenci. Změřit podélnou i příčnou intenzitu, optické ztráty a délku použitelné oblasti. Dvojice experimentů mají mít jasně stanovenou normalizaci: stejnou energii na vstupu do mezery a samostatně zdokumentované rozdíly v intenzitě a geometrii. Další srovnání se stejnou délkou kanálu je samostatný test, nikoli automaticky dosažená podmínka.

Besselův svazek neznamená sám o sobě optický vír. Pokud se má tvrdit vliv orbitálního momentu hybnosti, je nutné ověřit fázi a přidat odpovídající kontrolní svazek. Prstencový obraz sám takové tvrzení neprokazuje. Tento krok doporučuji ponechat mimo základ zadání.

<!-- PAGEBREAK -->

## Varianta D technika a provedení

### Požadovaná technika

Základ varianty A doplnit o axikon nebo jiný konkrétní tvarovací prvek, vhodnou reléovou optiku, měření profilu v několika podélných polohách a stabilní polohování vůči elektrodám. Materiál, povlaky a zatížitelnost optiky musejí odpovídat použité vlnové délce, délce impulzu a skutečné fluenci.

ICCD nebo jiná časově rozlišená zobrazovací diagnostika je silně žádoucí pro oddělení optického kanálu a následného elektrického výboje. Pro vírové svazky přibývá fázová diagnostika. Prostorový modulátor světla není automaticky vhodný pro plnou energii hlavního svazku; jeho zařazení závisí na skutečných mezích a optickém návrhu. Potřebný je partner se zkušeností s tvarováním intenzivních impulzů.

### Náročnost a harmonogram

| Období | Práce a ověřitelný výstup |
| --- | --- |
| Září až prosinec 2026 | Výběr jedné hypotézy, optický návrh a dostupnost komponent |
| Leden až duben 2027 | Ověření tvaru a stability svazku při pracovních parametrech |
| Květen až říjen 2027 | Kontrolované srovnání s Gaussovou referencí |
| Listopad 2027 až duben 2028 | Mechanismus, opakování a model přenosu |
| Květen až srpen 2028 | Minimální syntéza pouze při úspěšném časném pilotu |
| Září 2028 až duben 2029 | Realističtější rezerva na validaci a dokončení |

Odhad 55–80 laboratorních dnů: 15–20 vývoj optiky, 20–30 hlavní experiment, 12–18 validace a 8–12 rezerva. Obtížnost není jen ve výrobě svazku, ale v dokazování, že rozdíl není způsoben ztrátami, jinou energií nebo odlišným zásahem elektrod.

### Podmínka pokračování a záložní rozsah

Do dubna 2027 musí být tvar svazku kvantitativně ověřen a reprodukovatelný. Pokud nelze stabilně měřit jeho profil, nepokračovat k rozsáhlému srovnání výbojů. Pokud není prokázána výhoda, výsledkem může být hranice užitečnosti tvarování. Návrat k variantě B je možný, pokud již existuje kvalitní kanálová diagnostika; jinak k A.

### Technické aplikace výsledků

Optická spouštěcí hlavice tolerantnější k nepřesnosti seřízení, řízená poloha výboje a návrh kanálu pro obtížně přístupnou mezeru. Pro průmyslovou použitelnost je třeba započítat stabilitu seřízení, ztráty a znečišťování optiky. Vedení laboratorního výboje není důkazem ochrany vedení před bleskem; venkovní škálování je samostatný experimentální program. [S11]

<!-- PAGEBREAK -->

## Varianta E

### Synchronizace dvou jiskřišť

**Navržený název:** Optická synchronizace vysokonapěťových jiskřišť a predikce vzájemného časového rozptylu sepnutí

**Anglicky:** Optical Synchronisation of High Voltage Spark Gaps and Prediction of Relative Switching Jitter

### Návrh bodů zadání

1. Analyzujte zdroje společného a rozdílového zpoždění u opticky spouštěných jiskřišť.
2. Navrhněte dvoukanálový experiment s nezávisle měřenými optickými a elektrickými časovými značkami.
3. Určete vliv rozdělení laserové energie, pracovních napětí a geometrické nesymetrie na společné sepnutí.
4. Sestavte a ověřte model pravděpodobnosti společného sepnutí a rozdílu časů obou kanálů.
5. Demonstrujte přínos synchronizace na laboratorním obvodu a vymezte podmínky rozšíření na více stupňů.

### Vědecká otázka a přínos

Kdy společné optické buzení skutečně vede k malému rozdílu časů sepnutí a kdy převládá vlastní náhodnost jednotlivých mezer? Společný trigger může odstranit některé zdroje relativní chyby, ale neodstraní automaticky statistickou prodlevu každého výboje.

Novým přínosem může být model korelací a energetické nerovnováhy v konkrétním vzduchovém pikosekundovém režimu. Samotné současné laserové spouštění dvou spínačů už existuje v literatuře. Starší primární práce například popisuje dvojici paralelních laserem spouštěných mezer, ovšem v jiné vysokotlaké konfiguraci. Rekordní jitter cizího zařízení nelze převzít jako parametr vlastní sestavy. [S12]

### Experimentální návrh

Nejprve dvě galvanicky vhodně oddělené, energeticky omezené výbojové větve a rozdělení jediného laserového impulzu. Měřit energii a čas příchodu v obou větvích. Vyhodnotit jednotlivá zpoždění t1 a t2, jejich kovarianci a rozdíl Δt = t1 − t2. Samostatně uvádět pravděpodobnost, že sepne pouze jedna větev nebo ani jedna.

Teprve po zvládnutí dvojice navrhnout aplikaci na jednoduchý impulzní obvod. Připojení více stupňů Marxova generátoru mění vazby, napěťové rozdělení a rušení; není jen mechanickým zopakováním stejného testu. Plnohodnotný vysokoproudý Marxův generátor proto nemá být podmínkou základní obhajitelnosti této varianty.

Vědecký přínos vyžaduje přenos modelu na nezávislou nesymetrii nebo nastavení. Jediný záznam dvou téměř současných výbojů je demonstrace funkce, nikoli charakterizace synchronizace.

<!-- PAGEBREAK -->

## Varianta E technika a provedení

### Požadovaná technika

Dvě reprodukovatelné mezery s definovanými nabíjecími a výbojovými obvody, rozdělení optického svazku, dva energetické odběry a dvě optické časové značky. Potřebné je současně zaznamenat elektrický marker každé mezery a rozlišit vzájemné přeslechy. Zpravidla bude vhodných alespoň šest synchronních měřicích kanálů nebo dva přístroje s doloženou synchronizací; konkrétní počet závisí na zvolených markerech.

Přidává se konstrukce druhé větve, optické zpoždění, stínění, měřicí reference a podpora konstruktéra impulzní techniky. Nákladové těžiště je ve dvojí rychlé diagnostice a vývoji obvodu, nikoli pouze v děliči laserového svazku. ICCD může pomoci vysvětlit asymetrii, ale elektrická a optická časová metrologie má přednost.

### Náročnost a harmonogram

| Období | Práce a ověřitelný výstup |
| --- | --- |
| Září až prosinec 2026 | Návrh dvou větví, energetických mezí a měřicích cest |
| Leden až květen 2027 | Jednotlivé mezery, kalibrace relativního času a omezení přeslechů |
| Červen až říjen 2027 | Společné spouštění a mapa energetické nesymetrie |
| Listopad 2027 až duben 2028 | Nezávislá validace korelačního modelu |
| Květen až srpen 2028 | Syntéza dvojice; rozšíření jen při hotovém základním výsledku |
| Září 2028 až červen 2029 | Rezerva na aplikační obvod a dokončení |

Odhad 60–85 laboratorních dnů: 18–25 konstrukce a metrologie, 20–28 srovnávací experiment, 14–20 validace, 8–12 rezerva. Varianta je náročná na týmovou podporu; bez ní hrozí, že většinu disertace spotřebuje stavba aparatury.

### Podmínka pokračování a záložní rozsah

Do května 2027 musí oba kanály samostatně splnit referenční opakovatelnost a měřicí systém prokázat menší relativní nejistotu, než jaký rozdíl se má studovat. Jinak pokračovat jednou mezerou ve variantě A nebo B. Pokud korelace nepomůže, identifikovat příčinu a vyčíslit mez společného spouštění; nezvyšovat bez rozmyslu počet stupňů.

### Technické aplikace výsledků

Synchronizované spouštěče impulzních generátorů, vícekanálové laboratorní výboje a návazně některé pulzní napájecí systémy. Přenos do vysokých proudů vyžaduje další ověření indukčností, rozdělení proudu, eroze a rušení. Optické oddělení triggeru samo nezaručuje elektromagnetickou slučitelnost výkonové části.

<!-- PAGEBREAK -->

## Varianta F

### Obnova izolační pevnosti a opotřebení

**Navržený název:** Obnova izolační pevnosti a provozní stabilita laserem spouštěného vzduchového jiskřiště při opakovaných výbojích

**Anglicky:** Dielectric Recovery and Operational Stability of a Laser Triggered Air Spark Gap under Repetitive Discharges

### Návrh bodů zadání

1. Vymezte parametry obnovy izolační pevnosti a rozlište krátkodobou paměť kanálu od dlouhodobé změny elektrod.
2. Navrhněte experiment s definovanou energií prvního výboje a řízeným časovým odstupem následné napěťové zkoušky.
3. Určete závislost obnovy, předčasných přeskoků a opakovatelnosti sepnutí na elektrickém namáhání a opakování.
4. Kvantifikujte změny povrchu elektrod a ověřte jejich vztah k driftu spínacích parametrů.
5. Odvoďte meze provozní frekvence a doporučení pro údržbu pro konkrétní laboratorní spínací režim.

### Vědecká otázka a přínos

Co omezuje další použití mezery po výboji: zbytkový ionizovaný či ohřátý kanál, stav proudění, nebo změněný povrch elektrod? Diplomka řeší především snazší vznik výboje. Tato varianta zkoumá návrat do stavu, kdy mezera opět bezpečně drží požadované napětí, a stabilitu při opakovaném použití.

Novým výsledkem má být model a experimentálně ověřená mapa obnovy pro definované proudové a energetické zatížení. Pouhé nafocení poškozených elektrod není dostatečným přínosem. Změny je třeba spojit s přeneseným nábojem, energií v mezeře, počtem výbojů a spínacími parametry.

### Experimentální návrh

Oddělit krátkodobý dvouimpulzní experiment a dlouhodobé opakovací série. Po prvním výboji aplikovat druhou napěťovou zkoušku s řízeným odstupem a měřit pravděpodobnost opětovného přeskoku. Druhý laserový impulz sám nenahrazuje zkoušku obnovené izolační pevnosti. Pro opotřebení použít nejméně dvě nezávislé sady elektrod a referenční protokol jejich úpravy.

Měřit integrál proudu pro přenesený náboj a při dostatečné kalibraci obou kanálů také integrál napětí a proudu pro energii v mezeře. Optická energie není náhradou elektrického namáhání elektrod. Dlouhé série plánovat teprve po prokázání, že jejich jednotlivé výboje jsou skutečně reprodukovatelné.

Zkouška obnovy po přirozeném odeznění impulzního proudu není důkazem schopnosti vypínat trvalý DC proud. Formulace zadání má tento rozdíl zachovat.

<!-- PAGEBREAK -->

## Varianta F technika a provedení

### Požadovaná technika

Oproti variantě A přibývá definovaný energetický zásobník a zatěžovací obvod, možnost řízeně aplikovat druhé napětí, časový generátor a spolehlivý záznam dlouhých sérií. Návrh obvodu musí předem stanovit maximální energii, proud, náboj a způsob ukončení impulzu. Rozsah odvozený pouze z napětí zdroje by nestačil.

Nutná je proudová i napěťová diagnostika vhodná pro energii a dynamiku výboje, vyměnitelné elektrody, mikroskopie a nejlépe profilometrie povrchu. Samotné vážení může být při malé erozi nedostatečně citlivé. Podle zvoleného mechanismu lze doplnit proudění vzduchu a optickou diagnostiku zbytkového kanálu. SEM je přínosný až pro konkrétní otázku povrchové struktury.

Potřebný je konstruktér impulzních obvodů, odpovědná obsluha VN a partner pro analýzu materiálů. Největší náklady a kalendářní riziko představují vývoj dvouimpulzní zkoušky a dlouhodobé rezervace aparatury.

### Náročnost a harmonogram

| Období | Práce a ověřitelný výstup |
| --- | --- |
| Září až prosinec 2026 | Návrh zkušebního obvodu a vymezení elektrického namáhání |
| Leden až červen 2027 | Zprovoznění dvouimpulzní metody a kalibrace |
| Červenec až prosinec 2027 | Mapa krátkodobé obnovy a první rukopis |
| Leden až červen 2028 | Omezené série opotřebení a nezávislá sada elektrod |
| Červenec až prosinec 2028 | Model stability, potvrzující experiment a druhý rukopis |
| Leden až srpen 2029 | Reálná rezerva na syntézu a dokončení |

Odhad 65–95 laboratorních dnů: 20–28 vývoj a metrologie, 20–30 obnova, 15–22 série stability, 10–15 rezerva. Část dlouhodobých testů může probíhat mimo hlavní laserovou laboratoř pouze po ověření srovnatelnosti použitého spouštění.

### Podmínka pokračování a záložní rozsah

Do června 2027 musí fungovat měření obnovy s definovanou historií prvního výboje. Při zpoždění zúžit téma na krátkodobou obnovu a vypustit slib životnosti. Pokud je změna povrchu pod citlivostí metody, uvést horní mez měřitelné eroze; nepřevádět ji na tvrzení o nulovém opotřebení.

### Technické aplikace výsledků

Návrh opakovací frekvence laboratorního spínače, požadavky na výměnu elektrod a odhad provozní dostupnosti. Pro další vývoj jsou relevantní impulzní napájecí moduly a opakované testování součástí. Životnost v letech ani počet milionů sepnutí nelze extrapolovat z krátké série bez ověřeného mechanismu degradace.

<!-- PAGEBREAK -->

## Společné požadavky na důkaz a měření

### Minimální metrologický základ

Každý pokus musí mít jednoznačný identifikátor propojující surové průběhy, energii laseru, konfiguraci, stav elektrod, prostředí a kalibraci. Archivovat také neúspěchy a předčasná sepnutí. Definovat dobu působení napětí před laserem i časové okno po laseru. U50 není univerzální vlastnost mezery bez uvedení geometrie a měřicího postupu.

Pro časování použít skutečný optický marker a kalibrované relativní zpoždění kanálů. Jako výchozí návrh pro děje v jednotkách až desítkách ns lze zvažovat fotodiodu a osciloskop v třídě alespoň 500 MHz a záznam řádově 2,5 GS/s nebo rychlejší; tato čísla nejsou zárukou výsledné nejistoty. O vhodnosti rozhoduje celý řetězec včetně VN a proudového snímače, šumu a způsobu určování hrany. Pro subnanosekundový výsledek je nutný samostatně ověřený časový rozpočet.

Před zahájením se musí potvrdit elektrická energie, maximální proud a napěťový režim, optická zatížitelnost, dostupnost blokování a odpovědnosti obsluhy. Dokument není návod k zapojení vysokonapěťového experimentu; konkrétní schéma a provozní postup patří do dokumentace laboratoře.

### Počty pokusů a práce s nejistotou

Pilotně použít například 30–50 platných pokusů na několik reprezentativních bodů pro odhad variability a přechodové oblasti. Finální počty určit podle požadované šířky intervalu, driftu a testovaného účinku. Dva podobné průměry bez intervalů nejistoty nedokládají ekvivalenci.

Pro názornost: při n nezávislých úspěších bez jediného selhání je jednostranná 95% dolní binomická mez pravděpodobnosti úspěchu 0,05^(1/n). Pro dolní mez alespoň 99 % je třeba nejméně 299 úspěchů bez selhání; pro 99,9 % nejméně 2995. Výpočet platí pro předem určený bod a stabilní podmínky. Nelze ho bez úpravy použít po průběžném hledání nejpříznivějšího výsledku ani při silné závislosti pokusů.

Zpoždění uvádět společně s pravděpodobností sepnutí. Jitter úspěšných pokusů doplnit počtem selhání a šířkou časového okna; krátké okno může zdánlivě zlepšit rozptyl vyřazením pomalých výbojů. Pro neukončené děje zvážit analýzu času do události s pravostranným cenzorováním.

### Nezávislé ověření

Kalibrační a validační data oddělit po celých dnech nebo měřicích blocích, nikoli náhodným rozdělením téměř totožných sousedních výstřelů. Před konečnou kampaní zapsat rozhodovací pravidla, nejmenší relevantní účinek a definici chyb. Publikovat meze platnosti modelu a vazbu na konkrétní plyn, geometrii a rozsah energie.

<!-- PAGEBREAK -->

## Doporučený společný harmonogram

Plán níže rozpracovává variantu B při cíli dokončit jádro výzkumu do dubna 2028 a odevzdat pracovní finální text v létě 2028. Srpen 2028 je interní plánovací cíl; splnění formálních podmínek SDZ, obhajoby a publikačních požadavků musí potvrdit školitel a příslušné studijní orgány. [S3, S4]

| Termín | Výsledek | Rozhodnutí při nesplnění |
| --- | --- | --- |
| Do konce září 2026 | Zvolená varianta, konkrétní laser, odpovědnosti a rezervace | Zúžit rozsah ještě před objednáváním techniky |
| Říjen až prosinec 2026 | Audit DP/APL, kalibrace, optický pilot a datový protokol | Nezahajovat plnou mřížku bez validních časových značek |
| Leden až březen 2027 | Referenční mapa a rozlišitelný ukazatel kanálu | Upravit diagnostiku nebo připravit přechod k A |
| Duben až červen 2027 | Pilotní test mechanismu, reprodukce alespoň ve třech dnech | Uzavřít základní téma a odložit vedlejší rozšíření |
| Červenec až říjen 2027 | Potvrzující série a dataset pro první rukopis | Doplnit jen chybějící rozhodující měření |
| Listopad 2027 | Odeslaný první rukopis a identifikovaný model | Oddělit připomínky rukopisu od rozšiřování experimentu |
| Prosinec 2027 až únor 2028 | Validace na nových blocích, uzavřené nejistoty | Preferovat doložený užší model |
| Březen až duben 2028 | Druhý rukopis, uzavřené jádro výsledků | Nespouštět nový samostatný experimentální směr |
| Květen až červen 2028 | Úplný text disertace a interní připomínky | Soustředit kapacitu na syntézu a chybějící důkazy |
| Červenec až srpen 2028 | Finální revize a příprava odevzdání | Termín obhajoby určit podle skutečných podmínek |

### Kapacitní a publikační rezerva

Pro B rozdělit 45–65 laboratorních dnů do bloků, které umožní opakovat nastavení mezi dny. Po stabilizaci aparatury plánovat přibližně 3–4 dny měsíčně v hlavních měřicích obdobích, s intenzivnějšími bloky pro zavedení diagnostiky. Sepsání a modelování mají probíhat souběžně s měřením, ne až po něm.

Dva rukopisy jsou pracovní způsob rozdělení výsledků: první pro experimentální charakterizaci a kanálové ukazatele, druhý pro redukovaný model a nezávislé ověření. Nejde o ověřené minimum studijního programu. Již použité výsledky DP/APL jasně oddělit od nových dat a zabránit duplicitnímu vykazování přínosu. Odeslání rukopisu není totéž jako přijetí.

<!-- PAGEBREAK -->

## Doporučené znění zadání pro jednání

### Pracovní název disertační práce

**Vliv stavu laserem vytvořeného kanálu na pravděpodobnost a časování sepnutí vysokonapěťového jiskřiště**

### Vymezení cíle

Cílem práce je experimentálně určit, které měřitelné vlastnosti laserem vytvořeného kanálu ovlivňují spolehlivost a časový průběh přeskoku ve vysokonapěťové vzduchové mezeře, a vytvořit redukovaný model schopný předpovídat vybrané spínací parametry v podmínkách nepoužitých při jeho sestavení. Práce naváže na experimenty diplomové práce a navazující časová měření, ověří jejich metrologické předpoklady a stanoví podmínky technicky využitelného řízeného sepnutí.

### Navržené úkoly

1. Proveďte kritickou analýzu dosavadních výsledků laserového spouštění jiskřiště a literatury se zaměřením na iniciaci kanálu, jeho vývoj a pravděpodobnostní charakter přeskoku.
2. Navrhněte, realizujte a metrologicky ověřte souběžné měření optické a elektrické odezvy s dohledatelnou časovou referencí a záznamem úspěšných i neúspěšných pokusů.
3. Určete závislost pravděpodobnosti, zpoždění a časového rozptylu sepnutí na pracovním napětí a měřených ukazatelích kanálu v definované geometrii a prostředí.
4. Posuďte přidanou vypovídací hodnotu kanálových ukazatelů proti modelu založenému pouze na napětí a energii laserového impulzu.
5. Sestavte redukovaný fyzikálně odůvodněný model, určete nejistoty a ověřte jeho predikční schopnost na nezávislých měřicích blocích.
6. Odvoďte návrhová pravidla pro laboratorní opticky spouštěné impulzní zařízení a vymezte jejich technické možnosti a omezení.

### Rozsah a podmíněné rozšíření

Základ omezit na vzduch, jednu potvrzenou laserovou konfiguraci, referenční geometrii a jednu polaritu. Druhou geometrii nebo polaritu použít jako validační test pouze po uzavření základní mapy. Ekonomický přesah případně doplnit úzkým srovnáním nákladů na validní laboratorní sepnutí; samostatné adaptivní řízení už představuje rozšíření zadání.

### Co potvrdit během prvních tří měsíců

V září odsouhlasit rozsah se školitelem, dostupnost laseru a diagnostiky, návaznost na studijní program a skutečné termíny. V říjnu sjednotit stará data, identifikaci snímačů a intenzitní výpočty. V listopadu doložit časový rozpočet a pilot optického ukazatele. V prosinci uzavřít protokol, realistický počet experimentů a rezervace na rok 2027. Výsledkem má být konkrétní schválený experimentální plán, ne pouze nový název práce.

<!-- PAGEBREAK -->

## Technické využití a hranice rozšíření

### Od výsledku k aplikaci

| Výsledek disertace | Nejbližší technické využití | Co je ještě třeba ověřit |
| --- | --- | --- |
| Mapa spolehlivého sepnutí A | Nastavení spouštěče laboratorního impulzu | Přenos na jiné napětí, plyn a zatížení |
| Kanálový model B | Návrh geometrie a diagnostiky spouštění | Identifikace parametrů v novém zařízení |
| Adaptace C | Automatizované seřizování a omezení neplatných pokusů | Latence, stabilita, údržba a srovnání s jednoduchým řízením |
| Tvarovaný kanál D | Tolerance polohy a řízená dráha výboje | Optické ztráty, čistota a dlouhodobé seřízení |
| Synchronizace E | Dva společně spouštěné impulzní kanály | Výkonové vazby a škálování počtu stupňů |
| Obnova pevnosti F | Maximální opakovací režim a interval údržby | Dlouhodobé namáhání v cílové aplikaci |

### Přiměřený ekonomický přesah

Smysluplnou jednotkou je cena validního laboratorního impulzu při stejné amplitudě, časové toleranci a spolehlivosti. Do srovnání vstupuje příprava, obsluha, kalibrace, spotřeba infrastruktury, výměna dílů, odstávky a podíl neúspěšných pokusů. Rozlišit mezní cenu využití již existujícího laseru a plné náklady samostatně pořizovaného systému. Nižší optická energie sama nedokládá nižší celkové náklady.

Starší lokální model uvádí konkrétní návratnost a srovnání s výkonovými vypínači. V prověřených podkladech pro ně nejsou doložena potřebná data o životnosti, stejné funkci ani reálných cenách. Tyto hodnoty proto do nového zadání nepřebírám. Mohou být nahrazeny transparentní citlivostní analýzou po získání podkladů. [S13]

### Směry vhodné až po uzavření jádra

**HVDC vypínání a zhášení oblouku:** vyžaduje samostatný obvod přerušení proudu, obnovené napětí a další výkonové zkoušky. **Venkovní vedení blesku:** existuje jako výzkumný směr, ale není přímým pokračováním centimetrové laboratorní mezery bez nové infrastruktury. [S11]

**EMP stínění, dlouhožijící plazmoidy, neutronové zdroje a bezdrátový přenos energie:** nejsou v prověřené diplomce doloženým funkčním výsledkem; každý by otevřel vlastní soubor hypotéz a diagnostiky. **Laserové zpracování povrchů, optické senzory nebo LIBS jiných plynů:** mohou být samostatná témata, ale využila by méně z dosavadního výzkumného základu než varianty A až F.

Volba B zachovává nejpevnější návaznost. Volba C je vhodnou alternativou při požadavku na výraznější systémovou aplikaci. D až F mají smysl především s konkrétním partnerem, hotovou technikou a ochotou přehodnotit termín roku 2028.

<!-- PAGEBREAK -->

## Zdroje a dohledatelnost

### Vlastní výsledky a aktuální plán

**[S1] Michal Sakala. Diplomová práce z roku 2024 a její zadání.** Pokročilé spouštění vysokonapěťového jiskřiště laserovým paprskem. Kontrolovány zejména kap. 5–7, tabulky 5.3–5.6, tištěné strany 51–67. Číslování PDF je proti tištěnému textu posunuto o deset stran. Kanonické soubory:

- `IV Archives/01_DP_Master_Thesis/thesis/DP_sakalmic.pdf`
- `IV Archives/01_DP_Master_Thesis/thesis/DP_zadani.pdf`

**[S2] Posudky diplomové práce.** Posudek oponentky Evy Müllerové a posudek vedoucího Jana Mikeše, 2024. Použity zejména otázky k počtu pokusů, aplikacím a rozšíření mezer.

- `IV Archives/01_DP_Master_Thesis/thesis/Op-posudek-Sakala.pdf`
- `IV Archives/01_DP_Master_Thesis/thesis/Sakala_vedouci_2024.pdf`

**[S3] LTSG Core Research Package 2026–2028.** Aktuální interní návrh základního výzkumného balíčku, aktualizace 7. září 2026. Obsahuje otázku stavu kanálu, příspěvky C-A až C-C, metrologii, validaci a hranice základního rozsahu.

- `tools/Obsidian-PhD/I Projects/02_Campaigns/LTSG Core Research Package 2026-2028.md`

**[S4] Doctoral Scope & Decision Register.** Interní registr otevřených rozhodnutí. Použit k odlišení pracovního plánu od potvrzeného zadání, dostupné techniky a formálních studijních podmínek.

- `tools/Obsidian-PhD/II Areas/06_Administration/Supervisor_Sync/Doctoral Scope & Decision Register.md`

**[S5] Sakala a kol. The Dynamics of Laser-Driven Ionisation in High-Voltage Circuit Switching.** Lokální rukopis pro Asia-Pacific International Conference on Lightning 2025. Kontrolovány zejména metoda na PDF str. 3 a tabulky II–III na str. 4–5. APL zde označuje konferenci; dokument není zaměňován s časopisem Applied Physics Letters. Bibliografický stav finální publikace nebyl rozhodujícím podkladem tohoto posouzení.

- `I Projects/01_Manuscripts/2025-APL/20250319-Sent/APL_2025__IEEE_Conference_Template.pdf`

Cesty jsou uvedeny relativně vůči pracovní složce `General/sakalmic`. Analýza vychází z těchto dokumentů a veřejných zdrojů na následující straně. Úplný audit všech surových experimentálních záznamů, fyzická inventura aparatury a cenové poptávky nejsou součástí provedeného posouzení.

<!-- PAGEBREAK -->

## Odborné zdroje a historické návrhy

### Primární veřejné zdroje

**[S6] HiLASE. High repetition rate picosecond PERLA B laser.** Veřejné parametry nabízené větve. Použito pro rámec dostupných technologií; rezervace a konkrétní konfigurace projektu tím nejsou potvrzeny. [Parametry HiLASE](https://www.hilase.cz/en/high-repetition-rate-picosecond-perla-b-laser/)

**[S7] Pearson Electronics. Current Monitor Model 1423.** Katalogový list, revize 20160310. Použito pro kontrolu časové odezvy historicky uvedeného proudového monitoru. [Katalogový list 1423](https://pearsonelectronics.com/pdf/1423.pdf)

**[S8] Tektronix. Passive High Voltage Probes.** Katalogový list P6015A a souvisejících sond, 56W-10262-18. Použito pro rozlišení DC a impulzního napěťového rozsahu a kontrolu šířky pásma. Rozhoduje dokumentace konkrétního kusu. [Katalogový list Tektronix](https://www.tek.com/en/datasheet/passive-high-voltage-probes)

**[S9] Rosenthal, E. W., a kol. Air hydrodynamics of the ultrafast laser-triggered spark gap.** Autorský preprint 2020; související vydavatelské DOI 10.1364/OE.398836. Použito jako motivace role vývoje hustoty plynu, nikoli jako důkaz mechanismu vlastní sestavy. [Autorský preprint](https://arxiv.org/abs/2005.14198)

**[S10] Clerici, M., a kol. Laser-assisted guiding of electric discharges around objects.** Science Advances 1, e1400111, 2015. DOI 10.1126/sciadv.1400111. Použito k vymezení již existujícího výzkumu tvarovaných svazků. [Plný text na webu univerzity](https://www.physics.gla.ac.uk/XtremeLight/publications/SA-curved_discharges-Clerici%282015%29.pdf)

**[S11] Houard, A., a kol. Laser-guided lightning.** Nature Photonics 17, 231–235, 2023. DOI 10.1038/s41566-022-01139-z. Použito k odlišení venkovní aplikace od centimetrové laboratorní mezery. [Článek vydavatele](https://www.nature.com/articles/s41566-022-01139-z)

**[S12] Savage, M. E., Stoltzfus, B. S. High reliability low jitter 80 kV pulse generator.** Physical Review Special Topics Accelerators and Beams 12, 080401, 2009. DOI 10.1103/PhysRevSTAB.12.080401. Použito pro vymezení předchozího výzkumu spolehlivosti a společného spouštění dvojice mezer. [Článek vydavatele](https://journals.aps.org/prab/abstract/10.1103/PhysRevSTAB.12.080401)

Veřejné zdroje ověřeny 8. září 2026. Jde o cílené ověření pro rozhodovací podklad, nikoli úplnou systematickou rešerši nebo patentovou analýzu. Originalitu konečného zadání je třeba potvrdit rešerší přesně zvolené hypotézy a režimu.

### Historické návrhy použité pouze kriticky

**[S13] Starší návrhy témat, experimentální a ekonomické rozvahy.** Zahrnují `tools/Github/PhD-sakalmic-prezentace/Navrhy_temat_disertace_v03.tex` a v adresáři tohoto dokumentu soubory `Rozhodovaci_Podklad_Disertace_HiLASE_CVUT_2026-2028.pdf`, `Strategicky_Plan_Disertace_Varianta3_2026-2029_Final.pdf`, `experimentalni_program_vybaveni_a_postupy_v01.tex` a `TCO_Model_Disertace_Laserove_Spinani_CEPS_HVDC.md`. Použity jako zdroj dříve uvažovaných směrů; jejich předpoklady o výkonu, životnosti a ekonomice nejsou považovány za experimentální důkaz.
