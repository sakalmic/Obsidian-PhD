---
{"dg-publish":true,"permalink":"/ii-areas/01-research/experiments/hi-lase-lidt-laboratory/","title":"HiLASE LIDT Laboratory - relevance to PERLA timing","noteIcon":"","updated":"2026-09-16","dg-note-properties":{"title":"HiLASE LIDT Laboratory - relevance to PERLA timing","aliases":["HiLASE LIDT laboratoř","HiLASE LIDT Laboratory"],"type":"laboratory-context","status":"evidence-review","context":"research","topics":["topic/ltsg/metrology"],"created":"2026-09-16","last_updated":"2026-09-16"}}
---


# Laboratoř LIDT HiLASE a vztah k časování jiskřiště

**LIDT** znamená *laser-induced damage threshold*, práh poškození optické součásti laserem. Laboratoř měří poškození optiky; není to laboratoř vysokonapěťového průrazu. Je relevantní jako možný zdroj znalosti laserové platformy, diagnostických větví a interních kalibrací. Z publikací **neplyne**, že jiskřiště sdílelo totožné zapojení nebo časovou kalibraci.

## Přímá vazba na vlastní práci

Publikace Čech, Vanda, Mureșan, **Mydlář** a kol. (2019) popisuje stanici LIDT v HiLASE používající mimo jiné **PERLA B**: 1030 nm, 1 kHz, pulz přibližně 1,8 ps a energie do 10 mJ podle tehdejší konfigurace. Mydlář je také spoluautorem vlastního příspěvku APL 2025. To je silná personální a platformová vazba, ale nikoli důkaz stejné optické větve při měření jiskřiště. Vlastní APL uvádí 1,2 ps a více vlnových délek; rozdílné publikované nominální hodnoty mohou označovat konfigurace nebo dobu provozu a vyžadují identifikaci konkrétní větve z laboratorního záznamu.

## Co publikace o LIDT skutečně popisují

| Zdroj | Doložená informace | Co z něj nelze vyvozovat |
| --- | --- | --- |
| Čech a kol., 2019 | PERLA B jako jeden ze zdrojů LIDT; po zeslabení optická odbočka (<1 % energie) pro kontinuální diagnostiku profilu a energie; kalibrovaný měřič energie; fotodioda zakreslená ve schématu stanice. | Numerickou časovou korekci mezi elektrickým povelem, pulzem u jiskřiště a průrazem; kalibraci jitteru jiskřiště. |
| Vanda a kol., 2016 | U tehdejších LIDT zkoušek online detekce rozptýleného světla fotodiodou a softwarové řízení počtu dodaných pulzů. Pikosekundová zkouška v této práci používá jiný, Yb:KGW laser. | Že šlo o stejnou PERLA B nebo že fotodioda sloužila jako časová nula vysokonapěťového pokusu. |
| HiLASE, popis stanice LIDT | Stanice uvádí pikosekundový režim 1030 nm / 1 kHz a optickou inspekci. | Identifikaci historické větve, jejího zapojení v letech 2024–2025 a časový kalibrační list. |
| HiLASE, popis PERLA 100/C | Platforma má několik provedení, volbu pulzů a řídicí systém. | Záměnu produktových parametrů za hodnoty konkrétního experimentu. |

**Rozlišení metrologie:** kalibrovaná energie pulzu a sledování profilu potvrzují optické vstupy pro LIDT. Neprokazují kalibraci času elektrický trigger → optický příchod v mezeře. Fotodioda použitá k detekci poškození také není automaticky časovou referencí průrazu.

## Odkazy na primární podklady

1. P. Čech, J. Vanda, M.-G. Mureșan, M. Mydlář, K. Pilná a J. Brajer, „Laser Induced Damage Threshold Testing at HiLASE,“ *MM Science Journal*, 2019. [Plný text](https://www.mmscience.eu/journal/issues/december-2019/articles/laser-induced-damage-threshold-testing-at-hilase/download), [DOI: 10.17973/MMSJ.2019_12_2019118](https://doi.org/10.17973/MMSJ.2019_12_2019118).
2. J. Vanda a kol., „Comparative LIDT measurements of optical components for high-energy HiLASE lasers,“ *High Power Laser Science and Engineering* 4, e11 (2016). [DOI: 10.1017/hpl.2016.11](https://doi.org/10.1017/hpl.2016.11).
3. HiLASE, [Laser-induced damage threshold (LIDT) target area](https://www.hilase.cz/en/laser%E2%80%90induced-damage-threshold-lidt-target-area/) a [PERLA 100](https://www.hilase.cz/en/produkty/perla-100/) — institucionální popisy, nikoli kalibrační protokoly.
4. M. Sakala a kol., „The Dynamics of Laser-Driven Ionisation in High-Voltage Circuit Switching,“ APL 2025, [DOI: 10.1109/APL65034.2025.11108944](https://doi.org/10.1109/APL65034.2025.11108944) — vlastní vysokonapěťový experiment.

## Úkoly a návaznost

- [ ] Zjistit, zda vysokonapěťový experiment v letech 2024–2025 opravdu používal PERLA B a jak byl veden pulz k jiskřišti.
- [ ] Ověřit, zda LIDT a vysokonapěťová kampaň sdílely pouze laser, nebo i diagnostickou odbočku, fotodiodu a triggerový signál.
- [ ] Vyžádat udržovaný kalibrační či servisní záznam příslušné větve; existenci a použitelnost zapíše [[II Areas/01_Research/Experiments/Calibrations/HiLASE Trigger-to-Optical Timing - Verification Plan\|časová kalibrační poznámka]].

Zpět: [[II Areas/01_Research/Experiments/HiLASE Research Hub\|HiLASE rozcestník]].
