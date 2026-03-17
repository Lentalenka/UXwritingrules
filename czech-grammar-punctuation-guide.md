# Pravidla české gramatiky a interpunkce pro Air Bank

Tahle příručka je tu proto, aby se nám všem psalo líp a hlavně stejně. Najdete v ní pravidla českého pravopisu, interpunkce a typografie, která dodržujeme v textech naší aplikace a webu. Vychází z doporučení Ústavu pro jazyk český (ÚJČ), normy ČSN 01 6910 a osvědčené praxe v digitálním prostředí.

Píšeme pro lidi, ne pro úředníky. Ale i lidský jazyk má svá pravidla.

---

## 1. Vykání – velké V, nebo malé v?

### Co říká Ústav pro jazyk český

Velké `Vy`, `Vám`, `Váš` je předepsané pro vyjádření úcty **v dopisech a korespondenci**. Pravidlo ale vzniklo pro klasické dopisy a na digitální produkty se výslovně nevztahuje.

### Jak to děláme my

V aplikaci a na webu píšeme **malé `vy/vás/váš`**. Oslovujeme totiž všechny naše klienty najednou, ne jednoho konkrétního člověka. Velké V si šetříme na osobní komunikaci.

| Kde | Jaké v | Příklad |
|---|---|---|
| Aplikace (UI) | malé `vy/vás/váš` | `Zkontrolujte si váš zůstatek` |
| Nápověda, FAQ, články | malé `vy/vás/váš` | `Jak si změníte heslo` |
| Marketing | malé `vy/vás/váš` | `Založte si účet a získejte bonus` |
| Push notifikace | malé `vy/vás/váš` | `Na váš účet přišla platba` |
| Chatbot | malé `vy/vás/váš` | `Jak vám mohu pomoci?` |
| Osobní e-mail klientovi | velké `Vy/Vás/Váš` | `Vážený pane Nováku, Váš požadavek…` |
| Odpověď na reklamaci | velké `Vy/Vás/Váš` | `Potvrzujeme, že Vaše reklamace…` |

### Na co si dát pozor

- Jakmile si zvolíte malé nebo velké V, **držte se ho v celém produktu**. Přepínání mezi obrazovkami mate.
- I s malým `v` zůstáváme zdvořilí a přátelští – to je přece Air Bank.

---

## 2. Interpunkce

### 2.1 Kam patří mezery (a kam ne)

Tečka, čárka, dvojtečka, středník, vykřičník a otazník se **lepí k předchozímu slovu** (žádná mezera před nimi). Mezera patří **za ně**.

```
✅ Zadejte částku. Potvrdíte tlačítkem „Odeslat".
❌ Zadejte částku .Potvrdíte tlačítkem „Odeslat" .
```

### 2.2 Tečka

- Ukončuje oznamovací věty.
- **Nedáváme ji** za nadpisy, popisky, labely ani položky menu, které stojí samy na řádku.
- Dvě tečky vedle sebe nikdy – tečka za zkratkou na konci věty platí zároveň jako tečka za větou.

```
✅ Transakce byla provedena v 15.30 hod.     (stačí jedna tečka)
❌ Transakce byla provedena v 15.30 hod..    (dvě tečky = chyba)
```

### 2.3 Čárka

- Odděluje věty a větné členy, které nejsou spojené spojkami `a`, `i`, `ani`, `nebo`, `či`.
- **Vždycky** ji pište před `ale`, `avšak`, `nýbrž`, `neboť`, `přestože`, `ačkoli`.
- Čárka **před `a`**: jen když `a` spojuje věty s různým podmětem, nebo má význam „ale".

```
✅ Zadejte PIN, a pokud je správný, transakce proběhne.
✅ Účet je aktivní a připravený k použití.
```

### 2.4 Středník

- Odděluje silněji než čárka, ale mírněji než tečka.
- Hodí se hlavně v seznamech, kde položky samy o sobě obsahují čárky.
- V běžných UX textech ho moc nepotkáte – radši pište kratší věty s tečkou.

