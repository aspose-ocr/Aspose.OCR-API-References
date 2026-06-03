---
title: "PreprocessingFilter"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 10
url: /it/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Classe base per i comandi di elaborazione delle immagini.

Il tipo PreprocessingFilter espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| PreprocessingFilter() | Inizializza una nuova istanza della classe PreprocessingFilter |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| predefinito | La raccolta di filtri predefiniti contiene il filtro AutoSkew |
| empty | Raccolta di filtri vuota |
## Methods
| Nome | Descrizione |
| :- | :- |
| binarize() | Converte un'immagine in immagine in bianco e nero.<br/>            Le immagini binarie sono immagini i cui pixel hanno solo due possibili valori di intensità. <br/>            Sono normalmente visualizzate in bianco e nero. Numericamente, i due valori sono spesso 0 per il nero e 255 per il bianco.<br/>            Le immagini binarie sono prodotte mediante sogliatura automatica di un'immagine. |
| binarize(area) | Converte una parte dell'immagine in immagine in bianco e nero.<br/>            Le immagini binarie sono immagini i cui pixel hanno solo due possibili valori di intensità. <br/>            Sono normalmente visualizzate in bianco e nero. Numericamente, i due valori sono spesso 0 per il nero e 255 per il bianco.<br/>            Le immagini binarie sono prodotte mediante sogliatura automatica di un'immagine. |
| resize(width, height, type) | Riscala l'immagine - Aumenta o riduci la risoluzione dell'immagine. |
| resize(width, height) | Riscala l'immagine - Aumenta o riduci la risoluzione dell'immagine. |
| dilate() | La dilatazione aggiunge pixel ai bordi degli oggetti in un'immagine. |
| dilate(area) | La dilatazione aggiunge pixel ai bordi degli oggetti in una parte dell'immagine. |
| invert() | Inverte automaticamente i colori in un'immagine di documento. |
| invert(area) | Inverte automaticamente i colori in una parte dell'immagine. |
| rotate(angle) | Ruota l'immagine originale. |
| rotate(angle, area) | Ruota una parte dell'immagine. |
| scale(ratio) | Riscala immagine - Aumenta o diminuisci la risoluzione dell'immagine.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Riscala l'immagine - Aumenta o riduci la risoluzione dell'immagine. |
| threshold(value) | Crea un'immagine binaria impostando un valore di soglia sull'intensità dei pixel dell'immagine originale. |
| threshold(value, area) | Crea una parte binaria dell'immagine impostando un valore di soglia sull'intensità dei pixel della parte originale dell'immagine. |
| median() | Il filtro mediano scorre ogni elemento dell'immagine e sostituisce ogni pixel con la mediana dei pixel vicini. |
| median(area) | Il filtro mediano scorre ogni elemento della parte dell'immagine e sostituisce ogni pixel con la mediana dei pixel vicini. |
| auto_denoising() | Abilita l'uso di una rete neurale aggiuntiva per migliorare l'immagine - ridurre il rumore.<br/>            Utile per immagini con artefatti di scansione, distorsioni, macchie, bagliori, gradienti, elementi estranei. |
| auto_denoising(area) | Abilita l'uso di una rete neurale aggiuntiva per migliorare la parte dell'immagine - ridurre il rumore.<br/>            Utile per immagini con artefatti di scansione, distorsioni, macchie, bagliori, gradienti, elementi estranei. |
| auto_skew() | Abilita la correzione automatica dell'inclinazione dell'immagine. |
| auto_skew(area) | Abilita la correzione automatica dell'inclinazione della parte dell'immagine. |
| contrast_correction_filter() | Filtro di correzione del contrasto. |
| contrast_correction_filter(area) | Filtro di correzione del contrasto per la parte dell'immagine. |
| to_grayscale() | Converte un'immagine in immagine in scala di grigi.<br/>            L'immagine in scala di grigi ha 256 livelli di luminosità (da 0 a 255). |
| auto_dewarping() | Corregge automaticamente le distorsioni geometriche nell'immagine.<br/>            Estremamente intensivo di risorse! |
| add(filter) | Aggiungi il nuovo filtro alla collezione per eseguire ulteriormente tutte le operazioni.<br/>            La coerenza nella collezione è importante. |

### Vedi anche

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

