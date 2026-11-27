# Příklad mikčního deníku: jeden celý den, řádek po řádku
Source: https://fluidbalanceapp.com/cs/blog/bladder-diary-example/
Published: 2026-09-28 · Návod · Denis Zinin, vývojář aplikace Mikční deník: Fluid Balance. Není lékař.

Ve zkratce:
Níže je příklad mikčního deníku za jeden celý den, řádek po řádku: asi patnáct záznamů, kde každý nápoj má svůj objem, každá cesta objem nebo zaškrtnutí „neměřeno“, jsou tu časy ulehnutí a vstávání a tam, kde se něco stalo, poznámka. Den je vymyšlený, takže jeho součty nejsou cíle. Rozvržení jde po deníku Urology Care Foundation a kartách NHS, jejichž vlastní formuláře ukazují jen jeden dva ukázkové řádky. Co má ten den ukázat:

- Celý den je asi patnáct řádků: každý nápoj s objemem, každá cesta s objemem nebo zaškrtnutím, časy ulehnutí a vstávání a poznámka tam, kde se něco stalo.
- Den níže je vymyšlený. Jeho součty nejsou cíle a není tu norma, se kterou by se daly srovnat.
- Lékař z něj čte počet cest ve dne a v noci, objemy, rozložení nápojů, poznámky a to, jestli je den úplný.

