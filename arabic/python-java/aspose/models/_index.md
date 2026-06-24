---
title: "النماذج"
second_title: "Aspose.OCR للـ Python عبر Java مرجع API"
description: 
type: docs
weight: 271
url: /ar/python-java/aspose/models/
---

وحدة النماذج
=============

الفئات
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   يحدد نوع المناطق التي يكتشفها النموذج.
يُستخدم في get_text_areas لتحديد النتيجة التي سيتم الحصول عليها - إحداثيات الفقرة أو إحداثيات السطر.

### الأسلاف (في MRO)

    * enum.Enum

### متغيرات الفئة

`LINES`
:   يحدد المناطق كخطوط

`PARAGRAPHS`
:   يحدد المناطق كفقرات

`WORDS`
:   يحدد المناطق ككلمات

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   يحدد نوع الشبكة العصبية المستخدمة لاكتشاف المناطق.
يُستخدم في RecognitionSettings لتحديد نوع الصورة التي تريد التعرف عليها.

### الأسلاف (في MRO)

    * enum.Enum

### متغيرات الفئة

`COMBINE`
:   يكتشف الفقرات التي تحتوي على نص ثم يستخدم نموذج NN آخر لاكتشاف المناطق داخل الفقرات.
أفضل للصور ذات البنية المعقدة.

`CURVED_TEXT`
:   يكتشف الخطوط ويتعرف على النص في الصور المنحنية.
الوضع المفضل للصور لصفحات الكتب والمجلات.

`DOCUMENT`
:   يكتشف الفقرات باستخدام نموذج NN للمستندات.
أفضل للمستند متعدد الأعمدة، أو المستند الذي يحتوي على صور أو كائنات غير نصية أخرى.

`NONE`
:   لا يكتشف الفقرات.
أفضل لمستند بسيط بعمود واحد بدون صور.

`PHOTO`
:   يكتشف الفقرات باستخدام نموذج NN للصور.
أفضل للصور التي تحتوي على الكثير من الصور وكائنات غير نصية أخرى.

`TABLE`
:   يكتشف الخلايا التي تحتوي على نص.
الوضع المفضل للصور ذات بنية جدولية.

`TEXT_IN_WILD`
:   شبكة عصبية فائقة القوة متخصصة في استخراج الكلمات من الصور منخفضة الجودة مثل صور الشوارع، لوحات الترخيص، صور جواز السفر، صور العدادات، والصور ذات الخلفيات المزعجة.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   تنسيق لحفظ نتيجة التعرف كمستند.

### الأسلاف (في MRO)

    * enum.Enum

### متغيرات الفئة

`DOCX`
:   يحفظ النتيجة كوثيقة Office Open XML لمعالجة النصوص (بدون ماكرو).

`EPUB`
:   يحفظ المستند كملف EPUB.

`HTML`
:   يحفظ المستند كملف HTML.

`JSON`
:   يحفظ النتيجة كنص عادي مكتوب بصيغة كائنات جافاسكريبت.

`PDF`
:   يحفظ النتيجة كملف PDF (Adobe Portable Document)

`PDF_NO_IMG`
:   يحفظ المستند كملف PDF قابل للبحث (Adobe Portable Document) بدون صورة.

`RTF`
:   يحفظ المستند كملف rtf.

`TEXT`
:   يحفظ النتيجة بصيغة النص العادي.

`XLSX`
:   يحفظ النتيجة كملف Excel (2007 وما بعده) دفتر عمل.

`XML`
:   يحفظ النتيجة كملف XML.

`ImageData(javaClass)`
:

### الأسلاف (في MRO)

    * aspose.helper.BaseJavaClass

### الطرق

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   أنواع الصور/ المستندات للمعالجة / التعرف.

### الأسلاف (في MRO)

    * enum.Enum

### متغيرات الفئة

`BASE64`
:   سلسلة base64 مع الصورة أو مسار ملف .txt الذي يحتوي على محتوى base64. يدعم GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   مسار إلى الدليل. الأرشيفات والمجلدات المتداخلة غير مدعومة.
يدعم GIF, PNG, JPEG, BMP, TIFF.
العدد الافتراضي للصور المعالجة هو جميعها.

`PDF`
:   مستند PDF ممسوح ضوئياً من ملف أو من مصفوفة ثنائية.

`SINGLE_IMAGE`
:   يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF، مصفوفة ثنائية.

`TIFF`
:   مستند TIFF متعدد الصفحات، TIF من ملف أو من InputStream.

`URL`
:   رابط على الصورة. يدعم GIF، PNG، JPEG، BMP، TIFF.

