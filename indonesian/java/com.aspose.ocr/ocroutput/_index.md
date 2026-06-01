---
title: "OcrOutput"
second_title: "Referensi API Aspose.OCR untuk Java"
description: 
type: docs
weight: 21
url: /id/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OcrOutput()](#OcrOutput) | Menginisialisasi instance baru dari kelas OcrOutput dengan koleksi kosong. |
## Metode

| Metode | Deskripsi |
| --- | --- |

| [getTableData()](#getTableData) | Mengembalikan data tabel terstruktur yang diekstrak dari semua halaman yang dikenali. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | Simpan semua hasil pengenalan ke aliran memori dalam format yang ditentukan. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | Simpan semua hasil pengenalan ke aliran memori dalam format yang ditentukan. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Simpan semua hasil pengenalan ke aliran memori dalam format yang ditentukan. |
| [save(String fullFileName)](#save-java.lang.String) | Simpan semua hasil pengenalan ke sebuah file. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | Simpan semua hasil pengenalan ke sebuah file. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Simpan semua hasil pengenalan ke sebuah file. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | Simpan semua hasil pengenalan ke dalam dokumen PDF yang dapat dicari dalam memori, menyematkan gambar asli sebagai latar belakang. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Simpan semua hasil pengenalan ke dalam dokumen PDF yang dapat dicari dalam memori, menyematkan gambar asli sebagai latar belakang. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | Simpan semua hasil pengenalan ke dalam file PDF yang dapat dicari, dengan gambar asli diatur sebagai latar belakang. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Simpan semua hasil pengenalan ke dalam file PDF yang dapat dicari, dengan gambar asli diatur sebagai latar belakang. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


Mengembalikan data tabel terstruktur yang diekstrak dari semua halaman yang dikenali.

Setiap halaman berisi baris, dan setiap baris berisi sel dengan teks yang dikenali serta informasi posisi opsional.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


Simpan semua hasil pengenalan ke aliran memori dalam format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


Simpan semua hasil pengenalan ke aliran memori dalam format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Simpan semua hasil pengenalan ke aliran memori dalam format yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Kurangi ukuran file PDF dengan menurunkan kualitas gambar latar belakang. Secara default, kualitas gambar asli dipertahankan. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Simpan semua hasil pengenalan ke sebuah file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


Simpan semua hasil pengenalan ke sebuah file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Simpan semua hasil pengenalan ke sebuah file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Format dokumen (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Kurangi ukuran file PDF dengan menurunkan kualitas gambar latar belakang. Secara default, kualitas gambar asli dipertahankan. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


Simpan semua hasil pengenalan ke dalam dokumen PDF yang dapat dicari dalam memori, menyematkan gambar asli sebagai latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Simpan semua hasil pengenalan ke dalam dokumen PDF yang dapat dicari dalam memori, menyematkan gambar asli sebagai latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Kurangi ukuran file PDF dengan menurunkan kualitas gambar latar belakang. Secara default, kualitas gambar asli dipertahankan. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


Simpan semua hasil pengenalan ke dalam file PDF yang dapat dicari, dengan gambar asli diatur sebagai latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Simpan semua hasil pengenalan ke dalam file PDF yang dapat dicari, dengan gambar asli diatur sebagai latar belakang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullFileName | java.lang.String | Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih. |
| embeddedFontPath | java.lang.String | Opsional. Jalur lengkap ke font pengguna. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Kurangi ukuran file PDF dengan menurunkan kualitas gambar latar belakang. Secara default, kualitas gambar asli dipertahankan. |

### size() {#size}
```
public int size()
```




**Returns:**
int
