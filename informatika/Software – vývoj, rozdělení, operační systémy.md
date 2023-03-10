---
layout: default
title: Software – vývoj, rozdělení, operační systémy
permalink: /informatika/software-vyvoj-rozdeleni-operacni-systemy/
---

## Vývoj softwaru

Vývoj softwaru je proces **koncipování**, **popisu**, **specifikace**, **návrhu**, **programování**, **dokumentace**, **testování** a **oprav chyb** používaný při vytváření a údržbě aplikací, frameworků a jiných softwarových komponent. Jádrem vývoje softwaru je „programování“ – proces vytváření a údržby zdrojových kódů, ale v širším smyslu zahrnuje vše, co se používá od návrhu koncepce požadovaného softwaru až po jeho konečné nasazení, obvykle v plánovaném a strukturovaném procesu. Vývoj softwaru tak může zahrnovat výzkum, nový vývoj, prototypování, úpravy, znovupoužití, re-engineering, údržbu a všechny další činnosti, které přispívají k vytvoření softwarového produktu.

### Účely vývoje software

Software se vyvíjí pro různé účely; třemi nejobvyklejší jsou:
- Má splňovat specifické potřeby určitého zákazníka nebo firmy (v případě zakázkového softwaru).
- Má uspokojovat vnímanou potřebu nějaké skupiny potenciálních uživatelů (v případě komerčního softwaru a softwaru s otevřeným zdrojovým textem).
- Je určený pro vlastní použití (například vědec může vytvořit software pro automatizaci svých rutinních úkolů).

### Řízení procesu vývoje software

Potřeba lepšího řízení kvality procesu vývoje softwaru vedla k rozvoji softwarového inženýrství, které na proces vývoje softwaru aplikuje systematický přístup, jež je základem inženýrského paradigmatu.

Existují různé přístupy k řízení softwarových projektů známých jako modely životního cyklu vývoje softwaru, metodologie, procesy nebo modely. Tradičním přístupem je vodopádový model, který je protikladem mnoha novějších metodik agilního vývoje softwaru.

Vývoj softwaru se též liší dle toho, zda se jedná o vývoj vestavěného softwaru, tj. vývoj softwaru pro vestavěné systémy, a systémového software. Zatímco první se používá například pro řízení elektronických výrobků, a tak vyžaduje, aby byl vývojový proces integrován s vývojem příslušného fyzického výrobku, druhý vytváří prostředí pro běh aplikací a často i pro samotný proces programování, a proto se obvykle vyvíjí odděleně.

### Metodologie vývoje softwaru

Proces vývoje softwaru (známý také jako metodika, model nebo životní cyklus vývoje softwaru) je rámec používaný pro strukturování, plánování a řízení procesu vývoje informačních systémů. V průběhu let bylo vyvinuto množství metodik, z nichž každá má své silné a slabé stránky. Žádná metodika vývoje softwaru nemusí být vhodná pro použití ve všech druzích projektů.

**Většina metodologií však sdílí nějaké kombinace následujících fází vývoje softwaru:**

