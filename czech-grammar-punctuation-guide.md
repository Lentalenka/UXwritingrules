# Pravidla české gramatiky a interpunkce pro bankovní aplikace

Příručka shrnuje pravidla české gramatiky, pravopisu, interpunkce a typografie, která je třeba dodržovat při psaní UX textů v bankovních a finančních mobilních a webových aplikacích. Vychází z doporučení Ústavu pro jazyk český AV ČR (ÚJČ), normy ČSN 01 6910 a zavedené praxe v českém digitálním prostředí.

---

## 1. Vykání – velké V, nebo malé v?

### Oficiální pravidlo ÚJČ

Psaní zájmen `Vy`, `Vám`, `Váš` s velkým písmenem je předepsáno jako projev úcty a zdvořilosti **v dopisech a korespondenci**, ať už se obrací k jedné osobě, více osobám, nebo kolektivu.

### Pravidlo pro digitální produkty

Pravidlo vzniklo pro tradiční korespondenci a **explicitně nepokrývá** digitální produkty (weby, aplikace, UX texty).

| Kontext | Doporučení | Příklad |
|---|---|---|
| Rozhraní aplikace (UI) | malé `vy/vás/váš` | `Zkontrolujte si váš zůstatek` |
| Nápověda, FAQ, články | malé `vy/vás/váš` | `Jak si změníte heslo` |
| Marketingové materiály | malé `vy/vás/váš` | `Založte si účet a získejte bonus` |
| Osobní e-mail klientovi | velké `Vy/Vás/Váš` | `Vážený pane Nováku, Váš požadavek…` |
| Odpověď na reklamaci | velké `Vy/Vás/Váš` | `Potvrzujeme, že Vaše reklamace…` |
| Chatbot / živý chat | malé `vy/vás/váš` | `Jak vám mohu pomoci?` |
| Push notifikace | malé `vy/vás/váš` | `Na váš účet přišla platba` |

### Pravidlo pro bankovní aplikace

- V **UI aplikace** používejte **malé `vy/váš`** – jedná se o hromadnou, neadresnou komunikaci.
- V **individuální korespondenci** (e-maily o reklamacích, osobní zprávy klientovi) používejte **velké `Vy/Váš`**.
- Zvolenou variantu **dodržujte konzistentně** v celém produktu. Neměňte velké a malé V mezi obrazovkami.

> **Bankovní specifika:** Formální tón je v bankovnictví očekáván. Používejte vždy vykání, nikdy tykání. I přesto, že používáte malé `v`, zachovejte zdvořilý a profesionální tón.

---

## 2. Interpunkce

### 2.1 Obecné pravidlo mezer

Tečka, čárka, dvojtečka, středník, vykřičník a otazník se **připojují k předchozímu slovu bez mezery**. Za nimi **následuje mezera**.

```
✅ Zadejte částku. Potvrdíte tlačítkem „Odeslat".
❌ Zadejte částku .Potvrdíte tlačítkem „Odeslat" .
```

### 2.2 Tečka

- Ukončuje oznamovací věty.
- **Nepíše se** za nadpisy, popisky, štítky (labely) a položkami menu, které stojí samostatně.
- Dvě tečky se nikdy nepíšou vedle sebe – tečka za zkratkou na konci věty slouží zároveň jako tečka ukončující větu.

```
✅ Transakce byla provedena v 15.30 hod.     (jedna tečka na konci)
❌ Transakce byla provedena v 15.30 hod..    (dvě tečky)
```

### 2.3 Čárka

- Odděluje věty a rovnocenné větné členy, které nejsou spojeny spojkami `a`, `i`, `ani`, `nebo`, `či`.
- Píše se **vždy** před `ale`, `avšak`, `nýbrž`, `neboť`, `přestože`, `ačkoli`.
- Čárka **před `a`**: píše se pouze tehdy, když `a` spojuje věty s **různým podmětem** nebo má **odporovací význam** (= ale).

```
✅ Zadejte PIN, a pokud je správný, transakce bude provedena.
✅ Účet je aktivní a připravený k použití.
```

### 2.4 Středník