`ZIP`
:   الاسم الكامل لأرشيف ZIP. الأرشيفات المتداخلة والمجلدات غير مدعومة.
يدعم GIF، PNG، JPEG، BMP، TIFF، JFIF.
العدد الافتراضي للصور المعالجة هو جميعها.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   نموذج اللغة للتعرف.

### الأسلاف (في MRO)

    * enum.Enum

### متغيرات الفئة

`BEL`
:   الأبجدية البيلاروسية

`BUL`
:   الأبجدية البلغارية

`CHI`
:   الأبجدية الصينية

`CYRILLIC`
:   دعم متعدد اللغات (الأبجدية السيريلية)

`CZE`
:   الأبجدية التشيكية

`DAN`
:   الأبجدية الدنماركية

`DEU`
:   الأبجدية الألمانية

`DUM`
:   الأبجدية الهولندية

`ENG`
:   الأبجدية الإنجليزية

`EST`
:   الأبجدية الإستونية

`FIN`
:   الأبجدية الفنلندية

`FRA`
:   الأبجدية الفرنسية

`HIN`
:   الأبجدية الهندية

`ITA`
:   الأبجدية الإيطالية

`KAZ`
:   الأبجدية الكازاخستانية

`LATIN`
:   دعم متعدد اللغات (الأبجدية اللاتينية)

`LAV`
:   الأبجدية اللاتفية

`LIT`
:   الأبجدية الليتوانية

`NONE`
`:   دعم متعدد اللغات`

`NOR`
:   الأبجدية النرويجية

`POL`
:   الأبجدية البولندية

`POR`
:   الأبجدية البرتغالية

`RUM`
:   الأبجدية الرومانية

`RUS`
:   الأبجدية الروسية

`SLK`
:   الأبجدية السلوفاكية

`SLV`
:   الأبجدية السلوفينية

`SPA`
:   الأبجدية الإسبانية

`SRP`
:   الأبجدية الصربية

`SRP_HRV`
:   الأبجدية الصربية-الكرواتية

`SWE`
:   الأبجدية السويدية

`UKR`
:   الأبجدية الأوكرانية

`ModelsConverter()`
:

### الطرق

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   الفئة الرئيسية لجمع الصور.
    
منشئ لإنشاء الحاوية وتعيين نوع الصور / المستندات والفلاتر للمعالجة / التعرف اللاحقة.
@param type: تعيين نوع الصور/المستندات التي ستُضاف إلى الحاوية.
@param filters: تعيين فلاتر المعالجة التي ستُطبق للمعالجة أو التعرف اللاحق.

### الطرق

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   إضافة المسار أو URI الذي يحتوي على الصورة للتعرف / المعالجة.
يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ.
@param fullPath: المسار إلى الصورة/المستند/المجلد/الأرشيف.
@param startPage: الصفحة/الصورة الأولى للمعالجة / التعرف. يُستخدم للمستندات، والملفات المضغوطة، والمجلدات.
@param pagesNumber: العدد الإجمالي للصفحات/الصور للمعالجة / التعرف. يُستخدم للمستندات، والملفات المضغوطة، والمجلدات. الافتراضي = الكل.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   إضافة InputStream الذي يحتوي على الصورة للتعرف / المعالجة.
يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: يحتوي على الصورة أو المستند.
@param startPage: الصفحة/الصورة الأولى للمعالجة / التعرف. يُستخدم للمستندات، والملفات المضغوطة، والمجلدات.
@param pagesNumber: العدد الإجمالي للصفحات/الصور للمعالجة / التعرف. يُستخدم للمستندات، والملفات المضغوطة، والمجلدات. الافتراضي = الكل.

`add_base64(self, base64: str)`
:   أضف سلسلة base64 التي تحتوي على الصورة للتعرف / المعالجة.
يجب أن يتطابق نوع الصورة مع النوع المحدد في المنشئ.
@param base64: سلسلة Base64 مع صورة واحدة.

`clear(self)`
:   اضبط عدد العناصر للمعالجة / التعرف إلى 0.
امسح المجموعة.

`clear_filters(self)`
:   إزالة جميع الفلاتر.

`get(self, index: int) ‑> models.ImageData`
:   يُعيد معلومات عن الصورة المعالجة / المُعترف بها.
@param index: موضع الصورة في القائمة.
@return: كائن ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   عدد العناصر للمعالجة / التعرف.
@return: عدد العناصر.

`PreprocessingFilter()`
:   الفئة الأساسية لأوامر معالجة الصور.

### الأسلاف (في MRO)

    * aspose.helper.BaseJavaClass

### متغيرات الفئة

`JAVA_CLASS_NAME`
:

