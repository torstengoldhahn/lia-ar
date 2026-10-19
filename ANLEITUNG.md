LIA – AR-Avatar zur generalistischen Pflegeausbildung
=====================================================

Inhalt des Ordners
  audio/          Lias Stimme: lia-de.mp3 / lia-en.mp3 (+ Zeitmarken .json)
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
   QR-Code scannen → "Deutsch" oder "English" antippen → Kamera erlauben.
   Ohne Karte: Handy schräg auf den Tisch richten und dort tippen, wo Lia
   stehen soll. Android-Handys mit ARCore erkennen die Tischfläche echt;
   iPhones nutzen den Lagesensor (Lia bleibt beim Drehen des Handys stehen,
   beim Herumlaufen wandert sie mit).
   Mit Karte (am genauesten, auch auf dem iPhone): "Ich habe die Lia-Karte"
   tippen und Handy über das Bildmotiv halten.
   Oben: Sprache DE/EN umschalten, + / – für die Größe.

Hinweise
  - Lias Stimme besteht aus zwei durchgehenden Tonspuren (Deutsch und
    Englisch) im Ordner audio/. Die .json-Dateien enthalten die Zeitmarken
    der Sätze und die Lippenbewegung. Wer Texte ändert, braucht neue Spuren.
  - Nach dem Scannen einmal antippen: Erst dann dürfen Handys Ton abspielen.
  - Die Seite lädt three.js und MindAR von cdn.jsdelivr.net; das Gerät
    braucht dafür Internet.
  - Kapitel "Bei der AWO" und Texte stehen im oberen Teil von index.html
    (Abschnitt "Inhalte") und lassen sich dort anpassen.
