---
title: "OcrInput"
second_title: "Referensi API Aspose.OCR untuk Python via .NET"
description: 
type: docs
weight: 240
url: /id/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Kontainer untuk mengumpulkan semua gambar / dokumen untuk pra‑pemrosesan / pengenalan.

Tipe OcrInput menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| OcrInput(type, filters) | Menginisialisasi instance baru dari kelas OcrInput |
| OcrInput(type) | Menginisialisasi instance baru dari kelas OcrInput |
## Indexer
| Nama | Deskripsi |
| :- | :- |
| [index] | Mengembalikan informasi tentang gambar yang diproses / dikenali. |
## Methods
| Nama | Deskripsi |
| :- | :- |
| add(full_path) | Tambahkan jalur atau URI yang berisi gambar untuk pengenalan / pemrosesan.<br/>            Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor. |
| add(stream) | Tambahkan aliran memori yang berisi gambar untuk pengenalan / pemrosesan.<br/>            Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor. |
| add(full_path, start_page, pages_count) | Tambahkan gambar atau dokumen berhalaman banyak untuk pengenalan / pemrosesan.<br/>            Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor. |
| add(stream, start_page, pages_count) | Tambahkan aliran memori yang berisi gambar berhalaman banyak untuk pengenalan / pemrosesan.<br/>            Tipe gambar harus sesuai dengan tipe yang ditentukan dalam konstruktor. |
| add(arr, width, height, pixel_format) | Tambahkan gambar yang telah didekode ke daftar untuk pengenalan / pemrosesan.<br/>            Jenis gambar harus sesuai dengan jenis yang ditentukan dalam konstruktor (SingleImage). |
| replace_filters(filters) | Hapus filter lama dan atur yang baru. |
| clear_filters() | Hapus semua filter. |
| add_base64(base64) | Tambahkan string base64 yang berisi gambar untuk pengenalan / pemrosesan.<br/>            Jenis gambar harus sesuai dengan jenis yang ditentukan dalam konstruktor. |
| clear() | Hapus semua filter. |
| count() | Jumlah item untuk pemrosesan / pengenalan. |
| get_input_type() | Jenis gambar yang diizinkan untuk pengenalan. |

### Lihat Juga

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

