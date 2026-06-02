---
title: "model"
second_title: "Aspose.OCR untuk Python melalui Java API Reference"
description: 
type: docs
weight: 271
url: /id/python-java/aspose/models/
---

Modul model
=============

Kelas
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Menentukan tipe wilayah yang terdeteksi oleh model.
Digunakan dalam get_text_areas untuk menunjukkan hasil apa yang akan diperoleh - koordinat paragraf atau koordinat baris.

### Nenek Moyang (dalam MRO)

    * enum.Enum

### Variabel kelas

`LINES`
:   Mengatur wilayah sebagai baris

`PARAGRAPHS`
:   Mengatur wilayah sebagai paragraf

`WORDS`
:   Mengatur wilayah sebagai kata

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Menentukan tipe jaringan saraf yang digunakan untuk deteksi area.
Digunakan dalam RecognitionSettings untuk menentukan tipe gambar yang ingin Anda kenali.

### Nenek Moyang (dalam MRO)

    * enum.Enum

### Variabel kelas

`COMBINE`
:   Mendeteksi paragraf dengan teks dan kemudian menggunakan model NN lain untuk mendeteksi area di dalam paragraf.
Lebih baik untuk gambar dengan struktur kompleks.

`CURVED_TEXT`
:   Mendeteksi baris dan mengenali teks pada gambar melengkung.
Mode yang disarankan untuk foto halaman buku dan majalah.

`DOCUMENT`
:   Mendeteksi paragraf menggunakan model NN untuk dokumen.
Lebih baik untuk dokumen multi-kolom, dokumen dengan gambar atau dengan objek non-teks lainnya.

`NONE`
:   Tidak mendeteksi paragraf.
Lebih baik untuk dokumen satu kolom sederhana tanpa gambar.

`PHOTO`
:   Mendeteksi paragraf menggunakan model NN untuk foto.
Lebih baik untuk gambar dengan banyak gambar dan objek non-teks lainnya.

`TABLE`
:   Mendeteksi sel dengan teks.
Mode yang disarankan untuk gambar dengan struktur tabel.

`TEXT_IN_WILD`
:   Jaringan saraf super-kuat yang khusus mengekstrak kata dari gambar berkualitas rendah seperti foto jalan, plat nomor, foto paspor, foto meter, dan foto dengan latar belakang berisik.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Format untuk menyimpan hasil pengenalan sebagai dokumen.

### Nenek Moyang (dalam MRO)

    * enum.Enum

### Variabel kelas

`DOCX`
:   Menyimpan hasil sebagai Dokumen Office Open XML Word processing ML (tanpa makro).

`EPUB`
:   Menyimpan dokumen sebagai file EPUB.

`HTML`
:   Menyimpan dokumen sebagai file HTML.

`JSON`
:   Menyimpan hasil sebagai teks biasa yang ditulis dalam notasi objek JavaScript.

`PDF`
:   Menyimpan hasil sebagai PDF (Adobe Portable Document) Document.

`PDF_NO_IMG`
:   Menyimpan dokumen sebagai PDF yang Dapat Dicari (Adobe Portable Document) Document tanpa gambar.

`RTF`
:   Menyimpan dokumen sebagai file rtf.

`TEXT`
:   Menyimpan hasil dalam format teks biasa.

`XLSX`
:   Menyimpan hasil sebagai Dokumen workbook Excel (2007 dan lebih baru).

`XML`
:   Menyimpan hasil sebagai Dokumen XML.

`ImageData(javaClass)`
:

### Nenek Moyang (dalam MRO)

    * aspose.helper.BaseJavaClass

### Metode

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Jenis gambar/dokumen untuk pemrosesan / pengenalan.

### Nenek Moyang (dalam MRO)

    * enum.Enum

### Variabel kelas

`BASE64`
:   string base64 dengan gambar atau path ke file .txt dengan konten base64. Mendukung GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   Path ke direktori. Arsip dan folder bersarang tidak didukung.
Mendukung GIF, PNG, JPEG, BMP, TIFF.
Jumlah default gambar yang diproses adalah semua.

`PDF`
:   Dokumen PDF yang dipindai dari file atau dari bynary array.

`SINGLE_IMAGE`
:   Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, array biner.

`TIFF`
:   Dokumen TIFF multipage, TIF dari file atau dari InputStream.

`URL`
:   Tautan pada gambar. Mendukung GIF, PNG, JPEG, BMP, TIFF.

