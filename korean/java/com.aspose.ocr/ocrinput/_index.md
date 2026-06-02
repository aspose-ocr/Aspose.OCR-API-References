---
title: "OcrInput"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지에서 텍스트를 인식하기 위한 메인 클래스"
type: docs
weight: 20
url: /ko/java/com.aspose.ocr/ocrinput/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class OcrInput implements Iterable<ImageData>
```

이미지에서 텍스트를 인식하기 위한 메인 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OcrInput(InputType type, PreprocessingFilter filters)](#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter) | 컨테이너를 생성하고 이미지/문서 유형 및 추가 처리/인식을 위한 필터를 설정하는 생성자입니다. |
| [OcrInput(InputType type)](#OcrInput-com.aspose.ocr.InputType) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [add(int[] pixels, int width, int height, int bitsPerPixel)](#add-int---int-int-int) | 디코딩된 이미지를 인식/처리를 위한 목록에 추가합니다. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage) | 인식/처리를 위한 이미지를 포함하는 BufferedImage를 추가합니다. |
| [add(BufferedImage image, int startPage, int pagesCount)](#add-java.awt.image.BufferedImage-int-int) | 인식/처리를 위한 다중 페이지 이미지를 포함하는 BufferedImage를 추가합니다. |
| [add(InputStream stream)](#add-java.io.InputStream) | 인식/처리를 위한 이미지를 포함하는 InputStream을 추가합니다. |
| [add(InputStream stream, int startPage, int pagesCount)](#add-java.io.InputStream-int-int) | 인식/처리를 위한 다중 페이지 이미지를 포함하는 InputStream을 추가합니다. |
| [add(String fullPath)](#add-java.lang.String) | 인식/처리를 위한 이미지를 포함하는 경로나 URI를 추가합니다. |
| [add(String fullPath, int startPage, int pagesCount)](#add-java.lang.String-int-int) | 인식/처리를 위한 다중 페이지 이미지/문서를 추가합니다. |
| [addBase64(String base64)](#addBase64-java.lang.String) | 인식/처리를 위한 이미지를 포함하는 base64 문자열을 추가합니다. |
| [clear()](#clear) | 처리/인식 항목 수를 0으로 설정합니다. |
| [clearFilters()](#clearFilters) | 모든 필터를 제거합니다. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [get(int index)](#get-int) | 처리/인식된 이미지에 대한 정보를 반환합니다. |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [iterator()](#iterator) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [replaceFilters(PreprocessingFilter filters)](#replaceFilters-com.aspose.ocr.PreprocessingFilter) | 이전 필터를 제거하고 새 필터를 설정합니다. |
| [size()](#size) | 처리/인식할 항목 수. |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### OcrInput(InputType type, PreprocessingFilter filters) {#OcrInput-com.aspose.ocr.InputType-com.aspose.ocr.PreprocessingFilter}
```
public OcrInput(InputType type, PreprocessingFilter filters)
```


컨테이너를 생성하고 이미지/문서 유형 및 추가 처리/인식을 위한 필터를 설정하는 생성자입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) | 컨테이너에 추가될 이미지/문서 유형을 설정합니다. |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | 추가 처리 또는 인식을 위해 적용될 처리 필터를 설정합니다. |

### OcrInput(InputType type) {#OcrInput-com.aspose.ocr.InputType}
```
public OcrInput(InputType type)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | [InputType](../../com.aspose.ocr/inputtype/) |  |

### add(int[] pixels, int width, int height, int bitsPerPixel) {#add-int---int-int-int}
```
public void add(int[] pixels, int width, int height, int bitsPerPixel)
```


디코딩된 이미지를 인식/처리를 위한 목록에 추가합니다. 이미지 유형은 생성자에 지정된 유형(SingleImage)과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 픽셀 | int[] | 픽셀은 32비트 정수 값(rgb)으로 표현됩니다. |
| 너비 | int | 이미지 너비. |
| 높이 | int | 이미지 높이. |
| bitsPerPixel | int | 1-32비트를 지원합니다. |

### add(BufferedImage image) {#add-java.awt.image.BufferedImage}
```
public void add(BufferedImage image)
```


인식/처리를 위한 이미지를 포함하는 BufferedImage를 추가합니다. 이미지 유형은 생성자에 지정된 유형과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | java.awt.image.BufferedImage | 이미지 또는 문서를 포함하는 BufferedImage. |

