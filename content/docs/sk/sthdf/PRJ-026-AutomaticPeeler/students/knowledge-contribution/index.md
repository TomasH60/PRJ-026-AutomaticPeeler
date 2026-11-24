---
# 🧩 Versioning – systém dopĺňa automaticky
fm_version: "1.0.1"

# Dátum buildu – generuje skript
fm_build: "2026-10-06T13:23:32.796513+00:00"

# Poznámka k verzii – voliteľné
fm_version_comment: ""


# 🆔 IDENTITY --------------------------------------------------------

# ID generuje CLI / skript

# Unikátne UUID – generuje skript
guid: "f262f2a8-8a07-429e-b89b-7465364fadb6"


# 🧭 CONTEXT ---------------------------------------------------------

# DAO / doména (knife, sdlc, q12, 7ds...) dopĺňa skript
dao: "sthdf"

# Názov zápisu – dopĺňa používateľ
title: "Knowledge Contribution – Tomáš Horička a Marek Fiľo"

# Krátky popis – dopĺňa používateľ (voliteľné)
description: "Dva KNIFE príspevky: dokumentovanie výroby CNC dielov a prevod požiadaviek na návrh fyzického produktu."


# 👥 AUTHORSHIP ------------------------------------------------------

# Hlavný autor – z globálneho configu
author: "Tomáš Horička"

# Zoznam autorov – generuje skript
authors:
  - "Tomáš Horička"
  - "Marek Fiľo"


# 🗂 CLASSIFICATION ---------------------------------------------------

# Nadradená kategória – môže doplniť používateľ
category: ""

# Typ dokumentu (guide, case, tutorial...) – používateľ (voliteľné)
type: ""

# Priorita (low/medium/high) – voliteľné
priority: ""

# Tagy – odporúča sa 2–6 tagov.
# Typy tagov:
#   - rámce: knife, 7ds, sdlc, q12
#   - účel: tutorial, guide, pattern, case-study
#   - téma: git, backup, ai, communication
#   - úroveň: beginner, intermediate, advanced
tags: []


# 🌍 LOCALIZATION -----------------------------------------------------

# Jazyk dokumentu – doplní skript podľa štruktúry
locale: "sk"


# 🕒 LIFECYCLE --------------------------------------------------------

# Dátum vytvorenia – generuje skript
created: "2026-10-06 15:23"

# Dátum poslednej úpravy – dopĺňa človek
modified: "2026-11-24"

# Stav dokumentu – default "backlog"
status: "draft"

# Viditeľnosť – default "public"
privacy: "public"


# ⚖ INTELLECTUAL PROPERTY -------------------------------------------

# Držiteľ práv k obsahu – dopĺňa skript
rights_holder_content: "Roman Kazicka"

# Systémový vlastník práv
rights_holder_system: "CAA / KNIFE / LetItGrow"

# Licencia
license: "CC-BY-NC-SA-4.0"

# Disclaimer
disclaimer: "Use at your own risk. Methods provided as-is; participation is voluntary and context-aware."

# Copyright
copyright: "© 2025 Roman Kazicka"


# 🔗 ORIGIN / PROVENANCE ---------------------------------------------

# Repozitár pôvodu
origin_repo: ""

# URL pôvodného repozitára
origin_repo_url: ""

# Commit pôvodu
origin_commit: ""

# Branch pôvodu
origin_branch: ""

# Systém pôvodu (CAA/KNIFE/STHDF…)
origin_system: "CAA"

# Pôvodný autor
origin_author: "Roman Kazicka"

# Importovaný zdroj
origin_imported_from: ""

# Dátum importu
origin_import_date: ""


# 🧱 RESERVED ---------------------------------------------------------

fm_reserved1: ""
fm_reserved2: ""
---

<!-- SDLC_INSTANCE_ID: PRJ-026-AutomaticPeeler -->

# 📚 Knowledge Contribution

Táto stránka obsahuje dva autorské príspevky v štruktúre **KNIFE** pre projekt **PRJ-026-AutomaticPeeler**. Tomáš sa venuje dokumentovaniu výroby a Marek prevodu požiadaviek na návrh výrobku.

