---
title: "RecognitionResult"
second_title: "Справочник API Aspose.OCR для Python через .NET"
description: 
type: docs
weight: 290
url: /ru/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

Результаты распознавания изображения.<br/>            Содержит элементы с информацией о распознавании и методы экспорта результатов.

Тип RecognitionResult раскрывает следующие члены:


## Свойства
| Имя | Описание |
| :- | :- |
| recognition_regions_result | Получает список результатов распознавания со списком регионов (Прямоугольники). |
| recognition_lines_result | Получает список результатов распознавания со списком строк (прямоугольников). |
| recognition_characters_list | Набор символов, найденных алгоритмом распознавания и упорядоченных по убыванию вероятности. |
| recognition_text | Получает результат распознавания в виде одной строки. |
| file_name | Полный путь к файлу. |
| warnings | Получает список предупреждающих сообщений, описывающих некритические ошибки, возникшие во время генерации. |
| serializable_image |  |
## Методы
| Имя | Описание |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Сохраняет документ в виде простого текста, PDF или документа Microsoft Word. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Сохраняет документ в виде простого текста, PDF или документа Microsoft Word. |
| save(full_file_name, save_format, optimize_pdf) | Сохраняет документ в виде простого текста, PDF или документа Microsoft Word. |
| save(stream, save_format, optimize_pdf) | Сохраняет документ в виде простого текста, PDF или документа Microsoft Word. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Сохраняет документ в виде простого текста, PDF или документа Microsoft Word. |
| get_spell_check_corrected_text(language, dictionary_path) | Исправляет текст (заменяет ошибочно написанные слова). |
| get_spell_check_error_list(language, dictionary_path) | Находит ошибочно написанные слова с предложенными вариантами исправления для заданного входного текста. |
| get_json(is_readable) | Создаёт JSON-строку с результатами распознавания. |
| get_xml() | Создаёт XML-строку с результатами распознавания. |
| get_keywords() | Получить ключевые слова из паспорта (Тестовый режим. Работает только с паспортами США и МАДАГАСКАРА). |

### См. также

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

