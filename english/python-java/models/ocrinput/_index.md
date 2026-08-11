---
title: "OcrInput"
linktitle: "OcrInput"
second_title: "Aspose.OCR for Python via Java"
description: "Main class to collect images."
type: docs
weight: 10
url: /python-java/models/ocrinput/
---

## OcrInput class

**Module:** `models`


Main class to collect images.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) | Constructor to create container and set the type of images / documents and filters for further processing / recognition. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [add](#add) |  | No | Add the path or URI containing the image for recognition / processing. The type of the image must correspond to the type specified in the constructor. |
| [add_base64](#add_base64) |  | No | Add the base64 string containing the image for recognition / processing. The type of the image must correspond to the type specified in the constructor. |
| [addStream](#addstream) |  | No | Add the InputStream containing the image for recognition / processing. The type of the image must correspond to the type specified in the constructor. |
| [clear](#clear) |  | No | Set the amount of items for processing / recognition as 0. Clear the collection. |
| [clear_filters](#clear_filters) |  | No | Remove all filters. |
| [get](#get) | `ImageData` | No | Returns information about processed / recognized image. |
| [getJavaClass](#getjavaclass) |  | No |  |
| [init](#init) |  | No |  |
| [size](#size) |  | No | Amount of items for processing / recognition. |

### OcrInput Constructor {#constructor}

```python
__init__(self, InputType type, PreprocessingFilter filters)
```

Constructor to create container and set the type of images / documents and filters for further processing / recognition.

| Parameter | Type | Description |
| --- | --- | --- |
| `type` | `InputType` | Set the images/documents type will be added to container. |
| `filters` | `PreprocessingFilter` | Set processing filters will be applied for further processing or recognition. |

### OcrInput.add {#add}

```python
add(self, str fullPath, int startPage, int pagesNumber)
```

Add the path or URI containing the image for recognition / processing. The type of the image must correspond to the type specified in the constructor.

| Parameter | Type | Description |
| --- | --- | --- |
| `fullPath` | `str` | Path to the image/ document / folder / archive. |
| `startPage` | `int` | The first page/image for processing / recognition. Use for documents, zip, folders. |
| `pagesNumber` | `int` | The total amount of pages/images for processing / recognition. Use for documents, zip, folders. Default = all. |

### OcrInput.add_base64 {#add_base64}

```python
add_base64(self, str base64)
```

Add the base64 string containing the image for recognition / processing. The type of the image must correspond to the type specified in the constructor.

| Parameter | Type | Description |
| --- | --- | --- |
| `base64` | `str` | Base64 string with single image. |

### OcrInput.addStream {#addstream}

```python
addStream(self, image_data_binary, int startPage, int pagesNumber)
```

Add the InputStream containing the image for recognition / processing. The type of the image must correspond to the type specified in the constructor.

| Parameter | Type | Description |
| --- | --- | --- |
| `image_data_binary` | `` | containing the image or document. |
| `startPage` | `int` | The first page/image for processing / recognition. Use for documents, zip, folders. |
| `pagesNumber` | `int` | The total amount of pages/images for processing / recognition. Use for documents, zip, folders. Default = all. |

### OcrInput.clear {#clear}

```python
clear(self)
```

Set the amount of items for processing / recognition as 0. Clear the collection.

### OcrInput.clear_filters {#clear_filters}

```python
clear_filters(self)
```

Remove all filters.

### OcrInput.get {#get}

```python
get(self, int index) -> ImageData
```

Returns information about processed / recognized image.

| Parameter | Type | Description |
| --- | --- | --- |
| `index` | `int` | Position of the image in the List. |

**Return Type:** `ImageData` — The object of ImageData.

### OcrInput.getJavaClass {#getjavaclass}

```python
getJavaClass(self)
```

### OcrInput.init {#init}

```python
init(self, javaClass)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `javaClass` | `` |  |

### OcrInput.size {#size}

```python
size(self)
```

Amount of items for processing / recognition.