- Odděluje silněji než čárka, ale slaběji než tečka.
- Vhodný v seznamech, kde jednotlivé položky obsahují čárky.
- V moderních UX textech se používá zřídka – upřednostňujte kratší věty oddělené tečkou.

### 2.5 Dvojtečka

- Uvozuje výčty, vysvětlení a přímou řeč.
- Pokud po ní následuje **celá věta**: první písmeno je **velké**.
- Pokud po ní následuje **slovo nebo slovní spojení**: první písmeno je **malé**.

```
✅ Poznámka: transakce může trvat až 2 pracovní dny.
✅ Stav účtu: Váš účet je dočasně zablokován.
```

### 2.6 Otazník a vykřičník

- Za otazníkem ani vykřičníkem se **nepíše tečka**.
- V bankovních aplikacích **používejte vykřičník střídmě** – nadměrné použití působí neprofesionálně.

```
✅ Opravdu chcete zrušit platbu?
✅ Pozor: Tuto akci nelze vrátit zpět.
❌ Pozor! Tuto akci nelze vrátit zpět!     (příliš mnoho vykřičníků)
```

### 2.7 Tři tečky (výpustka)

- Správně se zapisují jako **jeden znak** `…` (Unicode U+2026), ne jako tři samostatné tečky.
- Za nedokončeným slovem: **bez mezery** před, **mezera** za: `Načítání…`
- Nikdy nepište čtyři tečky (tři tečky + tečka).
- Před dalším interpunkčním znaménkem bez mezery: `…?`, `…!`

```
✅ Zpracováváme vaši žádost…
✅ Načítání…
❌ Zpracováváme vaši žádost ...
```

### 2.8 Závorky

- Před otevírací závorkou mezera, za ní ne.
- Před uzavírací závorkou ne, za ní mezera.
- Tečka se píše **za** uzavírací závorkou, pokud je v závorkách jen část věty.

```
✅ Poplatek za vedení účtu (měsíčně) je 49 Kč.
```

---

## 3. Uvozovky

### České uvozovky

V češtině se používají **typografické uvozovky** ve stylu 99–66 (dolní–horní):

| Typ | Znaky | Příklad |
|---|---|---|
| Dvojité (primární) | `„…"` | `„Potvrdit platbu"` |
| Jednoduché (vnořené) | `‚…'` | `„Klikněte na ‚Odeslat' a počkejte"` |

### Pravidla

- **Nikdy nepoužívejte** rovné/ASCII uvozovky `"..."` ani anglické uvozovky `"..."`.
- Uvozovky se **připojují přímo** k uzavřenému textu bez mezer: `„takto"`.
- Vnořené uvozovky: jednoduché uvnitř dvojitých: `„řekl ‚ano' a odešel"`.
- Pokud je celá věta v uvozovkách, závěrečná uvozovka se píše **za interpunkcí**.

```
✅ Tlačítko „Odeslat platbu"
✅ Stiskněte „Potvrdit".
❌ Tlačítko "Odeslat platbu"     (rovné uvozovky)
❌ Tlačítko " Odeslat platbu "   (mezery uvnitř uvozovek)
```

---

## 4. Velká a malá písmena

### Základní pravidlo: sentence case

V češtině se **vždy** používá „sentence case" – velké písmeno pouze na začátku věty/fráze. „Title Case" (velká písmena na začátku každého slova) je anglický zvyk a v češtině působí nepřirozeně.

| Prvek UI | Pravidlo | Příklad |
|---|---|---|
| Nadpisy | Velké jen první slovo | `Přehled transakcí` |
| Tlačítka | Velké jen první písmeno | `Odeslat platbu` |
| Položky menu | Velké jen první písmeno | `Nastavení účtu` |
| Tooltipy | Činný rod, 3. osoba | `Zobrazí historii transakcí` |
| Popisky (labely) | Velké jen první písmeno | `Číslo účtu` |
| Chybové hlášky | Velké jen první písmeno | `Neplatné číslo karty` |

### Co se v češtině píše s malým písmenem (na rozdíl od angličtiny)

