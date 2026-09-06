# DupFinder

**Findet doppelte Dateien über mehrere Backup-Ordner hinweg und baut daraus ein einziges,
vollständiges Backup ohne Doppelungen.**

Wer über Jahre mehrere Backups angelegt hat, hat dieselben Dateien oft fünfmal auf der
Platte — unter verschiedenen Namen, in verschiedenen Ordnern, mit verschiedenen Datumsangaben.
DupFinder erkennt sie am Inhalt, nicht am Namen, und führt alles in einem sauberen
Zielordner zusammen.

---

## Installieren

**[➜ Zum aktuellen Download](../../releases/latest)**

1. `DupFinder-win-Setup.exe` herunterladen und doppelklicken.
2. Windows zeigt **„Der Computer wurde durch Windows geschützt"**. Das ist normal — die
   Software ist nicht kostenpflichtig signiert. Auf **„Weitere Informationen"** klicken und
   dann auf **„Trotzdem ausführen"**.
3. Die Installation läuft ohne weitere Fragen durch. Es sind **keine Administratorrechte**
   nötig; alles landet im eigenen Benutzerprofil.
4. Danach steht DupFinder im Startmenü und auf dem Desktop.

Künftige Verbesserungen holt sich das Programm selbst — einmal installieren genügt.

### Wenn die Installation blockiert wird

Auf manchen Windows-11-Rechnern ist **Smart App Control** aktiv und lässt unbekannte
Installationsprogramme gar nicht erst zu. Dann stattdessen
`DupFinder-win-Portable.zip` herunterladen, in einen beliebigen Ordner entpacken und
`DupFinder.exe` starten. Diese Fassung wird nicht installiert und aktualisiert sich nicht
selbst, funktioniert sonst aber genauso.

### Voraussetzungen

Windows 10 oder 11, 64 Bit. Sonst nichts — es muss keine Laufzeitumgebung nachinstalliert
werden.

---

## So benutzt du es

Das Programm führt in vier Schritten durch die Arbeit:

1. **Ordner** — die Backup-Ordner hinzufügen, die verglichen werden sollen. Die Reihenfolge
   entscheidet später, welche Kopie behalten wird: Der oberste Ordner gewinnt.
2. **Suchen** — DupFinder liest die Ordner. Jederzeit abbrechbar, es wird dabei nichts
   verändert.
3. **Ergebnis** — was doppelt vorliegt und wie viel Platz sich sparen lässt. Auf Wunsch als
   Tabelle exportierbar.
4. **Zusammenführen** — Zielordner wählen, **Vorschau berechnen**, prüfen, und erst dann
   ausführen.

### Es geht nichts verloren

- Der Standardmodus **kopiert**. Die Backup-Ordner bleiben unangetastet, bis du dich selbst
  vom Ergebnis überzeugt hast.
- Vor jeder Änderung gibt es eine **Vorschau**, die genau auflistet, was passieren würde.
- Nach dem Zusammenführen lässt sich alles mit einem Klick **rückgängig** machen.
- Dateien, die nicht auf Duplikate geprüft wurden — etwa leere oder versteckte —, werden
  trotzdem übernommen. Das Ergebnis ist vollständig, nur eben ohne Doppeltes.

### Läuft das Programm lokal?

Ja. Deine Dateien werden ausschließlich auf deinem Rechner gelesen und verglichen. Es
werden keine Namen, Pfade oder Inhalte irgendwohin übertragen. Die einzige Netzverbindung
ist die Frage beim Start, ob eine neuere Programmfassung vorliegt.

---

## Zu diesem Repository

Hier liegen **ausschließlich die fertigen Pakete**. Es ist öffentlich, damit die
Selbstaktualisierung ohne Zugangsdaten funktioniert; der Quellcode liegt privat.

Die Dateien `*.nupkg`, `RELEASES` und `releases.win.json` gehören zur Selbstaktualisierung
und müssen nicht heruntergeladen werden.
