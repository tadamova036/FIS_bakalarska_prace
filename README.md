# Analýza nákupního chování a výkonnosti prodeje

Repozitář obsahuje praktickou část bakalářské práce zaměřené na analýzu nákupního chování zákazníků a výkonnosti směn ve vybraném podniku rychlého občerstvení.

## Cíl práce

Cílem je identifikovat faktory ovlivňující výkonnost směn a nákupní chování zákazníků a na základě dat formulovat doporučení pro management.

## Struktura projektu

```plaintext
BP/
├── clustering/
├── detekce_anomalii/
├── histogramy/
├── priprava_dat/
├── eda_grafy/
├── script.ipynb
└── README.md
```

* clustering/
  Výstupy shlukové analýzy (segmentace směn podle výkonnosti).

* detekce_anomalii/
  Výstupy detekce anomálií (identifikace netypických směn).

* histogramy/
  Vizualizace základních metrik dat- SOS, AGC, Transakce_za_hodinu.

* priprava_dat/
  Výstupy z předzpracování dat a vytvořené agregované datové sady.

* eda_grafy/
  Grafy vytvořené v rámci explorační analýzy dat.

* script.ipynb
  Hlavní Jupyter Notebook obsahující celý analytický proces (příprava dat, explorační analýza, statistická analýza, shlukování a detekce anomálií).

## Použité metody

* explorační analýza dat
* testování statistických hypotéz (t-test, ANOVA)
* shluková analýza (K-means)
* detekce anomálií (Isolation Forest)

## Data

Data v repozitáři jsou agregovaná a anonymizovaná a neobsahují žádné citlivé ani identifikovatelné informace.

## Použité nástroje

* Python (pandas, numpy, scikit-learn)
* Jupyter Notebook
* Power BI

## Výstupy

Výsledkem analýzy je identifikace typů směn, odhalení anomálních směn a analýza vlivu vybraných faktorů na výkonnost prodeje.

## Kontext

Projekt vychází z metodiky CRISP-DM a je součástí bakalářské práce na Vysoké škole ekonomické v Praze.

## Autor

Tereza Adamová
