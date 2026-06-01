---
title: "RecognitionSettings"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Pengaturan untuk pengenalan gambar"
type: docs
weight: 27
url: /id/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Pengaturan untuk pengenalan gambar. Berisi elemen yang memungkinkan penyesuaian proses pengenalan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Konstruktor default: set recognitionAreas null, linesFiltration false, autoSkew false, recognizeSingleLine false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Konstruktor memungkinkan mengatur semua opsi. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Konstruktor memungkinkan mengatur recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Set karakter yang diizinkan. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Set karakter yang diizinkan. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Mendeteksi gambar dengan teks putih pada latar belakang gelap/hitam dan secara otomatis memilih algoritma OCR khusus untuk mereka. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Menentukan jenis jaringan saraf yang digunakan untuk deteksi area. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Mengatur daftar hitam untuk simbol pengenalan. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Menentukan tingkat deteksi bahasa untuk pengenalan teks. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Memungkinkan mengenali teks dalam tabel (wilayah yang dikelilingi garis). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Menetapkan daftar area teks untuk diproses. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Menetapkan pengenalan gambar satu baris. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Mendapatkan atau mengatur jumlah thread untuk pemrosesan. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Memungkinkan Anda menggunakan algoritma tambahan khusus untuk pengenalan font kecil. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Konstruktor default: set recognitionAreas null, linesFiltration false, autoSkew false, recognizeSingleLine false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Konstruktor memungkinkan mengatur semua opsi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Persegi untuk pengenalan. |
| recognizeSingleLine | boolean | Benar jika gambar hanya berisi satu baris. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Konstruktor memungkinkan mengatur recognizeSingleLine. Nilai default dalam kasus ini: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recognizeSingleLine | boolean | Benar jika gambar hanya berisi satu baris. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Set karakter yang diizinkan. Menentukan jenis karakter yang diizinkan untuk hasil pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | berisi nilai enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/). |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Set karakter yang diizinkan. Menentukan array karakter yang diizinkan untuk hasil pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| allowedCharacters | java.lang.String | berisi string karakter. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Mendeteksi gambar dengan teks putih pada latar belakang gelap/hitam dan secara otomatis memilih algoritma OCR khusus untuk mereka.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| automaticColorInversion | boolean | berisi nilai boolean - automaticColorInversion diatur. Benar secara default. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Menentukan jenis jaringan saraf yang digunakan untuk deteksi area.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | berisi nilai enum @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/). |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Mengatur daftar hitam untuk simbol pengenalan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| characters | java.lang.String | Karakter yang dikecualikan dari pengenalan. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Mengatur bahasa yang digunakan untuk OCR. Multi-bahasa (none) secara default. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Menentukan tingkat deteksi bahasa untuk pengenalan teks. Hanya berfungsi jika bahasa yang dipilih adalah Language.MULTILANGUAGE, Language.AUTO, atau Language.UNIVERSAL. Proses ini memakan waktu dan secara signifikan memperlambat pengenalan secara keseluruhan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Memungkinkan mengenali teks dalam tabel (wilayah yang dikelilingi garis).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| linesFiltration | boolean | false - memungkinkan peningkatan kinerja dan tidak mendeteksi tabel serta menghapus baris; sebaliknya - true. Dinonaktifkan (false) secara default. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Mengatur daftar area teks untuk pemrosesan. Memungkinkan menentukan secara manual area dengan teks untuk pengenalan yang lebih akurat. Jika area khusus diatur [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} bukan NONE atau [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} properti akan diabaikan. Menonaktifkan DetectAreas dan AutoSkew.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Persegi untuk pengenalan. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Mengatur pengenalan gambar satu baris. Dinonaktifkan (false) secara default. Menonaktifkan semua langkah pemrosesan yang terkait dengan pemisahan menjadi baris. Atur parameter ini ke true jika gambar Anda hanya berisi satu baris. Menonaktifkan pengaturan [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList), sehingga semua pengaturan area akan diabaikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| recognizeSingleLine | boolean | Benar untuk gambar satu baris |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Mendapatkan atau mengatur jumlah thread untuk pemrosesan. Secara default, 0 berarti gambar akan diproses dengan jumlah thread yang sama dengan jumlah prosesor Anda. ThreadsCount = 1 berarti gambar akan diproses di thread utama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| threadsCount | int | jumlah thread yang akan dibuat untuk pengenalan paralel fragmen gambar. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Memungkinkan Anda menggunakan algoritma tambahan khusus untuk pengenalan font kecil. Berguna untuk gambar dengan karakter berukuran kecil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| upscaleSmallFont | boolean | berisi nilai boolean - upscaleSmallFont diatur. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String