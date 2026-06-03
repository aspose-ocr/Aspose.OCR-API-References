---
title: "RecognitionResult"
second_title: "Referensi API Aspose.OCR untuk Python via .NET"
description: 
type: docs
weight: 290
url: /id/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Hasil dari pengenalan gambar.<br/>            Berisi elemen dengan informasi pengenalan dan metode untuk mengekspor hasil.

Tipe RecognitionResult menampilkan anggota-anggota berikut:


## Properti
| Nama | Deskripsi |
| :- | :- |
| recognition_regions_result | Mendapatkan daftar hasil pengenalan dengan daftar wilayah (Persegi panjang). |
| recognition_lines_result | Mendapatkan daftar hasil pengenalan dengan daftar baris (Rectangles). |
| recognition_characters_list | Sekumpulan karakter yang ditemukan oleh algoritma pengenalan dan diatur dalam urutan menurun berdasarkan probabilitas. |
| recognition_text | Mendapatkan hasil pengenalan dalam satu string. |
| file_name | Jalur lengkap ke file. |
| warnings | Mendapatkan daftar pesan peringatan yang menggambarkan kesalahan non-kritis yang muncul selama proses pembuatan. |
| serializable_image |  |
## Methods
| Nama | Deskripsi |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Menyimpan dokumen sebagai teks biasa, PDF, atau Dokumen Microsoft Word. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Menyimpan dokumen sebagai teks biasa, PDF, atau Dokumen Microsoft Word. |
| save(full_file_name, save_format, optimize_pdf) | Menyimpan dokumen sebagai teks biasa, PDF, atau Dokumen Microsoft Word. |
| save(stream, save_format, optimize_pdf) | Menyimpan dokumen sebagai teks biasa, PDF, atau Dokumen Microsoft Word. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Menyimpan dokumen sebagai teks biasa, PDF, atau Dokumen Microsoft Word. |
| get_spell_check_corrected_text(language, dictionary_path) | Mengoreksi teks (mengganti kata yang salah eja). |
| get_spell_check_error_list(language, dictionary_path) | Temukan kata yang salah eja dengan saran ejaan untuk teks masukan tertentu. |
| get_json(is_readable) | Buat string JSON dengan hasil pengenalan. |
| get_xml() | Buat string XML dengan hasil pengenalan. |
| get_keywords() | Dapatkan kata kunci dari paspor (Mode uji. Hanya berfungsi untuk paspor USA dan MADAGASCAR). |

### Lihat Juga

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

