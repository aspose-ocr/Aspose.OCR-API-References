---
title: "RecognitionResult"
linktitle: "RecognitionResult"
second_title: "Aspose.OCR for Python via Java"
description: "The results of the image recognition. Contains elements with recognition information and methods for result export."
type: docs
weight: 10
url: /python-java/recognitionresult/recognitionresult/
---

## RecognitionResult class

**Module:** `recognitionresult`


The results of the image recognition. Contains elements with recognition information and methods for result export.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [get_json](#get_json) |  | No | Form JSON string with recognition results. |
| [get_spell_check_corrected_text](#get_spell_check_corrected_text) | `str` | No | Corrects text (replaces misspelled words). |
| [get_spell_check_error_list](#get_spell_check_error_list) |  | No | Find the misspelled words with suggested spellings for a given input text. |
| [get_xml](#get_xml) |  | No | Form JSON string with recognition results. |
| [getJavaClass](#getjavaclass) |  | No |  |
| [init](#init) |  | No |  |
| [save](#save) |  | No | Saves the document in the plain text or other document format. |
| [save_multipage_document](#save_multipage_document) |  | Yes | Private. |
| [save_spell_check_corrected_text](#save_spell_check_corrected_text) |  | No | Corrects text (replaces misspelled words). Saves the corrected text in the document in the plain text or other format. |
| [use_user_dictionary](#use_user_dictionary) |  | No | Allows to use own dictionary for spell-check correction. |

### RecognitionResult Constructor {#constructor}

```python
__init__(self, javaClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `javaClass` | `` |  |

### RecognitionResult.get_json {#get_json}

```python
get_json(self)
```

Form JSON string with recognition results.

### RecognitionResult.get_spell_check_corrected_text {#get_spell_check_corrected_text}

```python
get_spell_check_corrected_text(self, SpellCheckLanguage language) -> str
```

Corrects text (replaces misspelled words).

| Parameter | Type | Description |
| --- | --- | --- |
| `language` | `SpellCheckLanguage` | Dictionary to use. |

**Return Type:** `str` — Corrected recognition results string.

### RecognitionResult.get_spell_check_error_list {#get_spell_check_error_list}

```python
get_spell_check_error_list(self, SpellCheckLanguage language)
```

Find the misspelled words with suggested spellings for a given input text.

| Parameter | Type | Description |
| --- | --- | --- |
| `language` | `SpellCheckLanguage` | Dictionary to use. |

### RecognitionResult.get_xml {#get_xml}

```python
get_xml(self)
```

Form JSON string with recognition results.

### RecognitionResult.getJavaClass {#getjavaclass}

```python
getJavaClass(self)
```

### RecognitionResult.init {#init}

```python
init(self)
```

### RecognitionResult.save {#save}

```python
save(self, str fullFileName, Format format)
```

Saves the document in the plain text or other document format.

| Parameter | Type | Description |
| --- | --- | --- |
| `fullFileName` | `str` | Filename with a path for saving recognition result. |
| `format` | `Format` | Document format enum type of Format. |

### RecognitionResult.save_multipage_document (static) {#save_multipage_document}

```python
save_multipage_document(str fullPath)
```

Private.

| Parameter | Type | Description |
| --- | --- | --- |
| `fullPath` | `str` |  |

### RecognitionResult.save_spell_check_corrected_text {#save_spell_check_corrected_text}

```python
save_spell_check_corrected_text(self, str fullFileName, Format format, SpellCheckLanguage language)
```

Corrects text (replaces misspelled words). Saves the corrected text in the document in the plain text or other format.

| Parameter | Type | Description |
| --- | --- | --- |
| `fullFileName` | `str` | Filename with a path for saving recognition result |
| `format` | `Format` | Document format enum type of Format. |
| `language` | `SpellCheckLanguage` | Dictionary for spell check. |

### RecognitionResult.use_user_dictionary {#use_user_dictionary}

```python
use_user_dictionary(self, str dictionaryPath)
```

Allows to use own dictionary for spell-check correction.

| Parameter | Type | Description |
| --- | --- | --- |
| `dictionaryPath` | `str` | Full path to the user dictionary (frequency dictionary). Dictionary file format: Plain text file in UTF-8 encoding. Word and Word Frequency are separated by comma, the word is expected in the first column and the frequency in the second column. Every word-frequency-pair in a separate line.A line is defined as a sequence of characters followed by a line feed ("\n"), a carriage return ("\r"), or a carriage return immediately followed by a line feed("\r\n"). Every word is expected to be in lower case. Example: word,5984819 hello,5761742 down,5582768 |

