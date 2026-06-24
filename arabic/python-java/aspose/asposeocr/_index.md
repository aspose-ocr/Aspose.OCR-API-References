---
title: "AsposeOcr"
second_title: "Aspose.OCR للـ Python عبر Java مرجع API"
description: 
type: docs
weight: 11
url: /ar/python-java/aspose/asposeocr/
---


الوحدة asposeocr
================
واجهة Python لـ Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
مع التعرف الضوئي على الأحرف (OCR) سهل الاستخدام
محرك لتطبيقاتك Python ومفكراتك.
في أقل من **10** سطرًا من الشيفرة، يمكنك التعرف على
نص بـ **28** لغة تعتمد على اللاتينية، السيريلي،
والخطوط الآسيوية، إرجاع النتائج بأكثر الصيغ شيوعًا
تنسيقات المستندات وتبادل البيانات.
ليس هناك حاجة لتعلم نماذج رياضية معقدة،
بناء خوارزميات التعلم الآلي وتدريب الشبكات
العصبية — API البسيطة والقوية ستقوم بكل شيء نيابةً عنك.

الفئات
-------

`AsposeOcr()`
:
الفئة الرئيسية AsposeOcr للتعرف.
    
هذا المثال يوضح كيفية التعرف على الصورة.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### الطرق الثابتة

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.
@param fullFileName: اسم الملف مع المسار لحفظ نتيجة التعرف بالتنسيق المحدد.
@param saveFormat: تنسيق المستند (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### الطرق

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
يحسب زوايا الانحراف للصور.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة. الحاوية التي تحتوي على المصادر.
@return: قائمة زوايا الانحراف بالدرجات - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
تحقق مما إذا كانت صورتان تحتويان على نفس النص.
@param fullPath1: المسار إلى الصورة الأولى.
@param fullPath2: المسار إلى الصورة الثانية.
@param settings: إعدادات التعرف.
@param ignoreCase: True - يعني بحث غير حساس لحالة الأحرف.
@return: True إذا كانت الصورتان تحتويان على نفس النص (تشابه 90٪).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
يصحح النص (يستبدل الكلمات المكتوبة خطأ).
@param text: النص للتصحيح.
@param language: القاموس لاستخدام SpellCheckLanguage.
@return: النص مع الكلمات المستبدلة.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
يكتشف مناطق النص في الصور.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param areasType: يحدد أي المستطيلات تُرجع - سطر، فقرات أو كلمات.
@param isDetectAreas: تمكين الكشف التلقائي عن مناطق النص.
@return: قائمة RectangleOutput مع مناطق النص المكتشفة أو السطور.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم.
@param fullPath: مسار إلى الصورة.
@param text: مقطع نصي للبحث في الصورة.
@param settings: إعدادات التعرف.
@param ignoreCase: True - يعني بحث غير حساس لحالة الأحرف.
@return: صحيح إذا كانت الصورة تحتوي على مقطع نصي. خطأ - الصورة لا تحتوي على مقطع نصي.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
قارن النصوص على الصورتين وأعد رقمًا يمثل مدى تشابهها (من 0 إلى 1).
@param fullPath1: المسار إلى الصورة الأولى.
@param fullPath2: المسار إلى الصورة الثانية.
@param settings: إعدادات التعرف.
@param ignoreCase: True - يعني بحث غير حساس لحالة الأحرف.
@return: 0 يعني أن النصوص مختلفة تمامًا؛ 1 يعني أن النصوص متطابقة.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على الصورة مع القدرة على تحديد RecognitionSettings.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param settings: كائن RecognitionSettings.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على لوحة السيارة مع القدرة على تحديد CarPlateRecognitionSettings.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param settings: CarPlateRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على النص في صورة ذات جودة جيدة. لا يستخدم تصحيح الانحراف التلقائي للصورة ومناطق النص.
الكشف.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على بطاقة الهوية مع القدرة على تحديد IDCardRecognitionSettings.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param settings: IDCardRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على الفاتورة مع القدرة على تحديد InvoiceRecognitionSettings
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param settings: InvoiceRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على صورة سطر واحد مع القدرة على تحديد RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param settings: كائن RecognitionSettings.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على جواز السفر مع القدرة على تحديد PassportRecognitionSettings.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param settings: PassportRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على الإيصالات مع القدرة على تحديد ReceiptRecognitionSettings.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@param settings: ReceiptRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على النص في صور الشوارع.
استخراج النص من صور الشوارع، صور كاميرات المرور، بطاقات الهوية، رخص القيادة، وغيرها من الصور التي تحتوي على نص متفرق وخلفيات صاخبة/ملونة.
يدعم GIF و PNG و JPEG و WBMP و TIFF و JFIF و TIFF و PDF ومصفوفة ثنائية ومجلد ومصفوفة وأرشيف zip وعنوان URL و base64.
@param input: :py:any:`~aspose.models.OcrInput`. نسخة.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`shutdown(self)`
:
إيقاف تشغيل آلة JVM.

`ImageProcessing()`
:
فئة مساعدة لمكتبة Aspose OCR. تسمح بتهيئة الصور مسبقًا وحفظها.

### الطرق الثابتة

`save(images, folderPath)`
:
استخدم معالجة الصور لتحسين دقة OCR.
إنشاء قائمة من الفلاتر التي سيتم تطبيقها على صورة الإدخال بالترتيب الذي تحدده.
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
أنت لا تحتاج إلى جميعها. اضبط فقط ما تحتاجه.
@param images: كائن OcrInput يحتوي على صور مختلفة OcrInput.
@param folderPath: المسار بدون أسماء الصور لحفظ الصور المعالجة.
@return: كائن OcrInput يحتوي على الصور المعالجة الناتجة OcrInput.


### انظر أيضًا

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)