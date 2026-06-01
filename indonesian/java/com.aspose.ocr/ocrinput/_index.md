---
title: "OcrInput"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Kelas utama untuk mengenali teks dari gambar"
type: docs
weight: 20
url: /id/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

Kelas utama untuk mengenali teks dari gambar.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | Konstruktor untuk membuat kontainer dan mengatur tipe gambar / dokumen serta filter untuk pemrosesan / pengenalan lebih lanjut. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | Tambahkan gambar yang didekode ke daftar untuk pengenalan / pemrosesan. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | Tambahkan BufferedImage yang berisi gambar untuk pengenalan / pemrosesan. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | Tambahkan BufferedImage yang berisi gambar multipage untuk pengenalan / pemrosesan. |
| [add(InputStream stream)](#add-java.io.InputStream) | Tambahkan InputStream yang berisi gambar untuk pengenalan / pemrosesan. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | Tambahkan InputStream yang berisi gambar multipage untuk pengenalan / pemrosesan. |
| [add(String fullPath)](#add-java.lang.String) | Tambahkan path atau URI yang berisi gambar untuk pengenalan / pemrosesan. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | Tambahkan gambar / dokumen multipage untuk pengenalan / pemrosesan. |
| [addBase64(String base64)](#addBase64-java.lang.String) | Tambahkan string base64 yang berisi gambar untuk pengenalan / pemrosesan. |
| [clear()](#clear) | Atur jumlah item untuk pemrosesan / pengenalan menjadi 0. |
| [clearFilters()](#clearFilters) | Hapus semua filter. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | Mengembalikan informasi tentang gambar yang diproses / dikenali. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | Hapus filter lama dan atur yang baru. |
| [size()](#size) | Jumlah item untuk pemrosesan / pengenalan. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


Konstruktor untuk membuat kontainer dan mengatur tipe gambar / dokumen serta filter untuk pemrosesan / pengenalan lebih lanjut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | Atur tipe gambar/dokumen yang akan ditambahkan ke kontainer. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Filter pemrosesan yang diatur akan diterapkan untuk pemrosesan atau pengenalan lebih lanjut. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


Tambahkan gambar terdekripsi ke daftar untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor (SingleImage).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| piksel | int[] | Piksel direpresentasikan sebagai nilai integer 32-bit (rgb). |
| lebar | int | Lebar gambar. |
| tinggi | int | Tinggi gambar. |
| bitsPerPixel | int | Mendukung 1-32 bit. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


Tambahkan BufferedImage yang berisi gambar untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | java.awt.image.BufferedImage | BufferedImage yang berisi gambar atau dokumen. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


Tambahkan BufferedImage yang berisi gambar multipage untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | java.awt.image.BufferedImage | BufferedImage yang berisi dokumen multipage. |
| startPage | int | Halaman/gambar pertama untuk pemrosesan / pengenalan. Gunakan untuk dokumen. |
| pagesCount | int | Jumlah total halaman/gambar untuk pemrosesan / pengenalan. Gunakan untuk dokumen. Default = semua. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


Tambahkan InputStream yang berisi gambar untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream yang berisi gambar atau dokumen. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


Tambahkan InputStream yang berisi gambar multipage untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | InputStream yang berisi dokumen multipage. |
| startPage | int | Halaman/gambar pertama untuk pemrosesan / pengenalan. Gunakan untuk dokumen. |
| pagesCount | int | Jumlah total halaman/gambar untuk pemrosesan / pengenalan. Gunakan untuk dokumen. Default = semua. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


Tambahkan path atau URI yang berisi gambar untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath | java.lang.String | Path ke gambar/ dokumen / folder / arsip. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


Tambahkan gambar / dokumen multipage untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fullPath | java.lang.String | Path ke gambar/ dokumen / folder / arsip. |
| startPage | int | Halaman/gambar pertama untuk pemrosesan / pengenalan. Gunakan untuk dokumen, zip, folder. |
| pagesCount | int | Jumlah total halaman/gambar untuk pemrosesan / pengenalan. Gunakan untuk dokumen, zip, folder. Default = semua. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


Tambahkan string base64 yang berisi gambar untuk pengenalan / pemrosesan. Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| base64 | java.lang.String | String Base64 dengan satu gambar. |

### clear() {#clear}
```
public void clear()
```


Setel jumlah item untuk pemrosesan / pengenalan menjadi 0. Bersihkan koleksi.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


Hapus semua filter.

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
### get(int index) {#get-int}
```
public ImageData get(int index)
```


Mengembalikan informasi tentang gambar yang diproses / dikenali.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi gambar dalam List. |

**Returns:**
[ImageData](../../com.aspose.ocr/imagedata/) - The object of @see [ImageData](../../com.aspose.ocr/imagedata/)
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
### iterator() {#iterator}
```
public Iterator<ImageData> iterator()
```




**Returns:**
java.util.Iterator<com.aspose.ocr.ImageData>
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### replaceFilters(PreprocessingFilter filters) {#replaceFilters-com.aspose.ocr.PreprocessingFilter}
```
public void replaceFilters(PreprocessingFilter filters)
```


Hapus filter lama dan atur yang baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | Filter pemrosesan akan diterapkan untuk pemrosesan atau pengenalan lebih lanjut. |

### size() {#size}
```
public int size()
```


Jumlah item untuk pemrosesan / pengenalan.

**Returns:**
int - Jumlah item.
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

