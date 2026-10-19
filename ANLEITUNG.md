LIA – AR-Avatar zur generalistischen Pflegeausbildung
=====================================================

Inhalt des Ordners
  index.html      Die AR-Seite (Startseite, Karten-AR, Tisch-AR, Druckkarte)
  lia-ziel.mind   Tracking-Daten für das Kartenmotiv (nicht verändern)
  lia-ziel.jpg    Das Kartenmotiv, auf dem Lia steht

1. Online stellen (https ist Pflicht, sonst gibt es keine Kamera)
   Variante A – eigene Website: Den ganzen Ordner z. B. nach
     https://www.awo-bamberg.de/lia/ hochladen (IT/Webagentur).
   Variante B – kostenlos in 2 Minuten: https://app.netlify.com/drop öffnen
     und den Ordner "lia-ar" in das Browserfenster ziehen. Netlify vergibt
     sofort eine https-Adresse (später eigener Name möglich, Konto nötig,
     damit die Seite dauerhaft bleibt).
   Wichtig: Alle drei Dateien müssen im selben Ordner liegen.

2. Karte drucken
   Die fertige Adresse am PC öffnen → "Karte drucken" → Drucken.
   Format A5 quer, farbig, möglichst mattes Papier. Der QR-Code zeigt
   automatisch auf genau diese Adresse.
   Tipp: Karte auf Pappe kleben, damit sie flach liegt.

3. Benutzen
   QR-Code scannen → "Mit Karte starten" → Kamera erlauben →
   Handy über das Bildmotiv halten (ca. 30–40 cm). Lia erscheint auf der
   Karte, winkt und erzählt. Mit + / – lässt sich ihre Größe ändern.
   Auf Android-Handys mit ARCore gibt es zusätzlich
   "Ohne Karte auf den Tisch stellen": Fläche suchen, antippen, fertig.

Hinweise
  - Die Stimme kommt aus der Sprachausgabe des Handys. iPhones klingen gut,
    noch besser nach Laden einer "Premium"-Stimme (Einstellungen →
    Bedienungshilfen → Gesprochene Inhalte → Stimmen → Deutsch).
  - Lautschalter am iPhone: Ist das Handy stumm geschaltet, bleibt Lia
    teilweise stumm. Dann Untertitel nutzen oder Ton einschalten.
  - Die Seite lädt three.js und MindAR von cdn.jsdelivr.net; das Gerät
    braucht dafür Internet.
  - Kapitel "Bei der AWO" und Texte stehen im oberen Teil von index.html
    (Abschnitt "Inhalte") und lassen sich dort anpassen.
