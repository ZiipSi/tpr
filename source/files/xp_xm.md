# XP
## Kdy je vhodné?
V případě velmi dynamických změn softwaru a jeho požadavků, při malém vývojářském týmu, při použití technologií, jež umožňují automatické testování

## Hodnoty
### Komunikace
Je důležitá, protože v programování dochází k přenosu vědění z jednoho člena týmu na druhého a na další členy týmu. XP využívá komunikace z očí do očí s pomocí kreslení na tabuli apod.
### Jednoduchost
Drží se hesla „jaká je nejjednoduší věc, která funguje?“, účel tohoto je vyhnout se veškrým zbytečným záležitostem. Pouze provádět nezbytné věci jako je udržování designu co nejjednodušší na údržbu, podporu a reinženýring. Jednoduchost také spočívá k řešení pouze požadavků, o kterých víme a nesnažit se předpovídat budoucnost.
### Zpětná vazba
Díky neustálé zpětné vazbě jsou schopné týmy identifikovat slabé místa v jejich práci a vylepšit jejich práci a postupy. Také podporuje jednoduchý design a tvoření, vytvoří se jedna část, získá se zpětná vazba a pak se upraví dle feedbacku, když už se jde dál.
### Kuráž
Efektivní čelení strachu. Je třeba kuráž aby se vyzvedli a řešili organizační problémy, jež snižují efektivitu týmu. Je třeba kuráž aby se přestalo dělat něco, co nefunguje a zkusilo se něco úplně jiného. Je třeba kuráž na správný postoj ke zpětné vazbě, její správné přijmutí i když je to někdy těžké.
### Respekt
Je třeba aby se jednotliví členové týmu respektovali a komunikovali navzájem. Podávali si zpětnou vazbu, která vylepší jejich vztahy.


## Činnosti
Došlo ke změnám původních činností.
Originální jsou:
+ The Planning Game,
+ Small Releases,
+ Metaphor,
+ Simple Design,
+ Testing,
+ Refactoring,
+ Pair Programming,
+ Collective Ownership,
+ Continuous Integration,
+ 40-hour week,
+ On-site Customer,
+ Coding Standard.

## Extreme Programming Explained Embrace Change
Nyní budou představeny činnosti z druhé edice „Extreme Programming Explained Embrace Change“.

### Společně
Komunikace je klíčová v XP. Většina lidí se shodne na nejlepší komunikaci z očí do očí. Výhoda, pokud si může tým spolu sednout a komunikovat bez bariér a omezení.

