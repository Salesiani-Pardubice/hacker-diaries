Materiály pro aktivitu na hodinu nábožentví, kde řešíme otázku: **Je dovoleno použít násilí k vlastní obraně?**. Aktivita se skládá z těchto kroků:

1. Děcka dostanou papír [`intro.pdf`](./intro.pdf), kde musejí vylušit klíče a dostat se na webovou stránku hackera.
2. Vloží správné klíče do webu a ten jim dá QR kódy, které je odkážou na 3 audiostorky.
3. Zkusí se vžít do situace a rozhdonout se, jak by dále pokračovat.

Rád posdílím další materiály, dejte vědět kucera@pce.sdb.cz.


**Popis webu generovaný AI:**

# Deník hackera — Temné příběhy 🕶️💻

**Deník hackera** je interaktivní webová stránka s temným, neonově laděným vzhledem, která vypráví tři příběhy plné napětí, hádanek a QR kódů. Každý zápis (log) obsahuje krátkou dramatickou scénu a hádanku, jejímž správným vyřešením se zobrazí QR kód vedoucí k dalšímu obsahu.

## 🔍 Obsah

- 💾 HTML + CSS + JS: Žádný build systém, vše je čistě statické a připravené k hostování.
- 📱 **Responsivní design**: Vhodné pro mobily i desktopy.
- 🔐 Interaktivní logy s hádankami a odhalením QR kódů.
- 🎨 Styl ve stylu retro terminálu / hacker kultury.

## 💡 Jak to funguje

Uživatel čte jednotlivé příběhy a snaží se odhalit správný klíč — řešení hádanky. Po zadání správné odpovědi se odemkne odpovídající QR kód.

Každá odpověď se kontroluje přes jednoduchou JavaScriptovou funkci `checkAnswer()`.

## 🚀 Hosting

Stránka je nasazena na Cloudflare pages a dostupná pod adresou: https://hackerdiaries.salesianipardubice.cz.

## 📁 Struktura projektu

```
📁 /projekt
├── index.html         # Hlavní soubor s příběhy a logikou
├── stara-krev.svg     # QR kód pro první log
├── kahan.svg          # QR kód pro druhý log
├── noc.svg            # QR kód pro třetí log
```

## 🧪 Klíče k odemčení (pro testování)

- Log #01: `voják123`
- Log #02: `chemie9A`
- Log #03: `bratr00`

## 📱 Responsivita

Stránka se automaticky přizpůsobí menším obrazovkám (mobily, tablety) — zmenší se velikost textu i okrajů, aby zůstala čitelná a přehledná.

## Cíle QR kódů

QR kódy jsou nasměrované na hororové audiostorky s ukončeným koncem, které slouží jako rozjezd diskuze na hodinu nábožentsví o otázce  **Je dovoleno použít násilí k vlastní obraně?**