- Dny v týdnu: `pondělí`, `úterý`, `středa`
- Měsíce: `leden`, `únor`, `březen`
- Jazyky: `čeština`, `angličtina`
- Přídavná jména odvozená od vlastních jmen: `pražský`, `evropský`
- Národnosti (přídavná jména): `český`, `německý`
- Názvy funkcí produktu: `ochrana proti podvodům`, `správa účtů`

### Co se píše s velkým písmenem

- Vlastní jména: `Česká národní banka`, `Česká republika`
- Názvy institucí: `Ministerstvo financí`
- Vlastní názvy produktů a služeb: `George`, `Servis 24`
- Názvy zákonů (první slovo): `Zákon o bankách`

> **Bankovní specifika:** Názvy konkrétních bankovních produktů (např. `Spořicí účet Plus`) jsou vlastní jména a píšou se s velkým písmenem. Obecné pojmy (`spořicí účet`, `běžný účet`, `kreditní karta`) se píšou s malým.

---

## 5. Formát data a času

### Datum

| Formát | Příklad | Použití |
|---|---|---|
| Vzestupný (standardní) | `17. 3. 2026` | UI, přehledy, obecné zobrazení |
| Slovně-číselný | `17. března 2026` | Formální dokumenty, smlouvy, potvrzení |
| Sestupný (ISO 8601) | `2026-03-17` | Technické/databázové kontexty |

#### Pravidla

- Za číslem dne a měsíce se píše **tečka a mezera**: `17. 3. 2026` (nikoli `17.3.2026`).
- Měsíce se v češtině píšou **s malým písmenem**: `března`, `ledna`.
- Ve slovně-číselném formátu je měsíc ve **2. pádu** (genitiv): `17. března 2026`.
- Rok se **nikdy neodděluje** mezerami: `2026` (nikoli `2 026`).

```
✅ Datum splatnosti: 17. 3. 2026
✅ Smlouva ze dne 17. března 2026
❌ Datum splatnosti: 17.3.2026         (chybí mezery)
❌ Datum splatnosti: 17. Března 2026   (velké M)
```

> **Bankovní specifika:** Pro výpisy a formální potvrzení upřednostňujte slovně-číselný formát (`17. března 2026`), který je jednoznačný a odpovídá požadavkům finančních dokumentů.

### Čas

- Hodiny a minuty se oddělují **tečkou** (český zvyk) nebo **dvojtečkou**: `9.30` nebo `9:30`.
- Zvolený formát musí být **konzistentní** v celé aplikaci.
- Jednotky se zkracují: `hod.`, `min.`, `s`

```
✅ Převod bude proveden v 14.00 hod.
✅ Pobočka otevřena: 9:00–17:00
```

> **Bankovní specifika:** U časových razítek transakcí uvádějte přesný čas včetně sekund: `17. 3. 2026, 14:35:22`. Používejte 24hodinový formát.

---

## 6. Formát čísel

### Desetinný oddělovač

V češtině je desetinným oddělovačem **čárka** (nikoli tečka):

```
✅ 3,14
✅ Úroková sazba: 5,49 % p. a.
❌ 3.14
```

### Oddělovač tisíců

Tisíce se oddělují **pevnou (nezlomitelnou) mezerou**:

```
✅ 1 234 567
✅ Zůstatek: 158 320,50 Kč
❌ 1,234,567
❌ 1.234.567
```

#### Podrobná pravidla

- Čísla s **5 a více ciframi** se povinně člení po třech: `12 345`, `1 234 567`.
- Čtyřciferná čísla: lze psát bez mezery (`6000`) i s mezerou (`7 530`).
- **Roky se nikdy nečlení**: `2026`, `1945`.
- Čísla za desetinnou čárkou se člení po třech od čárky doprava: `3,141 592 65`.

> **Bankovní specifika:** U finančních částek vždy oddělujte tisíce mezerou pro čitelnost. U čtyřciferných částek rovněž doporučujeme mezeru: `1 500 Kč` (nikoli `1500 Kč`).

---

## 7. Peněžní částky

### Česká koruna (Kč)

| Pravidlo | Příklad |
|---|---|
| Symbol `Kč` za číslem s mezerou | `1 234 Kč` |
| Haléře za desetinnou čárkou | `1 234,50 Kč` |
| Celé částky bez desetinných míst | `500 Kč` |
| V tabulkách s různými částkami zarovnávejte nulami | `500,00 Kč` |
| Kód CZK v mezinárodním kontextu | `1 234 CZK` |

