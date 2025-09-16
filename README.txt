FutureSkills360° – AuA-Demo (ohne LMS)
========================================

Was ist das?
------------
Ein einzelnes, barrierearmes HTML-Widget (self-contained), das Sie auf Ihrer Website hosten
und in Articulate Rise per Embed-Block einbetten können. Es speichert keine Daten dauerhaft.
Antworten werden nur in der laufenden Sitzung gehalten (sessionStorage).

Ordnerinhalt
------------
- index.html  → Alles in einer Datei (HTML, CSS, JS). Enthält 2 Demo-Szenarien.

Schnellstart
------------
1) Laden Sie die ZIP-Datei herunter und entpacken Sie sie.
2) Laden Sie den Ordner auf Ihre Website (z. B. https://IHRE-DOMAIN/fs360-aua-demo/).
3) Prüfen: Öffnen Sie im Browser https://IHRE-DOMAIN/fs360-aua-demo/index.html – das Quiz sollte laufen.
4) In Articulate Rise:
   - Erstellen Sie eine Lektion für die Zielgruppe "AuA".
   - Fügen Sie einen "Multimedia → Embed"-Block hinzu.
   - Tragen Sie als URL z. B. https://IHRE-DOMAIN/fs360-aua-demo/index.html ein.
   - Speichern, Vorschau testen.

Anpassen der Inhalte
--------------------
- Öffnen Sie index.html in einem Code-Editor.
- Suchen Sie nach "SCENARIOS". Hier können Sie neue Fragen ergänzen.
  Jede Antwort-Option hat:
    - "label": der sichtbare Text
    - "skill": der zugeordnete Future Skill (Maschinenschlüssel)
    - "weight": Gewichtung (Ganzzahl, typ. 1 oder 2)
- Nutzen Sie die bestehenden Skill-Keys aus den Kategorien in "CATEGORIES".
  (Umlaute als ae/oe/ue, keine Leerzeichen, Unterstriche als Trenner.)

Barrierefreiheit
----------------
- Überschriftenstruktur ist logisch, Focus-Stile sind sichtbar.
- Radiogruppen sind native HTML-Controls (tastaturbedienbar).
- Diagramm wird von einer Tabelle begleitet (Screenreader-freundlich).
- Kontrastfarben sind ausreichend; die Seite ist ohne Animationen.

Hinweis
-------
- Wenn Sie später mehrere Zielgruppen brauchen, kopieren Sie den Ordner, passen
  die SCENARIOS und (optional) die Texte an, und betten je Zielgruppe die passende
  index.html in die jeweilige Rise-Lektion ein (z. B. fs360-azubis-demo, fs360-lehrkraefte-demo usw.).