### add(BufferedImage image, int startPage, int pagesCount) {#add-java.awt.image.BufferedImage-int-int}
```
public void add(BufferedImage image, int startPage, int pagesCount)
```


인식/처리를 위한 다중 페이지 이미지를 포함하는 BufferedImage를 추가합니다. 이미지 유형은 생성자에 지정된 유형과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | java.awt.image.BufferedImage | 다중 페이지 문서를 포함하는 BufferedImage. |
| startPage | int | 처리/인식을 위한 첫 번째 페이지/이미지입니다. 문서에 사용합니다. |
| pagesCount | int | 처리/인식을 위한 페이지/이미지의 총 수입니다. 문서에 사용합니다. 기본값 = 전체. |

### add(InputStream stream) {#add-java.io.InputStream}
```
public void add(InputStream stream)
```


인식/처리를 위한 이미지를 포함하는 InputStream을 추가합니다. 이미지 유형은 생성자에 지정된 유형과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 이미지 또는 문서를 포함하는 InputStream. |

### add(InputStream stream, int startPage, int pagesCount) {#add-java.io.InputStream-int-int}
```
public void add(InputStream stream, int startPage, int pagesCount)
```


다중 페이지 이미지를 포함하는 InputStream을 인식/처리를 위해 추가합니다. 이미지 유형은 생성자에 지정된 유형과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 다중 페이지 문서를 포함하는 InputStream. |
| startPage | int | 처리/인식을 위한 첫 번째 페이지/이미지입니다. 문서에 사용합니다. |
| pagesCount | int | 처리/인식을 위한 페이지/이미지의 총 수입니다. 문서에 사용합니다. 기본값 = 전체. |

### add(String fullPath) {#add-java.lang.String}
```
public void add(String fullPath)
```


인식/처리를 위해 이미지를 포함하는 경로나 URI를 추가합니다. 이미지 유형은 생성자에 지정된 유형과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath | java.lang.String | 이미지/문서/폴더/아카이브의 경로. |

### add(String fullPath, int startPage, int pagesCount) {#add-java.lang.String-int-int}
```
public void add(String fullPath, int startPage, int pagesCount)
```


인식/처리를 위해 다중 페이지 이미지/문서를 추가합니다. 이미지 유형은 생성자에 지정된 유형과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullPath | java.lang.String | 이미지/문서/폴더/아카이브의 경로. |
| startPage | int | 처리/인식을 위한 첫 번째 페이지/이미지입니다. 문서, zip, 폴더에 사용합니다. |
| pagesCount | int | 처리/인식을 위한 페이지/이미지의 총 개수입니다. 문서, zip, 폴더에 사용합니다. 기본값 = 전체. |

### addBase64(String base64) {#addBase64-java.lang.String}
```
public void addBase64(String base64)
```


인식/처리를 위해 이미지를 포함하는 base64 문자열을 추가합니다. 이미지 유형은 생성자에 지정된 유형과 일치해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| base64 | java.lang.String | 단일 이미지를 포함하는 Base64 문자열. |

### clear() {#clear}
```
public void clear()
```


처리/인식을 위한 항목 수를 0으로 설정합니다. 컬렉션을 비웁니다.

### clearFilters() {#clearFilters}
```
public void clearFilters()
```


모든 필터를 제거합니다.

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### get(int index) {#get-int}
```
public ImageData get(int index)
```


처리/인식된 이미지에 대한 정보를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 리스트에서 이미지의 위치. |

**Returns:**
[ImageData](../../com.aspose.ocr/imagedata/) - The object of @see [ImageData](../../com.aspose.ocr/imagedata/)
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator}
```
public Iterator<ImageData> iterator()
```




**Returns:**
java.util.Iterator<com.aspose.ocr.ImageData>
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### replaceFilters(PreprocessingFilter filters) {#replaceFilters-com.aspose.ocr.PreprocessingFilter}
```
public void replaceFilters(PreprocessingFilter filters)
```


이전 필터를 제거하고 새 필터를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filters | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | 추가 처리 또는 인식을 위해 처리 필터가 적용됩니다. |

### size() {#size}
```
public int size()
```


처리/인식할 항목 수.

**Returns:**
int - 항목 수.
### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

