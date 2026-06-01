---
title: "AsposeOCR"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Kelas utama untuk mengenali teks dari gambar"
type: docs
weight: 10
url: /id/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Kelas utama untuk mengenali teks dari gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Konstruktor publik. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [DebugMode](#DebugMode) | Mengaktifkan mode debug. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Direktori tempat hasil debug akan disimpan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Menghitung sudut kemiringan gambar. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Periksa apakah dua gambar mengandung teks yang sama. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Periksa apakah dua gambar mengandung teks yang sama. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Periksa apakah dua gambar mengandung teks yang sama. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Mengoreksi teks (mengganti kata yang salah eja). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Mengoreksi teks (mengganti kata yang salah eja). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Secara otomatis menemukan area bermasalah pada gambar yang dapat secara signifikan memengaruhi akurasi OCR. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Menganalisis gambar dan mengidentifikasi berbagai jenis area konten di dalamnya. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Menganalisis teks pada gambar untuk menentukan bahasa yang digunakan. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Mendeteksi area teks pada gambar. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Mendeteksi wilayah tabel pada gambar. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Periksa apakah gambar mengandung fragmen teks yang diberikan dengan pencarian tidak sensitif huruf besar/kecil. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Periksa apakah gambar mengandung fragmen teks yang diberikan dengan pencarian tidak sensitif huruf besar/kecil. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Periksa apakah gambar mengandung fragmen teks yang diberikan. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Periksa apakah teks gambar cocok dengan ekspresi reguler yang diberikan. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Periksa apakah teks gambar cocok dengan ekspresi reguler yang diberikan. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip keduanya (0 hingga 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip keduanya (0 hingga 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip keduanya (0 hingga 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Mengenali gambar dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Mengenali gambar dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Mengenali plat mobil dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Mendeteksi simbol pada gambar. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Mendeteksi simbol pada gambar. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Mengenali teks pada gambar berkualitas baik. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Mengenali rumus matematika dari gambar masukan yang diberikan. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Mengenali teks tulisan tangan pada gambar. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Mengenali kartu identitas dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Mengenali faktur dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Mengenali paspor dengan kemampuan untuk menentukan. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Mengenali tanda terima dengan kemampuan untuk menentukan Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Mendeteksi tabel dan struktur, mengenali sel teks. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult dengan koreksi pemeriksaan ejaan. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Konstruktor publik.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Mengaktifkan mode debug. Ketika diaktifkan, sistem menyimpan hasil pemrosesan gambar menengah seperti gambar yang dipra-proses dan gambar dengan persegi panjang garis teks yang digambar.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Direktori tempat hasil debug akan disimpan. Jika tidak disetel, direktori kerja saat ini akan digunakan secara default.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Menghitung sudut kemiringan gambar. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - ArrayList sudut kemiringan dalam derajat [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Periksa apakah dua gambar mengandung teks yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath1 | java.lang.String | Jalur ke gambar pertama. |
| fullPath2 | java.lang.String | Jalur ke gambar kedua. |

**Returns:**
boolean - True jika gambar memiliki teks yang sama (kemiripan 90%).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Periksa apakah dua gambar mengandung teks yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath1 | java.lang.String | Jalur ke gambar pertama. |
| fullPath2 | java.lang.String | Jalur ke gambar kedua. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Pengaturan pengenalan. |

**Returns:**
boolean - True jika gambar memiliki teks yang sama (kemiripan 90%).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Periksa apakah dua gambar mengandung teks yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath1 | java.lang.String | Jalur ke gambar pertama. |
| fullPath2 | java.lang.String | Jalur ke gambar kedua. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Pengaturan pengenalan. |
| ignoreCase | boolean | True - berarti pencarian tidak sensitif huruf besar/kecil. |

**Returns:**
boolean - True jika gambar memiliki teks yang sama (kemiripan 90%).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Mengoreksi teks (mengganti kata yang salah eja).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks untuk koreksi. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kamus yang akan digunakan [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Teks dengan kata yang diganti.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Mengoreksi teks (mengganti kata yang salah eja).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks untuk koreksi. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Kamus yang akan digunakan [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Jalur lengkap ke kamus pengguna (kamus frekuensi). Format file kamus: File teks biasa dengan enkoding UTF-8. Kata dan Frekuensi Kata dipisahkan oleh koma, kata diharapkan berada di kolom pertama dan frekuensi di kolom kedua. Setiap pasangan kata-frekuensi berada pada baris terpisah. Baris didefinisikan sebagai urutan karakter yang diikuti oleh line feed ("\n"), carriage return ("\r"), atau carriage return yang langsung diikuti oleh line feed ("\r\n"). Setiap kata diharapkan dalam huruf kecil. |

**Returns:**
java.lang.String - Teks dengan kata yang diganti.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Secara otomatis menemukan area bermasalah pada gambar yang dapat secara signifikan memengaruhi akurasi OCR. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Jenis-jenis cacat yang akan dikenali [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList dari [DefectOutput](../../com.aspose.ocr/defectoutput/) dengan area teks atau baris yang terdeteksi.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Menganalisis gambar dan mengidentifikasi berbagai jenis area konten di dalamnya. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Area konten yang terdeteksi. ArrayList dari [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Menganalisis teks pada gambar untuk menentukan bahasa yang digunakan. Hal ini memungkinkan pemilihan bahasa pengenalan yang paling cocok dan membantu dalam tugas pemrosesan teks lebih lanjut seperti pemeriksaan ejaan atau terjemahan. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Mengembalikan daftar bahasa yang paling mungkin, diurutkan berdasarkan kemungkinan. ArrayList dari [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Mendeteksi area teks pada gambar. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Menentukan kotak mana yang akan dikembalikan - baris atau paragraf. |
| isDetectAreas | boolean | Aktifkan deteksi area teks otomatis. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList dari [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) dengan area teks atau baris yang terdeteksi.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Mendeteksi wilayah tabel pada gambar. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList dari [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) dengan wilayah tabel yang terdeteksi.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Periksa apakah gambar mengandung fragmen teks yang diberikan dengan pencarian tidak sensitif huruf besar/kecil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath | java.lang.String | Jalur ke gambar. |
| text | java.lang.String | Fragmen teks untuk pencarian pada gambar. |

**Returns:**
boolean - True jika gambar berisi fragmen teks. False - gambar tidak berisi fragmen teks.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Periksa apakah gambar mengandung fragmen teks yang diberikan dengan pencarian tidak sensitif huruf besar/kecil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath | java.lang.String | Jalur ke gambar. |
| text | java.lang.String | Fragmen teks untuk pencarian pada gambar. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Pengaturan pengenalan. |

**Returns:**
boolean - True jika gambar berisi fragmen teks. False - gambar tidak berisi fragmen teks.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Periksa apakah gambar mengandung fragmen teks yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath | java.lang.String | Jalur ke gambar. |
| text | java.lang.String | Fragmen teks untuk pencarian pada gambar. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Pengaturan pengenalan. |
| ignoreCase | boolean | True - berarti pencarian tidak sensitif huruf besar/kecil. |

**Returns:**
boolean - True jika gambar berisi fragmen teks. False - gambar tidak berisi fragmen teks.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Periksa apakah teks gambar cocok dengan ekspresi reguler yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath | java.lang.String | Jalur ke gambar. |
| regex | java.util.regex.Pattern | Objek java.util.regex.Pattern dengan pola dan opsi yang diberikan. |

**Returns:**
boolean - True jika teks gambar cocok dengan ekspresi reguler yang diberikan.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Periksa apakah teks gambar cocok dengan ekspresi reguler yang diberikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath | java.lang.String | Jalur ke gambar. |
| regex | java.util.regex.Pattern | Objek java.util.regex.Pattern dengan pola dan opsi yang diberikan. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Pengaturan pengenalan. |

**Returns:**
boolean - True jika teks gambar cocok dengan ekspresi reguler yang diberikan.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip keduanya (0 hingga 1).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath1 | java.lang.String | Jalur ke gambar pertama. |
| fullPath2 | java.lang.String | Jalur ke gambar kedua. |

**Returns:**
float - 0 berarti teks benar-benar berbeda; 1 berarti teks identik.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip keduanya (0 hingga 1).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath1 | java.lang.String | Jalur ke gambar pertama. |
| fullPath2 | java.lang.String | Jalur ke gambar kedua. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Pengaturan pengenalan. |

**Returns:**
float - 0 berarti teks benar-benar berbeda; 1 berarti teks identik.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip keduanya (0 hingga 1).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath1 | java.lang.String | Jalur ke gambar pertama. |
| fullPath2 | java.lang.String | Jalur ke gambar kedua. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Pengaturan pengenalan. |
| ignoreCase | boolean | True - berarti pencarian tidak sensitif huruf besar/kecil. |

**Returns:**
float - 0 berarti teks benar-benar berbeda; 1 berarti teks identik.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Mengenali gambar dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Mengenali gambar dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Mengenali plat mobil dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Mendeteksi simbol pada gambar. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList dari [Character](../../com.aspose.ocr.models/character/) dengan data simbol yang terdeteksi untuk setiap gambar.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Mendeteksi simbol pada gambar. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Kontainer dengan sumber.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Menentukan jenis jaringan saraf yang digunakan untuk deteksi area. |
| language | [Language](../../com.aspose.ocr.models/language/) | Bahasa yang digunakan untuk OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList dari [Character](../../com.aspose.ocr.models/character/) dengan data simbol yang terdeteksi.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Mengenali teks pada gambar berkualitas baik. Tidak menggunakan koreksi kemiringan gambar otomatis dan deteksi area teks. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Instansi [OcrInput](../../com.aspose.ocr/ocrinput/). |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList dengan teks yang dikenali.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Mengenali rumus matematika dari gambar masukan yang disediakan. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| detectAreas | boolean | Jika disetel ke true, secara otomatis mendeteksi dan mengisolasi wilayah rumus sebelum melakukan pengenalan. Jika false, memproses seluruh gambar sebagai rumus. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Mengenali teks tulisan tangan pada gambar. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Kontainer dengan sumber.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Mengenali kartu identitas dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Mengenali faktur dengan kemampuan untuk menentukan dukungan GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Mengenali paspor dengan kemampuan untuk menentukan. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Mengenali tanda terima dengan kemampuan untuk menentukan Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Mendeteksi tabel dan struktur, mengenali sel teks. Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, folder, array, arsip zip, URL, base64.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instansi. |
| language | [Language](../../com.aspose.ocr.models/language/) | Menentukan alfabet yang digunakan selama pengenalan. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - objek daftar OCRTablePage dengan teks yang dikenali dalam tabel. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Daftar [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objek. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Daftar [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objek. |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Daftar [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objek. |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Kurangi ukuran file PDF dengan menurunkan kualitas gambar latar belakang. Secara default, kualitas gambar asli dipertahankan. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Daftar [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objek. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult dengan koreksi pemeriksaan ejaan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Daftar [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objek. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) nilai enum. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Daftar [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objek. |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Memungkinkan mendapatkan dokumen multipage dari daftar objek RecognitionResult.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Daftar [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objek. |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Kurangi ukuran file PDF dengan menurunkan kualitas gambar latar belakang. Secara default, kualitas gambar asli dipertahankan. |

### close() {#close}
```
public void close()
```