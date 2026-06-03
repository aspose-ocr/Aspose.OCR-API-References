---
title: "PreprocessingFilter"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 10
url: /sv/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Basklass för bildbehandlingskommandon.

Typen PreprocessingFilter exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PreprocessingFilter() | Initierar en ny instans av klassen PreprocessingFilter |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| standard | Standardfiltersamlingen innehåller AutoSkew-filter |
| empty | Tom filtersamling |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| binarize() | Konverterar en bild till svart‑vit bild.<br/>            Binära bilder är bilder vars pixlar har endast två möjliga intensitetsvärden. <br/>            De visas normalt som svart och vit. Numeriskt är de två värdena ofta 0 för svart och 255 för vitt.<br/>            Binära bilder skapas genom automatisk tröskelvärdesbestämning av en bild. |
| binarize(area) | Konverterar en del av bilden till svart‑vit bild.<br/>            Binära bilder är bilder vars pixlar har endast två möjliga intensitetsvärden. <br/>            De visas normalt som svart och vit. Numeriskt är de två värdena ofta 0 för svart och 255 för vitt.<br/>            Binära bilder skapas genom automatisk tröskelvärdesbestämning av en bild. |
| resize(width, height, type) | Skala om bilden – förstora eller förminska bildens upplösning. |
| resize(width, height) | Skala om bilden – förstora eller förminska bildens upplösning. |
| dilate() | Dilatering lägger till pixlar på gränserna av objekt i en bild. |
| dilate(area) | Dilatering lägger till pixlar på gränserna av objekt i en del av bilden. |
| invert() | Inverterar automatiskt färger i en dokumentbild. |
| invert(area) | Inverterar automatiskt färger i en del av bilden. |
| rotate(angle) | Rotera originalbilden. |
| rotate(angle, area) | Rotera en del av bilden. |
| scale(ratio) | Skala om bilden - Höj eller sänk bildens upplösning.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Skala om bilden – förstora eller förminska bildens upplösning. |
| threshold(value) | Skapa en binär bild baserat på att sätta ett tröskelvärde på pixelintensiteten i den ursprungliga bilden. |
| threshold(value, area) | Skapa en binär del av bilden baserat på att sätta ett tröskelvärde på pixelintensiteten i den ursprungliga bilddelen. |
| median() | Medianfiltret går igenom varje element i bilden och ersätter varje pixel med medianen av dess närliggande pixlar. |
| median(area) | Medianfiltret går igenom varje element i bilddelen och ersätter varje pixel med medianen av dess närliggande pixlar. |
| auto_denoising() | Aktiverar användningen av ett extra neuralt nätverk för att förbättra bilden – minska brus.<br/>            Användbart för bilder med skanningsartefakter, förvrängning, fläckar, ljusreflexer, gradienter, främmande element. |
| auto_denoising(area) | Aktiverar användningen av ett extra neuralt nätverk för att förbättra bilddelen – minska brus.<br/>            Användbart för bilder med skanningsartefakter, förvrängning, fläckar, ljusreflexer, gradienter, främmande element. |
| auto_skew() | Aktiverar automatisk korrigering av bildens snedvridning. |
| auto_skew(area) | Aktiverar automatisk korrigering av bilddelens snedvridning. |
| contrast_correction_filter() | Kontrastkorrigeringsfilter. |
| contrast_correction_filter(area) | Kontrastkorrigeringsfilter för bilddelen. |
| to_grayscale() | Konverterar en bild till en gråskala bild.<br/>            Gråskalebilden har 256 ljusnivåer i bilden (0 till 255). |
| auto_dewarping() | Korrigerar automatiskt geometriska förvrängningar i bilden.<br/>            Extremt resurskrävande! |
| add(filter) | Lägg till det nya filtret i samlingen för att ytterligare köra alla operationer.<br/>            Konsistens i samlingen är viktigt. |

### Se även

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