### Celý tým
Je to multifunkční skupina lidí s potřebnými a nezbytnými rolemi pro vytvoření produktu tvoří jeden tým. Lidé, kteří mají určité potřeby a lidé, kteří jsou součástí uspokojování této potřeby denně pracují aby dosáhli určitého specifického cíle.
### Pracovní prostředí
Vytvoření pracovního prostředí, které umožňuje komunikaci s očí do očí. Ale také musí toto prostředí poskytovat určité soukromí, pokud je zrovna vyžadováno. Je také třeba aby všechny práce jednotlivých členů byly čitelné mezi jednotlivými členy. Aby před sebou v projektu nic neskrývali. Aby také neskrývali nic před ostatními z venčí.
### Energized work
Nejvíce efektivní vývoj a „myslící“ práce je konána, když je pracovník oddělen od všech vyrušení. Pojmem Energized work je míněno to, že je pracovník schopen se dostat fyzicky i psychicky do stavu soustředění. To mimo jiné znamená také nepřepracovanost, zůstat zdravý a dbát pokory vůči kolegům, aby i oni zůstali mentálně zdraví.
### Párové programování
Je velice zajímavá věc. Software je vytvářen pomocí dvou programátorů u jednoho počítače. U jednoho tvoření jsou tedy dva mozky a čtyři oči. Také dochází ke kontinuální kontrole kódu a rychlejší odezvě na vznikající problémy. Teamy, které využívají párové programování vykazují zlepšení kvality programování, také tato práce netrvá dvakrát déle, protože je tvořen kód čistější a jasnější.
### Příběhy
Popište co má vlastně produkt dělat, co je důležité pro zákazníky, jaké jsou souvislosti, proč se to vlastně dělá. Tyto popisky / příběhy by měly být krátké a výstižné. Stories mohou sloužit k budoucímu plánování. Tyto popisky také mohou sloužit jako základ a připomínky pro detailní konverzaci mezi členy teamu aby si uvědomili odpověď na otázku proč to děláme.
### Týdenní cyklus
Synonymum k iteraci. V XP první den v iteraci (týdnu) se tým setká a řeší jejich postup do data setkání. Zákazník vybere stories/příběhy, které by požadoval mít od týmu dodané v právě začínajícím týdnu. Tým se vyřeší, jaký přístup k řešení těchto příběhů zvolí. Důvod tohoto boxového dělení je, aby bylo vždy co předvést zákazníkovi a mohl se získat Feedback.
### Kvartální cyklus
Je to synonymum vydání softwaru. Cílem je udržet vždy týdenní práci v kontextu s celým projektem. Zákazník představí a udělí týmu požadavky na projekt na celý kvartál, což týmu umožní vytvořit si rozhled co je čeká a co musí pak naplánovat a k čemu směřují. Také toto kvartální rozplánování pomáhá ostatním zúčastněným stranám při představě, kdy jednotlivé části projektu budou hotové. Je také možné, že jednotlivé stories/příběhy navrhnuté pro celý kvartál se časem také mění. Tomu pomáhá týdenní cyklus, kde se o těchto změnách informuje, debatuje a pomáhá to udržet informovanost o projektu a minimalizuje překvapení.
### Uvolněnost
Celým smyslem uvolněnosti je vložit mezi důležité části a práce také nějaké odpočinkové s nízkou prioritou, které pokud dochází k zaostávání v harmonogramu, mohou být vynechány
### Ten minute build
Cílem je automaticky vytvořit build celého systému za deset minut. Také provést všechny testy v této době. Je doporučeno 10 minut, protože pokud je tento čas delší, je větší šance, že nebude prováděn pravidelně, což také znamená, že bude větší rozpětí mezi vzniklou a opravenou chybou. Smyslem je dostat tým do stádia, kdy budou automatizovat své buildy tak, že budou pravidelné a minimalizuje se čas chyba-oprava.
### Průběžná integrace
Je to činnost, kdy je kód testován ihned po vložení do větší části jiného, většího celku kódu. Benefit skýtá v tom, že je možné opravit chyby a problémy s integrací dříve. XP oproti systémům - „pokud něco bolí, vyhni se tomu co nejdéle“ využívá „pokud to bolí, dělej to častěji“. Hodně týmů nemá rádo integraci, protože dochází k nacházení dědičných problémů z jedné části na druhou. Řešení je takové, že pokud dochází k integraci častěji, je to po menších kouscích a tím pádem je snazší najít chyby, protože jich je většinou méně, než více u větší části kódu. Průběžná integrace vyžaduje disciplínu a je silně závislá na Ten minute build a test first development.
### Test-First programming
Místo toho, aby byl systém vývoj kódu -> napsat testy, vymyslet testy -> spustit testy je využit systém napsat automatický neprocházející test -> spustit neproch. Test -> vyvinout kód, který projde tímto testem -> spustit test -> opakovat. Stejně jako při průběžné integraci dochází ke snižování doby mezi cyklem feedbacku, chyby a opravy chyby. Tudíž snížení chyb, které se vyskytují v průběžné produkci.
### Incremental design
Spočívá ve vytvoření části projektu dopředu, ale jen části, aby byla jasná perspektiva a proč se vlastně dělají detailní části, do kterých se po tomto vytvoření rozhledu nastupuje. Tento přístup umožňuje snížení ceny změn. Pokud je nutnost pro rozhodování umožňuje se rozhodovat na základě nejnovějších informací.
## Role
### Zákazník
+ Je zodpovědný za všechny obchodní rozhodnutí jako jsou:
+ Co má systém dělat? Jaké features jsou zahrnuty a co čeho dosahují, proč?
+ Jak zjistíme, že systém je hotov. Jaké jsou kritéria dokončení?
+ Kolik je nutné utratit pro vytváření systému? Jaké je financování?
+ Co máme dělat dál? Jaká funkce bude vytvořena po jaké funkci.
Zákazník ve stylu XP je aktivní a prakticky se také stane částí týmu. Většinou je to jedna osoba ale po čase se ukázalo, že jedna osoba není schopna dodat dostatečné informace týmu o celém projektu. Je důležité aby zákazník měl kompletní představu o tomto projektu a věděl, kam se má projekt ubírat.
### Vývojář
XP nemá přímo definované jednotlivé role krom zákazníka a některých dalších. Vývojáři jsou zodpovědní za realizaci stories a požadavků zákazníka.
### The Tracker
Pouze v některých týmech. Většinou jeden z vývojářů, jehož role je částečně také tracker a ne vývojář. Cílem této role je vést přehled o relevantních metrikách, jež jsou pro tým nutné z hlediska udržení přehledu o pokroku a identifikování silných, slabých stránek a částí, kde je třeba se vylepšit. Není to klíčová role.
### The Coach
Pokud se začíná v týmu XP zavádět, je vhodné mít trenéra. Většinou se jedná o externího konzultanta nebo někoho ve společnosti, ale ne z myšleného týmu. Tento Coach už má zkušenosti s XP a slouží jako mentor týmu.

