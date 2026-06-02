---
title: "RecognitionResult"
second_title: "Aspose.OCR untuk Python melalui Java API Reference"
description: 
type: docs
weight: 171
url: /id/python-java/aspose/recognitionresult/
---

Modul recognitionresult
========================

Kelas
-------

`LinesResult(javaClass)`
:

### Nenek Moyang (dalam MRO)

    * aspose.helper.BaseJavaClass

### Metode

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Hasil dari pengenalan gambar. Berisi elemen dengan pengenalan
informasi dan metode untuk mengekspor hasil.

### Metode Statis

`save_multipage_document(self, fullPath: str)`
:
Privat

### Variabel instance

`recognition_areas_text`
:   Daftar hasil pengenalan dari daftar area (Persegi Panjang).

`recognition_lines_result`
:   Mendapatkan daftar hasil pengenalan dengan daftar baris (Persegi Panjang).

### Metode

`getJavaClass(self)`
:

`get_json(self)`
:
Bentuk string JSON dengan hasil pengenalan.
@return: Hasil pengenalan sebagai string JSON.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Mengoreksi teks (mengganti kata yang salah eja).
@param language: Kamus yang akan digunakan.
@return: String hasil pengenalan yang telah dikoreksi.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Temukan kata yang salah eja dengan ejaan yang disarankan untuk teks input yang diberikan.
@param language: Kamus yang akan digunakan.
@return: Daftar objek SpellCheckError yang mewakili kata yang salah eja dengan daftar ejaan yang benar yang disarankan untuk setiap kata yang salah eja,
dan dengan jarak edit.

`get_xml(self)`
:
Bentuk string JSON dengan hasil pengenalan.
@return: Hasil pengenalan sebagai string XML.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Menyimpan dokumen dalam format teks biasa atau format dokumen lainnya.
@param fullFileName: Nama file dengan jalur untuk menyimpan hasil pengenalan.
@param format: Tipe enum format dokumen dari Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Mengoreksi teks (mengganti kata yang salah eja).
Menyimpan teks yang telah dikoreksi dalam dokumen dalam format teks biasa atau format lainnya.
@param fullFileName: Nama file dengan jalur untuk menyimpan hasil pengenalan
@param format: Tipe enum format dokumen dari Format.
@param language: Kamus untuk pemeriksaan ejaan.

`use_user_dictionary(self, dictionaryPath: str)`
:
Memungkinkan penggunaan kamus sendiri untuk koreksi pemeriksaan ejaan.
@param dictionaryPath: Jalur lengkap ke kamus pengguna (kamus frekuensi).
Format file kamus:
File teks biasa dengan enkoding UTF-8.
Kata dan Frekuensi Kata dipisahkan oleh koma, kata diharapkan berada di kolom pertama dan frekuensi di kolom kedua.
Setiap pasangan kata‑frekuensi dalam baris terpisah. Sebuah baris didefinisikan sebagai urutan karakter yang diikuti oleh line feed (\")
\"), karakter kembali (\"
"),
atau carriage return yang segera diikuti oleh line feed("

").
Setiap kata diharapkan berada dalam huruf kecil.
Contoh:
\code
word,5984819
halo,5761742
bawah,5582768
\endcode

`RectangleOutput(javaClass)`
:
Data tentang area teks atau baris yang terdeteksi.
\code
source - Jalur lengkap ke file atau URL, jika ada. Kosong untuk stream, array byte, base64.
page - Nomor halaman.
image_index - Nomor urut gambar pada halaman.
rectangles - Daftar area teks atau baris yang terdeteksi.
\endcode

### Nenek Moyang (dalam MRO)

    * aspose.helper.BaseJavaClass

### Metode

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Data tentang sudut kemiringan dalam derajat dan nama file.
\code
source - Jalur lengkap ke file atau URL, jika ada. Kosong untuk stream, array byte, base64.
page - Nomor halaman.
image_index - Nomor urut gambar pada halaman.
angle - Sudut kemiringan dalam derajat.
\endcode

### Nenek Moyang (dalam MRO)

    * aspose.helper.BaseJavaClass

### Metode

`initParams(self)`
:


### Lihat Juga

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)