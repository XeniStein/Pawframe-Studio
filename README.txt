PAWFRAME STUDIO – LOKALE IPAD-VERWALTUNG
========================================

Enthaltene Funktionen
- Akquise-Pipeline: Akquise, Vorgespräch, Auftrag erstellt, Auftrag durchgeführt, Bestandskunde
- Privatkunden und Geschäftskunden getrennt verwalten
- Kontaktfelder: Name, Telefon, E-Mail, Channel, aktiv/passiv, Status, Datum, Tarif, Vertragsmodell, Preis/Konditionen, Notizen
- Geschäftskunden: Einzelauftrag oder monatliches Abo
- Tarife mit Preis, Abrechnungsart und Kundengruppe
- Dokumentenablage mit Kundenverknüpfung (PDF, Office-Dokumente, Bilder, TXT)
- Kennzahlen: private und geschäftliche Einzelaufträge sowie Abo-/Einzelkundenanteile
- JSON-Datensicherung und Wiederherstellung
- Offline-Betrieb nach erstmaligem Laden und lokaler Speicherung im Browser

WICHTIG ZUR LOKALEN NUTZUNG
Die Anwendung benötigt keinen eigenen Backend-Server und verursacht keine Servergebühren. Kundendaten und hochgeladene Dokumente werden in IndexedDB im Browser des iPads gespeichert. Sie werden nicht synchronisiert. Browserdaten-Löschung, Geräteverlust oder ein Zurücksetzen des iPads kann die Daten entfernen. Deshalb regelmäßig über „Daten sichern“ exportieren und die Sicherungsdatei zusätzlich an einem sicheren Ort aufbewahren.

INSTALLATION AUF DEM IPAD
Für eine installierbare Offline-Web-App muss das Verzeichnis einmalig über eine HTTPS-Adresse bereitgestellt werden (z. B. kostenloses statisches Hosting wie GitHub Pages). Es ist kein eigener Server und keine Datenbank nötig. Danach:
1. Die HTTPS-Adresse in Safari auf dem iPad öffnen.
2. Teilen antippen.
3. „Zum Home-Bildschirm“ wählen.
4. Pawframe Studio vom Home-Bildschirm starten.
5. Die App einmal online vollständig laden; danach kann sie offline geöffnet werden.

Die Dateien direkt aus der Dateien-App zu öffnen ist für den dauerhaften Offline-App-Betrieb nicht zuverlässig, da Service Worker und PWA-Installation eine sichere HTTPS-Adresse benötigen.

DATENSCHUTZ / SICHERHEIT
Diese erste Version speichert Daten unverschlüsselt im Browserprofil des iPads. Sie besitzt keine Benutzeranmeldung, keine Mehrgeräte-Synchronisation und keine automatische Cloud-Sicherung. Für sensible Kundendokumente das iPad mit Gerätecode schützen und regelmäßige verschlüsselte Backups außerhalb der App aufbewahren. Dokumente werden lokal gespeichert; bei sehr großen Dateien hängt die mögliche Menge vom freien Gerätespeicher ab.

LOGO
Das originale Pawframe-Tierfotografie-Logo ist in der Seitenleiste integriert. Die Datei logo.png kann bei Bedarf durch eine neue Logo-Datei mit demselben Namen ersetzt werden.
