---
title: "RecognitionResult"
second_title: "Справочник API Aspose.OCR для Python через Java"
description: 
type: docs
weight: 171
url: /ru/python-java/aspose/recognitionresult/
---

Модуль recognitionresult
========================

Классы
-------

`LinesResult(javaClass)`
:

### Предки (в MRO)

    * aspose.helper.BaseJavaClass

### Методы

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Результаты распознавания изображений. Содержит элементы с распознаванием
информацию и методы для экспорта результатов.

### Статические методы

`save_multipage_document(self, fullPath: str)`
:
Приватный

### Переменные экземпляра

`recognition_areas_text`
:   Список результатов распознавания списка областей (Прямоугольники).

`recognition_lines_result`
:   Получает список результатов распознавания со списком строк (Прямоугольники).

### Методы

`getJavaClass(self)`
:

`get_json(self)`
:
Формирует строку JSON с результатами распознавания.
@return: Результаты распознавания в виде строки JSON.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Корректирует текст (заменяет ошибочно написанные слова).
@param language: Словарь для использования.
@return: Строка с исправленными результатами распознавания.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Найдите слова с ошибками и предложенные варианты их написания для данного входного текста.
@param language: Словарь для использования.
@return: Список объектов SpellCheckError, представляющих слова с ошибками, с перечнями предложенных правильных написаний для каждого ошибочного слова,
и с расстоянием редактирования.

`get_xml(self)`
:
Формирует строку JSON с результатами распознавания.
@return: Результаты распознавания в виде XML-строки.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Сохраняет документ в виде обычного текста или в другом формате документа.
@param fullFileName: Имя файла с путём для сохранения результата распознавания.
@param format: Перечисление типа формата документа Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Корректирует текст (заменяет ошибочно написанные слова).
Сохраняет исправленный текст в документе в виде обычного текста или в другом формате.
@param fullFileName: Имя файла с путём для сохранения результата распознавания
@param format: Перечисление типа формата документа Format.
@param language: Словарь для проверки орфографии.

`use_user_dictionary(self, dictionaryPath: str)`
:
Позволяет использовать собственный словарь для исправления орфографических ошибок.
@param dictionaryPath: Полный путь к пользовательскому словарю (словарю частот).
Формат файла словаря:
Текстовый файл в кодировке UTF-8.
Слово и частота слова разделены запятой, слово ожидается в первом столбце, а частота — во втором.
Каждая пара слово‑частота в отдельной строке. Строка определяется как последовательность символов, за которой следует перевод строки ("
"), возврат каретки ("
"),
или возврат каретки, сразу за которым следует перевод строки("

").
Каждое слово должно быть в нижнем регистре.
Пример:
\\code
слово,5984819
привет,5761742
вниз,5582768
\\endcode

`RectangleOutput(javaClass)`
:
Данные о обнаруженных текстовых областях или строках.
\\code
source - Полный путь к файлу или URL, если имеется. Пусто для потоков, массивов байтов, base64.
page - Номер страницы.
image_index - Порядковый номер изображения на странице.
rectangles - Список обнаруженных областей текста или строк.
\\endcode

### Предки (в MRO)

    * aspose.helper.BaseJavaClass

### Методы

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Данные об угле наклона в градусах и имени файла.
\\code
source - Полный путь к файлу или URL, если имеется. Пусто для потоков, массивов байтов, base64.
page - Номер страницы.
image_index - Порядковый номер изображения на странице.
angle - Угол наклона в градусах.
\\endcode

### Предки (в MRO)

    * aspose.helper.BaseJavaClass

### Методы

`initParams(self)`
:


### См. также

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)