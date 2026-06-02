---
title: "Resurser"
second_title: "Aspose.OCR för Java API-referens"
description: "Hantera nedladdningsbara resurser som förbättrar Aspose.OCR:s igenkänningsförmåga"
type: docs
weight: 32
url: /sv/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Hantera nedladdningsbara resurser som förbättrar Aspose.OCR:s igenkänningsförmåga.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Resources()](#Resources) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Tillåt (true) eller blockera (false) automatisk nedladdning av nödvändiga resurser från det online-arkivet. |
| [FetchAll()](#FetchAll) | Ladda ner alla kompatibla resurser från det online-arkivet. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Ladda ner resursen som anges i name-parametern från det online-arkivet. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Ladda ner resurserna som anges i names-parametern från det online-arkivet. |
| [GetLocalPath()](#GetLocalPath) | Returnera den fullständiga sökvägen till katalogen där resurserna kommer att laddas ner. |
| [GetRepository()](#GetRepository) | Returnera URL:en för det online-arkivet från vilket Aspose.OCR-resurser laddas ner. |
| [ListLocal()](#ListLocal) | Lista alla Aspose.OCR-resurser som lagras i den lokala katalogen. |
| [ListRemote()](#ListRemote) | Lista alla kompatibla resurser från det online-arkivet. |
| [ReleaseMemory()](#ReleaseMemory) | Ladda ur OCR-moduler för att frigöra minne. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Tar bort den lokalt lagrade Aspose.OCR-resursen. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Ange en absolut eller relativ sökväg till katalogen där resurserna kommer att laddas ner. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Ange en absolut eller relativ sökväg till katalogen där resurserna kommer att laddas ner. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Ange URL:en för det online-arkivet från vilket Aspose.OCR-resurser kommer att laddas ner. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Tillåt (true) eller blockera (false) automatisk nedladdning av nödvändiga resurser från det online-arkivet. Som standard laddas en resurs automatiskt ner när en metod som beror på den anropas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tillåt | java.lang.Boolean | Booleskt värde för att tillåta eller blockera automatisk nedladdning av nödvändiga resurser. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Ladda ner alla kompatibla resurser från det online-arkivet. De befintliga resursfilerna kommer att skrivas över.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Ladda ner resursen som anges i name-parametern från det online-arkivet. Om resursen redan är nedladdad kommer den att skrivas över. Du kan utelämna .OCR-tillägget och bara använda filnamnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Sträng med resursnamn. Se metoden ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Ladda ner resurserna som anges i names-parametern från det online-arkivet. Om en eller flera resurser redan är nedladdade kommer de att skrivas över. Du kan utelämna .OCR-tillägget och bara använda filnamnen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String[] | Array med resursnamn. Se metoden ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Returnera den fullständiga sökvägen till katalogen där resurserna kommer att laddas ner.

**Returns:**
java.lang.String - Sträng med sökvägen till resurskatalogen.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Returnera URL:en för det online-arkivet från vilket Aspose.OCR-resurser laddas ner.

**Returns:**
java.lang.String - URL för det online-arkivet.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Lista alla Aspose.OCR-resurser som lagras i den lokala katalogen.

**Returns:**
java.util.List<java.lang.String> - Lista alla Aspose.OCR-resurser som lagras i den lokala katalogen.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Lista alla kompatibla resurser från det online-arkivet.

**Returns:**
java.util.List<java.lang.String> - Lista med resursnamn.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Ladda ur OCR-moduler för att frigöra minne. De nedladdade modulfilerna förblir intakta.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Tar bort den lokalt lagrade Aspose.OCR-resursen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Ange en absolut eller relativ sökväg till den katalog där resurserna kommer att hämtas. Om katalogen inte finns skapas den automatiskt. Som standard hämtas resurserna till katalogen aspose\_data i applikationens arbetskatalog.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Absolut eller relativ sökväg till katalogen. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Ange en absolut eller relativ sökväg till den katalog där resurserna kommer att hämtas. Skicka false till parametern create för att förhindra att katalogen skapas automatiskt. Om den angivna katalogen inte finns och skapande inte är tillåtet, kommer resurserna att laddas in i katalogen aspose\_data i applikationens arbetskatalog.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sökväg | java.lang.String | Absolut eller relativ sökväg till katalogen. |
| create | java.lang.Boolean | Parameter för att förhindra att katalogen skapas automatiskt. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Ange URL:en till det online‑arkiv från vilket Aspose.OCR‑resurser kommer att hämtas. Som standard hämtas resurserna från https://github.com/aspose-ocr/resources/.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | URL till det online‑arkivet. |


