---
title: "Kaynaklar"
second_title: "Aspose.OCR for Java API Referansı"
description: "Aspose.OCR tanıma yeteneklerini geliştiren indirilebilir kaynakları yönetin"
type: docs
weight: 32
url: /tr/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Aspose.OCR tanıma yeteneklerini artıran indirilebilir kaynakları yönetin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Resources()](#Resources) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Gerekli kaynakların çevrimiçi depodan otomatik indirilmesine izin ver (true) veya engelle (false). |
| [FetchAll()](#FetchAll) | Çevrimiçi depodan tüm uyumlu kaynakları indirin. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | İsim parametresinde belirtilen kaynağı çevrimiçi depodan indirin. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | İsimler parametresinde belirtilen kaynakları çevrimiçi depodan indirin. |
| [GetLocalPath()](#GetLocalPath) | Kaynakların indirileceği dizinin tam yolunu döndürün. |
| [GetRepository()](#GetRepository) | Aspose.OCR kaynaklarının indirildiği çevrimiçi deponun URL'sini döndürün. |
| [ListLocal()](#ListLocal) | Yerel dizinde depolanan tüm Aspose.OCR kaynaklarını listeleyin. |
| [ListRemote()](#ListRemote) | Çevrimiçi depodaki tüm uyumlu kaynakları listeleyin. |
| [ReleaseMemory()](#ReleaseMemory) | Belleği boşaltmak için OCR modüllerini kaldırın. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Yerel olarak depolanan Aspose.OCR kaynağını kaldırır. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Kaynakların indirileceği dizine mutlak ya da göreceli bir yol belirtin. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Kaynakların indirileceği dizine mutlak ya da göreceli bir yol belirtin. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Aspose.OCR kaynaklarının indirileceği çevrimiçi deponun URL'sini belirtin. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Gerekli kaynakların çevrimiçi depodan otomatik indirilmesine izin verin (true) veya engelleyin (false). Varsayılan olarak, bir kaynağa bağımlı bir yöntem çağrıldığında kaynak otomatik olarak indirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| izin | java.lang.Boolean | Gerekli kaynakların otomatik indirilmesine izin vermek veya engellemek için Boolean değeri. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Çevrimiçi depodan tüm uyumlu kaynakları indirin. Mevcut kaynak dosyaları üzerine yazılacak.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


İsim parametresinde belirtilen kaynağı çevrimiçi depodan indirin. Kaynak zaten indirilmişse, üzerine yazılacak. .OCR uzantısını atlayabilir ve yalnızca dosya adını kullanabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isim | java.lang.String | Kaynak adını içeren dize. ListRemote yöntemine bakın. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


İsimler parametresinde belirtilen kaynakları çevrimiçi depodan indirin. Bir veya daha fazla kaynak zaten indirilmişse, üzerine yazılacak. .OCR uzantısını atlayabilir ve yalnızca dosya adlarını kullanabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isimler | java.lang.String[] | Kaynak adlarını içeren dizi. ListRemote yöntemine bakın. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Kaynakların indirileceği dizinin tam yolunu döndürün.

**Returns:**
java.lang.String - Kaynaklar dizinine giden yolu içeren dize.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Aspose.OCR kaynaklarının indirildiği çevrimiçi deponun URL'sini döndürün.

**Returns:**
java.lang.String - Çevrimiçi deponun URL'si.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Yerel dizinde depolanan tüm Aspose.OCR kaynaklarını listeleyin.

**Returns:**
java.util.List<java.lang.String> - Yerel dizinde depolanan tüm Aspose.OCR kaynaklarını listeleyin.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Çevrimiçi depodaki tüm uyumlu kaynakları listeleyin.

**Returns:**
java.util.List<java.lang.String> - Kaynak adlarının listesi.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Belleği boşaltmak için OCR modüllerini boşaltın. İndirilen modül dosyaları bozulmadan kalacaktır.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Yerel olarak depolanan Aspose.OCR kaynağını kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isim | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Kaynakların indirileceği dizine mutlak ya da göreli bir yol belirtin. Dizin mevcut değilse, otomatik olarak oluşturulur. Varsayılan olarak, kaynaklar uygulamanın çalışma dizinindeki aspose\_data dizinine indirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Dizine mutlak ya da göreli yol. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Kaynakların indirileceği dizine mutlak ya da göreli bir yol belirtin. Dizinin otomatik olarak oluşturulmasını önlemek için create parametresine false gönderin. Sağlanan dizin mevcut değil ve oluşturulmasına izin verilmezse, kaynaklar uygulamanın çalışma dizinindeki aspose\_data dizinine yüklenecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Dizine mutlak ya da göreli yol. |
| create | java.lang.Boolean | Dizinin otomatik olarak oluşturulmasını önleyen parametre. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Aspose.OCR kaynaklarının indirileceği çevrimiçi depo URL'sini belirtin. Varsayılan olarak, kaynaklar https://github.com/aspose-ocr/resources/ adresinden indirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Çevrimiçi deponun URL'si. |


