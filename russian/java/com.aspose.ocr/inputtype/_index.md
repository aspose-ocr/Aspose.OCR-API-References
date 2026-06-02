---
title: "InputType"
second_title: "Aspose.OCR для Java API Reference"
description: "Типы изображений/документов для обработки/распознавания"
type: docs
weight: 38
url: /ru/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Типы изображений/документов для обработки/распознавания.
## Поля

| Поле | Описание |
| --- | --- |
| [Base64](#Base64) | Строка base64 с изображением или путь к файлу .txt с содержимым base64. |
| [Directory](#Directory) | Путь к каталогу. |
| [PDF](#PDF) | Отсканированный PDF‑документ из файла или из InputStream. |
| [SingleImage](#SingleImage) | Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Многостраничный TIFF, TIF документ из файла или из InputStream. |
| [URL](#URL) | Ссылка на изображение. |
| [Zip](#Zip) | Полное имя ZIP‑архива. |

### Base64 {#Base64}
```
public static final InputType Base64
```


Строка base64 с изображением или путь к файлу .txt с содержимым base64. Поддерживает GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Путь к каталогу. Вложенные архивы и папки не поддерживаются. Поддерживает GIF, PNG, JPEG, BMP, TIFF. По умолчанию количество обрабатываемых изображений — все.

### PDF {#PDF}
```
public static final InputType PDF
```


Отсканированный PDF‑документ из файла или из InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Многостраничный TIFF, TIF документ из файла или из InputStream.

### URL {#URL}
```
public static final InputType URL
```


Ссылка на изображение. Поддерживает GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Полное имя ZIP‑архива. Вложенные архивы и папки не поддерживаются. Поддерживает GIF, PNG, JPEG, BMP, TIFF, JFIF. По умолчанию количество обрабатываемых изображений — все.
