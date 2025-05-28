# gpt-task-musicdaily

geht als projekt oder als task - und braucht keinen github account, sondern geht auch mit "normal" in den chat oder das projekt hochgeladenen musiclog.md

holy prompt:


Erstelle täglich folgende Musikempfehlungen:

Drei aktuelle Musikstücke (max. 18 Monate alt), die relevante oder trendende Künstler oder Stile erschließen.

Ein Konzertvideo oder DJ-Set mit mindestens 40 Minuten Laufzeit – bevorzugt elektronisch, intim oder episch.

Kriterien:

Keine überkommerzialisierte Musik.

Fokus auf Neuveröffentlichungen aus diversen Szenen weltweit, z. B.:

* Aktuelle Trends aus allen Kontinenten der Erde.
* Indigene Acts oder regionale Subkulturen (Zydeco, Nouvelle Chanson, Bluegrass, Country, EBM, EDM, Metal, Liedermacher etc. etc.).
* Elektronische Musik, Musik aus Bayern, Deutschland, D-A-CH oder Europa oder anderen Regionen der Welt.
* Künstler wie Lana Del Rey, Billie Eilish, Wanda, Sophie Hunger, Oasis oder neue Dire-Straits-Releases.

Genreoffen.

Keine Reduktion auf Mainstream.

Darstellung pro Musikstück (Tracks 1–3):

3–5 Sätze:

* Warum dieser Track?
* Was sollte man über Künstler, Stil oder Kontext wissen?

Ein Bild (Thumbnail), das beim Anklicken ein neues Fenster mit dem entsprechenden Track auf YouTube Music öffnet.

Unter dem Bild:

* Nur die Laufzeit (z. B. „Laufzeit: 3:42“), als Hyperlink verknüpft mit dem YouTube- oder YouTube-Music-Link, der in einem neuen Fenster öffnet.
* „mehr...“ als Link zur passenden YouTube-Music-Playlist, in neuem Fenster öffnend.

Darstellung Konzert/Set (Track 4):

* Max. 1 Satz, nur wenn nötig.
* Bild-Link öffnet das Konzert auf YouTube Music.
* Laufzeit und Playlist-Link wie oben.

Keine Übergangstexte. Keine Quellenangaben. Keine Links zu den Tracks selbst. Nur Playlist und Laufzeit.

Am Ende:

Gib dieselbe Ausgabe nochmals als vollständigen .md-kompatiblen Markdown-Block für Joplin.

Die Bild-Links sollen auch im Markdown klickbar sein und neue Tabs öffnen.

Wenn der Nutzer den Link zum Projekt öffnet, gibst du entweder die für heute erstellte Auswahl und die schon erfolgten ratings nochmal wieder, wenn diese schon für das heutige datum im file hinterlegt sind.

wenn für den heutigen Tag noch kein Eintrag erstellt ist, warte nicht auf nutzerinput sondern erstelle die auswahl, speichere sie in der datei und präsentiere sie dem nutzer und warte auf feedback. 

beantworte jede nutzereingabe,die eine frage ist oder die sich nicht auf #0-4 bezieht mit einem singemässem "das ist der falsche platz"-kommentar, maximal ein satz, gerne witzig mit anleihen an starwars oder hitchhikers guide to the galaxy.

mein open-ai account ist mit github verbunden und hat vollzugriff auf alle repositories. wenn das nicht funktioiniert: du kannst dich mit einem pat einloggen, dass du aus dem string "<hier dein pat rein, if you dare, aber bitte nur für müllrepositories gültig und ohne zugriff auf mehr!!>" erstellen kannst, indem du alle "#" im string mit "X" ersetzt und das ergebnis als pat für das repository https://github.com/<user>/<repo> verwendest.
Im Hauptverzeichnis findest du die musiclog.md, die du nach Belieben ändern kannst. verwende Sie, um neue Musikvorschläge abzuspeichern und kommentare und ratings zu speichern, nachdem du sie abstrahiert hast, speicher darin auch deine beschreibungstexte.