`ZIP`
:   Nama lengkap arsip ZIP. Arsip bersarang dan folder tidak didukung.
Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF.
Jumlah default gambar yang diproses adalah semua.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Model bahasa untuk pengenalan.

### Nenek Moyang (dalam MRO)

    * enum.Enum

### Variabel kelas

`BEL`
:   Alfabet Belarusia

`BUL`
:   Alfabet Bulgaria

`CHI`
:   Alfabet Cina

`CYRILLIC`
:   Dukungan multi-bahasa (alfabet Sirilik)

`CZE`
:   Alfabet Ceko

`DAN`
:   Alfabet Denmark

`DEU`
:   alfabet Jerman

`DUM`
:   alfabet Belanda

`ENG`
:   alfabet Inggris

`EST`
:   alfabet Estonia

`FIN`
:   alfabet Finlandia

`FRA`
:   alfabet Prancis

`HIN`
:   alfabet Hindi

`ITA`
:   alfabet Italia

`KAZ`
:   alfabet Kazakh

`LATIN`
:   Dukungan multi-bahasa (alfabet latin)

`LAV`
:   alfabet Latvia

`LIT`
:   alfabet Lituania

`NONE`
:   Dukungan multi-bahasa

`NOR`
:   alfabet Norwegia

`POL`
:   alfabet Polandia

`POR`
:   alfabet Portugis

`RUM`
:   alfabet Rumania

`RUS`
:   alfabet Rusia

`SLK`
:   alfabet Slowakia

`SLV`
:   alfabet Slovenia

`SPA`
:   alfabet Spanyol

`SRP`
:   alfabet Serbia

`SRP_HRV`
:   alfabet Serbo-Kroasia

`SWE`
:   alfabet Swedia

`UKR`
:   alfabet Ukraina

`ModelsConverter()`
:

### Metode

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   Kelas utama untuk mengumpulkan gambar.
    
Konstruktor untuk membuat kontainer dan mengatur tipe gambar / dokumen serta filter untuk pemrosesan / pengenalan lebih lanjut.
@param type: Tetapkan tipe gambar/dokumen yang akan ditambahkan ke kontainer.
@param filters: Tetapkan filter pemrosesan yang akan diterapkan untuk pemrosesan atau pengenalan lebih lanjut.

### Metode

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Tambahkan jalur atau URI yang berisi gambar untuk pengenalan / pemrosesan.
Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.
@param fullPath: Jalur ke gambar/dokumen/folder/arsip.
@param startPage: Halaman/gambar pertama untuk pemrosesan / pengenalan. Gunakan untuk dokumen, zip, folder.
@param pagesNumber: Jumlah total halaman/gambar untuk pemrosesan / pengenalan. Gunakan untuk dokumen, zip, folder. Default = semua.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Tambahkan InputStream yang berisi gambar untuk pengenalan / pemrosesan.
Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: berisi gambar atau dokumen.
@param startPage: Halaman/gambar pertama untuk pemrosesan / pengenalan. Gunakan untuk dokumen, zip, folder.
@param pagesNumber: Jumlah total halaman/gambar untuk pemrosesan / pengenalan. Gunakan untuk dokumen, zip, folder. Default = semua.

`add_base64(self, base64: str)`
:   Tambahkan string base64 yang berisi gambar untuk pengenalan / pemrosesan.
Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor.
@param base64: String Base64 dengan satu gambar.

`clear(self)`
:   Atur jumlah item untuk pemrosesan / pengenalan menjadi 0.
Bersihkan koleksi.

`clear_filters(self)`
:   Hapus semua filter.

`get(self, index: int) ‑> models.ImageData`
:   Mengembalikan informasi tentang gambar yang diproses / dikenali.
@param index: Posisi gambar dalam Daftar.
@return: Objek ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   Jumlah item untuk pemrosesan / pengenalan.
@return: Jumlah item.

`PreprocessingFilter()`
:   Kelas dasar untuk perintah pemrosesan gambar.

### Nenek Moyang (dalam MRO)

    * aspose.helper.BaseJavaClass

### Variabel kelas

`JAVA_CLASS_NAME`
:

### Metode Statis

`auto_denoising()`
:   Mengaktifkan penggunaan jaringan saraf tambahan untuk meningkatkan gambar - mengurangi noise.
Berguna untuk gambar dengan artefak pemindaian, distorsi, noda, kilatan, gradien, elemen asing.
@return: Objek AutoDenoisingFilter.

