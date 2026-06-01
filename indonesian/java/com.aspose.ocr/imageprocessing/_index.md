---
title: "ImageProcessing"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Kelas pembantu untuk pustaka Aspose OCR"
type: docs
weight: 19
url: /id/java/com.aspose.ocr/imageprocessing/
---

**Inheritance:**
java.lang.Object
```
public class ImageProcessing
```

Kelas pembantu untuk pustaka Aspose OCR. Memungkinkan pra‑pemrosesan dan penyimpanan gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageProcessing()](#ImageProcessing) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [Render(OcrInput images)](#Render-com.aspose.ocr.OcrInput) | Gunakan pemrosesan gambar untuk meningkatkan akurasi OCR. |
| [Save(OcrInput images, String folderPath)](#Save-com.aspose.ocr.OcrInput-java.lang.String) | Gunakan pemrosesan gambar untuk meningkatkan akurasi OCR. |

### ImageProcessing() {#ImageProcessing}
```
public ImageProcessing()
```


### Render(OcrInput images) {#Render-com.aspose.ocr.OcrInput}
```
public static OcrInput Render(OcrInput images)
```


Gunakan pemrosesan gambar untuk meningkatkan akurasi OCR. Buat daftar filter yang akan diterapkan pada gambar masukan dalam urutan yang Anda tentukan. Contoh untuk membuat filter: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Anda tidak perlu semua filter tersebut. Atur hanya yang Anda butuhkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Objek OcrInput yang berisi berbagai gambar @see \#OcrInput. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput in Image field.
### Save(OcrInput images, String folderPath) {#Save-com.aspose.ocr.OcrInput-java.lang.String}
```
public static OcrInput Save(OcrInput images, String folderPath)
```


Gunakan pemrosesan gambar untuk meningkatkan akurasi OCR. Buat daftar filter yang akan diterapkan pada gambar masukan dalam urutan yang Anda tentukan. Contoh untuk membuat filter: PreprocessingFilter filters = new PreprocessingFilter(); filters.add(PreprocessingFilter.AutoDewarping()); filters.add(PreprocessingFilter.Invert()); filters.add(PreprocessingFilter.Threshold(150)); filters.add(PreprocessingFilter.Binarize()); filters.add(PreprocessingFilter.Rotate(180)); filters.add(PreprocessingFilter.Scale(6f)); filters.add(PreprocessingFilter.Dilate()); Anda tidak perlu semua filter tersebut. Atur hanya yang Anda butuhkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Objek OcrInput yang berisi berbagai gambar @see \#OcrInput. |
| folderPath | java.lang.String | Jalur tanpa nama gambar untuk menyimpan gambar yang diproses. |

**Returns:**
[OcrInput](../../com.aspose.ocr/ocrinput/) - OcrInput object containing result processed images @see \#OcrInput.
