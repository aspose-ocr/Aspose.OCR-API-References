---
title: "RecognitionSettings"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 330
url: /de/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

Einstellungen für die Bilderkennung.<br/>            Enthält Elemente, die die Anpassung des Erkennungsprozesses ermöglichen.

Der RecognitionSettings-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| RecognitionSettings() | Initialisiert eine neue Instanz von |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | Initialisiert eine neue Instanz der Klasse RecognitionSettings. |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | Liest oder setzt die Anzahl der Threads für die Verarbeitung. |
| language | Liest oder setzt die für OCR verwendete Sprache. |
| ignored_symbols | Setzt die Blacklist für Erkennungssymbole. |
| allowed_symbols | Setzt die zulässigen Zeichen mit der Eigenschaft alphabet. |
| allowed_characters | Zulässige Zeichen festgelegt. Bestimmt die Art der Zeichen, die für das Erkennungsergebnis erlaubt sind. |
| automatic_color_inversion | Erkennt Bilder mit weißem Text auf dunklem/schwarzem Hintergrund und wählt automatisch einen speziellen OCR-Algorithmus dafür aus. |
| recognition_areas | Ruft die Liste der Textbereiche für die Verarbeitung ab oder legt sie fest. |
| recognize_single_line | Legt die einzeilige Bild-Erkennung fest. <br/>            Deaktiviert (false) standardmäßig. <br/>            Deaktiviert alle Verarbeitungsschritte, die mit dem Aufteilen in Zeilen verbunden sind. <br/>            Setzen Sie diesen Parameter auf true, wenn Ihr Bild nur eine Zeile enthält. Deaktiviert die Einstellungen für RecognitionAreas, sodass alle Bereichseinstellungen ignoriert werden. |
| language_detection_level |  |
| lines_filtration | Ermöglicht das Erkennen von Text in Tabellen (Regionen, die von Linien umgeben sind). |
| detect_areas_mode | Ermöglicht die Auswahl des optimalen Modus für Dokumenttyp-Bereiche: Dokument, Foto, Klartext, Spalte, Bild. |
| upscale_small_font | Ermöglicht die Verwendung zusätzlicher Algorithmen speziell für die Erkennung kleiner Schriftarten.<br/>            Nützlich für Bilder mit kleinformatigen Zeichen. |

### Siehe auch

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

