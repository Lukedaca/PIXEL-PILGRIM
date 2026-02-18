# ⚔️ PIXEL PILGRIM DELUXE QUEST

Game created by Lukáš with Claude Sonnet 4.6

---

## O hře

Pixel Pilgrim DELUXE QUEST je originální 2D platformerová hra vytvořená v čistém HTML5 Canvas + JavaScript bez jakýchkoliv externích frameworků. Hlavní hrdina je cestovatel v širokém klobouku a plášti, který prochází třemi unikátními světy a poráží bossy na konci každého.

---

## Jak spustit

Stáhni soubor `index.html` a otevři ho v libovolném moderním prohlížeči. Hra nevyžaduje žádnou instalaci, server ani internetové připojení.

Nebo hraj online: https://pixelpilgrim.vercel.app

---

## Ovládání

| Klávesa | Akce |
|---|---|
| ← → / A D | Pohyb |
| ↑ / W / Mezerník | Skok |
| ↑ ↑ (ve vzduchu) | Dvojskok |
| Shift / Z / X | Sprint |
| ↓ / S | Dřep |
| P / Escape | Pauza |

Na mobilních zařízeních je k dispozici dotykové ovládání — D-pad vlevo, tlačítka JUMP / RUN / 2×↑ vpravo.

---

## Světy

**🌿 Realm 1 — Enchanted Forest**
Kouzelný les. Boss: 🐗 Boar King (6 HP). Čas: 300s. Obtížnost: ★★☆

**💎 Realm 2 — Crystal Caves**
Temné jeskyně s křišťály. Boss: 🐙 Krakenstein (7 HP). Čas: 250s. Obtížnost: ★★★

**🔥 Realm 3 — Dark Fortress**
Pevnost s lávou. Boss: 🔥 Ignis Rex (8 HP). Čas: 200s. Obtížnost: ★★★★

---

## Herní mechaniky

**Pohyb & Fyzika**
- Coyote time — skok krátce po opuštění platformy stále funguje
- Jump buffer — skok se zaregistruje těsně před dopadem na zem
- Proměnná výška skoku — přidržením klávesy skočíš výš
- Dvojskok — druhý skok ve vzduchu s modrým particle efektem
- Inerce a zatáčení — postava má setrvačnost, prudké otočení je rychlejší

**Power-upy**
- 🍄 Houbička — postava je větší, vydrží jeden zásah navíc
- ⭐ Hvězda — dočasná nesmrtelnost, porážení nepřátel dotykem
- 🪙 Mince — +100 bodů, 💎 Gem = +500 bodů

**Nepřátelé**
- Goomba — základní nepřítel, šlápnutím eliminuješ
- Koopa — má krunýř, obtížnější na poražení
- Para Koopa — létá ve vlnách
- Boss — skáče, střílí projektily, ve fázi 2 zrychlí a střílí více

**Combo systém**
Šlápnutí na více nepřátel za sebou bez dotyku země multiplifikuje body: 100 → 200 → 400 → 800 → 1600 → 3200 → 6400 bodů.

---

## Technické informace

- Technologie: HTML5 Canvas API + Vanilla JavaScript (ES6+)
- Audio: Web Audio API — procedurálně generované zvuky, bez souborů
- Závislosti: žádné — jeden soubor, vše v sobě
- Kompatibilita: Chrome 80+, Firefox 75+, Edge 80+, Safari 14+, mobilní prohlížeče
- Velikost: ~100 KB (jeden HTML soubor, bez obrázků)
- Rozlišení: 820 × 460 px

---

## Tipy

- Snaž se šlápnout na nepřátele za sebou bez dotyku země — body se exponenciálně násobí až na 6400 za jedno šlápnutí.
- Přes velké mezery využij nejprve normální skok a pak ve vzduchu druhý skok pro maximální dosah.
- Pokud sesbíráš hvězdičku těsně před bossem, přejíždění ho dá damage bez rizika.
- Po ztrátě poloviny HP boss zrychlí a začne střílet dvojité projektily — drž se ve větší vzdálenosti.

---

Autor: Lukáš · Vytvořeno s AI · © 2026