### الطرق الثابتة

`auto_denoising()`
:   يتيح استخدام شبكة عصبية إضافية لتحسين الصورة - تقليل الضوضاء.
مفيد للصور التي تحتوي على عيوب مسح، تشوه، بقع، توهجات، تدرجات، عناصر غريبة.
@return: كائن AutoDenoisingFilter.

`auto_dewarping()`
:   يصحح تلقائيًا التشوهات الهندسية في الصورة.
مستهلك للموارد بشكل كبير!
@return: كائن AutoDewarpingFilter.

`auto_skew()`
:   يتيح تصحيح الانحراف التلقائي للصورة.
@return: كائن AutoSkewFilter.

`binarize()`
:   يحول الصورة إلى صورة بالأبيض والأسود.
الصور الثنائية هي صور تكون بكسلاتها ذات قيمتين محتملتين للسطوع فقط.
عادةً ما تُعرض باللونين الأسود والأبيض. عدديًا، القيمتان غالبًا ما تكونان 0 للون الأسود و255 للون الأبيض.
يتم إنتاج الصور الثنائية عن طريق تطبيق عتبة تلقائية على الصورة.
@return: كائن BinarizeFilter.

`binarize_and_dilate()`
:   تضيف عملية التوسيع بكسلات إلى حدود الكائنات في الصورة.
@return: كائن DilateFilter.

`contrast_correction()`
:   مرشح تصحيح التباين.
@return: كائن ContrastCorrectionFilter.

`invert()`
:   يعكس الألوان تلقائيًا في صورة المستند.
@return: كائن InvertFilter.

`median()`
:   يمر مرشح الوسيط عبر كل عنصر في الصورة ويستبدل كل بكسل بوسيط بكسلاته المجاورة.
@return: كائن MedianFilter.

`resize(width: int, height: int)`
:   إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة.
@param width: العرض الجديد للصورة.
@param height: الارتفاع الجديد للصورة.
@return: كائن ResizeFilter.

`rotate(angle: float)`
:   تدوير الصورة الأصلية.
@param angle: زاوية الدوران. القيمة من -360 إلى 360.
@return: كائن RotateFilter.

`scale(ratio: float)`
:   إعادة تحجيم الصورة - تكبير أو تصغير دقة الصورة.
InterpolationFilterType ثنائي الخطية أو أقرب جار.
@param ratio: عامل التحجيم. القيمة الموصى بها من 0.1 إلى 1 للتقليل. من 1 إلى 10 للتكبير.
@return: كائن ScaleFilter.

`threshold(value: int)`
:   إنشاء صورة ثنائية بناءً على تعيين قيمة عتبة لشدة بكسل الصورة الأصلية.
@param value: القيمة القصوى.
@return: كائن BinarizeFilter.

`to_grayscale()`
:   تحويل صورة إلى صورة تدرج رمادي.
صورة التدرج الرمادي تحتوي على 256 مستوى إضاءة في الصورة (0 إلى 255).
@return: كائن GrayscaleFilter.

### الطرق

`add(self, filter)`
:   إضافة مرشح إلى المجموعة للمعالجة المسبقة الإضافية.
@param filter: كائن PreprocessingFilter.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   تمثيل كلمة مكتوبة خطأً مع بيانات إضافية.

### الأسلاف (في MRO)

    * aspose.helper.BaseJavaClass

### الطرق

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   لغة القاموس لتصحيح التدقيق الإملائي.

### الأسلاف (في MRO)

    * enum.Enum

### متغيرات الفئة

`CZE`
:   القاموس التشيكي

`DAN`
:   قاموس الدنماركية

`DEU`
:   قاموس الألمانية

`DUM`
:   قاموس الهولندية

`ENG`
:   قاموس الإنجليزية

`EST`
:   قاموس الإستونية

`FIN`
:   قاموس الفنلندية

`FRA`
:   قاموس الفرنسية

`ITA`
:   قاموس الإيطالية

`LAV`
:   قاموس اللاتفية

`LIT`
:   قاموس الليتوانية

`POL`
:   قاموس البولندية

`POR`
:   قاموس البرتغالية

`RUM`
:   قاموس الرومانية

`SLK`
:   قاموس السلوفاكية

`SLV`
:   قاموس السلوفينية

`SPA`
:   قاموس الإسبانية

`SWE`
:   قاموس السويدية

`SuggestedWord(javaClass)`
:   اقتراح إملائي تم إرجاعه من get_spell_check_error_list.

### الأسلاف (في MRO)

    * aspose.helper.BaseJavaClass

### الطرق

`initParams(self)`
:


### انظر أيضًا

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)