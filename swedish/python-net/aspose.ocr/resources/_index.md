---
title: "Resources"
second_title: "Aspose.OCR för Python via .NET API-referens"
description: 
type: docs
weight: 360
url: /sv/python-net/aspose.ocr/resources/
---

## Resources class

Hantera nedladdningsbara resurser som förbättrar Aspose.OCR:s igenkänningsförmåga.

Typen Resources exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| Resources() | Initierar en ny instans av klassen Resources |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| set_local_path(path) | Ange en absolut eller relativ sökväg till katalogen där resurserna ska hämtas ner.<br/>            Om katalogen inte finns skapas den automatiskt.<br/>            Som standard hämtas resurserna ner till katalogen aspose_data i applikationens arbetskatalog. |
| set_local_path(path, create) | Ange en absolut eller relativ sökväg till katalogen där resurserna ska hämtas ner.<br/>            Skicka `false` till parametern `create` för att förhindra att katalogen skapas automatiskt.<br/>            Om den angivna katalogen inte finns och skapande inte är tillåtet, kommer resurserna att laddas in i katalogen aspose_data i applikationens arbetskatalog. |
| set_repository(url) | Ange URL:en för det online‑arkivet varifrån Aspose.OCR‑resurser kommer att hämtas.<br/>            Som standard hämtas resurserna från https://github.com/aspose-ocr/resources/. |
| get_repository() | Returnera URL:en för det online‑arkivet varifrån Aspose.OCR‑resurser hämtas. |
| list_remote() | Lista alla kompatibla resurser från det online‑arkivet. |
| get_local_path() | Returnera den fullständiga sökvägen till katalogen där resurserna kommer att hämtas. |
| list_local() | Lista alla Aspose.OCR‑resurser som lagras i den lokala katalogen. |
| allow_automatic_downloads(allow) | Tillåt (true) eller blockera (false) automatisk nedladdning av erforderliga resurser från det online‑arkivet.<br/>             Som standard laddas en resurs automatiskt ner när en metod som beror på den anropas. |
| fetch_resources(names) | Ladda ner de resurser som anges i parametern `names` från det online‑arkivet. Om en eller flera resurser redan har hämtats kommer de att skrivas över.<br/>            Du kan utelämna .OCR‑ändelsen och bara använda filnamn. |
| fetch_resource(name) | Ladda ner de resurser som anges i parametern `names` från det online‑arkivet. Om en eller flera resurser redan har hämtats kommer de att skrivas över.<br/>            Du kan utelämna .OCR‑ändelsen och bara använda filnamn. |
| fetch_all() | Ladda ner alla kompatibla resurser från det online‑arkivet. Befintliga resursfiler kommer att skrivas över. |
| remove_local(name) | Tar bort den lokalt lagrade Aspose.OCR‑resursen. |
| release_memory() |  |

### Se även

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

