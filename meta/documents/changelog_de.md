# Release Notes für Elastic Export Google Shopping

## v1.1.6 (2017-10-18)

### Behoben
- Bild-URLs werden nun gemäß der Formateinstellungen mit der korrekten Mandanten-URL exportiert.

## v1.1.4 (2017-10-04)

### Behoben
- Es wurde ein Fehler behoben, der dazu geführt hat das manche Hersteller nicht exportiert wurden.

## v1.1.3 (2017-09-26)

### Behoben
- Versandkosten werden nun inklusive der Währung exportiert.

## v1.1.2 (2017-09-18)

### Geändert
- Der User Guide wurde aktualisiert.

## v1.1.1 (2017-07-21)

### Behoben
- Es wurde ein Fehler behoben, der dazu geführt hat, dass bei Preisen die Währung nicht angegeben wurde.

## v1.1.0 (2017-06-07)

### Hinzugefügt
- Der Feed wurde um das Feld "availabilty_date" erweitert, welche die Angabe eines Erscheiungsdatums ermöglicht.

## v1.0.16 (2017-06-06)

### Geändert
- Das Plugin Elastic Export ist nun Voraussetzung zur Nutzung des Pluginformats GoogleShopping.

## v1.0.15 (2017-05-30)

### Behoben
- Es wurde ein Fehler behoben, der dazu geführt hat, dass Merkmale ohne deutschen Merkmalnamen nicht übertragen wurden.

### Geändert
- Werte für die Spalten "gender", "age_group", "size_system", "size_type" und "energy_efficiency_class" werden nicht mehr entfernt,
 wenn diese nicht den vorgegebenen Werten von Google Shopping entsprechen.
 Dadurch sind fehlende oder falsche Werte einfacher ersichtlich und korrigierbar.

## v1.0.14 (2017-05-19)

### Behoben
- Es wurde ein Fehler behoben, der dazu geführt hat, dass die Merkmale nicht in der ausgewählten Sprache übertragen wurden.

## v1.0.13 (2017-05-18)

### Behoben
- Es wurde ein Fehler behoben, der dazu geführt hat, dass bei dem Barcode die Markplatzfreigabe ignoriert wurde.

## v1.0.12 (2017-05-12)

### Behoben
- Es wurde ein Fehler behoben, der die Berechnung des Grundpreises in bestimmten Fällen verhindert hat.
- Es wurde ein Fehler behoben, der dazu geführt hat, dass das Exportformat Texte in der falschen Sprache exportierte.

## v1.0.11 (2017-05-05)

### Behoben
- Es wurde ein Fehler behoben, der dazu geführt hat, dass das Exportformat teilweise nicht geladen werden konnte.

## v1.0.10 (2017-05-02)

### Geändert
- Die Bestandsfilterlogik wurde in das Elastic Export-Plugin ausgelagert.

## v1.0.9 (2017-04-18)

### Behoben
- Es wurde ein Fehler behoben, der dazu geführt hat, dass das Plugin nicht mehr gebaut werden konnte.

## v1.0.8 (2017-04-05)

### Behoben
- Das optionale Merkmal für "Artikelbeschreibung" wird nun korrekt ausgewertet.

## v1.0.7 (2017-04-05)

### Geändert
- Das Format funktioniert nun komplett über Elastic Search.
- Die Performance wurde verbessert.

## v1.0.6 (2017-04-03)

### Behoben
- Der API-Zustand wird nun korrekt ausgegeben.

## v1.0.5 (2017-03-31)

### Geändert
- Die Logik wurde an einigen Stellen zur Verbesserung der Stabilität angepasst.

### Behoben
- Die Artikelverfügbarkeit wird nun korrekt ausgegeben.

## v1.0.4 (2017-03-28)

### Behoben
- Ein Fehler das die Merkmale nicht ausgelesen werden konnten, wurde behoben.

## v1.0.3 (2017-03-22)

### Behoben
- Es wird nun ein anderes Feld genutzt um die Bild-URLs auszulesen für Plugins die elastic search benutzen.

## v1.0.2 (2017-03-13)

### Hinzugefügt
- Marketplace Namen hinzugefügt

### Geändert
- Plugin Icons aktualisiert

## v1.0.1 (2017-03-01)

### Geändert
- Es wird nun für jede übertragene Variante eine SKU generiert.
- Die ResultFields wurden angepasst, sodass der imageMutator bei der Auftragsherkunft "ALLE" nicht mehr greift.

## v1.0.0 (2017-02-20)

### Hinzugefügt
- Initiale Plugin-Dateien hinzugefügt