### 2.5 Dvojtečka

- Uvádí výčty, vysvětlení nebo přímou řeč.
- Když po ní následuje **celá věta**, píšeme velké písmeno. Když jen slovo nebo fráze, malé.

```
✅ Poznámka: transakce může trvat až 2 pracovní dny.
✅ Stav účtu: Váš účet je dočasně zablokován.
```

### 2.6 Otazník a vykřičník

- Za otazníkem ani vykřičníkem se **nepíše tečka**.
- S vykřičníky to nepřehánějte. Jeden vykřičník řekne všechno, tři působí hystericky.

```
✅ Opravdu chcete zrušit platbu?
✅ Pozor: Tuto akci nelze vrátit zpět.
❌ Pozor! Tuto akci nelze vrátit zpět!     (příliš dramatické)
```

### 2.7 Tři tečky (výpustka)

- Správně to je **jeden znak** `…` (Unicode U+2026), ne tři tečky za sebou.
- Když navazují na slovo, píšou se **bez mezery** před a s **mezerou** za: `Načítání…`
- Čtyři tečky neexistují (tři tečky + tečka = špatně).
- Před `?` nebo `!` taky bez mezery: `…?`, `…!`

```
✅ Zpracováváme vaši žádost…
✅ Načítání…
❌ Zpracováváme vaši žádost ...
```

### 2.8 Závorky

- Před otevírací závorkou mezera, za ní ne. Před zavírací ne, za ní mezera.
- Tečka patří **za** zavírací závorku, pokud závorka obklopuje jen část věty.

```
✅ Poplatek za vedení účtu (měsíčně) je 0 Kč.
```

---

## 3. Uvozovky

### Jak vypadají české uvozovky

V češtině se používají **typografické uvozovky** – dolní na začátku, horní na konci (styl 99–66):

| Typ | Znaky | Příklad |
|---|---|---|
| Dvojité (primární) | `„…"` | `„Potvrdit platbu"` |
| Jednoduché (vnořené) | `‚…'` | `„Klikněte na ‚Odeslat' a počkejte"` |

### Pravidla

- **Nikdy nepoužívejte** rovné uvozovky `"..."` ani anglické `"..."`. Vypadá to nedodělaně.
- Uvozovky se **lepí přímo k textu** bez mezer: `„takto"`.
- Uvozovky v uvozovkách? Jednoduché dovnitř dvojitých: `„řekl ‚ano' a odešel"`.
- U celé věty v uvozovkách jde závěrečná uvozovka **za interpunkci**.

```
✅ Tlačítko „Odeslat platbu"
✅ Stiskněte „Potvrdit".
❌ Tlačítko "Odeslat platbu"     (rovné uvozovky)
❌ Tlačítko " Odeslat platbu "   (mezery uvnitř – taky špatně)
```

---

## 4. Velká a malá písmena

### Základní pravidlo: sentence case

V češtině velké písmeno jen na začátku věty nebo fráze. „Title Case" (velká písmena u každého slova) je anglický zvyk – v češtině to vypadá divně a nezvykle.

| Prvek UI | Pravidlo | Příklad |
|---|---|---|
| Nadpisy | Velké jen první slovo | `Přehled transakcí` |
| Tlačítka | Velké jen první písmeno | `Odeslat platbu` |
| Položky menu | Velké jen první písmeno | `Nastavení účtu` |
| Tooltipy | Činný rod, 3. osoba | `Zobrazí historii transakcí` |
| Popisky (labely) | Velké jen první písmeno | `Číslo účtu` |
| Chybové hlášky | Velké jen první písmeno | `Neplatné číslo karty` |

### V češtině píšeme s malým písmenem (na rozdíl od angličtiny)

- Dny v týdnu: `pondělí`, `úterý`, `středa`
- Měsíce: `leden`, `únor`, `březen`
- Jazyky: `čeština`, `angličtina`
- Přídavná jména od vlastních jmen: `pražský`, `evropský`
- Názvy funkcí produktu: `ochrana proti podvodům`, `správa účtů`