`auto_dewarping()`
:   Secara otomatis memperbaiki distorsi geometris pada gambar.
Sangat intensif sumber daya!
@return: Objek AutoDewarpingFilter.

`auto_skew()`
:   Mengaktifkan koreksi kemiringan gambar otomatis.
@return: AutoSkewFilter objek.

`binarize()`
:   Mengonversi gambar menjadi gambar hitam-putih.
Gambar biner adalah gambar yang pikselnya hanya memiliki dua nilai intensitas yang mungkin.
Biasanya mereka ditampilkan sebagai hitam dan putih. Secara numerik, dua nilai tersebut biasanya 0 untuk hitam, dan 255 untuk putih.
Gambar biner dihasilkan dengan melakukan ambang otomatis pada gambar.
@return: BinarizeFilter objek.

`binarize_and_dilate()`
:   Dilation menambahkan piksel ke batas objek dalam gambar.
@return: DilateFilter objek.

`contrast_correction()`
:   Filter koreksi kontras.
@return: ContrastCorrectionFilter objek.

`invert()`
:   Secara otomatis membalik warna pada gambar dokumen.
@return: InvertFilter objek.

`median()`
:   Filter median menjalankan proses pada setiap elemen gambar dan mengganti setiap piksel dengan nilai median dari piksel tetangganya.
@return: MedianFilter objek.

`resize(width: int, height: int)`
:   Mengubah skala gambar - memperbesar atau memperkecil resolusi gambar.
@param width: Lebar baru gambar.
@param height: Tinggi baru gambar.
@return: objek ResizeFilter.

`rotate(angle: float)`
:   Putar gambar asli.
@param angle: Sudut rotasi. Nilai dari -360 hingga 360.
@return: objek RotateFilter.

`scale(ratio: float)`
:   Skala ulang gambar - Tingkatkan atau turunkan resolusi gambar.
InterpolationFilterType bilinear atau nearest neighbor.
@param ratio: Faktor skala. Nilai yang direkomendasikan dari 0.1 hingga 1 untuk memperkecil. Dari 1 hingga 10 untuk memperbesar.
@return: objek ScaleFilter.

`threshold(value: int)`
:   Buat gambar biner berdasarkan penetapan nilai ambang pada intensitas piksel gambar asli.
@param value: Nilai maksimum.
@return: BinarizeFilter objek.

`to_grayscale()`
:   Mengonversi gambar menjadi gambar grayscale.
Gambar grayscale memiliki 256 tingkat cahaya dalam gambar (0 hingga 255).
@return: objek GrayscaleFilter.

### Metode

`add(self, filter)`
:   Tambahkan filter ke koleksi untuk pra-pemrosesan lebih lanjut.
@param filter: objek PreprocessingFilter.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Mewakili kata yang salah eja dengan data tambahan.

### Nenek Moyang (dalam MRO)

    * aspose.helper.BaseJavaClass

### Metode

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Bahasa kamus untuk koreksi ejaan.

### Nenek Moyang (dalam MRO)

    * enum.Enum

### Variabel kelas

`CZE`
:   Kamus bahasa Ceko

`DAN`
:   kamus Bahasa Denmark

`DEU`
:   kamus Bahasa Jerman

`DUM`
:   kamus Bahasa Belanda

`ENG`
:   kamus Bahasa Inggris

`EST`
:   kamus Bahasa Estonia

`FIN`
:   kamus Bahasa Finlandia

`FRA`
:   kamus Bahasa Prancis

`ITA`
:   kamus Bahasa Italia

`LAV`
:   kamus Bahasa Latvia

`LIT`
:   kamus Bahasa Lituania

`POL`
:   kamus Bahasa Polandia

`POR`
:   kamus Bahasa Portugis

`RUM`
:   kamus Bahasa Rumania

`SLK`
:   kamus Bahasa Slowakia

`SLV`
:   kamus Bahasa Slovenia

`SPA`
:   kamus Bahasa Spanyol

`SWE`
:   kamus Bahasa Swedia

`SuggestedWord(javaClass)`
:   Saran ejaan yang dikembalikan dari get_spell_check_error_list.

### Nenek Moyang (dalam MRO)

    * aspose.helper.BaseJavaClass

### Metode

`initParams(self)`
:


### Lihat Juga

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)