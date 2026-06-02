---
title: "AsposeOcr"
second_title: "Aspose.OCR untuk Python melalui Java API Reference"
description: 
type: docs
weight: 11
url: /id/python-java/aspose/asposeocr/
---


Modul asposeocr
================
Antarmuka Python untuk Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
sementara pengenalan karakter optik (OCR) yang mudah digunakan
mesin untuk aplikasi Python Anda dan notebook.
Dalam kurang dari **10** baris kode, Anda dapat mengenali
teks dalam **28** bahasa berdasarkan Latin, Cyrillic,
dan skrip Asia, mengembalikan hasil dalam format paling populer
dokumen dan format pertukaran data.
Tidak perlu mempelajari model matematika yang kompleks,
membangun algoritma pembelajaran mesin dan melatih neural
network — API kami yang sederhana dan kuat akan melakukan semuanya untuk Anda.

Kelas
-------

`AsposeOcr()`
:
Kelas utama AsposeOcr untuk pengenalan.
    
Contoh ini menunjukkan cara mengenali gambar.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Metode Statis

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Memungkinkan untuk mendapatkan dokumen multipage dari daftar objek RecognitionResult.
@param fullFileName: Nama file dengan jalur untuk menyimpan hasil pengenalan dalam format yang dipilih.
@param saveFormat: Format dokumen (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Metode

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Menghitung sudut kemiringan gambar.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance. Kontainer dengan sumber.
@return: Daftar sudut kemiringan dalam derajat - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Periksa apakah dua gambar berisi teks yang sama.
@param fullPath1: Path ke gambar pertama.
@param fullPath2: Path ke gambar kedua.
@param settings: Pengaturan pengenalan.
@param ignoreCase: True - berarti pencarian tidak memperhatikan huruf besar/kecil.
@return: True jika gambar memiliki teks yang sama (kemiripan 90%).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Mengoreksi teks (mengganti kata yang salah eja).
@param text: Teks untuk dikoreksi.
@param language: Kamus yang digunakan SpellCheckLanguage.
@return: Teks dengan kata yang diganti.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Mendeteksi area teks pada gambar.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param areasType: Menentukan rectangle mana yang akan dikembalikan - baris, paragraf, atau kata.
@param isDetectAreas: Mengaktifkan deteksi otomatis area teks.
@return: Daftar RectangleOutput dengan area teks atau baris yang terdeteksi.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Periksa apakah gambar mengandung fragmen teks yang diberikan.
@param fullPath: Jalur ke gambar.
@param text: Fragmen teks untuk pencarian pada gambar.
@param settings: Pengaturan pengenalan.
@param ignoreCase: True - berarti pencarian tidak memperhatikan huruf besar/kecil.
@return: True jika gambar berisi fragmen teks. False - gambar tidak berisi fragmen teks.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Bandingkan teks pada dua gambar dan kembalikan angka yang mewakili seberapa mirip mereka (0 hingga 1).
@param fullPath1: Path ke gambar pertama.
@param fullPath2: Path ke gambar kedua.
@param settings: Pengaturan pengenalan.
@param ignoreCase: True - berarti pencarian tidak memperhatikan huruf besar/kecil.
@return: 0 berarti teks benar‑benar berbeda; 1 berarti teks identik.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali gambar dengan kemampuan untuk menentukan RecognitionSettings.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: objek RecognitionSettings.
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali plat mobil dengan kemampuan untuk menentukan CarPlateRecognitionSettings.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: CarPlateRecognitionSettings
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali teks pada gambar berkualitas baik. Tidak menggunakan koreksi kemiringan gambar otomatis dan area teks
deteksi.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali kartu ID dengan kemampuan untuk menentukan IDCardRecognitionSettings.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: IDCardRecognitionSettings
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali faktur dengan kemampuan untuk menentukan InvoiceRecognitionSettings
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: InvoiceRecognitionSettings
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali gambar baris tunggal dengan kemampuan untuk menentukan RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: objek RecognitionSettings.
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali paspor dengan kemampuan untuk menentukan PassportRecognitionSettings.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: PassportRecognitionSettings
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali struk dengan kemampuan untuk menentukan ReceiptRecognitionSettings.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@param settings: ReceiptRecognitionSettings
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Mengenali teks pada foto jalan.
Ekstrak teks dari foto jalan, gambar kamera lalu lintas, kartu identitas, surat izin mengemudi, dan gambar lainnya dengan teks yang jarang serta latar belakang yang berisik/berwarna.
Mendukung GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array biner, folder, array, arsip zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instance.
@return: daftar RecognitionResult dengan hasil pengenalan gambar.

`shutdown(self)`
:
Matikan mesin JVM.

`ImageProcessing()`
:
Kelas pembantu untuk pustaka Aspose OCR. Memungkinkan untuk melakukan pra‑pemrosesan dan menyimpan gambar.

### Metode Statis

`save(images, folderPath)`
:
Gunakan pemrosesan gambar untuk meningkatkan akurasi OCR.
Buat daftar filter yang akan diterapkan pada gambar input dalam urutan yang Anda tentukan.
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
Anda tidak memerlukan semuanya. Atur hanya apa yang Anda butuhkan.
@param images: objek OcrInput yang berisi berbagai gambar OcrInput.
@param folderPath: Jalur tanpa nama gambar untuk menyimpan gambar yang diproses.
@return: objek OcrInput yang berisi hasil gambar yang diproses OcrInput.


### Lihat Juga

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)