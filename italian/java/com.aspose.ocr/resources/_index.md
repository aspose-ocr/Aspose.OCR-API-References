---
title: "Risorse"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Gestisci le risorse scaricabili che migliorano le capacità di riconoscimento di Aspose.OCR"
type: docs
weight: 32
url: /it/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Gestisci le risorse scaricabili che migliorano le capacità di riconoscimento di Aspose.OCR.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Resources()](#Resources) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Consenti (true) o blocca (false) il download automatico delle risorse richieste dal repository online. |
| [FetchAll()](#FetchAll) | Scarica tutte le risorse compatibili dal repository online. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Scarica la risorsa specificata nel parametro name dal repository online. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Scarica le risorse specificate nel parametro names dal repository online. |
| [GetLocalPath()](#GetLocalPath) | Restituisce il percorso completo della directory in cui le risorse verranno scaricate. |
| [GetRepository()](#GetRepository) | Restituisce l'URL del repository online da cui vengono scaricate le risorse Aspose.OCR. |
| [ListLocal()](#ListLocal) | Elenca tutte le risorse Aspose.OCR memorizzate nella directory locale. |
| [ListRemote()](#ListRemote) | Elenca tutte le risorse compatibili dal repository online. |
| [ReleaseMemory()](#ReleaseMemory) | Rilascia i moduli OCR per liberare memoria. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Rimuove la risorsa Aspose.OCR memorizzata localmente. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Specifica un percorso assoluto o relativo della directory in cui le risorse verranno scaricate. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Specifica un percorso assoluto o relativo della directory in cui le risorse verranno scaricate. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Specifica l'URL del repository online da cui verranno scaricate le risorse Aspose.OCR. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Consenti (true) o blocca (false) il download automatico delle risorse richieste dal repository online. Per impostazione predefinita, una risorsa viene scaricata automaticamente quando viene chiamato un metodo che dipende da essa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| allow | java.lang.Boolean | Valore booleano per consentire o bloccare il download automatico delle risorse richieste. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Scarica tutte le risorse compatibili dal repository online. I file di risorse esistenti saranno sovrascritti.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Scarica la risorsa specificata nel parametro name dal repository online. Se la risorsa è già stata scaricata, verrà sovrascritta. È possibile omettere l'estensione .OCR e utilizzare solo il nome del file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Stringa con il nome della risorsa. Vedi il metodo ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Scarica le risorse specificate nel parametro names dal repository online. Se una o più risorse sono già state scaricate, verranno sovrascritte. È possibile omettere l'estensione .OCR e utilizzare solo i nomi dei file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| names | java.lang.String[] | Array con i nomi delle risorse. Vedi il metodo ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Restituisce il percorso completo della directory in cui le risorse verranno scaricate.

**Returns:**
java.lang.String - Stringa con il percorso della directory delle risorse.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Restituisce l'URL del repository online da cui vengono scaricate le risorse Aspose.OCR.

**Returns:**
java.lang.String - URL del repository online.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Elenca tutte le risorse Aspose.OCR memorizzate nella directory locale.

**Returns:**
java.util.List<java.lang.String> - Elenca tutte le risorse Aspose.OCR memorizzate nella directory locale.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Elenca tutte le risorse compatibili dal repository online.

**Returns:**
java.util.List<java.lang.String> - Elenco dei nomi delle risorse.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Rimuovi i moduli OCR per liberare memoria. I file dei moduli scaricati rimarranno intatti.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Rimuove la risorsa Aspose.OCR memorizzata localmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Specifica un percorso assoluto o relativo alla directory in cui le risorse verranno scaricate. Se la directory non esiste, verrà creata automaticamente. Per impostazione predefinita, le risorse vengono scaricate nella directory aspose\_data nella cartella di lavoro dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Percorso assoluto o relativo alla directory. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Specifica un percorso assoluto o relativo alla directory in cui le risorse verranno scaricate. Passa false al parametro create per impedire la creazione automatica della directory. Se la directory fornita non esiste e la creazione non è consentita, le risorse verranno caricate nella directory aspose\_data nella cartella di lavoro dell'applicazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| percorso | java.lang.String | Percorso assoluto o relativo alla directory. |
| create | java.lang.Boolean | Parametro per impedire la creazione automatica della directory. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Specifica l'URL del repository online da cui verranno scaricate le risorse Aspose.OCR. Per impostazione predefinita, le risorse vengono scaricate da https://github.com/aspose-ocr/resources/.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL del repository online. |


