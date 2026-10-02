# Nell – The First Descendant (Fanseite)

Live: **https://nell.freyna.org/**

Inoffizielle, KI-lesbare Fanseite über die Descendant **Nell** (offizieller voller Name: **Nell Hathaway**) aus *The First Descendant* (Nexon):
Überblick, Fakten, Werte auf Lv 40 (Max-Level), Fertigkeiten, Nell-exklusive Module (Max-Level), Story, exklusive Fähigkeit und Forschungskosten.

- Nur offizielle Daten: [NEXON LIBRARY – NELL](https://tfd.nexon.com/en/library/descendants/101000029) und die Metadaten der [NEXON OPEN API](https://openapi.nexon.com/game/tfd/) (`descendant.json`, `module.json`).
- Alle Werte auf Max-Level (Descendant Lv 40, Module auf maximaler Verbesserungsstufe, Waffen Lv 100 / 4 Sterne).
- Eine einzige `index.html`, Inline-CSS, kein JavaScript (nur JSON-LD), semantisches HTML mit Tabellen.
- Klartext für KIs: [`LLMS.TXT`](https://nell.freyna.org/llms.txt), [`LLMS-FULL.TXT`](https://nell.freyna.org/llms-full.txt).
- Keine Nexon-Bilder enthalten.

## Header-Bild (9:16)

Oben auf der Seite ist ein leerer 9:16-Rahmen mit „IMAGE COMING SOON“. Bild einsetzen:

1. Eigenes (oder lizenziertes) Bild im Format 9:16 (z. B. 1080×1920) als `nell.jpg` ins Hauptverzeichnis dieses Repos legen.
2. In `index.html` im `<figure class="ph" id="portrait">` das `<div class="ph-empty">…</div>` ersetzen durch:
   `<img src="nell.jpg" alt="Nell – The First Descendant" width="1080" height="1920" fetchpriority="high" decoding="async">`
   (Der Kommentar `HEADER IMAGE` in `index.html` zeigt die Stelle. Das Build-Skript macht das automatisch, sobald `nell.jpg` existiert.)

Weitere Seiten: [FREYNA.ORG](https://freyna.org/) · [MODULES.FREYNA.ORG](https://modules.freyna.org/) · [WEAPONS.FREYNA.ORG](https://weapons.freyna.org/) · [RAVEN.FREYNA.ORG](https://raven.freyna.org/) · [SERENA.FREYNA.ORG](https://serena.freyna.org/) · [ABOUT](https://zagathou.github.io/zagathou/) · [GITHUB](https://github.com/Zagathou)

Alle spielbezogenen Inhalte © [NEXON](https://tfd.nexon.com/). Inoffizielle Fanseite – nicht mit Nexon verbunden oder von Nexon unterstützt. The First Descendant ist eine Marke von Nexon.

Last Updated: 02.10.2026