### Velké písmeno patří k

- Vlastním jménům: `Česká národní banka`, `Air Bank`
- Názvům institucí: `Ministerstvo financí`
- Názvům našich produktů a služeb (pokud je to jejich oficiální jméno)
- Názvům zákonů (první slovo): `Zákon o bankách`

Obecné pojmy jako `spořicí účet`, `běžný účet` nebo `kreditní karta` se píšou s malým písmenem. Velké je jen u konkrétního pojmenování produktu, když je to jeho oficiální název.

---

## 5. Formát data a času

### Datum

| Formát | Příklad | Kdy ho použít |
|---|---|---|
| Vzestupný (standardní) | `17. 3. 2026` | V aplikaci – přehledy, seznamy, obecné zobrazení |
| Slovně-číselný | `17. března 2026` | Smlouvy, výpisy, potvrzení – formálnější kontext |
| ISO 8601 | `2026-03-17` | Technické a databázové kontexty, API |

#### Na co nezapomenout

- Za číslem dne i měsíce je **tečka a mezera**: `17. 3. 2026` (ne `17.3.2026`).
- Měsíce píšeme **s malým písmenem**: `března`, `ledna`.
- Ve slovně-číselném formátu je měsíc ve **2. pádu**: `17. března 2026`.
- Rok se **nikdy nerozděluje** mezerami: `2026` (ne `2 026`).

```
✅ Datum splatnosti: 17. 3. 2026
✅ Smlouva ze dne 17. března 2026
❌ Datum splatnosti: 17.3.2026         (chybí mezery)
❌ Datum splatnosti: 17. Března 2026   (velké M u měsíce)
```

Pro výpisy a formální potvrzení je lepší slovně-číselný formát (`17. března 2026`) – je jednoznačný a nikdo si ho nesplete.

### Čas

- Hodiny a minuty oddělujeme **tečkou** (český zvyk) nebo **dvojtečkou**: `9.30` nebo `9:30`.
- V rámci celé aplikace se ale držte **jednoho** formátu.
- U transakcí uvádějte přesný čas i se sekundami: `17. 3. 2026, 14:35:22`. Vždy 24hodinový formát.

```
✅ Převod proběhne v 14.00 hod.
✅ Pobočka otevřena: 9:00–17:00
```

---

## 6. Formát čísel

### Desetinná čárka (ne tečka!)

V češtině je desetinným oddělovačem **čárka**. Tečka je anglický zvyk.

```
✅ 3,14
✅ Úroková sazba: 5,49 % p. a.
❌ 3.14
```

### Oddělování tisíců

Tisíce oddělujeme **mezerou** (ideálně nezlomitelnou). Ne tečkou, ne čárkou.

```
✅ 1 234 567
✅ Zůstatek: 158 320,50 Kč
❌ 1,234,567
❌ 1.234.567
```

#### Detaily

- Čísla s **5 a více ciframi** členíme po třech: `12 345`, `1 234 567`.
- Čtyřciferná čísla: jde to obojí (`6000` i `6 000`), ale u peněžních částek doporučujeme mezeru pro lepší čitelnost: `1 500 Kč`.
- **Roky nečleníme nikdy**: `2026`, `1945`.
- Za desetinnou čárkou členíme po třech směrem doprava: `3,141 592 65`.

---

## 7. Peněžní částky

### Česká koruna (Kč)

| Co | Jak | Příklad |
|---|---|---|
| Symbol `Kč` | Za číslem, s mezerou | `1 234 Kč` |
| Haléře | Za desetinnou čárkou | `1 234,50 Kč` |
| Celé částky | Bez desetinných míst | `500 Kč` |
| V tabulkách | Zarovnat nulami | `500,00 Kč` |
| Mezinárodní kód | `CZK` za číslem | `1 234 CZK` |

#### Co si zapamatovat

