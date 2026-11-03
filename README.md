# Kita-RisikoCheck – Andreas Aguirre

Eine lokal laufende, responsive Web-App zur strukturierten **vorläufigen** Risiko- und Schutzanalyse in Kindertageseinrichtungen.

## Direkt testen

1. ZIP-Datei entpacken.
2. `index.html` im Browser öffnen (auch ohne Internet möglich).
3. Mit „Eigene Analyse starten“ beginnen oder „Musteranalyse laden“ auswählen.
4. Angaben in den Schritten 1–4 erfassen; in Schritt 5 Text kopieren, als TXT speichern oder über „Drucken / als PDF speichern“ als PDF ausgeben.

**Datenschutz:** Keine Datenbank, keine Anmeldung, kein Tracking, kein LocalStorage und keine Übertragung von Eingaben. Eingaben gehen beim Schließen oder Neuladen verloren. Keine personenbezogenen Falldaten eingeben.

## Auf GitHub Pages veröffentlichen

1. Auf [github.com](https://github.com) anmelden und ein neues **öffentliches Repository** anlegen, beispielsweise `kita-risikocheck`.
2. Die ZIP **entpacken**. In GitHub unter **Add file → Upload files** die vier Dateien `index.html`, `logo.jpeg`, `favicon.svg` und `README.md` **einzeln in das Hauptverzeichnis** hochladen. Mit **Commit changes** bestätigen.
3. Im Repository **Settings → Pages** öffnen. Unter **Build and deployment** die Quelle **Deploy from a branch** wählen, Branch `main`, Ordner `/(root)` und **Save**.
4. Einige Minuten warten. Die Website ist anschließend typischerweise unter `https://DEIN-NUTZERNAME.github.io/kita-risikocheck/` erreichbar. Der genaue Link steht in **Settings → Pages**.
5. Bei Änderungen die aktualisierte `index.html` erneut hochladen und committen.

## Hinweise

- Die App arbeitet ausschließlich mit HTML, CSS und JavaScript ohne Bibliotheken, APIs oder Backend.
- Das fiktive Beispiel ist anonymisiert und ausdrücklich **keine** reale Einrichtungsbewertung.
- Ankreuzungen bestätigen nur Angaben der Bearbeitenden; sie führen **nicht** automatisch zu einer günstigen Risikobewertung.
- Alle Einstufungen bleiben vorläufig. Die verpflichtende fachliche Einschränkung wird auf der Startseite, im Bewertungsprozess und im Ergebnis angezeigt.
- Fachliche, rechtliche und landesspezifische Meldepflichten sind durch die Verantwortlichen im Einzelfall zu prüfen.

© Andreas Aguirre – Coaching für Kitas & Familienzentren · https://www.andreas-aguirre.de