# XM
Kocept založen na Agility - hbitosti. Nejdříve pouze v SW části ale pak do celkové produkce. Tento projektový rámec je podobný jako XP ve své opakovanosti - iteracích, a incremental development - přírůstcích vývoje. Pevně založen na Scrumu. Staví na 10 základních principech.

Agility approach byl vymyšlen z důvodu problémů/krize ve vývoji software.
**Velmi často přicházeli problémy jako:**
+ Cena SW převyšovala rozpočet,
+ Nedodržení deadline,
+ Software byl velmi neefektivní,
+ Software byl nekvalitní,
+ SW nesplňoval požadavky,
+ Projekty byly neřiditelné a bylo složitá udržitelnost kódu,
+ SW nebyl nikdy dodán,
+ Vývoj HW každý den, tudíž nutná reakce SW.

Je více důvodů této krize a problémů např. neustálá změna požadavků ze strany zákazníka nebo rychlá změna okolního prostředí, HW apod.
Toto mělo za následek vytvoření tzv. „Manifesto for Agile Software Development“. Je vidět, že se toto zajímá převážně o SW. Ale pokud dojde k přeformulování některých částí, je toto možné aplikovat i na výrobní procesy.
**Nyní upravené principy:**
+ Naší nejvyšší prioritou je uspokojení zákazníka pomocí včasného a kvalitního dodání hodnotného produktu.
+ Změny požadavků jsou možné i v pokročilém stádiu vývoje. Díky těmto změnám se vylepšuje pozice zákazníka a jeho výhoda na trhu.
+ Často dodávejte potřebné funkční moduly nebo prototypy. Často v rámci měsíců nebo týdnů. Preferujte však kratší rozestupy mezi prototypy.
+ Lidé z business oddělení a vývojáři musí pracovat společně. Nejlépe denně.
+ Vytvářejte projekty s motivovanými účastníky. Dejte jim prostor a podporujte je. Také jim věřte, že opravdu práci udělají.
+ Nejlepší způsob komunikace je mezi očima.
+ Fungující produkt je hlavní metrika postupu - progressu.
+ Agilní proces vyzdvihává neustálý vývoj. Sponzoři - investoři, vývojáři a uživatelé by jejich zapálení měli udržet do nekonečna.
+ Je třeba udržovat neustálou pozornost vůči technické dokonalosti. Dobrý design napomáhá vylepšení hybnosti projektu - stále dopředu.
+ Jednoduchost je důležitá. Umění maximalizovat množství práce, která není udělána, protože není třeba, byla by zbytečná.
+ Nejlepší design, požadavky, návrhy jsou produkovány samořiditelnými týmy.
+ V pravidelných intervalech dochází k vyhodnocení, jak být více efektivní. Následně dochází k upravení chování a procesů aby se efektivita zvýšila.

