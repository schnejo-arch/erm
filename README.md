# Expositions- und Reaktionsmanagement

Eine kleine Web-App, mit der du Übungen zum Expositions- und Reaktionsmanagement planst, abhakst und im Verlauf auswertest. Die App besteht aus einer einzigen HTML-Datei und läuft komplett im Browser. Es gibt keine Anmeldung und keinen Server.

## Inhalt

1. [Schnellstart](#schnellstart)
2. [Reiter „Übungen“](#reiter-übungen)
3. [Reiter „Verlauf“](#reiter-verlauf)
4. [Reiter „Farben“](#reiter-farben)
5. [Reiter „Daten“](#reiter-daten)
6. [Wo die Daten liegen](#wo-die-daten-liegen)
7. [Auf dem iPhone wie eine App nutzen](#auf-dem-iphone-wie-eine-app-nutzen)
8. [Häufige Fragen](#häufige-fragen)

## Schnellstart

1. Öffne die App im Browser.
2. Wähle links neben dem Textfeld die Anspannung von 1 bis 10 aus.
3. Schreibe die Übung in das Textfeld und tippe auf **Übung hinzufügen** (oder drücke die Eingabetaste).
4. Setze das Häkchen vor der Übung, sobald du sie erledigt hast.
5. Im Reiter **Verlauf** siehst du, wie viele Übungen du gemacht hast und welche Belohnungen du erreicht hast.
6. Speichere im Reiter **Daten** ab und zu eine Sicherung.

## Reiter „Übungen“

### Mantras

Über der Eingabezeile steht der Rahmen **Mantras**. Schreibe einen Satz, der dir Mut macht, in das Feld (bis zu 200 Zeichen) und tippe auf **Hinzufügen** oder drücke die Eingabetaste. Jedes Mantra erscheint einzeln als Karte in Anführungszeichen, das neueste oben. Mit ✕ löschst du ein Mantra ohne Rückfrage. Mantras werden wie die Übungen im Browser gespeichert und in der Sicherung mitgesichert.

### Neue Übung eintragen

- **Anspannung (Dropdown links):** Wert von 1 bis 10. Die Auswahl „–“ bedeutet: keine Angabe.
- **Textfeld:** Die Übung darf bis zu 200 Zeichen lang sein.
- **Übung hinzufügen:** Fügt die Übung oben in die Liste der offenen Übungen ein. Das Textfeld wird geleert, damit du gleich die nächste eintragen kannst.

### Eine Übungszeile

Offene Übungen stehen in einem Rahmen mit der Beschriftung „noch offen“, erledigte in einem Rahmen mit der Beschriftung „erledigt“. Jede Übung steht in einer einzeiligen Zeile. Von links nach rechts:

| Element | Bedeutung |
| --- | --- |
| Häkchen | Markiert die Übung als erledigt. Nimmst du das Häkchen wieder weg, ist sie wieder offen. |
| Zahl (Dropdown) | Anspannung von 1 bis 10. Du kannst sie jederzeit ändern. |
| Text | Die Übung. Ist der Text zu lang, wird er mit „…“ abgeschnitten. Hältst du den Mauszeiger darüber, erscheint der volle Text. |
| Datum und Uhrzeit | Bei offenen Übungen: wann sie erstellt wurde. Bei erledigten Übungen: wann sie erledigt wurde. Mit dem Mauszeiger siehst du Erstellungs- und Erledigungszeitpunkt mit Jahr. |
| ↻ | Nur bei erledigten Übungen: „Nochmal üben“. Legt eine neue, offene Kopie der Übung mit gleicher Anspannung an. Die erledigte Übung bleibt erhalten. |
| ✕ | Löscht die Übung. Es gibt keine Rückfrage, und gelöschte Übungen zählen nicht mehr im Verlauf. |

Alle Zahlen in der Anspannungsauswahl haben standardmäßig dieselbe Farbe. Unter „Farben“ kannst du eine eigene Schriftfarbe wählen.

### Erledigte Übungen

- Im Rahmen **erledigt** stehen alle Übungen, die du in den **letzten 14 Tagen** erledigt hast. Die zuletzt erledigte steht oben.
- Ältere erledigte Übungen werden **pro Monat zusammengefasst**, zum Beispiel „Oktober 2026 (12 Übungen)“. Diese Monatszeilen sind zunächst eingeklappt.
- Tippe auf eine Monatszeile, um sie aufzuklappen (▸ wird zu ▾). Tippe erneut, um sie wieder einzuklappen. Welche Monate aufgeklappt sind, merkt sich die App nur, bis du die Seite neu lädst.

## Reiter „Verlauf“

### Kacheln

Drei Kacheln zeigen, wie viele Übungen du erledigt hast:

- **Diese Woche** (die Woche beginnt am Montag)
- **Dieser Monat**
- **Insgesamt**

Gezählt wird immer das Datum, an dem du eine Übung erledigt hast, nicht das Datum, an dem du sie eingetragen hast.

### Belohnungen

**Punkte:** Jede erledigte Übung gibt so viele Punkte, wie ihre Anspannung beträgt. Ohne Angabe gibt es 1 Punkt. Eine Übung mit Anspannung 8 bringt also 8 Punkte.

**Stufen:** Mit deinen Punkten steigst du auf. Ein Fortschrittsbalken zeigt, wie viele Punkte bis zur nächsten Stufe fehlen.

| Stufe | Ab Punkten |
| --- | --- |
| 1 Anfänger | 0 |
| 2 Mutig | 10 |
| 3 Standhaft | 30 |
| 4 Durchhalter | 75 |
| 5 Könner | 150 |
| 6 Meister | 300 |

**Serie:** Zeigt, an wie vielen Tagen in Folge du mindestens eine Übung erledigt hast, und deine beste Serie bisher. Hast du heute noch nichts erledigt, aber gestern, läuft die Serie weiter, bis der Tag vorbei ist.

**Abzeichen:** Die Abzeichen sind in zwei Gruppen getrennt: **Anzahl Übungen** und **Serie**. Erreichte Abzeichen sind farbig, noch gesperrte sind grau. Mit dem Mauszeiger siehst du die Bedingung.

| Abzeichen | Bedingung |
| --- | --- |
| 🌱 Erste Übung | 1 Übung erledigt |
| ⭐ 10 Übungen | 10 Übungen erledigt |
| 🏅 25 Übungen | 25 Übungen erledigt |
| 🏆 50 Übungen | 50 Übungen erledigt |
| 👑 100 Übungen | 100 Übungen erledigt |
| 🥈 200 Übungen | 200 Übungen erledigt |
| 🥇 300 Übungen | 300 Übungen erledigt |
| 🌟 400 Übungen | 400 Übungen erledigt |
| 💫 500 Übungen | 500 Übungen erledigt |
| 🎯 600 Übungen | 600 Übungen erledigt |
| 🌈 700 Übungen | 700 Übungen erledigt |
| 🧗 800 Übungen | 800 Übungen erledigt |
| 🚩 900 Übungen | 900 Übungen erledigt |
| 🗻 1000 Übungen | 1000 Übungen erledigt |
| 🔥 3 Tage Serie | An 3 Tagen in Folge geübt |
| ⚡ 7 Tage Serie | An 7 Tagen in Folge geübt |
| 💪 14 Tage Serie | An 14 Tagen in Folge geübt |
| 🚀 30 Tage Serie | An 30 Tagen in Folge geübt |

Erreichst du beim Abhaken eine neue Stufe oder ein neues Abzeichen, erscheint unten für fünf Sekunden eine Meldung.

### Diagramme

- **Erledigte Übungen pro Woche:** die letzten 8 Wochen. Unter jedem Balken steht der Montag der Woche.
- **Erledigte Übungen pro Monat:** die letzten 6 Monate.
- **Gesamt:** Oben steht, wie viele Übungen du insgesamt erledigt hast. Darunter zeigen Balken den Gesamtstand zum Ende der letzten 12 Monate. Der letzte Balken ist die Summe aller Übungen bisher.

Der aktuelle Zeitraum ist jeweils kräftiger eingefärbt. Auf schmalen Bildschirmen kannst du die Diagramme seitlich wischen.

## Reiter „Farben“

Hier stellst du die Farben für die ganze App ein. Die Einstellung gilt für alle Übungen gemeinsam, nicht pro Übung.

- **Farbe der Buttons:** Blau, Grün, Lila, Rot, Orange, Rosa oder Grau. Sie gilt auch für die aktive Registerkarte, Häkchen und Fortschrittsbalken.
- **Farbe der Aufgaben:** Blau, Grün, Gelb, Orange, Rot, Lila oder Rosa. Die Übungszeilen werden in einem hellen Ton dieser Farbe eingefärbt.
- **Schriftfarbe der Dropdown-Zahlen:** Betrifft nur die Schrift, nicht den Hintergrund. Alle Zahlen bekommen dieselbe gewählte Farbe.

Mit **Standard** setzt du die jeweilige Farbe auf den ursprünglichen Wert zurück.

Hell und Dunkel richten sich automatisch nach der Einstellung deines Geräts.

## Reiter „Daten“

### Sicherung speichern

Erstellt eine Datei mit dem Namen `erm-sicherung-JJJJ-MM-TT.json`. Sie enthält alle Übungen, deine Mantras und deine Farbeinstellungen und landet im Download-Ordner deines Geräts. Darunter zeigt die App an, wann du zuletzt gesichert hast.

Bewahre die Datei an einem sicheren Ort auf, zum Beispiel in deiner Cloud oder auf einem USB-Stick. Sie ist nicht verschlüsselt.

### Sicherung laden

Liest eine zuvor gespeicherte Sicherungsdatei wieder ein, etwa nach einem Gerätewechsel oder nachdem Browserdaten gelöscht wurden.

- Vor dem Laden fragt die App nach und nennt die Anzahl der Übungen in der Datei.
- Übungen mit gleicher Kennung werden durch die Version aus der Sicherung ersetzt. Alle anderen Übungen auf dem Gerät bleiben erhalten.
- Die Farbeinstellungen aus der Sicherung werden übernommen.
- Mantras aus der Sicherung werden hinzugefügt, vorhandene Mantras bleiben erhalten.
- Dateien, die nicht aus dieser App stammen, werden abgelehnt.

### Speicher auf diesem Gerät

Die App bittet den Browser, die Daten dauerhaft zu behalten, und zeigt an, ob das geklappt hat. Das schützt vor automatischem Aufräumen bei Speichermangel, aber nicht davor, dass du selbst Browserdaten löschst.

## Wo die Daten liegen

Alles, was du eingibst, wird im `localStorage` deines Browsers gespeichert, also nur auf deinem Gerät. Es wird nichts an einen Server gesendet. Weder der Betreiber der Seite noch GitHub sehen deine Einträge.

Daraus folgt:

- Die Daten gelten **pro Browser und pro Gerät**. Am Handy und am Computer hast du getrennte Einträge.
- Die Daten sind **weg**, wenn du Browserdaten löscht („Cookies und Websitedaten“, „Verlauf löschen“).
- Im **privaten Modus** werden sie beim Schließen gelöscht.
- **Safari** kann Daten von Webseiten löschen, die etwa 7 Tage nicht geöffnet wurden. Eine Installation auf dem Home-Bildschirm verhindert das (siehe nächster Abschnitt).
- Die Daten sind **nicht verschlüsselt**. Wer Zugriff auf dein entsperrtes Gerät hat, kann sie im Browser auslesen.

Der wichtigste Schutz ist deshalb eine regelmäßige Sicherung im Reiter **Daten**.

## Auf dem iPhone wie eine App nutzen

1. Öffne die Seite in **Safari**.
2. Tippe auf **Teilen** (Quadrat mit Pfeil).
3. Wähle **Zum Home-Bildschirm**.
4. Öffne die App künftig über das neue Symbol.

Nach dem Hinzufügen kann es sein, dass die App zunächst leer ist, weil sie getrennte Daten von Safari verwendet. Lade in diesem Fall eine vorher gespeicherte Sicherung. Mache die Sicherung also vor dem Hinzufügen.

## Häufige Fragen

**Meine Übungen sind verschwunden.**
Vermutlich wurden Browserdaten gelöscht, oder du nutzt einen anderen Browser, ein anderes Gerät oder den privaten Modus. Lade deine letzte Sicherung im Reiter **Daten**.

**Die Sicherung lässt sich nicht laden.**
Prüfe, ob die Datei aus dieser App stammt (`erm-sicherung-….json`) und nicht verändert wurde.

**Ich finde die gespeicherte Sicherungsdatei nicht.**
Sieh im Download-Ordner deines Geräts nach. Auf dem iPhone findest du sie in der App **Dateien** unter **Downloads**.

**Ich möchte alles zurücksetzen.**
Lösche die Websitedaten dieser Seite in den Browser-Einstellungen. Speichere vorher eine Sicherung, falls du die Daten behalten willst.

**Die Zahl in einer Zeile hat sich geändert, die Punkte auch.**
Die Punkte hängen von der aktuellen Anspannung der erledigten Übungen ab. Ändert man die Zahl einer erledigten Übung, ändern sich die Punkte entsprechend.