**Stav:** Pracovné návrhy postupov určených na použitie v projekte. Príklady ilustrujú navrhovaný spôsob práce; výsledky výroby a testovania doplníme po jeho praktickom overení. Samostatné publikovanie príspevkov v KNIFE katalógu zatiaľ nie je doložené.

## Tomáš Horička – ST057

### 🔖 Názov a stručný popis
**Od návrhu k dielu: ako dokumentovať výrobu CNC súčiastky**

Príspevok opisuje jednoduchý spôsob vedenia výrobného záznamu. Je určený študentským tímom, ktoré potrebujú prepojiť verziu modelu, vyrobený diel, kontrolu a následné úpravy. V našom projekte ho chceme použiť pri výrobe súčiastok ručného šúpača.

### 🎯 Čo rieši – účel a cieľ
Pri úpravách výrobku potrebujeme vedieť, podľa ktorého návrhu bol diel vyrobený a prečo sme ho neskôr zmenili. Cieľom je vytvoriť stručný záznam, z ktorého druhý člen tímu pochopí priebeh práce a vie dohľadať súvisiace podklady.

### 🧩 Ako to rieši – princíp
Každému dielu priradíme označenie a ku každej výrobnej verzii vytvoríme samostatný záznam. Ten prepojí vstupné podklady, priebeh výroby, kontrolu a rozhodnutie o ďalšom kroku. Staršie záznamy zachováme, aby sa dal sledovať vývoj návrhu.

### 🧪 Ako to použiť – aplikácia
Postup použijeme pri dieloch šúpača, ktoré budeme vyrábať alebo upravovať. Záznam pripravíme pred výrobou a doplníme ho po kontrole dielu a po skúšobnej montáži. Pri každej novej verzii uvedieme, na ktorú predchádzajúcu verziu nadväzuje.

### ⚡ Rýchly návod
1. Pomenuj diel a označ verziu jeho modelu alebo výkresu.
2. Pripoj odkazy na výrobné podklady a zapíš plánovaný materiál.
3. Stručne zaznamenaj vykonané operácie a odchýlky od plánu.
4. Doplň fotografie a výsledky kontroly podľa výkresu.
5. Zapíš výsledok skúšobnej montáže a otvorené problémy.
6. Rozhodni, či diel použiješ, upravíš alebo pripravíš novú verziu, a uveď dôvod.

### 📜 Detailný článok

#### 1. Príprava záznamu
Pred výrobou vytvoríme kartu dielu. Jej základom je jednoznačný odkaz na podklady, ktoré sa majú použiť. Ak sa počas prípravy zmení model, aktualizujeme označenie verzie aj odkazy. V zázname oddelíme plánované údaje od údajov o skutočne vykonanej práci.

Navrhovaná karta dielu obsahuje:

| Položka | Čo zaznamenať |
|---|---|
| Identifikácia | Názov dielu, verzia, dátum a zodpovedná osoba |
| Podklady | Odkazy na model, výkres a príslušné výrobné súbory |
| Materiál | Plánovaný a skutočne použitý materiál |
| Výroba | Vykonané operácie a zmeny oproti plánu |
| Kontrola | Kontrolovaná vlastnosť, požiadavka z výkresu a zistený výsledok |
| Montáž | Pozorovanie pri zostavení a odkaz na fotografiu |
| Ďalší krok | Použitie, úprava alebo nová verzia spolu s dôvodom |

#### 2. Záznam priebehu a kontroly
Počas práce zaznamenávame najmä rozhodnutia, ktoré môžu ovplyvniť ďalší postup. Pri kontrole rozlišujeme medzi tým, čo sme zmerali, a tým, čo sme iba pozorovali. Záznam „diel je v poriadku“ nahradíme konkrétnym údajom alebo opisom kontroly. Ak kontrola ešte neprebehla, označíme ju ako nevykonanú.