#### Podrobná pravidla

- Symbol `Kč` se píše **za číslem** s mezerou: `500 Kč`.
- ČSN 01 6910 **již nedoporučuje** zápis s pomlčkou místo haléřů (`500,– Kč`). Pište `500 Kč` nebo `500,00 Kč`.
- V tabulkách, kde se mísí celé částky a částky s haléři, doplňte nuly pro zarovnání: `500,00 Kč`.
- Tisíce oddělujte mezerou: `1 234 567,89 Kč`.

```
✅ Zůstatek na účtu: 158 320,50 Kč
✅ Poplatek: 49 Kč
✅ Převedená částka: 25 000,00 Kč
❌ Zůstatek na účtu: 158320.50 CZK
❌ Poplatek: 49,- Kč
❌ Převedená částka: 25,000.00 Kč
```

### Zahraniční měny

| Měna | Formát | Příklad |
|---|---|---|
| Euro | `EUR` za číslem nebo `€` | `1 500,00 EUR` |
| Americký dolar | `USD` za číslem nebo `$` | `2 340,00 USD` |
| Britská libra | `GBP` za číslem nebo `£` | `890,00 GBP` |

- Slovo `euro` je **středního rodu**, skloňuje se jako `město`: 1 euro, 2 eura, 5 eur.
- Píše se **s malým písmenem**: `euro` (nikoli `Euro`).

> **Bankovní specifika:** V přehledech kurzů a mezinárodních převodech vždy používejte mezinárodní kódy ISO 4217 (`CZK`, `EUR`, `USD`). V běžném UI pro domácí transakce používejte `Kč`.

---

## 8. Procenta a úrokové sazby

- Značka `%` se odděluje **mezerou** od čísla: `5,49 %`.
- Výjimka – když tvoří přídavné jméno, píše se **bez mezery**: `5% úrok` (= pětiprocentní úrok).
- Zkratka `p. a.` (per annum) se píše s mezerami a tečkami: `5,49 % p. a.`
- Zkratka `p. m.` (per mensem) analogicky: `0,46 % p. m.`

```
✅ Úroková sazba: 5,49 % p. a.
✅ RPSN: 6,12 %
✅ 5% sleva na poplatek
❌ Úroková sazba: 5.49% p.a.
```

---

## 9. Čísla účtů, karty, identifikátory

### Číslo bankovního účtu (český formát)

- Formát: `předčíslí-číslo účtu/kód banky`
- Předčíslí (nepovinné, max. 6 číslic): `19-2000145399/0800`
- Bez předčíslí: `2000145399/0800`
- IBAN: `CZ65 0800 0000 1920 0014 5399` (skupiny po 4 znacích oddělené mezerami)

```
✅ 19-2000145399/0800
✅ CZ65 0800 0000 1920 0014 5399
```

### Číslo platební karty

- Zobrazuje se ve skupinách po **4 číslicích** oddělených mezerou: `4321 1234 5678 9012`.
- Z bezpečnostních důvodů maskujte středové skupiny: `4321 •••• •••• 9012`.

### Variabilní symbol, specifický symbol, konstantní symbol

- Zobrazujte **bez mezer a oddělovačů**: `1234567890`.

---

## 10. Telefonní čísla

- Česká telefonní čísla mají **9 číslic** (po předvolbě `+420`).
- Standardní formát: `+420 XXX XXX XXX` (tři skupiny po třech).
- Předvolba se odděluje mezerou: `+420 234 567 890`.

```
✅ +420 234 567 890
✅ 800 123 456 (bezplatná linka)
❌ +420234567890
❌ +420-234-567-890
```

> **Bankovní specifika:** U zákaznické linky banky uvádějte vždy ve formátu s mezerami. Pro bezplatné linky uvádějte: `800 XXX XXX` (bez předvolby +420).

---

## 11. Spojovník a pomlčka

### Spojovník (krátká čárka `-`)

