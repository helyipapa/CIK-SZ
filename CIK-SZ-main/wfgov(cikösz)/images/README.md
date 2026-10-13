# images/

Ide töltsd fel az LSGOV logóját és egyéb képeket.

## Ajánlott fájlok:
- `logo.png`        – Fő logó (ajánlott: 512×512px, átlátszó háttér)
- `logo-circle.png` – Körvágott verzió (navigáció és avatárokhoz)
- `lsgov.svg`       – Jelenlegi LSGOV-jelvény; az oldal ezt használja logóként és ikonként

## Logó beillesztése az index.html-be:
Keresd meg ezeket a elemeket és cseréld le a betűt képre:

### Navigáció (.nav-seal):
```html
<!-- Helyett: -->
<div class="nav-seal">C</div>
<!-- Ezt írd: -->
<div class="nav-seal">
  <img src="images/logo-circle.png" alt="LSGOV logó" />
</div>
```

### Hero kör (.hero-crest):
```html
<!-- Helyett: -->
<div class="hero-crest">C</div>
<!-- Ezt írd: -->
<div class="hero-crest">
  <img src="images/logo.png" alt="LSGOV pecsét" />
</div>
```

### Polgármester avatar (.leader-avatar):
```html
<!-- Helyett: -->
<div class="leader-avatar">G</div>
<!-- Ezt írd: -->
<div class="leader-avatar">
  <img src="images/polgarmester.jpg" alt="DR Gróf Ramos TurboFutyi Atya" />
</div>
```
