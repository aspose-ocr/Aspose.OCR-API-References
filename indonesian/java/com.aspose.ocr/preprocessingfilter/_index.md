---
title: "PreprocessingFilter"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Kelas dasar untuk perintah pemrosesan gambar"
type: docs
weight: 24
url: /id/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

Kelas dasar untuk perintah pemrosesan gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Empty](#Empty) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | Mengaktifkan penggunaan jaringan saraf tambahan untuk meningkatkan gambar - mengurangi noise. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | Mengaktifkan penggunaan jaringan saraf tambahan untuk meningkatkan bagian gambar - mengurangi noise. |
| [AutoDewarping()](#AutoDewarping) | Secara otomatis memperbaiki distorsi geometris pada gambar. |
| [AutoSkew()](#AutoSkew) | Mengaktifkan koreksi kemiringan gambar secara otomatis. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | Mengaktifkan koreksi kemiringan bagian gambar secara otomatis. |
| [Binarize()](#Binarize) | Mengonversi gambar menjadi gambar hitam-putih. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | Mengonversi bagian gambar menjadi gambar hitam-putih. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | Dilasi menambahkan piksel ke batas objek dalam gambar. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | Dilasi menambahkan piksel ke batas objek dalam bagian gambar. |
| [ContrastCorrection()](#ContrastCorrection) | Filter koreksi kontras. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | Filter koreksi kontras untuk bagian gambar. |
| [Invert()](#Invert) | Secara otomatis membalikkan warna pada gambar dokumen. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | Secara otomatis membalikkan warna pada bagian gambar. |
| [Median()](#Median) | Filter median berjalan melalui setiap elemen gambar dan menggantikan setiap piksel dengan median piksel tetangganya. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | Filter median berjalan melalui setiap elemen bagian gambar dan mengganti setiap piksel dengan median piksel tetangganya. |
| [Resize(int width, int height)](#Resize-int-int) | Ubah skala gambar - Tingkatkan atau turunkan resolusi gambar. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | Ubah skala gambar - tingkatkan atau turunkan resolusi gambar. |
| [Rotate(float angle)](#Rotate-float) | Putar gambar asli. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | Putar bagian gambar. |
| [Scale(float ratio)](#Scale-float) | Ubah skala gambar - Tingkatkan atau turunkan resolusi gambar. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | Ubah skala gambar - Tingkatkan atau turunkan resolusi gambar. |
| [Threshold(int value)](#Threshold-int) | Buat gambar biner berdasarkan penetapan nilai ambang pada intensitas piksel gambar asli. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | Buat bagian gambar biner berdasarkan penetapan nilai ambang pada intensitas piksel bagian gambar asli. |
| [ToGrayscale()](#ToGrayscale) | Mengonversi gambar menjadi gambar skala abu-abu. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | Tambahkan filter baru ke koleksi untuk menjalankan semua operasi lebih lanjut. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### PreprocessingFilter() {#PreprocessingFilter}
```
public PreprocessingFilter()
```


### Empty {#Empty}
```
public static final PreprocessingFilter Empty
```


### AutoDenoising() {#AutoDenoising}
```
public static PreprocessingFilter AutoDenoising()
```


Mengaktifkan penggunaan jaringan saraf tambahan untuk meningkatkan gambar - mengurangi noise. Berguna untuk gambar dengan artefak pemindaian, distorsi, noda, flare, gradien, elemen asing.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


Mengaktifkan penggunaan jaringan saraf tambahan untuk meningkatkan bagian gambar - mengurangi noise. Berguna untuk gambar dengan artefak pemindaian, distorsi, noda, flare, gradien, elemen asing.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


Secara otomatis memperbaiki distorsi geometris pada gambar. Sangat intensif sumber daya!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


Mengaktifkan koreksi kemiringan gambar secara otomatis.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


Mengaktifkan koreksi kemiringan bagian gambar secara otomatis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


Mengonversi gambar menjadi gambar hitam-putih. Gambar biner adalah gambar yang pikselnya hanya memiliki dua nilai intensitas yang mungkin. Mereka biasanya ditampilkan sebagai hitam dan putih. Secara numerik, dua nilai tersebut biasanya 0 untuk hitam, dan 255 untuk putih. Gambar biner dihasilkan dengan melakukan ambang otomatis pada gambar.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


Mengonversi bagian gambar menjadi gambar hitam-putih. Gambar biner adalah gambar yang pikselnya hanya memiliki dua nilai intensitas yang mungkin. Mereka biasanya ditampilkan sebagai hitam dan putih. Secara numerik, dua nilai tersebut biasanya 0 untuk hitam, dan 255 untuk putih. Gambar biner dihasilkan dengan melakukan ambang otomatis pada gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


Dilasi menambahkan piksel ke batas objek dalam gambar.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


Dilasi menambahkan piksel ke batas objek dalam bagian gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


Filter koreksi kontras.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


Filter koreksi kontras untuk bagian gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


Secara otomatis membalikkan warna pada gambar dokumen.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


Secara otomatis membalikkan warna pada bagian gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


Filter median berjalan melalui setiap elemen gambar dan menggantikan setiap piksel dengan median piksel tetangganya.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


Filter median berjalan melalui setiap elemen bagian gambar dan mengganti setiap piksel dengan median piksel tetangganya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


Ubah skala gambar - Tingkatkan atau turunkan resolusi gambar. InterpolationFilterType = bilinear atau nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Lebar baru gambar. |
| tinggi | int | Tinggi baru gambar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


Ubah skala gambar - tingkatkan atau turunkan resolusi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar | int | Lebar baru gambar. |
| tinggi | int | Tinggi baru gambar. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @lihat [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


Putar gambar asli.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. Nilai dari -360 hingga 360. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


Putar bagian gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut | float | Sudut rotasi. Nilai dari -360 hingga 360. |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


Ubah skala gambar - Meningkatkan atau menurunkan resolusi gambar. InterpolationFilterType default bilinear atau nearest neighbor @lihat [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rasio | float | Faktor skala. Nilai yang direkomendasikan dari 0,1 hingga 1 untuk memperkecil. Dari 1 hingga 10 untuk memperbesar. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


Ubah skala gambar - Tingkatkan atau turunkan resolusi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rasio | float | Faktor skala. Nilai yang direkomendasikan dari 0,1 hingga 1 untuk memperkecil. Dari 1 hingga 10 untuk memperbesar. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @lihat [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


Buat gambar biner berdasarkan penetapan nilai ambang pada intensitas piksel gambar asli.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai maksimum. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


Buat bagian gambar biner berdasarkan penetapan nilai ambang pada intensitas piksel bagian gambar asli.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai maksimum. |
| area | java.awt.Rectangle | Rectangle untuk diproses sebelumnya. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


Mengonversi gambar menjadi gambar skala abu-abu. Gambar skala abu-abu memiliki 256 tingkat cahaya dalam gambar (0 hingga 255).

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


Tambahkan filter baru ke koleksi untuk menjalankan semua operasi lebih lanjut. Konsistensi dalam koleksi penting.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Operasi baru untuk ditambahkan ke daftar filter. |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