## Základy ze Scrum
### Optimizováno pro změnu
Při použití XM je produkce schopná se aklimatizovat a přizpůsobit změně už při vytváření produktu. Vysvětlení: je možnost vytvářet upravovaný produkt beze změny výrobní linky
### Objektivně orientované, modulární architektura
Využití maximální modularity architektury. Modularizace produktu umožňuje snazší úpravy v budoucnu.
### Test Driven Development
Jedná se o návrh komponent při využití různých principů.
S návrhem komponent, systému současně vytvářet testy a testovat je. Klade se důraz na co nejvyšší míru automatizace aby došlo ke snížení nákladů na minimum.
Co nejjednodušší návrh aby se co nejjednodušeji testoval.
Iterativní návrh, jehož středem je neustálý vývoj a zlepšování.
### Contact First Design
Před návrhem samostatných komponent musí být vytvořeno jejich vzájemné propojení.
### Iterate the Design
Je vhodné vylepšovat návrh a dělat různé prototypy, iterativním způsobem a následně vylepšovat. Zjednodušovat návrh tak, aby byl jednoduchý, elegantní a aby v něm bylo díky tomu méně chyb. Opakovat tento proces dokud návrh není to nejlepší, co je možné dodat.
### Agile Hardware Design Patterns
Vzory. Pokud dochází k využívání vzorů, aplikuje se známé řešení na známý problém, který jsme už například jednou vyřešili.
### Continuous Integration Development
Činnost, při které dochází z kompletování a spojení jednotlivých funkčních částí návrhu od jednotlivých vývojářů - pracovníků, do hlavní větve. Toto je prováděno několikrát denně. Umožní to tedy snížení iteračních problémů.
### Continuous Deployment Development - Continuous Delivery
Důležitý poznatek, že kvalita a správná funkčnost je důležitá u zákazníka, ne ve vývojářské místnosti u nás.
### Scaling Patterns
Schopnost upravení postupu návrhu/výroby pro malé nebo velké cíle.
### Partner Patterns
Schopnost zahrnout již funkční produkty nebo zkušenosti třetích stran.


# Zdroje
## XP
+ [Agile Alliance](https://www.agilealliance.org/glossary/xp/#q=~(infinite~false~filters~(postType~(~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'xp))~searchTerm~'~sort~false~sortDirection~'asc~page~1)
)
+ [Extreme Programming](http://www.extremeprogramming.org)

## XM
+ [M. Molhanec, "Extreme manufacturing — Agility to greater productivity and quality," Proceedings of the 2014 37th International Spring Seminar on Electronics Technology, Dresden, Germany, 2014, pp. 164-169, doi: 10.1109/ISSE.2014.6887585.](https://ieeexplore.ieee.org/document/6887585)

# Upozornění
Tento text slouží jako pomůcka pro prezentující studenty. Jmenovitě pro studenty Petr Zakopal a Jan Hnát. Můžou se zde vyskytovat chyby a jsou to pouze pomůcka k nahlížení při prezentaci. Nejedná se o oficiální vydávanou práci. Všechny informace jsou brány z uvedených zdrojů.

Určité termíny jsou volně přeloženy, aby prezentace nebyla plná anglických slov. Některé nebylo vhodné překládat.
