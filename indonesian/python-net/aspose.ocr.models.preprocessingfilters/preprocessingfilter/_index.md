---
title: "PreprocessingFilter"
second_title: "Referensi API Aspose.OCR untuk Python via .NET"
description: 
type: docs
weight: 10
url: /id/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Kelas dasar untuk perintah pemrosesan gambar.

Tipe PreprocessingFilter menampilkan anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PreprocessingFilter() | Menginisialisasi instance baru dari kelas PreprocessingFilter |
## Properti
| Nama | Deskripsi |
| :- | :- |
| default | Koleksi filter default berisi filter AutoSkew |
| kosong | Koleksi filter kosong |
## Methods
| Nama | Deskripsi |
| :- | :- |
| binarize() | Mengonversi gambar menjadi gambar hitam-putih.<br/>            Gambar biner adalah gambar yang pikselnya hanya memiliki dua nilai intensitas yang mungkin. <br/>            Gambar ini biasanya ditampilkan sebagai hitam dan putih. Secara numerik, dua nilai tersebut biasanya 0 untuk hitam, dan 255 untuk putih.<br/>            Gambar biner dihasilkan dengan melakukan threshold otomatis pada gambar. |
| binarize(area) | Mengonversi sebagian gambar menjadi gambar hitam-putih.<br/>            Gambar biner adalah gambar yang pikselnya hanya memiliki dua nilai intensitas yang mungkin. <br/>            Gambar ini biasanya ditampilkan sebagai hitam dan putih. Secara numerik, dua nilai tersebut biasanya 0 untuk hitam, dan 255 untuk putih.<br/>            Gambar biner dihasilkan dengan melakukan threshold otomatis pada gambar. |
| resize(width, height, type) | Ubah skala gambar - Memperbesar atau memperkecil resolusi gambar. |
| resize(width, height) | Ubah skala gambar - Memperbesar atau memperkecil resolusi gambar. |
| dilate() | Dilasi menambahkan piksel ke batas objek dalam gambar. |
| dilate(area) | Dilasi menambahkan piksel ke batas objek dalam sebagian gambar. |
| invert() | Secara otomatis membalikkan warna pada gambar dokumen. |
| invert(area) | Secara otomatis membalikkan warna pada sebagian gambar. |
| rotate(angle) | Putar gambar asli. |
| rotate(angle, area) | Putar sebagian gambar. |
| scale(ratio) | Ubah skala gambar - Memperbesar atau memperkecil resolusi gambar.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Ubah skala gambar - Memperbesar atau memperkecil resolusi gambar. |
| threshold(value) | Buat gambar biner berdasarkan penetapan nilai ambang pada intensitas piksel gambar asli. |
| threshold(value, area) | Buat bagian biner dari gambar berdasarkan penetapan nilai ambang pada intensitas piksel bagian gambar asli. |
| median() | Filter median berjalan melalui setiap elemen gambar dan mengganti setiap piksel dengan nilai median dari piksel tetangganya. |
| median(area) | Filter median berjalan melalui setiap elemen bagian gambar dan mengganti setiap piksel dengan nilai median dari piksel tetangganya. |
| auto_denoising() | Mengaktifkan penggunaan jaringan saraf tambahan untuk meningkatkan gambar - mengurangi noise.<br/>            Berguna untuk gambar dengan artefak pemindaian, distorsi, noda, flare, gradien, elemen asing. |
| auto_denoising(area) | Mengaktifkan penggunaan jaringan saraf tambahan untuk meningkatkan bagian gambar - mengurangi noise.<br/>            Berguna untuk gambar dengan artefak pemindaian, distorsi, noda, flare, gradien, elemen asing. |
| auto_skew() | Mengaktifkan koreksi kemiringan gambar secara otomatis. |
| auto_skew(area) | Mengaktifkan koreksi kemiringan bagian gambar secara otomatis. |
| contrast_correction_filter() | Filter koreksi kontras. |
| contrast_correction_filter(area) | Filter koreksi kontras untuk bagian gambar. |
| to_grayscale() | Mengonversi gambar menjadi gambar skala abu-abu.<br/>            Gambar skala abu-abu memiliki 256 tingkat cahaya dalam gambar (0 hingga 255). |
| auto_dewarping() | Secara otomatis memperbaiki distorsi geometris pada gambar.<br/>            Sangat memakan banyak sumber daya! |
| add(filter) | Tambahkan filter baru ke koleksi untuk menjalankan semua operasi lebih lanjut.<br/>            Konsistensi dalam koleksi penting. |

### Lihat Juga

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

