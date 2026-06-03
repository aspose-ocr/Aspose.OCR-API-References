---
title: "Metered"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 190
url: /sv/python-net/aspose.ocr/metered/
---

## Metered class

Tillhandahåller metoder för att ange en mätt nyckel.

Metered-typen exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Metered() | Initierar en ny instans av denna klass. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| set_metered_key(public_key, private_key) | Sätter metered offentliga och privata nycklar.<br/>            Om du köper en metered-licens, bör detta API anropas när applikationen startas, normalt räcker det. <br/>            Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus, <br/>            för att undvika detta bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen. |
| get_consumption_quantity() | Hämtar förbrukningsfilens storlek. |
| get_consumption_credit() | Hämtar förbrukningskredit. |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

