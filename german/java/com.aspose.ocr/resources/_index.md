---
title: "Ressourcen"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Verwalten Sie herunterladbare Ressourcen, die die Erkennungsfähigkeiten von Aspose.OCR verbessern"
type: docs
weight: 32
url: /de/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Verwalten Sie herunterladbare Ressourcen, die die Erkennungsfähigkeiten von Aspose.OCR erweitern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Resources()](#Resources) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Erlauben (true) oder blockieren (false) das automatische Herunterladen erforderlicher Ressourcen aus dem Online-Repository. |
| [FetchAll()](#FetchAll) | Laden Sie alle kompatiblen Ressourcen aus dem Online-Repository herunter. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Laden Sie die im Parameter name angegebene Ressource aus dem Online-Repository herunter. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Laden Sie die im Parameter names angegebenen Ressourcen aus dem Online-Repository herunter. |
| [GetLocalPath()](#GetLocalPath) | Geben Sie den vollständigen Pfad zu dem Verzeichnis zurück, in das die Ressourcen heruntergeladen werden. |
| [GetRepository()](#GetRepository) | Geben Sie die URL des Online-Repositorys zurück, aus dem Aspose.OCR-Ressourcen heruntergeladen werden. |
| [ListLocal()](#ListLocal) | Listen Sie alle Aspose.OCR-Ressourcen auf, die im lokalen Verzeichnis gespeichert sind. |
| [ListRemote()](#ListRemote) | Listen Sie alle kompatiblen Ressourcen aus dem Online-Repository auf. |
| [ReleaseMemory()](#ReleaseMemory) | Entladen Sie OCR-Module, um Speicher freizugeben. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Entfernt die lokal gespeicherte Aspose.OCR-Ressource. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Geben Sie einen absoluten oder relativen Pfad zu dem Verzeichnis an, in das die Ressourcen heruntergeladen werden. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Geben Sie einen absoluten oder relativen Pfad zu dem Verzeichnis an, in das die Ressourcen heruntergeladen werden. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Geben Sie die URL des Online-Repositorys an, aus dem Aspose.OCR-Ressourcen heruntergeladen werden. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Erlauben (true) oder blockieren (false) Sie das automatische Herunterladen erforderlicher Ressourcen aus dem Online-Repository. Standardmäßig wird eine Ressource automatisch heruntergeladen, wenn eine Methode, die davon abhängt, aufgerufen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allow | java.lang.Boolean | Boolescher Wert, um das automatische Herunterladen erforderlicher Ressourcen zu erlauben oder zu blockieren. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Laden Sie alle kompatiblen Ressourcen aus dem Online-Repository herunter. Die vorhandenen Ressourcendateien werden überschrieben.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Laden Sie die im Parameter name angegebene Ressource aus dem Online-Repository herunter. Wenn die Ressource bereits heruntergeladen wurde, wird sie überschrieben. Sie können die .OCR-Erweiterung weglassen und nur den Dateinamen verwenden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Zeichenkette mit dem Ressourcennamen. Siehe die Methode ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Laden Sie die im Parameter names angegebenen Ressourcen aus dem Online-Repository herunter. Wenn eine oder mehrere Ressourcen bereits heruntergeladen wurden, werden sie überschrieben. Sie können die .OCR-Erweiterung weglassen und nur die Dateinamen verwenden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| names | java.lang.String[] | Array mit Ressourcennamen. Siehe die Methode ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Geben Sie den vollständigen Pfad zu dem Verzeichnis zurück, in das die Ressourcen heruntergeladen werden.

**Returns:**
java.lang.String - Zeichenkette mit dem Pfad zum Ressourcenverzeichnis.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Geben Sie die URL des Online-Repositorys zurück, aus dem Aspose.OCR-Ressourcen heruntergeladen werden.

**Returns:**
java.lang.String - URL des Online-Repositorys.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Listen Sie alle Aspose.OCR-Ressourcen auf, die im lokalen Verzeichnis gespeichert sind.

**Returns:**
java.util.List<java.lang.String> - Listet alle Aspose.OCR-Ressourcen auf, die im lokalen Verzeichnis gespeichert sind.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Listen Sie alle kompatiblen Ressourcen aus dem Online-Repository auf.

**Returns:**
java.util.List<java.lang.String> - Liste der Ressourcennamen.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Entladen Sie OCR-Module, um Speicher freizugeben. Die heruntergeladenen Moduldaten bleiben unverändert.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Entfernt die lokal gespeicherte Aspose.OCR-Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Geben Sie einen absoluten oder relativen Pfad zu dem Verzeichnis an, in das die Ressourcen heruntergeladen werden sollen. Wenn das Verzeichnis nicht existiert, wird es automatisch erstellt. Standardmäßig werden die Ressourcen in das Verzeichnis aspose\_data im Arbeitsverzeichnis der Anwendung heruntergeladen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Absoluter oder relativer Pfad zum Verzeichnis. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Geben Sie einen absoluten oder relativen Pfad zu dem Verzeichnis an, in das die Ressourcen heruntergeladen werden sollen. Übergeben Sie false an den Parameter create, um zu verhindern, dass das Verzeichnis automatisch erstellt wird. Wenn das angegebene Verzeichnis nicht existiert und die Erstellung nicht erlaubt ist, werden die Ressourcen in das Verzeichnis aspose\_data im Arbeitsverzeichnis der Anwendung geladen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Absoluter oder relativer Pfad zum Verzeichnis. |
| create | java.lang.Boolean | Parameter, um zu verhindern, dass das Verzeichnis automatisch erstellt wird. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Geben Sie die URL des Online-Repositorys an, von dem die Aspose.OCR-Ressourcen heruntergeladen werden sollen. Standardmäßig werden die Ressourcen von https://github.com/aspose-ocr/resources/ heruntergeladen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | java.lang.String | URL des Online-Repositorys. |


