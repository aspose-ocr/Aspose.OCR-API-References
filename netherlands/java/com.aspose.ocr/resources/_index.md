---
title: "Bronnen"
second_title: "Aspose.OCR for Java API-referentie"
description: "Beheer downloadbare bronnen die de herkenningsmogelijkheden van Aspose.OCR verbeteren."
type: docs
weight: 32
url: /nl/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Beheer downloadbare bronnen die de herkenningsmogelijkheden van Aspose.OCR verbeteren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Resources()](#Resources) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Sta (true) of blokkeer (false) het automatisch downloaden van vereiste bronnen van de online repository. |
| [FetchAll()](#FetchAll) | Download alle compatibele bronnen van de online repository. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Download de resource die is gespecificeerd in de naamparameter van de online repository. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Download de resources die zijn gespecificeerd in de namenparameter van de online repository. |
| [GetLocalPath()](#GetLocalPath) | Retourneer het volledige pad naar de map waar de resources worden gedownload. |
| [GetRepository()](#GetRepository) | Retourneer de URL van de online repository waaruit Aspose.OCR-resources worden gedownload. |
| [ListLocal()](#ListLocal) | Geef een lijst weer van alle Aspose.OCR-resources die zijn opgeslagen in de lokale map. |
| [ListRemote()](#ListRemote) | Geef een lijst weer van alle compatibele resources van de online repository. |
| [ReleaseMemory()](#ReleaseMemory) | Ontlaad OCR-modules om geheugen vrij te maken. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Verwijdert de lokaal opgeslagen Aspose.OCR-resource. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Specificeer een absoluut of relatief pad naar de map waar de resources worden gedownload. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Specificeer een absoluut of relatief pad naar de map waar de resources worden gedownload. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Specificeer de URL van de online repository waaruit Aspose.OCR-resources zullen worden gedownload. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Sta (true) of blokkeer (false) het automatisch downloaden van vereiste resources van de online repository. Standaard wordt een resource automatisch gedownload wanneer een methode die ervan afhankelijk is wordt aangeroepen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| toestaan | java.lang.Boolean | Booleaanse waarde om het automatisch downloaden van vereiste resources toe te staan of te blokkeren. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Download alle compatibele resources van de online repository. De bestaande resourcebestanden worden overschreven.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Download de resource die is gespecificeerd in de naamparameter van de online repository. Als de resource al is gedownload, wordt deze overschreven. Je kunt de .OCR-extensie weglaten en alleen de bestandsnaam gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | String met de resource-naam. Zie de ListRemote-methode. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Download de resources die zijn gespecificeerd in de namenparameter van de online repository. Als een of meer resources al zijn gedownload, worden ze overschreven. Je kunt de .OCR-extensie weglaten en alleen bestandsnamen gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| namen | java.lang.String[] | Array met resource-namen. Zie de ListRemote-methode. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Retourneer het volledige pad naar de map waar de resources worden gedownload.

**Returns:**
java.lang.String - String met het pad naar de resource-map.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Retourneer de URL van de online repository waaruit Aspose.OCR-resources worden gedownload.

**Returns:**
java.lang.String - URL van de online repository.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Geef een lijst weer van alle Aspose.OCR-resources die zijn opgeslagen in de lokale map.

**Returns:**
java.util.List<java.lang.String> - Lijst alle Aspose.OCR-resources die zijn opgeslagen in de lokale map.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Geef een lijst weer van alle compatibele resources van de online repository.

**Returns:**
java.util.List<java.lang.String> - Lijst met namen van bronnen.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Laad OCR-modules uit om geheugen vrij te maken. De gedownloade modulebestanden blijven ongewijzigd.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Verwijdert de lokaal opgeslagen Aspose.OCR-resource.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Geef een absoluut of relatief pad op naar de map waarin de bronnen worden gedownload. Als de map niet bestaat, wordt deze automatisch aangemaakt. Standaard worden de bronnen gedownload naar de aspose\\_data map in de werkmap van de applicatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | Absoluut of relatief pad naar de map. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Geef een absoluut of relatief pad op naar de map waarin de bronnen worden gedownload. Geef false door aan de create‑parameter om te voorkomen dat de map automatisch wordt aangemaakt. Als de opgegeven map niet bestaat en aanmaken niet is toegestaan, worden de bronnen geladen in de aspose\\_data map in de werkmap van de applicatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pad | java.lang.String | Absoluut of relatief pad naar de map. |
| create | java.lang.Boolean | Parameter om te voorkomen dat de map automatisch wordt aangemaakt. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Geef de URL op van de online repository waarvan Aspose.OCR‑bronnen worden gedownload. Standaard worden de bronnen gedownload van https://github.com/aspose-ocr/resources/.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | URL van de online repository. |


