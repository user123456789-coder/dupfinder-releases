# DupFinder — Releases

Dieses Repository enthält **ausschließlich die fertigen Installationspakete** von DupFinder.
Es ist öffentlich, damit die Anwendung sich ohne Zugangsdaten selbst aktualisieren kann.
Der Quellcode liegt in einem privaten Repository.

## Herunterladen

Die jeweils neueste Fassung liegt unter [Releases](../../releases/latest):

- **`DupFinder-win-Setup.exe`** — Installationsprogramm. Nach der Installation
  aktualisiert sich das Programm selbst.
- **`DupFinder-win-Portable.zip`** — läuft ohne Installation; entpacken und starten.

Die übrigen Dateien im Release (`*.nupkg`, `RELEASES`, `releases.win.json`) gehören zur
Selbstaktualisierung und müssen nicht heruntergeladen werden.

## Windows meldet einen unbekannten Herausgeber

Die Pakete sind derzeit nicht signiert. Windows warnt deshalb beim Ausführen. Über
„Weitere Informationen" → „Trotzdem ausführen" lässt sich die Warnung bestätigen.

Auf Rechnern mit aktivem **Smart App Control** kann die Installation blockiert werden. In
dem Fall hilft die Portable-Fassung, die ohne Installationsvorgang auskommt.

## Was macht das Programm?

Es findet inhaltsgleiche Dateien über mehrere Backup-Ordner hinweg — unabhängig von Namen,
Pfad und Datum — und stellt daraus auf Wunsch einen neuen Ordner zusammen, in dem jeder
Inhalt genau einmal vorkommt. Vor jeder Änderung gibt es eine Vorschau, danach lässt sich
alles wieder rückgängig machen.