- Bez mezer.
- Použití: složená slova (`česko-slovenský`), spojené obce (`Praha-Hostivař`), přípona `-li` (`mohl-li`).

### Pomlčka (delší čárka `–`)

**S mezerami** – vsuvka, význam „versus":

```
✅ Přihlásit se – pokud máte účet – můžete zde.
✅ Výhody – Nevýhody
```

**Bez mezer** – rozsah „od–do":

```
✅ 1. 1.–31. 12. 2026
✅ 9:00–17:00
✅ 1 000–5 000 Kč
✅ strana 12–15
```

- U rozsahů s víceslovnými výrazy se pomlčka píše **s mezerami**: `Praha 1 – Praha 5`.
- **Nepoužívejte spojovník** místo pomlčky a naopak.

### Znaménko minus `−`

- Zvláštní znak (Unicode U+2212), jiný než spojovník i pomlčka.
- Záporná čísla: `−10 °C`, `−1 500 Kč`.
- V matematických operacích s mezerami: `10 − 5 = 5`.

> **Bankovní specifika:** U záporných zůstatků a debetních transakcí používejte správné znaménko minus: `−1 500,00 Kč`. Nikoli spojovník `-1 500,00 Kč`.

---

## 12. Zkratky

### Zkratky s tečkou

| Zkratka | Plný tvar |
|---|---|
| `č.` | číslo |
| `tj.` | to jest |
| `např.` | například |
| `popř.` | popřípadě |
| `atd.` | a tak dále |
| `apod.` | a podobně |
| `resp.` | respektive |
| `příp.` | případně |
| `tel.` | telefon |
| `max.` | maximálně |
| `min.` | minimálně |

#### Pravidla

- Víceslovné zkratky se píšou **jako jedno slovo**: `tj.`, `mj.`, `atd.`, `apod.`
- Před `atd.`, `apod.`, `aj.` se **nepíše čárka** – pokračují výčet spojený spojkou `a`.
- Dvě tečky vedle sebe se nikdy nepíšou.

### Stažené zkratky (bez tečky)

- Vznikají z prvního a posledního písmene: `fa` (firma), `pí` (paní), `ca` (circa).

### `viz` není zkratka

- Je to rozkazovací způsob slovesa `vidět`. **Nepíše se za ním tečka** (pokud neukončuje větu).

```
✅ Více informací viz sekce „Poplatky".
❌ Více informací viz. sekce „Poplatky".
```

### Značky a jednotky

- Bez tečky, oddělené mezerou: `30 m`, `15 %`, `100 kg`, `20 °C`.
- Výjimka – tvoří-li přídavné jméno, bez mezery: `5%`, `30denní`.

### Finanční a bankovní zkratky

| Zkratka | Význam |
|---|---|
| `IBAN` | International Bank Account Number |
| `BIC` / `SWIFT` | Bank Identifier Code |
| `RPSN` | roční procentní sazba nákladů |
| `p. a.` | per annum (ročně) |
| `p. m.` | per mensem (měsíčně) |
| `PSČ` | poštovní směrovací číslo |
| `IČO` | identifikační číslo osoby |
| `DIČ` | daňové identifikační číslo |
| `ČNB` | Česká národní banka |

---

## 13. Seznamy a výčty

### Tři přístupy k formátování výčtů

| Typ | První písmeno | Koncová interpunkce | Poslední položka |
|---|---|---|---|
| Neslovesné položky (slova, fráze) | malé | čárka nebo středník | tečka |
| Větné položky (celé věty) | velké | tečka | tečka |
| Graficky oddělené (odrážky, bez vět) | malé | žádná | žádná |

### Pravidla pro bankovní aplikace

**Krátké položky (slova, fráze) – bez interpunkce:**

```
Pro aktivaci potřebujete:
• občanský průkaz
• číslo účtu
• mobilní telefon
```

**Delší položky (fráze s čárkami) – středníky:**

```
K žádosti o úvěr přiložte:
• kopii občanského průkazu, případně cestovního pasu;
• potvrzení o příjmu za posledních 12 měsíců;
• výpis z účtu za poslední 3 měsíce.
```

**Celé věty – tečky:**

