# PHANTOM Research Lab

Wissenschaftliches Lehrprojekt zur KI-Kompetenz.

**Transparenz:** Prof. Dr. Adrian Matthias Falkenried ist eine fiktive Person.
Das Falkenried-Paradoxon ist ein eigens entwickeltes, nicht empirisch validiertes Lehrmodell.
Die auf der Website genannten realen Forschungsarbeiten validieren dieses Modell nicht.

Website: https://renkerweiss.github.io/phantom_research/

## Veröffentlichung

Statische Dateien im Repository-Stamm. Der bestehende Pages-Build veröffentlicht main;
die erfolgreiche ursprüngliche Bereitstellung ist unter
https://github.com/renkerweiss/phantom_research/actions/runs/39979427286 dokumentiert.
.nojekyll deaktiviert die Jekyll-Verarbeitung; eine zusätzliche Jekyll-Konfiguration ist nicht erforderlich.

In Settings > Pages prüfen: Deploy from a branch, main, / (root), sowie Enforce HTTPS.
Die Verwaltungsoptionen konnten über die verwendete GitHub-Verbindung nicht direkt ausgelesen
oder geändert werden. Der Browser war nicht bei GitHub angemeldet.
Keine benutzerdefinierte Domain/CNAME wird benötigt.

## SEO und Crawling

- Deutscher Seitentitel und Beschreibung mit ausdrücklicher Fiktionskennzeichnung.
- Absolute HTTPS-Canonical-URL, Open Graph und Twitter Summary-Metadaten.
- JSON-LD als WebPage, ohne die fiktive Person als reale Wissenschaftlerin oder realen Wissenschaftler auszuzeichnen.
- Sprachangabe, UTF-8 und mobile Viewport-Angabe vorhanden.
- sitemap.xml enthält ausschließlich die kanonische Startseite; keine Fragment-URLs oder erfundenen Änderungsdaten.
- index, follow erlaubt Indexierung, garantiert sie aber nicht.

### Wichtige Grenze von robots.txt

Crawler lesen die Datei an der Domainwurzel:
https://renkerweiss.github.io/robots.txt
Die Projektdatei https://renkerweiss.github.io/phantom_research/robots.txt ist dort **nicht wirksam**.
Bei Bedarf die Allow- und Sitemap-Zeilen in die bestehende Root-Datei einfügen
(im separaten Repository renkerweiss/renkerweiss.github.io, sofern vorhanden und für diese Domain genutzt).
Vorhandene Regeln anderer Projekte dabei erhalten. Eine übergeordnete Disallow-Regel kann
nicht durch die Projektdatei oder den robots-Meta-Tag aufgehoben werden.

Alternativ bzw. ergänzend in Google Search Console die URL-Präfix-Property
https://renkerweiss.github.io/phantom_research/ verifizieren und https://renkerweiss.github.io/phantom_research/sitemap.xml einreichen.
Dafür ist die Anmeldung des Eigentümers und dessen individueller Verifizierungscode erforderlich;
ein solcher Code wurde nicht erfunden oder hinzugefügt.

Dokumentation:
- https://developers.google.com/search/docs/crawling-indexing/robots/create-robots-txt
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

