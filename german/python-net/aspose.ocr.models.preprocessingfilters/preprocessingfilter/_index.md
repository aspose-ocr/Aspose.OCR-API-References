---
title: "PreprocessingFilter"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 10
url: /de/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Basisklasse für Bildverarbeitungsbefehle.

Der PreprocessingFilter-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PreprocessingFilter() | Initialisiert eine neue Instanz der Klasse PreprocessingFilter |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Standard | Standardfiltersammlung enthält den AutoSkew-Filter |
| empty | Leere Filtersammlung |
## Methoden
| Name | Beschreibung |
| :- | :- |
| binarize() | Konvertiert ein Bild in ein Schwarz‑weiß‑Bild.<br/>            Binärbilder sind Bilder, deren Pixel nur zwei mögliche Intensitätswerte haben. <br/>            Sie werden normalerweise als Schwarz und Weiß angezeigt. Numerisch sind die beiden Werte oft 0 für Schwarz und 255 für Weiß.<br/>            Binärbilder werden durch automatisches Schwellenwertsetzen eines Bildes erzeugt. |
| binarize(area) | Konvertiert einen Teil des Bildes in ein Schwarz‑weiß‑Bild.<br/>            Binärbilder sind Bilder, deren Pixel nur zwei mögliche Intensitätswerte haben. <br/>            Sie werden normalerweise als Schwarz und Weiß angezeigt. Numerisch sind die beiden Werte oft 0 für Schwarz und 255 für Weiß.<br/>            Binärbilder werden durch automatisches Schwellenwertsetzen eines Bildes erzeugt. |
| resize(width, height, type) | Bild neu skalieren – Bildauflösung vergrößern oder verkleinern. |
| resize(width, height) | Bild neu skalieren – Bildauflösung vergrößern oder verkleinern. |
| dilate() | Dilatation fügt Pixel zu den Grenzen von Objekten in einem Bild hinzu. |
| dilate(area) | Dilatation fügt Pixel zu den Grenzen von Objekten in einem Teil des Bildes hinzu. |
| invert() | Invertiert automatisch die Farben in einem Dokumentenbild. |
| invert(area) | Invertiert automatisch die Farben in einem Teil des Bildes. |
| rotate(angle) | Originalbild drehen. |
| rotate(angle, area) | Einen Teil des Bildes drehen. |
| scale(ratio) | Bild skalieren - Bildauflösung hoch- oder herunterskalieren.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Bild neu skalieren – Bildauflösung vergrößern oder verkleinern. |
| threshold(value) | Erstelle ein binäres Bild, indem ein Schwellenwert basierend auf der Pixelintensität des Originalbildes festgelegt wird. |
| threshold(value, area) | Erstelle einen binären Bildteil, indem ein Schwellenwert basierend auf der Pixelintensität des Originalbildteils festgelegt wird. |
| median() | Der Medianfilter durchläuft jedes Element des Bildes und ersetzt jedes Pixel durch den Median seiner Nachbarpixel. |
| median(area) | Der Medianfilter durchläuft jedes Element des Bildteils und ersetzt jedes Pixel durch den Median seiner Nachbarpixel. |
| auto_denoising() | Ermöglicht die Verwendung eines zusätzlichen neuronalen Netzwerks zur Verbesserung des Bildes – Rauschen reduzieren.<br/>            Nützlich für Bilder mit Scan-Artefakten, Verzerrungen, Flecken, Lichthöfen, Farbverläufen, Fremdelementen. |
| auto_denoising(area) | Ermöglicht die Verwendung eines zusätzlichen neuronalen Netzwerks zur Verbesserung des Bildteils – Rauschen reduzieren.<br/>            Nützlich für Bilder mit Scan-Artefakten, Verzerrungen, Flecken, Lichthöfen, Farbverläufen, Fremdelementen. |
| auto_skew() | Ermöglicht die automatische Korrektur der Bildschrägstellung. |
| auto_skew(area) | Ermöglicht die automatische Korrektur der Schrägstellung des Bildteils. |
| contrast_correction_filter() | Kontrastkorrekturfilter. |
| contrast_correction_filter(area) | Kontrastkorrekturfilter für den Bildteil. |
| to_grayscale() | Konvertiert ein Bild in ein Graustufenbild.<br/>            Graustufenbilder haben 256 Helligkeitsstufen im Bild (0 bis 255). |
| auto_dewarping() | Korrigiert automatisch geometrische Verzerrungen im Bild.<br/>            Äußerst ressourcenintensiv! |
| add(filter) | Fügen Sie den neuen Filter zur Sammlung hinzu, um alle Vorgänge weiter auszuführen.<br/>            Konsistenz in der Sammlung ist wichtig. |

### Siehe auch

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

