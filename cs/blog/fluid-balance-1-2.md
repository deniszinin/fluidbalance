# Mikční deník: Fluid Balance 1.2 je v App Store
Source: https://fluidbalanceapp.com/cs/blog/fluid-balance-1-2/
Published: 2026-10-26 · Novinka · Denis Zinin, vývojář aplikace Mikční deník: Fluid Balance.

Verze 1.2 je v App Store a je skoro celá o jedné věci: teď si můžete zapsat, jak silné bylo nucení před mikcí. Zbytek jsou drobná vylepšení pro pohodlí.

## Jak silné bylo nucení?

V mikčním deníku při hyperaktivním močovém měchýři a únicích se nucení hodnotí před každou mikcí — a aplikace to dosud neuměla. Abyste to mohli použít, zapněte to v nastavení: **Síla nucení**. Od té chvíle dostane každý záznam o mikci odznak **Ohodnotit nucení** s pěti stupni:

- **0** Bez nucení
- **1** Běžné nucení
- **2** Silné nucení
- **3** Sotva jsem to stihl(a)
- **4** Nestihl(a) jsem to


Stupeň 4 znamená, že moč vyšla cestou na záchod; proto zůstává připnutý ke své mikci místo toho, aby se stal samostatnou událostí, kterou by vaše počty musely potom srovnávat.

**Neohodnoceno není nula.** Záznam, který jste neohodnotil, neukládá vůbec nic — totéž pravidlo jako „Neměřeno“ u objemu. Den bez hodnocení ukáže ve zprávě pomlčku, ne řadu nul, a průměry se počítají ze záznamů, které hodnocení opravdu nesou. Nula v této aplikaci vždycky znamená, že jste zvolil „Bez nucení“.

**Kde se hodnocení objeví.** V deníku vedle záznamu. Ve zprávě v PDF jako dva řádky — stupně 3–4 za den a stupeň 4 za den — plus sloupec v tabulce po dnech. V CSV jako nový sloupec na konci, připojený a nevložený doprostřed, aby tabulka nebo skript postavené na starém exportu dál fungovaly. Pokud ve zvoleném období není ohodnoceno nic, zpráva ten oddíl vynechá, místo aby tiskla prázdný.

Dokud to nezapnete, zůstává záznam dvě klepnutí.

## Připomenutí, které přestane otravovat

Záleží nám na vaší pozornosti: připomenutí se nemá změnit v šum na pozadí. Dřív chodilo každý den ve zvolený čas, dokud byla aplikace nainstalovaná. Teď přijde jen ve dnech bez záznamů, a po týdnu bez jediného se samo pozastaví. Deník se vede tři až sedm dní; připomenutí, které chodí ještě druhý měsíc, je jen oznámení k vypnutí.


## Snadná cesta ke včerejšku

Dokud je dnešek ještě prázdný, nese obrazovka Dnes kartu se včerejšími záznamy a jedno klepnutí ten den otevře. Nejčastější způsob, jak přijít o den deníku, je vzpomenout si na něj až druhý den ráno.


## Dále v 1.2

- **12- nebo 24hodinový formát**, jak je vám milejší, v nastavení.
- **Plná podpora iPhonu Duo.**
- **Velký widget na plochu**, vedle malého a toho na uzamčené obrazovce.
- **Čtyři nové jazyky:** polština, švédština, čeština a tradiční čínština, aplikace jich má tedy čtrnáct. Zpráva v PDF se překládá spolu s rozhraním; CSV zůstává anglicky.
- **Rychlejší, když se nasbíralo hodně záznamů**, a k tomu řada drobných oprav.

## Co zůstalo stejné

Štítek o soukromí v App Store zní dál „Nesbírá žádná data“: žádný účet, žádný server, žádná analytika uvnitř aplikace, žádný cizí kód. Záznamy žijí na vašem zařízení a, pokud to zapnete, ve vaší vlastní soukromé databázi iCloud — podrobnosti má [zásady ochrany soukromí](https://fluidbalanceapp.com/privacy/). Aplikace pořád nestanovuje diagnózy, neporovnává vaše záznamy s žádnou normou a nepřipomíná vám pití; síla nucení je číslo, které jste zadal vy, a co znamená, je rozhovor s lékařem. Zapisování, Dnes, statistiky, widgety, Apple Watch, iCloud i export do CSV zůstávají zdarma a Pro je pořád jednorázový nákup, ne předplatné.

## Požadavky

iPhone s iOS 18 nebo novějším, iPhone Duo včetně. Apple Watch s watchOS 11 nebo novějším. Na iPadu běží jako aplikace pro iPhone. Kategorie v App Store: Zdraví a medicína.

Dotazy nebo přání: [nápověda](https://fluidbalanceapp.com/support/) má odpovědi na ty časté a adresu, kam napsat.
