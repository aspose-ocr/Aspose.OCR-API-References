---
title: "AsposeOcr"
second_title: "Referensi API Aspose.OCR untuk Python via .NET"
description: 
type: docs
weight: 10
url: /id/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

API utama untuk pustaka Aspose OCR

Tipe AsposeOcr menampilkan anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| AsposeOcr() | Menginisialisasi instance baru dari kelas [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/).<br/>            Konstruktor kosong. |
## Properti
| Nama | Deskripsi |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## Methods
| Nama | Deskripsi |
| :- | :- |
| recognize(images) | Mengenali teks pada gambar / dokumen.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, aliran, direktori, array, arsip. |
| recognize(images, preset) |  |
| recognize(images, settings) | Mengenali teks pada gambar / dokumen.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, aliran, direktori, array, arsip. |
| recognize_receipt(images) | Mengenali teks pada struk. |
| recognize_receipt(images, settings) | Mengenali teks pada struk. |
| recognize_invoice(images) | Mengenali teks pada faktur. |
| recognize_invoice(images, settings) | Mengenali teks pada faktur. |
| recognize_id_card(images) | Mengenali teks pada kartu identitas. |
| recognize_id_card(images, settings) | Mengenali teks pada kartu identitas. |
| recognize_car_plate(images) | Mengenali teks pada plat mobil. |
| recognize_car_plate(images, settings) | Mengenali teks pada plat mobil. |
| recognize_passport(images) | Mengenali teks pada paspor. |
| recognize_passport(images, settings) | Mengenali teks pada paspor. |
| recognize_lines(images) | Mengenali gambar yang berisi satu baris teks.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, array, arsip. |
| recognize_lines(images, settings) | Mengenali gambar yang berisi satu baris teks.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, array, arsip. |
| detect_rectangles(images) | Mendeteksi area teks pada gambar.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, array, arsip. |
| detect_rectangles(images, areas_type, detect_areas) | Mendeteksi area teks pada gambar.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, array, arsip. |
| recognize_characters(images) | Mendeteksi simbol pada gambar.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, array, arsip. |
| recognize_characters(images, detect_areas_mode, language) | Mendeteksi simbol pada gambar.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, array, arsip. |
| save_multipage_document(full_file_name, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results, optimize_pdf) |  |
| save_multipage_document(full_file_name, save_format, results) |  |
| save_multipage_document(stream, save_format, results) |  |
| save_multipage_document(stream, save_format, results, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, embedded_font_path, optimize_pdf) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path) |  |
| save_multipage_document(stream, save_format, results, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) |  |
| recognize_fast(images) | Mengenali teks pada gambar / dokumen.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, aliran, direktori, array, arsip. |
| recognize_handwritten_text(images) | Mengenali teks tulisan tangan pada gambar. |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | Menghitung sudut kemiringan gambar.<br/>            Mendukung GIF, PNG, JPEG, BMP, TIFF, JFIF, stream, folder, array, arsip. |
| detect_defects(images, defect_type) | Secara otomatis menemukan area bermasalah pada gambar yang dapat secara signifikan memengaruhi akurasi OCR.<br/>            Mendukung gambar PNG, JPEG, BMP, TIFF, JFIF, dan GIF yang disediakan sebagai file, stream, atau array piksel. Mendukung pengenalan massal. |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | Periksa apakah gambar mengandung fragmen teks yang diberikan. |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | Periksa apakah dua gambar mengandung teks yang sama. |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip mereka (0 hingga 1). |
| correct_spelling(text, language, dictionary_path) | Mengoreksi teks (mengganti kata yang salah eja). |

### Lihat Juga

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

