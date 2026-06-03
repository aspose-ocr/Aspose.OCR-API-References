---
title: "AsposeOcr"
second_title: "Справочник API Aspose.OCR для Python через Java"
description: 
type: docs
weight: 11
url: /ru/python-java/aspose/asposeocr/
---


Модуль asposeocr
================
Python-интерфейс к Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
в то время как простое в использовании оптическое распознавание символов (OCR)
движок для ваших Python‑приложений и ноутбуков.
Менее чем **10** строк кода, вы можете распознать
текст на **28** языках, основанных на латинице, кириллице,
и азиатских письменностях, возвращая результаты в самых популярных
форматах документов и обмена данными.
Нет необходимости изучать сложные математические модели,
создавать алгоритмы машинного обучения и обучать нейронные
сети — наш простой и надёжный API сделает всё за вас.

Классы
-------

`AsposeOcr()`
:
Основной класс AsposeOcr для распознавания.
    
Этот пример показывает, как распознать изображение.
\\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, \"SpanishOCR.bmp\"))
result = api.recognize(input)
\\endcode

### Статические методы

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Позволяет получить многостраничный документ из списка объектов RecognitionResult.
@param fullFileName: Имя файла с путём для сохранения результата распознавания в выбранном формате.
@param saveFormat: Формат документа (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Методы

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Вычисляет углы наклона изображений.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр. Контейнер с источниками.
@return: Список углов наклона в градусах — SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Проверяет, содержат ли два изображения одинаковый текст.
@param fullPath1: Путь к первому изображению.
@param fullPath2: Путь ко второму изображению.
@param settings: Параметры распознавания.
@param ignoreCase: True — означает поиск без учёта регистра.
@return: True, если изображения имеют одинаковый текст (90 % сходства).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Корректирует текст (заменяет ошибочно написанные слова).
@param text: Текст для коррекции.
@param language: Словарь, используемый SpellCheckLanguage.
@return: Текст с заменёнными словами.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Обнаруживает текстовые области на изображениях.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param areasType: Определяет, какие прямоугольники возвращать — строки, абзацы или слова.
@param isDetectAreas: Включает автоматическое обнаружение текстовых областей.
@return: Список RectangleOutput с обнаруженными текстовыми областями или строками.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Проверяет, содержит ли изображение предоставленный фрагмент текста.
@param fullPath: Путь к изображению.
@param text: Фрагмент текста для поиска на изображении.
@param settings: Параметры распознавания.
@param ignoreCase: True — означает поиск без учёта регистра.
@return: True если изображение содержит фрагмент текста. False — изображение не содержит фрагмент текста.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Сравните тексты на двух изображениях и верните число, представляющее степень их схожести (от 0 до 1).
@param fullPath1: Путь к первому изображению.
@param fullPath2: Путь ко второму изображению.
@param settings: Параметры распознавания.
@param ignoreCase: True — означает поиск без учёта регистра.
@return: 0 означает, что тексты полностью различны; 1 означает, что тексты идентичны.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознаёт изображение с возможностью указать RecognitionSettings.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param settings: объект RecognitionSettings.
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознаёт номер автомобиля с возможностью указать CarPlateRecognitionSettings.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param settings: CarPlateRecognitionSettings
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознаёт текст на изображении хорошего качества. Не использует автоматическую коррекцию наклона изображения и области текста
обнаружения.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознаёт удостоверение личности с возможностью указать IDCardRecognitionSettings.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param settings: IDCardRecognitionSettings
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознаёт счёт-фактуру с возможностью указать InvoiceRecognitionSettings
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param settings: InvoiceRecognitionSettings
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознаёт изображение с одной строкой с возможностью указать RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param settings: объект RecognitionSettings.
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознает паспорт с возможностью указать PassportRecognitionSettings.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param settings: PassportRecognitionSettings
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознает чеки с возможностью указать ReceiptRecognitionSettings.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@param settings: ReceiptRecognitionSettings
@return: список RecognitionResult с результатами распознавания изображений.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Распознает текст на уличных фотографиях.
Извлекает текст из уличных фотографий, изображений с камер дорожного наблюдения, удостоверений личности, водительских прав и других изображений с разреженным текстом и шумными/цветными фонами.
Поддерживает GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, бинарный массив, папку, массив, zip‑архив, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. экземпляр.
@return: список RecognitionResult с результатами распознавания изображений.

`shutdown(self)`
:
Выключает машину JVM.

`ImageProcessing()`
:
Вспомогательный класс для библиотеки Aspose OCR. Позволяет предварительно обрабатывать и сохранять изображения.

### Статические методы

`save(images, folderPath)`
:
Используйте обработку изображений для повышения точности OCR.
Создайте список фильтров, которые будут применяться к входному изображению в указанном вами порядке.
\\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\\endcode
Вам не нужны все из них. Установите только то, что требуется.
@param images: объект OcrInput, содержащий разные изображения OcrInput.
@param folderPath: Путь без имён изображений для сохранения обработанных изображений.
@return: объект OcrInput, содержащий результат обработанных изображений OcrInput.


### См. также

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)