Formuláře ambulancí ukazují jeden dva ukázkové řádky: deník Urology Care Foundation má jediný řádek s plechovkou limonády a únikem moči při smíchu,[1] karta NHS Gloucestershire ukazuje ráno s hrnkem čaje a únikem,[2] fyzioterapeutická karta ze Sussexu tři ranní řádky se součty.[3] Užitečné, ale nikomu den netrvá tři řádky. Tady je celý vymyšlený den ve formátu našeho [formuláře k vytištění](https://fluidbalanceapp.com/bladder-diary-template/) a za ním to, co každá jeho část lékaři říká. Čísla patří tomuhle příkladu a ničemu jinému; na této stránce není norma, se kterou by se dala srovnat.

## Jak vypadá celý den deníku?

Vyplněný příklad mikčního deníku. Den 1 ze 7. Šel jsem spát 22:45. Vstal jsem 7:00.

| Čas | Vypito (ml) | Co | Vymočeno (ml nebo ✓) | Noc | Poznámka |
|---|---|---|---|---|---|
| 7:05 | | | 350 | | první ráno |
| 7:20 | 250 | čaj | | | |
| 8:30 | 200 | káva | | | |
| 9:40 | | | ✓ | | ve spěchu, malý únik |
| 11:00 | 500 | voda | | | |
| 11:45 | | | 220 | | |
| 13:10 | 330 | džus | | | |
| 13:30 | | | 180 | | silné nucení |
| 15:00 | 250 | čaj | | | |
| 16:20 | | | 260 | | |
| 18:00 | 250 | voda | | | |
| 19:30 | 200 | pivo | | | |
| 20:15 | | | 300 | | |
| 22:30 | | | 150 | | před spaním |
| 3:10 | | | 180 | ✓ | |

Patnáct řádků, jedna strana. Den běží od vstávání do vstávání, takže cesta ve 3:10 patří ke dni 1, i když se datum změnilo.

## Řádek po řádku

**7:05, 350 ml, „první ráno“.** První cesta po vstávání. Noční není, protože noc deníku skončila v 7:00, ale podle definice ICS vznikla tehdy vymočená moč přes noc a přičítá se k nočnímu objemu,[5] proto se měří a nezaškrtává. Na papíře je to prostě první řádek dne.

**7:20 a 8:30, čaj a káva.** Nápoje s objemem a druhem. Objem pochází z toho, že se hrnek jednou změřil; druh tu je, protože ho formuláře ambulancí chtějí.[1,2]

**9:40, zaškrtnutí, „ve spěchu, malý únik“.** Na měření nebyl čas, takže zaškrtnutí místo objemu, a cesta se stejně počítá do denního počtu cest.[2] Poznámka zachycuje únik moči s přibližnou velikostí. Na formuláři se sloupci na úniky by to bylo „malý“ nebo „+“; v prostém deníku je to poznámka s časem.

**11:00, 500 ml vody.** Lahev, takže objem je na ní vytištěný.

**13:30, 180 ml, „silné nucení“.** Změřená cesta se zapsaným nucením: náhlá, těžko odložitelná potřeba.[4] Zapsáno hned, dvěma slovy, víc není třeba.

**19:30, 200 ml piva.** Alkohol je na papíře nápoj jako každý jiný: objem, druh, čas. Deník má ukázat běžný večer, ne uklizený.

**22:30, 150 ml, „před spaním“.** Poslední cesta před časem ulehnutí, který je nahoře na straně. Je to denní cesta; noc začíná ve 22:45.

**3:10, 180 ml, zaškrtnuto jako Noc.** Mezi ulehnutím a vstáváním, takže dostane zaškrtnutí. Právě tenhle řádek umožňuje noční počet; deník bez časů ulehnutí a vstávání tuhle cestu od té ve 22:30 nerozliší.

## Kolik ten den dělá dohromady

Jen proto, že to příklad dovolí: 1 980 ml vypito v sedmi nápojích; 1 640 ml vymočeno v sedmi změřených cestách, plus jedna cesta zaškrtnutá bez objemu; celkem osm cest, jedna z nich v noci. Na formuláři ambulance vás možná požádají, abyste tyhle součty napsali do spodního řádku; v aplikaci se objeví na dnešní obrazovce a ve zprávě, aniž by někdo sčítal. Nejsou to cíle a nejsou typické pro nikoho konkrétního. Jejich jediný úkol tady je ukázat, jak vypadá úplný den, když se spočítá.

## Co v něm lékař vidí

Osm cest s časy, jedna v noci, jedna neměřená. Sedm změřených objemů, od 150 do 350 ml. Nápoje rozložené od 7:20 do 19:30 se zapsanými druhy. Dvě poznámky, únik moči se spouštěčem a nucení. Časy ulehnutí a vstávání, takže jde noc oddělit ode dne. A den, který je úplný od probuzení do probuzení — to je první věc, kterou kontrolují, protože samotná paměť plete i počet cest.[6] Co ta fakta znamenají, to je na návštěvě; úkolem deníku bylo je přinést.

## Váš den bude vypadat jinak

Víc řádků nebo míň, jiné nápoje, jiné časy. Stejný zůstává formát: každý nápoj, každá cesta, objem nebo zaškrtnutí, dva časy, které noc rámují, a poznámka tam, kde se něco stalo. [Jak si vést mikční deník](https://fluidbalanceapp.com/blog/how-to-keep-a-bladder-diary/) popisuje návyky, které k tomu vedou, a [jak doma změřit množství moči](https://fluidbalanceapp.com/blog/how-to-measure-urine-output-at-home/) odměrku.

## Otázky

**Kam zapsat první ranní cestu?**
Jako první řádek nového dne, za váš čas vstávání, s objemem, pokud jste měřili. Není to noční cesta, protože jste už byli vzhůru, ale podle definice ICS vznikla tehdy vymočená moč přes noc a počítá se do nočního objemu, takže se vyplatí ji změřit. Třídění je na lékaři.

**Musím součty dělat sám?**
Ne. Formuláře ambulancí mají řádek na součty a některé o ně žádají, ale lékař je může sečíst sám; karta NHS to tak říká. Pokud používáte aplikaci, součty, počet cest i noční počet se spočítají za vás. Co se delegovat nedá, jsou samotné řádky.

**Co když má můj den dvacet řádků?**
Vezměte další stranu a pokračujte. Den s mnoha řádky je úplný den a jen takový lékař chce; vynechávat řádky, aby se to vešlo, je ta chyba. Náš formulář má na A4 24 řádků na stranu a aplikace limit nemá.

## Zdroje

1. Urology Care Foundation. Overactive bladder diary. Linthicum, MD: American Urological Association; 2025. https://www.urologyhealth.org/documents/Product-Store/English/Overactive-Bladder-OAB-Bladder-Diary.pdf
2. Gloucestershire Hospitals NHS Foundation Trust. Frequency volume chart: three day bladder diary. Patient information leaflet GHNHSFT/X941/05_16. https://www.gloshospitals.nhs.uk/documents/22054/X941_05_16_Frequency_Volume_Chart.pdf
3. University Hospitals Sussex NHS Foundation Trust. Bladder record chart: pelvic health physiotherapy patient information. Reference 2198; 2023. https://www.uhsussex.nhs.uk/wp-content/uploads/2023/03/Bladder-Record-chart.pdf
4. Abrams P, Cardozo L, Fall M, et al. The standardisation of terminology of lower urinary tract function: report from the Standardisation Sub-committee of the International Continence Society. Neurourol Urodyn. 2002;21(2):167–178. https://doi.org/10.1002/nau.10052
5. van Kerrebroeck P, Abrams P, Chaikin D, et al. The standardisation of terminology in nocturia: report from the Standardisation Sub-committee of the International Continence Society. Neurourol Urodyn. 2002;21(2):179–183. https://doi.org/10.1002/nau.10053
6. Stav K, Dwyer PL, Rosamilia A. Women overestimate daytime urinary frequency: the importance of the bladder diary. J Urol. 2009;181(5):2176–2180. https://doi.org/10.1016/j.juro.2009.01.042

Tento text vysvětluje, jak si vést deník. Je to obecná informace od vývojáře aplikace, ne lékařská rada: co váš deník znamená, rozhoduje lékař. Deník si vedete sami. Není to zdravotnický dokument.
