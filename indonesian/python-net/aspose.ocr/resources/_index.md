---
title: "Resources"
second_title: "Referensi API Aspose.OCR untuk Python via .NET"
description: 
type: docs
weight: 360
url: /id/python-net/aspose.ocr/resources/
---

## Resources class

Kelola sumber daya yang dapat diunduh yang meningkatkan kemampuan pengenalan Aspose.OCR.

Tipe Resources menyediakan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Resources() | Menginisialisasi instance baru dari kelas Resources |
## Methods
| Nama | Deskripsi |
| :- | :- |
| set_local_path(path) | Tentukan jalur absolut atau relatif ke direktori tempat sumber daya akan diunduh.<br/>            Jika direktori tidak ada, akan dibuat secara otomatis.<br/>            Secara default, sumber daya diunduh ke direktori aspose_data di direktori kerja aplikasi. |
| set_local_path(path, create) | Tentukan jalur absolut atau relatif ke direktori tempat sumber daya akan diunduh.<br/>            Berikan `false` pada parameter `create` untuk mencegah direktori dibuat secara otomatis.<br/>            Jika direktori yang diberikan tidak ada dan pembuatan tidak diizinkan, sumber daya akan dimuat ke dalam direktori aspose_data di direktori kerja aplikasi. |
| set_repository(url) | Tentukan URL repositori daring dari mana sumber daya Aspose.OCR akan diunduh.<br/>            Secara default, sumber daya diunduh dari https://github.com/aspose-ocr/resources/. |
| get_repository() | Kembalikan URL repositori daring dari mana sumber daya Aspose.OCR diunduh. |
| list_remote() | Daftar semua sumber daya yang kompatibel dari repositori daring. |
| get_local_path() | Kembalikan jalur lengkap ke direktori tempat sumber daya akan diunduh. |
| list_local() | Daftar semua sumber daya Aspose.OCR yang disimpan di direktori lokal. |
| allow_automatic_downloads(allow) | Izinkan (true) atau blokir (false) pengunduhan otomatis sumber daya yang diperlukan dari repositori daring.<br/>             Secara default, sebuah sumber daya diunduh secara otomatis ketika metode yang bergantung padanya dipanggil. |
| fetch_resources(names) | Unduh sumber daya yang ditentukan dalam parameter `names` dari repositori daring. Jika satu atau lebih sumber daya sudah diunduh, mereka akan ditimpa.<br/>            Anda dapat menghilangkan ekstensi .OCR dan hanya menggunakan nama file. |
| fetch_resource(name) | Unduh sumber daya yang ditentukan dalam parameter `names` dari repositori daring. Jika satu atau lebih sumber daya sudah diunduh, mereka akan ditimpa.<br/>            Anda dapat menghilangkan ekstensi .OCR dan hanya menggunakan nama file. |
| fetch_all() | Unduh semua sumber daya yang kompatibel dari repositori daring. File sumber daya yang ada akan ditimpa. |
| remove_local(name) | Menghapus sumber daya Aspose.OCR yang disimpan secara lokal. |
| release_memory() |  |

### Lihat Juga

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