#### 3. Prepojenie s ďalšou verziou
Ak pri montáži vznikne problém, pripojíme ho ku konkrétnemu dielu a verzii. Zapíšeme pozorovaný stav, navrhovanú zmenu a spôsob jej budúceho overenia. Nový model uložíme ako ďalšiu verziu, aby zostala dohľadateľná súvislosť medzi pôvodným návrhom a úpravou.

**Ilustračný príklad:** Ak pri skúšobnej montáži zistíme kolíziu dvoch dielov, zaznamenáme ich označenia, verzie a miesto kolízie. Pripojíme fotografiu a návrh úpravy. Po vyrobení novej verzie zopakujeme montážnu skúšku a výsledok priradíme k novému záznamu. Tento príklad nepredstavuje už zistenú chybu nášho šúpača.

### 💡 Tipy a poznámky
- Používaj rovnaké označenie dielu v modeli, výkrese aj výrobnom zázname.
- Fotografie pomenuj tak, aby sa dali priradiť ku konkrétnej verzii.
- Zapisuj aj neúspešné pokusy a dôvody zmien.
- Konkrétne výrobné parametre preberaj z overených podkladov pre použité vybavenie; tento príspevok rieši vedenie dokumentácie.

### ✅ Hodnota
Výstupom je dohľadateľná história výroby a úprav dielu. Tím vie vysvetliť, čo bolo vyrobené, podľa akých podkladov a čo sa má zmeniť pri ďalšom pokuse. Rovnaký záznam poslúži aj pri príprave projektovej dokumentácie a prezentácie.

### 🗂️ Taxonómia KNIFE
- **Kategória:** Digitálna fabrikácia, dokumentácia
- **Typ:** Návod
- **Tagy:** CNC, výroba, dokumentácia, verzovanie, kontrola

### 🌍 Referencie a podklady
- [Project Summary – návrh, výroba a testovanie šúpača](../project-summary/index.md)
- [Project Outcomes – miesto pre výsledné podklady a dôkazy](../project-outcomes/index.md)
- Vlastné výrobné záznamy, výkresy a fotografie doplníme počas realizácie.

---

## Marek Fiľo – ST056

### 🔖 Názov a stručný popis
**Od nápadu k návrhu: ako premeniť požiadavky na fyzický produkt**

Príspevok opisuje postup, ako všeobecný zámer rozložiť na požiadavky, návrhové rozhodnutia a spôsob overenia. Je určený menším tímom, ktoré potrebujú dohodnúť, čo má výrobok robiť a podľa čoho budú posudzovať jeho úspešnosť.

### 🎯 Čo rieši – účel a cieľ
Slová ako „kompaktný“, „pohodlný“ či „prémiový“ samy osebe nestačia na rozhodovanie o návrhu. Cieľom je spresniť ich význam pre konkrétny projekt a dohodnúť sa, ako tím overí splnenie jednotlivých požiadaviek.

### 🧩 Ako to rieši – princíp
Ku každej potrebe používateľa priradíme požiadavku, návrhové rozhodnutie a plán overenia. Požiadavky rozdelíme podľa priority a otvorene označíme predpoklady, ktoré ešte potrebujeme preveriť. Pri zmene návrhu sledujeme, ktorých požiadaviek sa zmena dotkne.

### 🧪 Ako to použiť – aplikácia
V projekte šúpača postup použijeme pred dokončením 3D návrhu a znovu po prvých praktických skúškach. Spoločne posúdime, či navrhované riešenie zodpovedá používaniu v kuchyni a či ho dokážeme vyrobiť s dostupným vybavením, časom a rozpočtom.

### ⚡ Rýchly návod
1. Opíš používateľa a situáciu, v ktorej bude výrobok používať.
2. Spíš jeho hlavné potreby a obmedzenia projektu.
3. Každú potrebu preveď na konkrétnu požiadavku a priraď jej prioritu.
4. Navrhni spôsob overenia a dohodni kritérium prijatia.
5. Porovnaj možnosti riešenia a zapíš dôvod výberu.
6. Po skúške aktualizuj návrh aj zoznam nesplnených alebo zmenených požiadaviek.

### 📜 Detailný článok

