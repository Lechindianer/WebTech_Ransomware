# WebTech Vortrag

Dauer lt. Tom: ca. 25 Minuten

Fallbeispiele (3 min):
-----
- Dettelbach (Stadt in Unterfranken:
	(https://www.polizei.bayern.de/unterfranken/news/presse/aktuell/index.html/237562)
	(https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/Wappen_von_Dettelbach.svg/140px-Wappen_von_Dettelbach.svg.png)
	- Städtische Server mit "Tesla-Crypt" infiziert
	- Infektion per E-Mail-Anhang
	- Backups vorhanden, aber nicht mehr wiederherstellbar.
	- Nach Zahlung von ca. 490 € konnten große Teile der Daten entschlüsselt werden

- Lukaskrankenhaus Neuss
	(http://www1.wdr.de/cyberangriff-lukaskrankenhaus-neuss-100.html)
	- Infektion per E-Mail-Anhang
	- Sofortmaßnahme: Abschalten aller Dienste und Server
	- Organisation mit Formularen auf Papier
	- Aktuelles Backup vorhanden und wiederherstellbar

Kryptographie (3 min):
-----

- Symmetrische Verschlüsselung
	- Gleicher Schlüssel für Ver- und Entschlüsselung
	- Typischer Vertreter: AES (Advanced Encrytpion Standard)
	- Schneller Algroithmus mit Prozessorunterstützung
	- Geeignet auch für große Datenmengen

- Asymmetrische Verschlüsselung
	- Zwei Schlüssel: Verschlüsselung und Entschlüsselung (Private / Public)
	- Mathematisch sicher
	- Großer Rechenaufwand => Nicht für große Datenmengen

- Kombination:
	- Sitzungsschlüssel zufällig erzeugen
	- Mittels asym. verschlüsseln
	- Als Schlüssel für AES verwenden


Funktionsweise:
-----




Fazit:
-----
- Backups, Backups, Backups
- Wiederherstellung testen
- Virenscanner schützen nicht vor allem
- Ambitionierte Nutzer finden einen Weg um die Sicherheit zu umgehen