- `Kč` píšeme **za číslem** s mezerou: `500 Kč`.
- Zápis s pomlčkou místo haléřů (`500,– Kč`) je zastaralý – norma ČSN 01 6910 ho už nedoporučuje. Pište `500 Kč` nebo `500,00 Kč`.
- Když v tabulce máte mix celých částek a haléřových, sjednoťte to nulami: `500,00 Kč`.
- Tisíce vždy s mezerou: `1 234 567,89 Kč`.

```
✅ Zůstatek na účtu: 158 320,50 Kč
✅ Poplatek: 0 Kč
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

Slovo `euro` je středního rodu a skloňuje se jako `město`: 1 euro, 2 eura, 5 eur. Píše se s malým písmenem.

V kurzovních přehledech a mezinárodních převodech používejte ISO kódy (`CZK`, `EUR`, `USD`). V běžném UI pro domácí transakce stačí `Kč`.

---

## 8. Procenta a úrokové sazby

- Značka `%` se od čísla odděluje **mezerou**: `5,49 %`.
- Výjimka – pokud z toho děláte přídavné jméno, mezeru vynechte: `5% sleva` (= pětiprocentní sleva).
- Zkratka `p. a.` (per annum) se píše s mezerami a tečkami: `5,49 % p. a.`
- Stejně tak `p. m.` (per mensem): `0,46 % p. m.`

```
✅ Úroková sazba: 5,49 % p. a.
✅ RPSN: 6,12 %
✅ 5% sleva na poplatek
❌ Úroková sazba: 5.49% p.a.
```

---

## 9. Čísla účtů, karty a identifikátory

### Číslo bankovního účtu (český formát)

- Formát: `předčíslí-číslo účtu/kód banky`
- S předčíslím: `19-2000145399/0800`
- Bez předčíslí: `2000145399/0800`
- IBAN: skupiny po 4 znacích oddělené mezerami: `CZ65 0800 0000 1920 0014 5399`

### Číslo platební karty

- Skupiny po **4 číslicích** s mezerou: `4321 1234 5678 9012`.
- Z bezpečnostních důvodů maskujeme střední skupiny: `4321 •••• •••• 9012`.

### Variabilní symbol, specifický symbol, konstantní symbol

- Zobrazujeme **bez mezer a oddělovačů**: `1234567890`.

---

## 10. Telefonní čísla

Česká telefonní čísla mají 9 číslic (po předvolbě `+420`) a formátujeme je po trojicích:

```
✅ +420 234 567 890
✅ 800 123 456 (bezplatná linka)
❌ +420234567890       (nečitelné)
❌ +420-234-567-890    (pomlčky tu nepatří)
```

Pro bezplatné linky stačí formát bez předvolby: `800 XXX XXX`.

---

## 11. Spojovník a pomlčka

Jsou to dva různé znaky a každý má jiný úkol. Zaměňovat je je typografický hřích.

### Spojovník (krátký `-`)

Bez mezer. Spojuje části složených slov.

- Složená slova: `česko-slovenský`
- Spojené obce: `Praha-Hostivař`
- Přípona `-li`: `mohl-li`

### Pomlčka (delší `–`)

Má dva režimy:

**S mezerami** – vsuvka nebo význam „versus":

```
✅ Přihlásit se – pokud máte účet – můžete zde.
✅ Výhody – Nevýhody
```

**Bez mezer** – rozsah „od do":

```
✅ 1. 1.–31. 12. 2026
✅ 9:00–17:00
✅ 1 000–5 000 Kč
```

Pozor: u víceslovných rozsahů se pomlčka píše **s mezerami**: `Praha 1 – Praha 5`.

### Znaménko minus `−`

Tohle je ještě jiný znak (Unicode U+2212) – není to ani spojovník, ani pomlčka.

- Záporná čísla: `−10 °C`, `−1 500 Kč`
- Matematika: `10 − 5 = 5`

U záporných zůstatků a debetních transakcí v aplikaci používejte správné minus: `−1 500,00 Kč`. Spojovník `-1 500,00 Kč` vypadá neprofesionálně.

---

## 12. Zkratky

### Zkratky s tečkou

| Zkratka | Co znamená |
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

#### Co si hlídat

- Víceslovné zkratky píšeme **dohromady**: `tj.`, `mj.`, `atd.`, `apod.`
- Před `atd.`, `apod.`, `aj.` se **nedává čárka** – pokračují výčet se spojkou `a`.
- Dvě tečky vedle sebe neexistují. Když zkratka s tečkou končí větu, platí ta jedna za obě.

### `viz` není zkratka

Tohle je častý omyl. `viz` je rozkazovací způsob slovesa `vidět` – **nepíšeme za ním tečku**.

```
✅ Více informací viz sekce „Poplatky".
❌ Více informací viz. sekce „Poplatky".
```

### Značky a jednotky

- Bez tečky, s mezerou od čísla: `30 m`, `15 %`, `100 kg`, `20 °C`.
- Výjimka: když z toho děláte přídavné jméno, mezeru vynechte: `5%`, `30denní`.

### Finanční zkratky, které potkáte denně

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

Výčty se dají formátovat třemi způsoby – záleží na tom, co v nich máte:

| Typ položek | První písmeno | Čím končí | Poslední položka |
|---|---|---|---|
| Krátká slova, fráze | malé | čárka nebo středník | tečka |
| Celé věty | velké | tečka | tečka |
| Graficky oddělené (odrážky, krátké) | malé | nic | nic |

### Jak to vypadá v praxi

**Krátké fráze s odrážkami – bez interpunkce:**

```
Pro aktivaci potřebujete:
• občanský průkaz
• číslo účtu
• mobilní telefon
```

**Delší fráze (s čárkami uvnitř) – středníky:**

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

Důležité: všechny položky v jednom výčtu musí mít **stejnou strukturu**. Nemíchejte věty s jednoslovnými hesly.

---

## 14. Generické maskulinum a inkluzivní jazyk

### Jak to je

Generické maskulinum (mužský rod pro obě pohlaví) je v češtině pořád **gramaticky správné**. ÚJČ ho popisuje jako „úsporné a jasné".

### Jak to řešíme

Nejjednodušší cesta? **Mluvte přímo na člověka.** Většinu textů v aplikaci píšeme ve 2. osobě (`vy`), takže se problému generického maskulina přirozeně vyhneme.

| Místo tohoto | Napište raději |
|---|---|
| `Klient si může zvolit…` | `Můžete si zvolit…` |
| `Uživatel musí zadat PIN` | `Zadejte svůj PIN` |
| `Klienti mají nárok na…` | `Máte nárok na…` |

V právních textech a smlouvách je generické maskulinum stále standardem – tam ho klidně nechte.

Hvězdičkovou notaci (`klient*ka`) nepoužíváme. Snižuje čitelnost a v bankovním prostředí působí nepatřičně.

---

## 15. Činný rod vs. trpný rod

### Proč na tom záleží

Činný rod je přímější, osobnější a srozumitelnější. Trpný rod zní úředně a neosobně. A to nechceme.

| Trpný rod (raději ne) | Činný rod (takhle ano) |
|---|---|
| `Platba byla odeslána.` | `Odeslali jsme platbu.` |
| `Heslo bylo změněno.` | `Změnili jsme vaše heslo.` |
| `Transakce bude provedena.` | `Provedeme transakci.` |
| `Účet byl zablokován.` | `Zablokovali jsme váš účet.` |

### Kdy je trpný rod v pohodě

- Když není důležité, kdo akci provedl: `Karta byla doručena.`
- Když to udělal systém automaticky: `Platba je naplánována na 17. 3. 2026.`

### Tooltipy a popisy funkcí

Tady používáme 3. osobu činného rodu:

```
✅ Zobrazí přehled transakcí
✅ Otevře nastavení účtu
✅ Odešle platbu
```

---

## 16. Typografie – rychlý přehled

### Mezery a interpunkce na jednom místě

| Znak | Mezera před | Mezera za | Příklad |
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

\* Když navazuje na slovo (nedokončená myšlenka).

### Nezlomitelné mezery

Nezlomitelná mezera zabrání tomu, aby se text rozlomil na nešťastném místě. Použijte ji:

- Mezi číslem a jednotkou/měnou: `500 Kč`, `15 %`, `20 °C`
- V datu: `17. 3. 2026`
- Mezi skupinami číslic: `1 234 567`
- Za jednopísmennými předložkami: `v bance`, `s účtem`, `k platbě`
- V telefonních číslech: `+420 234 567 890`

Osamocená předložka na konci řádku (`Přihlaste se k` / `vašemu účtu`) vypadá nepěkně. Nezlomitelná mezera to vyřeší.

---

## 17. Adresy a PSČ

### Formát české adresy

```
Jméno Příjmení
Ulice číslo orientační/číslo popisné
PSČ Město
```

### Pravidla

- **PSČ** má 5 číslic s mezerou za třetí: `110 00`.
- PSČ je na **stejném řádku** jako město a stojí **před ním**: `110 00 Praha 1`.
- Číslo popisné (červená tabulka) a číslo orientační (modrá tabulka) se oddělují lomítkem: `Vodičkova 699/34`.

```
✅ Jan Novák
   Vodičkova 699/34
   110 00 Praha 1

