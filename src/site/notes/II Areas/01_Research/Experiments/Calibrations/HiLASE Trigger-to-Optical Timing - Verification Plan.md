---
{"dg-publish":true,"permalink":"/ii-areas/01-research/experiments/calibrations/hi-lase-trigger-to-optical-timing-verification-plan/","title":"HiLASE - verification of electrical-trigger to optical-arrival timing","noteIcon":"","updated":"2026-09-16","dg-note-properties":{"title":"HiLASE - verification of electrical-trigger to optical-arrival timing","aliases":["Kalibrace elektrického triggeru HiLASE","HiLASE trigger-to-optical timing"],"type":"calibration-plan","status":"verification-pending","evidence_state":"unverified","calibration_id":"HILASE-TIME-2024-2025-OPEN","created":"2026-09-16","last_updated":"2026-09-16","topics":["topic/ltsg/timing","topic/ltsg/metrology"]}}
---


# HiLASE: ověření kalibrace elektrický trigger → optický pulz → průraz

## Závěr k 16. září 2026

Elektrický spouštěcí systém **mohl být při kampani kalibrován**. Prohlédnuté publikace a dosavadní pracovní záznamy však zatím nedokládají konkrétní časovou korekci a nejistotu pro celý řetězec použitý na vysokonapěťovém jiskřišti. To **není tvrzení, že kalibrace neexistuje**. Je třeba vyžádat záznam u odpovědného pracoviště a ověřit jeho shodu s konkrétní konfigurací 2024/2025.

V APL 2025 jsou série 8–10 z února 2025 vyhodnoceny vzhledem k elektrické triggerové hraně. Uvedený rozsah 0,164–8,124 µs proto nesmí být bez dalšího přejmenován na interval od optického příchodu do mezery. Sedm sérií z května 2024 se týká zejména snížení průrazného napětí; původ a neověřené počty jsou v [[II Areas/01_Research/Experiments/Dataset Manifests/Historical Measurements 2024-2025 - Provenance\|Historical Measurements 2024-2025 - Provenance]]. Obecný trend „vyšší intenzita → kratší zpoždění“ zůstává k ověření.

## Tři rozdílné časové události

| Symbol | Událost | Současný stav |
| --- | --- | --- |
| $t_E$ | Zvolená hrana elektrického signálu spouštění laseru v definovaném měřicím bodě | APL používá elektrickou referenci; přesné místo signálu a kanál je nutno ověřit. |
| $t_O$ | Skutečný příchod optického pulzu do interakční oblasti jiskřiště | Z dosud prohlédnutých podkladů není k dispozici přiřazená kalibrovaná časová značka. |
| $t_B$ | Průraz označený předem definovaným napěťovým/proudovým kritériem | Marker a odezva sondy mohou nést další posun a nejistotu. |

Elektricky vztažený interval je $D_E=t_B-t_E$ po korekci příslušných elektrických kanálů. Fyzikálně požadovaný interval je $D_O=t_B-t_O$. Při společné definici časových značek platí $D_O=D_E-(t_O-t_E)$. Člen $(t_O-t_E)$ se nesmí odhadovat ze samotné délky kabelu: zahrnuje elektroniku laseru, výběr pulzu, konkrétní optickou dráhu a jejich případné kolísání. Rovnice je účetnictvím časových značek, nikoli již změřenou korekcí.

Pro optickou odbočku v místě $P$ je nutno navíc převést čas pulzu naměřený fotodiodou na čas v mezeře. Opravy zahrnují rozdíl optických drah, odezvu fotodiody, kabel/kanál osciloskopu a elektrický marker průrazu. Pevný posun mění střední zpoždění. Kolísání od pulzu k pulzu a nestálost markerů může měnit i odhad jitteru; variance nelze bez ověření nezávislosti mechanicky odečítat.

## Co je nyní doloženo

