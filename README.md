# 🏺 Latinské BINGO

Interaktivní bingo hra pro hodiny latiny na střední škole. Bez instalace, bez serveru — stačí otevřít v prohlížeči nebo nasadit na GitHub Pages jedním kliknutím.

## ✨ Co to umí

| Záložka | Kdo ji používá | Co dělá |
|---|---|---|
| **Losování** | Učitel (projektor) | Náhodně tahá pojmy, zobrazuje latinský výraz + překlad |
| **Moje karta** | Každý žák (mobil / PC) | Generuje unikátní 5×5 kartu, označuje políčka, detekuje BINGO |
| **Pojmy** | Kdokoliv | Přehled všech 89 pojmů s překlady |

- 45 latinských slovíček (*aqua, bellum, tempus*…)
- 44 římských reálií (*Caesar, Koloseum, veni vidi vici*…)
- Automatická detekce BINGO (řada, sloupec, diagonála)
- Funguje offline po prvním načtení

## 🚀 Nasazení na GitHub Pages

1. Forkni nebo nahraj tento repozitář na GitHub
2. Jdi do **Settings → Pages**
3. V sekci *Source* vyber větev `main` a složku `/ (root)`
4. Klikni **Save** — za chvíli dostaneš odkaz `https://tvoje-jmeno.github.io/latinbingo/`

## 🗂️ Struktura projektu

```
latinbingo/
├── index.html      ← celá aplikace (jedna stránka)
└── README.md       ← tento soubor
```

## 🎮 Jak hrát

1. Učitel otevře aplikaci na projektoru, žáci na svých zařízeních
2. Každý žák klikne **Nová karta** — každá karta je jiná
3. Učitel kliká **Vytáhni pojem** a čte latinský výraz nahlas
4. Žáci označují políčka; prostřední políčko FREE je zdarma
5. Kdo první doplní řadu, křičí **BINGO!**

## 📝 Přidání vlastních pojmů

V souboru `index.html` najdi pole `const TERMS = [` a přidej řádky ve formátu:

```js
{ t: "latinský výraz", s: "český překlad", c: "vocab" },   // slovíčko
{ t: "Název reálie",   s: "stručný popis", c: "realia" },  // reálie
```

## Licence

Volně k použití pro vzdělávací účely.