```
Jak si aktivujete mobilní bankovnictví:
• Stáhněte si aplikaci z App Store nebo Google Play.
• Přihlaste se svými údaji.
• Potvrďte aktivaci SMS kódem.
```

- Všechny položky ve výčtu musí mít **stejnou gramatickou strukturu**.
- Nemíchejte věty s jednoslovnými položkami.

---

## 14. Generické maskulinum a inkluzivní jazyk

### Aktuální stav

Generické maskulinum (použití mužského rodu pro obě pohlaví) je v češtině stále **gramaticky správné** a běžně používané. ÚJČ jej uznává jako „úsporné a jasné".

### Inkluzivní alternativy vhodné pro bankovní aplikace

| Místo generického maskulina | Použijte | Příklad |
|---|---|---|
| `klienti` | slovesné přídavné jméno | `klientela`, `klienti a klientky` |
| `uživatelé` | opis | `osoby využívající službu` |
| `podnikatelé` | obě formy | `podnikatelé a podnikatelky` |
| – | 2. osoba | `Můžete si zvolit…` (místo `Klient si zvolí…`) |

### Doporučení pro bankovní aplikace

- **V UI textech** upřednostňujte 2. osobu (`vy`), čímž se problému generického maskulina většinou vyhnete: `Zkontrolujte si zůstatek` místo `Klient si zkontroluje zůstatek`.
- **V právních textech a smlouvách** je generické maskulinum stále standardem.
- **Nepoužívejte** hvězdičkovou notaci (`klient*ka`) – v bankovním prostředí působí neprofesionálně a snižuje čitelnost.

---

## 15. Činný rod vs. trpný rod

### Pravidlo

V UX textech **upřednostňujte činný rod** (aktivní) před trpným rodem (pasivním). Činný rod je srozumitelnější a přímější.

| Trpný rod (nevhodné) | Činný rod (doporučené) |
|---|---|
| `Platba byla odeslána.` | `Odeslali jsme platbu.` |
| `Heslo bylo změněno.` | `Změnili jsme vaše heslo.` |
| `Transakce bude provedena.` | `Provedeme transakci.` |
| `Účet byl zablokován.` | `Zablokovali jsme váš účet.` |

### Výjimky

Trpný rod je přijatelný, pokud:

- Není důležité, kdo akci provedl: `Karta byla doručena.` (doručil ji kurýr, ale to není podstatné).
- Systém provedl akci automaticky: `Platba je naplánována na 17. 3. 2026.`

### Tooltipy a popisy funkcí

Používejte 3. osobu činného rodu:

```
✅ Zobrazí přehled transakcí
✅ Otevře nastavení účtu
✅ Odešle platbu
```

---

## 16. Typografie – souhrn pravidel

### Mezery a interpunkce – přehled

| Znak | Před | Za | Příklad |
|---|---|---|---|
| Tečka `.` | ne | ano | `věta. Další` |
| Čárka `,` | ne | ano | `slovo, slovo` |
| Dvojtečka `:` | ne | ano | `Stav: aktivní` |
| Středník `;` | ne | ano | `položka; položka` |
| Otazník `?` | ne | ano | `Opravdu? Ano.` |
| Vykřičník `!` | ne | ano | `Pozor! Ověřte.` |
| Otevírací závorka `(` | ano | ne | `text (závorka)` |
| Uzavírací závorka `)` | ne | ano | `(závorka) text` |
| Otevírací uvozovka `„` | ano | ne | `text „uvozovka"` |
| Uzavírací uvozovka `"` | ne | ano | `„uvozovka" text` |
| Tři tečky `…` | ne* | ano | `Načítání… hotovo` |
| Pomlčka `–` (vsuvka) | ano | ano | `text – vsuvka – text` |
| Pomlčka `–` (rozsah) | ne | ne | `9:00–17:00` |
| Spojovník `-` | ne | ne | `česko-německý` |
| Procento `%` | ano | – | `5,49 %` |

\* Pokud navazuje na slovo (nedokončená myšlenka).

### Nezlomitelné mezery

Používejte nezlomitelné mezery (`&nbsp;` / Unicode U+00A0) v těchto případech:

