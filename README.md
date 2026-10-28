# Trójkąt 100 (PWA)

Piąta apka warsztatowa Roberta (po Kalkulatorze PCD, Makrocyklach L9xx, Cyklach stałych i Pasowaniach ISO 286).
Trygonometria warsztatowa na jednej ręce — jak stara ściąga frezera, tylko zawsze w kieszeni.

## Zakładki

- **Klin** — klin sinusowy: kąt → wysokość klocków H = L·sin α (L = 100/200/300 mm lub własna)
  oraz w drugą stronę: wysokość klocków → kąt (α = arcsin(H/L)).
- **Funkcje** — sin/cos/tan/cot dla dowolnego kąta + wartości na 100 mm podstawy
  (przyprostokątna, rzut, podniesienie — stąd nazwa „Trójkąt 100").
- **Trójkąt** — trójkąt prostokątny: podaj dokładnie 2 dane (a, b, c lub α) → reszta boków,
  oba kąty, pole P i wysokość h. Presety: 3·4·5, 30–60–90, 45°.

## Kąty

Wpisujesz jak na rysunku — stopnie dziesiętnie (30,5) albo stopnie-minuty-sekundy (30 30, 30°30′15″).
Wyniki kątów apka podaje w obu formatach jednocześnie.

## Pliki

- `index.html` — cała apka (vanilla JS, bez zależności)
- `sw.js` — service worker, cache `trojkat-100-v1`
- `manifest.json` + `icon.svg` + `icon-mask.svg` — PWA
- `README.md` — ten plik

## Weryfikacja

Silnik przeszedł 34 testy krzyżowe (klasyki: sin 30° = 0,5 → H = 50 mm na klinie 100;
trójkąt 3·4·5 → α = 36,8699°; 30–60–90; a=20, α=35° itd.). Czysta trygonometria — żadnych
tabel, żadnych zaokrągleń normowych.
