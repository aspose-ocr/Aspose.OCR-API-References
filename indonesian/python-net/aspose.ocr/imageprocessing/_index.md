---
title: "ImageProcessing"
second_title: "Referensi API Aspose.OCR untuk Python via .NET"
description: 
type: docs
weight: 120
url: /id/python-net/aspose.ocr/imageprocessing/
---

## ImageProcessing class

Kelas pembantu untuk pustaka Aspose OCR. Memungkinkan pra‑pemrosesan dan penyimpanan gambar.

Tipe ImageProcessing menyediakan anggota-anggota berikut:
## Methods
| Nama | Deskripsi |
| :- | :- |
| save(images, folder_path) | Gunakan pemrosesan gambar untuk meningkatkan akurasi OCR.<br/>            Buat daftar filter yang akan diterapkan pada gambar input dalam urutan yang Anda tentukan.<br/>            Contoh untuk membuat filter:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Anda tidak memerlukan semua filter tersebut. Setel hanya yang Anda butuhkan. |
| render(images) | Gunakan pemrosesan gambar untuk meningkatkan akurasi OCR.<br/>            Buat daftar filter yang akan diterapkan pada gambar input dalam urutan yang Anda tentukan.<br/>            contoh untuk membuat filter:<br/>            PreprocessingFilter filters = new PreprocessingFilter<br/>               {<br/>                   PreprocessingFilter.Invert(),<br/>                   PreprocessingFilter.Threshold(150),<br/>                   PreprocessingFilter.Binarize(),<br/>                   PreprocessingFilter.Rotate(180),<br/>                   PreprocessingFilter.Resize(3000,3000, Aspose.OCR.Filters.InterpolationFilterType.Box),<br/>                   PreprocessingFilter.Scale(6f),<br/>                   PreprocessingFilter.Dilate()<br/>            };<br/>            Anda tidak memerlukan semua filter tersebut. Setel hanya yang Anda butuhkan. |

### Lihat Juga

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

