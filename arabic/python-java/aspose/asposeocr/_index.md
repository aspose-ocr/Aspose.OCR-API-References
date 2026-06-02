---
title: "AsposeOcr"
second_title: "مرجع API لـ Aspose.OCR للبايثون عبر جافا"
description: 
type: docs
weight: 11
url: /ar/python-java/aspose/asposeocr/
---


الوحدة asposeocr
================
واجهة بايثون لـ Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
بينما تقنية التعرف الضوئي على الأحرف (OCR) سهلة الاستخدام
محرك لتطبيقاتك بايثون والمفكرات.
في أقل من **10** سطرًا من الشيفرة، يمكنك التعرف على
نص بـ **28** لغة تعتمد على اللاتينية، السيريلي،
والخطوط الآسيوية، مع إرجاع النتائج بأكثر الصيغ شيوعًا
صيغ المستندات وتبادل البيانات.
ليس هناك حاجة لتعلم نماذج رياضية معقدة،
بناء خوارزميات التعلم الآلي وتدريب الشبكات
العصبية — API البسيط والقوي لدينا سيفعل كل شيء نيابةً عنك.

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

### طرق ثابتة

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
يسمح بالحصول على مستند متعدد الصفحات من قائمة كائنات RecognitionResult.
@param fullFileName: اسم الملف مع المسار لحفظ نتيجة التعرف بالتنسيق المحدد.
@param saveFormat: تنسيق المستند (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### طرق

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
يحسب زوايا الانحراف للصور.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال. الحاوية التي تحتوي على المصادر.
@return: قائمة زوايا الانحراف بالدرجات - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
تحقق مما إذا كانت الصورتان تحتويان على نفس النص.
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
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param areasType: يحدد أي المستطيلات تُرجع - سطر، فقرات أو كلمات.
@param isDetectAreas: تمكين الكشف التلقائي عن مناطق النص.
@return: قائمة RectangleOutput مع مناطق النص المكتشفة أو الأسطر.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
تحقق مما إذا كانت الصورة تحتوي على الجزء النصي المقدم.
@param fullPath: مسار الصورة.
@param text: جزء نصي للبحث في الصورة.
@param settings: إعدادات التعرف.
@param ignoreCase: True - يعني بحث غير حساس لحالة الأحرف.
@return: True إذا كانت الصورة تحتوي على جزء نصي. False - الصورة لا تحتوي على جزء نصي.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
قارن النصوص على الصورتين وأعد رقمًا يمثل مدى تشابههما (من 0 إلى 1).
@param fullPath1: المسار إلى الصورة الأولى.
@param fullPath2: المسار إلى الصورة الثانية.
@param settings: إعدادات التعرف.
@param ignoreCase: True - يعني بحث غير حساس لحالة الأحرف.
@return: 0 يعني أن النصوص مختلفة تمامًا؛ 1 يعني أن النصوص متطابقة.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على الصورة مع القدرة على تحديد RecognitionSettings.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param settings: كائن RecognitionSettings.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على لوحة السيارة مع القدرة على تحديد CarPlateRecognitionSettings.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param settings: CarPlateRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على النص في صورة ذات جودة جيدة. لا يستخدم تصحيح الانحراف التلقائي للصورة ومناطق النص
الكشف.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على بطاقة الهوية مع القدرة على تحديد IDCardRecognitionSettings.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param settings: IDCardRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على الفاتورة مع القدرة على تحديد InvoiceRecognitionSettings
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param settings: InvoiceRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على صورة سطر واحد مع القدرة على تحديد RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param settings: كائن RecognitionSettings.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على جواز السفر مع إمكانية تحديد إعدادات PassportRecognitionSettings.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param settings: PassportRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على الإيصالات مع إمكانية تحديد إعدادات ReceiptRecognitionSettings.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@param settings: ReceiptRecognitionSettings
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
يتعرف على النص في صور الشوارع.
استخراج النص من صور الشوارع، صور كاميرات المرور، بطاقات الهوية، رخص القيادة، وغيرها من الصور التي تحتوي على نص متفرق وخلفيات صاخبة/ملونة.
يدعم صيغ GIF، PNG، JPEG، WBMP، TIFF، JFIF، TIFF، PDF، مصفوفة ثنائية، مجلد، مصفوفة، أرشيف zip، URL، base64.
@param input: :py:any:`~aspose.models.OcrInput`. مثال.
@return: قائمة RecognitionResult مع نتائج التعرف على الصور.

`shutdown(self)`
:
إيقاف تشغيل آلة JVM.

`ImageProcessing()`
:
فئة مساعدة لمكتبة Aspose OCR. تسمح بمعالجة الصور مسبقًا وحفظها.

### طرق ثابتة

`save(images, folderPath)`
:
استخدم معالجة الصور لتحسين دقة OCR.
أنشئ قائمة بالمرشحات التي سيتم تطبيقها على صورة الإدخال بالترتيب الذي تحدده.
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
ليس عليك استخدام جميعها. اضبط فقط ما تحتاجه.
@param images: كائن OcrInput يحتوي على صور مختلفة OcrInput.
@param folderPath: المسار بدون أسماء الصور لحفظ الصور المعالجة.
@return: كائن OcrInput يحتوي على صور النتائج المعالجة OcrInput.


### انظر أيضًا

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)