#### 1. Opis používania
Začneme krátkym scenárom: používateľ pripravuje ovocie alebo zeleninu, vloží ho do šúpača, ručne ovláda mechanizmus a po práci výrobok vyčistí a odloží. Tento scenár použijeme ako osnovu otázok k návrhu. Čo potrebuje pri každom kroku urobiť? Čo mu môže prekážať? Ktoré predpoklady potrebujeme overiť rozhovorom alebo skúškou?

#### 2. Tabuľka požiadaviek
Požiadavky zapíšeme do spoločnej tabuľky. Každej priradíme identifikátor, prioritu, zodpovednú osobu, kritérium prijatia a stav overenia. Nasledujúce riadky sú návrhom oblastí na dopracovanie pre náš projekt:

| Potreba | Čo spresniť v návrhu | Plánované overenie |
|---|---|---|
| Kompaktnosť | Cieľové vonkajšie rozmery a priestor na uloženie | Zmeranie zostavy a porovnanie s dohodnutým limitom |
| Ručné ovládanie | Spôsob uchopenia a vykonania pracovného pohybu | Praktická skúška a spätná väzba používateľa |
| Funkčné šúpanie | Rozsah ovocia a zeleniny a požadovaný výsledok | Opakované skúšky na vopred dohodnutých vzorkách |
| Kvalitné spracovanie | Požiadavky na povrch a zostavenie dielov | Kontrola podľa vopred pripraveného zoznamu |
| Čistenie | Prístup k častiam, na ktorých zostávajú zvyšky | Praktická skúška čistenia po použití |

Konkrétne limity a kritériá ešte dohodneme pred príslušnými skúškami. Kým chýbajú alebo neboli overené, požiadavku neoznačíme ako splnenú.

#### 3. Výber riešenia a kompromisy
Pri porovnávaní variantov posúdime funkciu, rozmery, vzhľad, vyrobiteľnosť a náklady. Ku zvolenému variantu zapíšeme dôvod výberu a otázky, ktoré zostávajú otvorené. Ak napríklad menšie rozmery obmedzia priestor na ovládanie, zachytíme tento konflikt a určíme, čo chceme overiť na modeli alebo prototype.

#### 4. Spätná väzba do návrhu
Po skúške priradíme pozorovania k požiadavkám. Rozlíšime chybu návrhu, problém pri výrobe a zmenu očakávaní. Pri navrhovanej úprave uvedieme jej dôvod, dopad na ďalšie diely a spôsob opätovného overenia. Takto vznikne záznam rozhodnutí použiteľný aj pri záverečnej prezentácii.

### 💡 Tipy a poznámky
- Oddeľuj povinné vlastnosti od vylepšení, ktoré môžu počkať.
- Kritériá prijatia dohodni pred skúškou.
- Predpoklad o záujme zákazníkov označ ako predpoklad, kým ho neoveríš.
- Väčšie zmeny návrhu konzultuj s členom tímu zodpovedným za výrobu.

### ✅ Hodnota
Výstupom je spoločný zoznam požiadaviek a rozhodnutí, o ktorý sa tím môže oprieť pri návrhu, výrobe aj testovaní. Umožní vysvetliť, prečo má výrobok konkrétnu podobu a aké dôkazy ešte potrebujeme na posúdenie jeho funkčnosti.

### 🗂️ Taxonómia KNIFE
- **Kategória:** Produktový dizajn, tímová spolupráca
- **Typ:** Návod
- **Tagy:** požiadavky, dizajn, plánovanie, prototyp, overovanie

### 🌍 Referencie a podklady
- [Project Summary – cieľový zákazník, hodnoty a plán projektu](../project-summary/index.md)
- [Project Outcomes – miesto pre výsledky overenia](../project-outcomes/index.md)
- Vlastnú tabuľku požiadaviek, porovnanie variantov a spätnú väzbu doplníme počas návrhu a skúšok.

## Navigácia
- [🙋 About Me – predstavenie oboch autorov](../about-me/index.md)
- [↩️ Späť na prehľad výstupov](../index.md)