- Analýza problému
- Průzkum trhu
- Získávání požadavků pro navrhované obchodní řešení
- Vytvoření plánu nebo návrhu softwarového řešení (Objektově orientovaná analýza a design)
- Implementace softwaru (programování/kódování, ladění
- Testování software
- Nasazení softwaru (Instalace, Release management)
- Údržba softwaru a oprava chyb

Tyto fáze se často souhrnně označují jako životní cyklus vývoje softwaru nebo SDLC.

Různé přístupy k vývoji softwaru mohou provádět tyto fáze v různém pořadí a věnovat různým fázím více nebo méně času. Také podrobnost dokumentace vytvářené v každé fázi vývoje softwaru se mění.

#### Vodopádový přístup

U vodopádového a od něj odvozených přístupů jsou všechny fáze vývoje prováděný postupně. Vývojáři, popř. zadavatelé softwaru se snaží posoudit všechna rizika vývoje a vytvořit si podrobný plán softwaru ještě před zahájením samotné implementace (kódování). Tím vším se snaží vyhnout jakékoliv rozsáhle změně návrhu a opakovanému kódování v pozdějších fázích plánování životního cyklu vývoje softwaru. Rizikem zde však je, že se v průběhu vývoje software objeví nedomyšlené detaily nebo se nějak zásadně změní situace na trhu či trendy v oboru. Na takové situace obvykle tento přístup nedokáže pružně reagovat. Ilustruje to i fakt, že statisticky pouhých 15 % takto řízených projektů je dokončeno bez zdražení, včas a s udržením požadované kvality a funkcionality.

#### Agilní přístup

Vývojáři zde tedy obvykle rozdělují vývoj aplikace či softwaru do jednotlivých cyklů (sprintů), během kterých je vždy zhotovena nějaká funkcionalita produktu. První cíl vývoje bývá obvykle tzv. minimum viable produkt (minimální životaschopný produkt), který se zaměřuje na základní problém, kvůli kterému je software vyvíjen. Na konci každého cyklu je vždy produkt s danou funkcionalitou ukázán klientovi a při dosažení fáze MVP je obvykle předán k otestování zákazníkům, popř. rovnou uveden na trh. Podle zpětné vazby klienta a zákazníků je produkt dále rozvíjen, mění se designově, jsou přidaný žádané funkcionality apod. Agilní přístup tedy zahrnuje aktivní začlenění klienta i zákazníků již do raných fází vývoje produktu. Výhodou je, že se software už od samého počátku vyvíjí přesně podle představ klienta i cílové skupiny. Nic se nevyvíjí zbytečně a vývoj pružněji reaguje na reálné potřeby zákazníků i změny na trhu.

### Volba přístupu

Různé metodologie mají významné výhody a nevýhody a nejlepší přístup k řešení problému pomocí softwaru bude často záviset na typu problému. Pokud je problém dobře pochopen a řešení lze efektivně předem naplánovat, klasický „vodopádový přístup“ může fungovat nejlépe. Tento přístup se proto volí častěji u neinovativních softwarů. Pokud je naopak problém nejednoznačný, jde o inovativní software, který reaguje na dosud neuchopené problémy, a strukturu softwarového řešení si nelze snadno představit, pak může být mnohem vhodnější agilní přístup.

## Rozdělení softwaru

- **Aplikační software** - Aplikační software je nejběžnějším typem softwaru, je to balík počítačového softwaru, který vykonává konkrétní funkci pro uživatele nebo v některých případech pro jinou aplikaci. Aplikace může být samostatná, nebo se může jednat o skupinu programů, které aplikaci pro uživatele spouštějí. Příkladem moderních aplikací jsou kancelářské balíky, grafický software, databáze a programy pro správu databází, webové prohlížeče, textové procesory, nástroje pro vývoj softwaru, grafické editory a komunikační platformy.
- **Systémový software** - Tyto softwarové programy jsou určeny k provozu aplikačních programů a hardwaru počítače. Systémový software koordinuje činnosti a funkce hardwaru a softwaru. Kromě toho řídí činnost hardwaru počítače a poskytuje prostředí nebo platformu pro práci všech ostatních typů softwaru. Operační systém je nejlepším příkladem systémového softwaru; řídí všechny ostatní počítačové programy. Dalšími příklady systémového softwaru jsou firmware, překladače počítačových jazyků a systémové nástroje.
- **Software ovladačů** Tento software, známý také jako ovladače zařízení, je často považován za typ systémového softwaru. Ovladače zařízení řídí zařízení a periferie připojené k počítači a umožňují jim vykonávat jejich specifické úkoly. Každé zařízení připojené k počítači potřebuje ke své funkci alespoň jeden ovladač zařízení. Příkladem může být software dodávaný s jakýmkoli nestandardním hardwarem, včetně speciálních herních ovladačů, a také software umožňující použití standardního hardwaru, jako jsou úložná zařízení USB, klávesnice, sluchátka a tiskárny.
- **Middleware** Termín middleware označuje software, který je prostředníkem mezi aplikačním a systémovým softwarem nebo mezi dvěma různými druhy aplikačního softwaru. Například middleware umožňuje systému Microsoft Windows komunikovat s aplikacemi Excel a Word. Používá se také k odeslání požadavku na vzdálenou práci z aplikace v počítači s jedním druhem operačního systému do aplikace v počítači s jiným operačním systémem. Umožňuje také novějším aplikacím pracovat se staršími.
- **Programovací software** Počítačoví programátoři používají programovací software k psaní kódu. Programovací software a programovací nástroje umožňují vývojářům vyvíjet, psát, testovat a ladit další programy. Mezi příklady programovacího softwaru patří assemblery, 
kompilátory, ladicí programy a interprety.

![Rozdělení softwaru](https://i.ibb.co/LZYQhGc/software-stack.png)

## Operační systémy

- **Rozhraní mezi uživatelem a hardwarem počítače.**

### Typy operačních systémů (OS)

- Dávkový OS - sada podobných úloh je uložena v hlavní paměti k provedení. Úloha se přiřadí procesoru, až když se dokončí provádění předchozí úlohy.
- Víceprogramový OS - V hlavní paměti jsou uloženy úlohy, které čekají na čas procesoru. OS vybere jednu z nich a přiřadí ji procesoru. Kdykoli vykonávaný proces potřebuje čekat na nějakou jinou operaci (např. I/O), OS vybere z fronty úloh jiný proces a přiřadí jej CPU. Tímto způsobem procesor nikdy nezůstane nečinný a uživatel získá možnost provádět více úloh najednou.
- Víceúlohový OS - Víceúlohový OS kombinuje výhody víceprogramového OS a plánování procesoru, aby bylo možné provádět rychlé přepínání mezi úlohami. Přepínání je tak rychlé, že uživatel může s každým programem komunikovat v průběhu jeho běhu
OS s rozdělením času - Systémy s rozdělením času vyžadují interakci s uživatelem, který dává OS pokyny k provádění různých úloh. OS reaguje výstupem. Pokyny jsou obvykle zadávány prostřednictvím vstupního zařízení, jako je klávesnice.
- OS reálného času - OS reálného času jsou obvykle vytvářeny pro specializované systémy, které mají ve stanovených termínech splnit určitý soubor úloh.

### Vlákna (Threads)

Vlákna, která se používají v systémech OS, jsou určena pro práci s informacemi, které jsou v nich obsažené: **Vlákno je lehký proces a tvoří základní jednotku využití procesoru**. Proces může vykonávat více úloh najednou tím, že zahrnuje více vláken.

Vlákno má vlastní programový čítač, sadu registrů a zásobník.
Vlákno sdílí s ostatními vlákny téhož procesu prostředky kód, datovou část, soubory a signály.
Nové vlákno nebo podřízený proces daného procesu lze zavést pomocí systémového volání fork(). Proces s n systémovými voláními fork() generuje 2<sup>n</sup>-1 podřízených procesů. Existují dva typy vláken:

- Uživatelská vlákna
- Vlákna kernelu

### Procesy

Proces je prováděný program. Hodnota programového čítače (PC) udává adresu další instrukce prováděného procesu. Každý proces je reprezentován blokem řízení procesu (PCB).

### Nejznámější operační systémy

#### Linux (GNU/Linux, Android)

**Linux (GNU/Linux)** je označení pro svobodný a otevřený počítačový operační systém, který je založený na linuxovém jádru. Linuxové systémy jsou šířeny v podobě distribucí, které je možné nainstalovat nebo používat bez instalace (tzv. live CD). Používané licence umožňují systém zdarma a velmi volně používat, distribuovat (kopírovat, sdílet) i upravovat. Tím se odlišuje od proprietárních systémů (např. Windows či macOS), za které je nutné platit a dodržovat omezující licence.

**Android** je mobilní operační systém založený na jádře Linuxu, který je dostupný jako otevřený software (open source). Obvykle je doplněn o proprietární software, který poskytuje důležité služby.[3] Je používán na smartphonech, tabletech, chytrých televizích a dalších zařízeních. Vývoj Androidu vede firma Google pod hlavičkou konsorcia firem Open Handset Alliance a výrobci různých zařízení mohou Android upravovat při dodržení stanovených podmínek. Takto upravený systém zpravidla vývojáři nazývají jinak (One UI v telefonech Samsung, MIUI od Xiaomi nebo dobrovolníky udržovaný LineageOS).

#### Windows

Windows je v informatice označení pro několik různých operačních systémů od firmy Microsoft. Všechny mají grafické uživatelské rozhraní, avšak liší se použitým jádrem systému, úrovní podpory multitaskingu (současného běhu více úloh najednou) i používanými knihovnami a účelem použití.

#### macOS

macOS (dříve OS X a původně Mac OS X) je unixový operační systém vyvíjený a prodávaný společností Apple Inc. od roku 2001. Je to primární operační systém pro počítače Mac společnosti Apple. V rámci trhu stolních a přenosných počítačů je druhým nejrozšířenějším operačním systémem pro stolní počítače, hned po Microsoft Windows a před ChromeOS.

#### FreeBSD

FreeBSD je svobodný unixový operační systém, který vznikl z BSD verze Unixu vyvinutého na Kalifornské Univerzitě v Berkeley. První verze byla vydána v roce 1993.

FreeBSD je vyvíjen jako kompletní operační systém – jádro, ovladače zařízení a všechny uživatelské utility jako například shell jsou vyvíjeny ve stejném stromu systému pro správu verzí zdrojových kódů (SVN). V tomto se odlišuje od Linuxu, ve kterém je typicky každý program vyvíjen jinou skupinou vývojářů, a ty jsou poté vydány jako kompletní operační systém jinými vývojáři ve formě linuxových distribucí.