❌ Jan Novák
   Vodičkova 699/34
   Praha 1, 110 00          (PSČ patří před město)
```

---

## 18. Formáty data podle typu dokumentu

Různé dokumenty si žádají různé formáty – tady je přehled:

| Typ dokumentu | Formát | Příklad |
|---|---|---|
| Smlouva | slovně-číselný | `dne 17. března 2026` |
| Výpis z účtu | vzestupný číselný | `17. 3. 2026` |
| Transakční historie | vzestupný + čas | `17. 3. 2026, 14:35:22` |
| SWIFT zprávy | ISO 8601 | `2026-03-17` |
| API / technické logy | ISO 8601 | `2026-03-17T14:35:22+01:00` |

---

## 19. Odkazy a URL v textech

### Popisný text odkazu

Pište odkaz tak, aby člověk věděl, kam ho to pošle – i bez kontextu kolem.

```
✅ Přečtěte si podmínky pro vedení účtu.
✅ Zjistěte víc o úrokových sazbách.
❌ Klikněte zde pro více informací.
❌ Více zde.
```

`Klikněte zde` je klasika, která nic neříká. Tomu se vyhýbáme.

### Terminologie

- Odkaz = `odkaz` nebo `hypertextový odkaz`
- URL = `URL adresa` nebo `URL` (v češtině středního rodu)

---

## 20. Dělení slov

### Základní pravidla

- Jednoslabičná slova se **nedělí**.
- Dvouslabičná slova začínající samohláskou se **nedělí**: `účet`, `úrok`.
- Nenechávejte osamocené písmeno na konci nebo začátku řádku.
- Složená slova dělíme na hranici složek: `banko-mat`.
- Slova s předponou dělíme za předponou: `pře-vod`, `do-platek`, `na-stavení`.

### Pomlčkové složeniny

Když se slovo s pomlčkou láme přesně na tom místě, pomlčka se **zopakuje** na začátku nového řádku: `česko-` | `-slovenský`.

---

## Zdroje

- [Internetová jazyková příručka (ÚJČ)](https://prirucka.ujc.cas.cz/) – hlavní online příručka českého jazyka
- [ČSN 01 6910](https://ujc.cas.cz/wp-content/uploads/2024/06/otazky-a-odpovedi-k-csn-01-6910_2014_ed1.pdf) – norma pro úpravu dokumentů
- [Pravidla.cz](https://www.pravidla.cz/) – pravidla českého pravopisu
- [Mozilla Czech L10n Style Guide](https://mozilla-l10n.github.io/styleguides/cs/general.html) – lokalizační pravidla pro software
- [PeckaDesign – Typografický tahák](https://www.peckadesign.cz/blog/typograficky-tahak-nejen-pro-grafiky) – přehled českých typografických pravidel
