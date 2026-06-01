---
title: "RecognitionResult"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Hasil pengenalan gambar"
type: docs
weight: 26
url: /id/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Hasil pengenalan gambar. Berisi elemen dengan informasi pengenalan dan metode untuk mengekspor hasil.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Menginisialisasi instance baru dari |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [language](#language) | Bahasa teks yang dikenali dalam gambar. |
| [recognitionCharactersList](#recognitionCharactersList) | Sekumpulan karakter yang ditemukan oleh algoritma pengenalan dan diurutkan dalam urutan menurun berdasarkan probabilitas. |
| [recognitionLinesResult](#recognitionLinesResult) | Mendapatkan daftar hasil pengenalan dengan daftar baris (Persegi panjang). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Mendapatkan daftar hasil pengenalan dengan daftar wilayah (Persegi panjang). |
| [recognitionText](#recognitionText) | Hasil pengenalan semua halaman atau satu area. |
| [warnings](#warnings) | Mendapatkan atau mengatur daftar pesan peringatan yang menggambarkan kesalahan non-kritis yang muncul selama proses pembuatan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [GetJson()](#GetJson) | Buat string JSON dengan hasil pengenalan. |
| [GetKeywords()](#GetKeywords) | Dapatkan kata kunci dari paspor (Mode uji. |
| [GetXml()](#GetXml) | Buat string JSON dengan hasil pengenalan. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Mengoreksi teks (mengganti kata yang salah eja). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Mengoreksi teks (mengganti kata yang salah eja). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Temukan kata-kata yang salah eja dengan ejaan yang disarankan untuk teks input yang diberikan. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Temukan kata-kata yang salah eja dengan ejaan yang disarankan untuk teks input yang diberikan. |
| [save(String fullFileName)](#save-java.lang.String) | Menyimpan dokumen dalam teks biasa |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Menyimpan dokumen dalam teks biasa atau format dokumen lain. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Menyimpan dokumen dalam teks biasa atau format dokumen lain. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Menyimpan teks yang telah dikoreksi dengan kamus bahasa Inggris dalam dokumen dalam format teks biasa atau format Dokumen Teks Microsoft Word. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Menyimpan teks yang telah dikoreksi dalam dokumen dalam format teks biasa atau format lain. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Memungkinkan penggunaan kamus sendiri untuk koreksi pemeriksaan ejaan. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Menginisialisasi instance baru dari

### language {#language}
```
public Language language
```


Bahasa dari teks yang dikenali dalam gambar. Nilai ini ditentukan secara otomatis jika  Language.AUTO ,  Language.MULTILANGUAGE , atau  Language.UNIVERSAL  dipilih.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Sekumpulan karakter yang ditemukan oleh algoritma pengenalan dan diurutkan dalam urutan menurun berdasarkan probabilitas.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Mendapatkan daftar hasil pengenalan dengan daftar baris (Persegi panjang).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Mendapatkan daftar hasil pengenalan dengan daftar wilayah (Persegi panjang).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Hasil pengenalan semua halaman atau satu area.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Mendapatkan atau mengatur daftar pesan peringatan yang menggambarkan kesalahan non-kritis yang muncul selama proses pembuatan.

### GetJson() {#GetJson}
```
public String GetJson()
```


Buat string JSON dengan hasil pengenalan.

**Returns:**
java.lang.String - Hasil pengenalan sebagai string JSON.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Dapatkan kata kunci dari paspor (Mode uji. Hanya berfungsi untuk paspor USA dan MADAGASCAR).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Kamus dengan kata kunci sebagai kunci dan LinesResult sebagai nilai.
### GetXml() {#GetXml}
```
public String GetXml()
```


Buat string JSON dengan hasil pengenalan.

**Returns:**
java.lang.String - Hasil pengenalan sebagai string XML.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Mengoreksi teks (mengganti kata yang salah eja).

**Returns:**
java.lang.String - String hasil pengenalan yang telah dikoreksi. Kamus bahasa Inggris default.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Mengoreksi teks (mengganti kata yang salah eja).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kamus yang akan digunakan. |

**Returns:**
java.lang.String - String hasil pengenalan yang telah dikoreksi.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Temukan kata-kata yang salah eja dengan ejaan yang disarankan untuk teks input yang diberikan. Kamus bahasa Inggris default.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList objek SpellCheckError yang mewakili kata-kata yang salah eja dengan daftar ejaan yang disarankan untuk setiap kata yang salah eja, serta jarak edit.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Temukan kata-kata yang salah eja dengan ejaan yang disarankan untuk teks input yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kamus yang akan digunakan. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList objek SpellCheckError yang mewakili kata-kata yang salah eja dengan daftar ejaan yang disarankan untuk setiap kata yang salah eja, serta jarak edit.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Menyimpan dokumen dalam teks biasa

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Menyimpan dokumen dalam teks biasa atau format dokumen lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan. |
| format | [Format](../../com.aspose.ocr.models/format/) | Enum tipe format dokumen dari Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Menyimpan dokumen dalam teks biasa atau format dokumen lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan. |
| format | [Format](../../com.aspose.ocr.models/format/) | Enum tipe format dokumen dari Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Kurangi ukuran file PDF dengan menurunkan kualitas gambar latar belakang. Secara default, kualitas gambar asli dipertahankan. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Menyimpan teks yang telah dikoreksi dengan kamus bahasa Inggris dalam dokumen dalam format teks biasa atau format Dokumen Teks Microsoft Word.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan. |
| format | [Format](../../com.aspose.ocr.models/format/) | Enum tipe format dokumen dari Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Menyimpan teks yang telah dikoreksi dalam dokumen dalam format teks biasa atau format lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan. |
| format | [Format](../../com.aspose.ocr.models/format/) | Enum tipe format dokumen dari Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kamus untuk pemeriksaan ejaan. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Memungkinkan penggunaan kamus sendiri untuk koreksi pemeriksaan ejaan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Jalur lengkap ke kamus pengguna (kamus frekuensi). Format file kamus: File teks biasa dengan enkoding UTF-8. Kata dan Frekuensi Kata dipisahkan oleh koma, kata diharapkan berada di kolom pertama dan frekuensi di kolom kedua. Setiap pasangan kata-frekuensi berada pada baris terpisah. Baris didefinisikan sebagai urutan karakter yang diikuti oleh line feed ("\n"), carriage return ("\r"), atau carriage return yang langsung diikuti oleh line feed ("\r\n"). Setiap kata diharapkan dalam huruf kecil. |