- Vlastní APL 2025 uvádí elektricky referencované zpoždění, nikoli dokumentovanou optickou časovou nulu v mezeře. [DOI: 10.1109/APL65034.2025.11108944](https://doi.org/10.1109/APL65034.2025.11108944).
- Publikace laboratoře LIDT z roku 2019 popisuje PERLA B, optickou diagnostickou odbočku, fotodiodu ve schématu a **kalibrovaný měřič energie**. Časový kalibrační protokol pro jiskřiště neuvádí. [Čech a kol., 2019](https://www.mmscience.eu/journal/issues/december-2019/articles/laser-induced-damage-threshold-testing-at-hilase/download).
- Fotodioda ve starší práci LIDT slouží k online detekci rozptýleného světla při poškození optiky. To není důkaz optické časové reference pro jiskřiště. [Vanda a kol., 2016](https://doi.org/10.1017/hpl.2016.11).
- V místním archivu února 2025 jsou čtyřkanálové oscilogramy. Samotné hlavičky CSV potvrzují společnou časovou osu kanálů, ale neidentifikují jejich fyzické zapojení, kalibrační list ani optický čas v mezeře. To je kontrola formátu, nikoli úplný audit všech průběhů.

Kontext pracoviště: [[II Areas/01_Research/Experiments/HiLASE LIDT Laboratory\|LIDT laboratoř]] · [[II Areas/01_Research/Experiments/HiLASE Research Hub\|HiLASE rozcestník]] · [[II Areas/01_Research/Concepts/202609031300 - Timing Jitter Must Be De-Embedded from the Measurement Chain\|Oddělení jitteru přístrojů]].

## Ověřovací úkoly

- [ ] **Kontaktovat Martina Mydláře** jako spoluautora APL a publikace LIDT; požádat o určení odpovědné osoby pro konkrétní laserovou větev a o potvrzení, zda a jak byl v roce 2025 kalibrován vztah elektrický trigger ↔ optický pulz u jiskřiště. Kontakt je plánovaný úkol; zpráva dosud nebyla odeslána.
- [ ] Získat písemné potvrzení nebo existující protokol: datum, identifikace systému/větve, verze zapojení, schéma triggeru a optické trasy, místo měření fotodiodou, metoda korekce, změřený posun, nejistota a kolísání mezi pulzy, platnost pro kampaně květen 2024 a únor 2025. Při absenci protokolu zaznamenat výslovné potvrzení, co bylo a nebylo kalibrováno.
- [ ] Přiřadit kanály archivovaných oscilogramů k signálům podle laboratorního logu/schématu; ověřit, zda některý kanál skutečně snímal optický pulz, a nezaměnit elektrický laserový marker za fotodiodu.
- [ ] Rozlišit kalibraci elektrického kabelového řetězce, vnitřního laserového zpoždění, fotodiody a markeru elektrického průrazu. Ověřit, zda se některé korekce měnily se zvolenou laserovou větví, vlnovou délkou, frekvencí nebo optickým vedením.
- [ ] Je-li kompletní původní časový řetězec doložen, provést reprodukovatelný přepočet historických zpoždění se sdílenými i náhodnými nejistotami. Chybějící složky uvést jako meze; nevydávat nový fyzikální jitter za zjištěný.
- [ ] Pro novou kampaň připravit protokol společného záznamu elektrického markeru, optické odbočky a průrazu. Zkontrolovat časové posuny po změně zapojení a archivovat konfiguraci i kalibrační data.

## Kritéria uzavření

**A — historická kalibrace potvrzena:** existuje konfiguračně platný protokol a lze zveřejnit opravený interval včetně nejistoty. **B — dílčí kalibrace:** lze opravit jen prokázanou část, zbytek zůstává omezením interpretace. **C — nedoloženo:** historický výsledek zůstane výslovně elektricky referencovaný; nová disertační kampaň zavede optickou nulu prospektivně. V žádné větvi se automaticky nepřepisují publikované hodnoty APL.

## Zdroj pro metrologické zpracování

JCGM, *Evaluation of measurement data — Guide to the expression of uncertainty in measurement*, JCGM 100:2008, [DOI: 10.59161/JCGM100-2008E](https://doi.org/10.59161/JCGM100-2008E). Metoda bude muset zachovat korelace společných časových posunů a odlišit nejistotu středního posunu od variability mezi pulzy.
