---
title: "AsposeOcr"
second_title: "Aspose.OCR 用于 Python via .NET API 参考"
description: 
type: docs
weight: 10
url: /zh/python-net/aspose.ocr/asposeocr/
---

## AsposeOcr class

Aspose OCR 库的主要 API

AsposeOcr 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| AsposeOcr() | 初始化 [AsposeOcr](/ocr/python-net/aspose.ocr/asposeocr/) 类的新实例。<br/>            空构造函数。 |
## 属性
| 名称 | 描述 |
| :- | :- |
| set_debug_mode |  |
| set_debug_mode_save_directory |  |
## 方法
| 名称 | 描述 |
| :- | :- |
| recognize(images) | 识别图像/文档中的文本。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、目录、数组、归档。 |
| recognize(images, preset) |  |
| recognize(images, settings) | 识别图像/文档中的文本。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、目录、数组、归档。 |
| recognize_receipt(images) | 识别收据上的文本。 |
| recognize_receipt(images, settings) | 识别收据上的文本。 |
| recognize_invoice(images) | 识别发票上的文本。 |
| recognize_invoice(images, settings) | 识别发票上的文本。 |
| recognize_id_card(images) | 识别身份证上的文本。 |
| recognize_id_card(images, settings) | 识别身份证上的文本。 |
| recognize_car_plate(images) | 识别车牌上的文本。 |
| recognize_car_plate(images, settings) | 识别车牌上的文本。 |
| recognize_passport(images) | 识别护照上的文本。 |
| recognize_passport(images, settings) | 识别护照上的文本。 |
| recognize_lines(images) | 识别包含单行文本的图像。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、文件夹、数组、归档。 |
| recognize_lines(images, settings) | 识别包含单行文本的图像。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、文件夹、数组、归档。 |
| detect_rectangles(images) | 检测图像中的文本区域。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、文件夹、数组、归档。 |
| detect_rectangles(images, areas_type, detect_areas) | 检测图像中的文本区域。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、文件夹、数组、归档。 |
| recognize_characters(images) | 检测图像中的符号。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、文件夹、数组、归档。 |
| recognize_characters(images, detect_areas_mode, language) | 检测图像中的符号。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、文件夹、数组、归档。 |
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
| recognize_fast(images) | 识别图像/文档中的文本。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、目录、数组、归档。 |
| recognize_handwritten_text(images) | 识别图像上的手写文本。 |
| detect_document_layout(images) |  |
| recognize_formula(images, detect_areas) |  |
| recognize_formula_ai(images) |  |
| recognize_tables(images, language) |  |
| detect_tables(images) |  |
| calculate_skew(images) | 计算图像的倾斜角度。<br/>            支持 GIF、PNG、JPEG、BMP、TIFF、JFIF、流、文件夹、数组、归档。 |
| detect_defects(images, defect_type) | 自动查找图像中可能显著影响 OCR 准确性的有问题区域。<br/>            支持以文件、流或像素数组形式提供的 PNG、JPEG、BMP、TIFF、JFIF 和 GIF 图像。支持批量识别。 |
| detect_languages(images) |  |
| image_has_text(full_path, text, settings, ignore_case, auto_skew) | 检查图像是否包含提供的文本片段。 |
| compare_image_texts(full_path1, full_path2, settings, ignore_case) | 检查两幅图像是否包含相同的文本。 |
| image_text_diff(full_path1, full_path2, settings, ignore_case, auto_skew) | 比较两幅图像上的文本，并返回一个表示相似度的数值（0 到 1）。 |
| correct_spelling(text, language, dictionary_path) | 纠正文本（替换拼写错误的单词）。 |

### 另请参见

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

