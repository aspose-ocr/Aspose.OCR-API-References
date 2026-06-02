---
title: "RecognitionResult"
second_title: "Aspose.OCR for Java API Referansı"
description: "Görüntü tanımanın sonuçları"
type: docs
weight: 26
url: /tr/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Görüntü tanımanın sonuçları. Tanıma bilgileri içeren öğeler ve sonuç dışa aktarma yöntemleri içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Yeni bir örnek başlatır |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [language](#language) | Görüntüde tanınan metnin dili. |
| [recognitionCharactersList](#recognitionCharactersList) | Tanıma algoritması tarafından bulunan ve olasılık sırasına göre azalan şekilde düzenlenen karakter kümesi. |
| [recognitionLinesResult](#recognitionLinesResult) | Satırların (Dikdörtgenler) listesiyle tanıma sonuçlarının bir listesini alır. |
| [recognitionRegionsResult](#recognitionRegionsResult) | Bölgelerin (Dikdörtgenler) listesiyle tanıma sonuçlarının bir listesini alır. |
| [recognitionText](#recognitionText) | Tüm sayfanın veya tek bir alanın tanıma sonucu. |
| [warnings](#warnings) | Oluşturma sırasında ortaya çıkan kritik olmayan hataları açıklayan uyarı mesajları listesini alır veya ayarlar. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [GetJson()](#GetJson) | Tanıma sonuçlarıyla JSON dizesi oluştur. |
| [GetKeywords()](#GetKeywords) | Pasaporttan anahtar kelimeleri al (Test modu). |
| [GetXml()](#GetXml) | Tanıma sonuçlarıyla JSON dizesi oluştur. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Metni düzeltir (yanlış yazılmış kelimeleri değiştirir). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Metni düzeltir (yanlış yazılmış kelimeleri değiştirir). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Verilen giriş metni için önerilen yazım düzeltmeleriyle hatalı yazılmış kelimeleri bulun. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Verilen giriş metni için önerilen yazım düzeltmeleriyle hatalı yazılmış kelimeleri bulun. |
| [save(String fullFileName)](#save-java.lang.String) | Belgeyi düz metin olarak kaydeder |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Belgeyi düz metin ya da başka bir belge formatında kaydeder. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Belgeyi düz metin ya da başka bir belge formatında kaydeder. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Belgeyi düz metin veya Microsoft Word Metin Belgesi formatında, İngilizce sözlük ile düzeltilmiş metin olarak kaydeder. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Belgeyi düz metin ya da başka bir formatta düzeltilmiş metin olarak kaydeder. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Yazım denetimi düzeltmesi için kendi sözlüğünüzü kullanmanıza izin verir. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Yeni bir örnek başlatır

### language {#language}
```
public Language language
```


Görüntüde tanınan metnin dili. Bu değer, Language.AUTO, Language.MULTILANGUAGE veya Language.UNIVERSAL seçildiğinde otomatik olarak belirlenir.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Tanıma algoritması tarafından bulunan ve olasılık sırasına göre azalan şekilde düzenlenen karakter kümesi.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Satırların (Dikdörtgenler) listesiyle tanıma sonuçlarının bir listesini alır.

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Bölgelerin (Dikdörtgenler) listesiyle tanıma sonuçlarının bir listesini alır.

### recognitionText {#recognitionText}
```
public String recognitionText
```


Tüm sayfanın veya tek bir alanın tanıma sonucu.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Oluşturma sırasında ortaya çıkan kritik olmayan hataları açıklayan uyarı mesajları listesini alır veya ayarlar.

### GetJson() {#GetJson}
```
public String GetJson()
```


Tanıma sonuçlarıyla JSON dizesi oluştur.

**Returns:**
java.lang.String - Tanıma sonuçları JSON dizesi olarak.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Pasaporttan anahtar kelimeleri alın (Test modu. Yalnızca ABD ve MADAGASKAR pasaportları için çalışır).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Anahtar kelimeyi anahtar ve LinesResult'ı değer olarak içeren sözlük.
### GetXml() {#GetXml}
```
public String GetXml()
```


Tanıma sonuçlarıyla JSON dizesi oluştur.

**Returns:**
java.lang.String - Tanıma sonuçları XML dizesi olarak.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Metni düzeltir (yanlış yazılmış kelimeleri değiştirir).

**Returns:**
java.lang.String - Düzeltildiği tanıma sonuçları dizesi. Varsayılan İngilizce sözlük.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Metni düzeltir (yanlış yazılmış kelimeleri değiştirir).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kullanılacak sözlük. |

**Returns:**
java.lang.String - Düzeltildiği tanıma sonuçları dizesi.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Verilen giriş metni için önerilen yazım düzeltmeleriyle hatalı kelimeleri bulun. Varsayılan İngilizce sözlük.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - Her hatalı kelime için önerilen doğru yazımları ve düzenleme mesafesini içeren listelerle hatalı kelimeleri temsil eden SpellCheckError nesnesinin ArrayList'i.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Verilen giriş metni için önerilen yazım düzeltmeleriyle hatalı yazılmış kelimeleri bulun.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kullanılacak sözlük. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - Her hatalı kelime için önerilen doğru yazımları ve düzenleme mesafesini içeren listelerle hatalı kelimeleri temsil eden SpellCheckError nesnesinin ArrayList'i.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Belgeyi düz metin olarak kaydeder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Tanıma sonucunu kaydetmek için yol içeren dosya adı |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Belgeyi düz metin ya da başka bir belge formatında kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format'ın belge formatı enum türü. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Belgeyi düz metin ya da başka bir belge formatında kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format'ın belge formatı enum türü. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Arka plan görüntülerinin kalitesini düşürerek PDF dosya boyutunu azaltın. Varsayılan olarak, orijinal görüntü kalitesi korunur. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Belgeyi düz metin veya Microsoft Word Metin Belgesi formatında, İngilizce sözlük ile düzeltilmiş metin olarak kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format'ın belge formatı enum türü. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Belgeyi düz metin ya da başka bir formatta düzeltilmiş metin olarak kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullFileName | java.lang.String | Tanıma sonucunu kaydetmek için yol içeren dosya adı. |
| format | [Format](../../com.aspose.ocr.models/format/) | Format'ın belge formatı enum türü. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Yazım denetimi için sözlük. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Yazım denetimi düzeltmesi için kendi sözlüğünüzü kullanmanıza izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Kullanıcı sözlüğünün (frekans sözlüğü) tam yolu. Sözlük dosya biçimi: UTF-8 kodlamalı düz metin dosyası. Kelime ve Kelime Frekansı virgülle ayrılır, kelime ilk sütunda, frekans ikinci sütunda bulunur. Her kelime-frekans çifti ayrı bir satırda yer alır. Bir satır, karakter dizisinin ardından satır beslemesi ("\\n"), satır dönüşü ("\\r") veya satır dönüşünün hemen ardından satır beslemesi ("\\r\\n") ile tanımlanır. Her kelime küçük harfle olmalıdır. |