- Mezi číslem a jednotkou/měnou: `500 Kč`, `15 %`, `20 °C`
- V datu mezi dnem a měsícem: `17. 3. 2026`
- Mezi skupinami číslic: `1 234 567`
- Za jednopísmennými předložkami a spojkami: `v bance`, `s účtem`, `k platbě`
- V telefonních číslech: `+420 234 567 890`

> **Bankovní specifika:** Nezlomitelné mezery za jednopísmennými předložkami (`k`, `s`, `v`, `z`, `o`, `u`) jsou v bankovních textech obzvláště důležité – zabraňují osamocení předložky na konci řádku, což působí neprofesionálně.

---

## 17. Adresy a PSČ

### Formát české adresy

```
Jméno Příjmení
Ulice číslo orientační/číslo popisné
PSČ Město
```

### Pravidla

- **PSČ** má 5 číslic, mezera za třetí: `110 00`.
- PSČ se píše na **stejném řádku** jako město, **před názvem města**: `110 00 Praha 1`.
- Dva typy čísel budov: `číslo popisné` (červená tabulka) a `číslo orientační` (modrá tabulka), oddělené lomítkem: `Vodičkova 699/34`.

```
✅ Jan Novák
   Vodičkova 699/34
   110 00 Praha 1

❌ Jan Novák
   Vodičkova 699/34
   Praha 1, 110 00          (PSČ za městem)
```

---

## 18. Formát data v právních a finančních dokumentech

Pro formální bankovní dokumenty (smlouvy, výpisy, potvrzení) platí přísnější pravidla:

| Typ dokumentu | Doporučený formát data | Příklad |
|---|---|---|
| Smlouva | slovně-číselný | `dne 17. března 2026` |
| Výpis z účtu | vzestupný číselný | `17. 3. 2026` |
| Transakční historie | vzestupný + čas | `17. 3. 2026, 14:35:22` |
| SWIFT zprávy | ISO 8601 | `2026-03-17` |
| API/technické logy | ISO 8601 | `2026-03-17T14:35:22+01:00` |

---

## 19. Odkazy a URL v textech

### Pravidla pro kotevní text

- Používejte **popisný text odkazu**, který říká, kam odkaz vede.
- **Nepoužívejte** generické texty jako `Klikněte zde` nebo `Více informací`.

```
✅ Přečtěte si podmínky pro vedení účtu.
✅ Zjistěte více o úrokových sazbách.
❌ Klikněte zde pro více informací.
❌ Více zde.
```

### Terminologie

- Odkaz = `odkaz` nebo `hypertextový odkaz`
- URL = `URL adresa` nebo `URL` (v češtině středního rodu)

---

## 20. Dělení slov

### Základní pravidla

- Jednoslabičná slova se **nedělí**: `účt`, `bank`.
- Dvouslabičná slova začínající samohláskou se **nedělí**: `účet`, `úrok`.
- Nikdy nenechávejte osamocené písmeno na konci nebo začátku řádku.
- Složená slova se dělí na hranici složek: `banko-mat`, `spořicí`.
- Slova s předponou se dělí za předponou: `pře-vod`, `do-platek`, `na-stavení`.

### Pravidlo pro pomlčkové složeniny

- Pokud se slovo s pomlčkou dělí na místě pomlčky, pomlčka se **opakuje** na začátku dalšího řádku: `česko-` | `-slovenský`.

---

## Zdroje

- [Internetová jazyková příručka (ÚJČ)](https://prirucka.ujc.cas.cz/) – hlavní online referenční příručka českého jazyka
- [ČSN 01 6910](https://ujc.cas.cz/wp-content/uploads/2024/06/otazky-a-odpovedi-k-csn-01-6910_2014_ed1.pdf) – norma pro úpravu dokumentů
- [Pravidla.cz](https://www.pravidla.cz/) – pravidla českého pravopisu
- [Mozilla Czech L10n Style Guide](https://mozilla-l10n.github.io/styleguides/cs/general.html) – lokalizační pravidla pro software
- [PeckaDesign – Typografický tahák](https://www.peckadesign.cz/blog/typograficky-tahak-nejen-pro-grafiky) – přehled českých typografických pravidel
