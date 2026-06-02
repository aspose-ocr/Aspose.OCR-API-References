---
title: "PreprocessingFilter"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지 처리 명령에 대한 기본 클래스"
type: docs
weight: 24
url: /ko/java/com.aspose.ocr/preprocessingfilter/
---

**Inheritance:**
java.lang.Object
```
public class PreprocessingFilter
```

이미지 처리 명령을 위한 기본 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PreprocessingFilter()](#PreprocessingFilter) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Empty](#Empty) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AutoDenoising()](#AutoDenoising) | 추가 신경망을 사용하여 이미지를 개선하고 노이즈를 감소시킵니다. |
| [AutoDenoising(Rectangle area)](#AutoDenoising-java.awt.Rectangle) | 추가 신경망을 사용하여 이미지의 일부를 개선하고 노이즈를 감소시킵니다. |
| [AutoDewarping()](#AutoDewarping) | 이미지의 기하학적 왜곡을 자동으로 보정합니다. |
| [AutoSkew()](#AutoSkew) | 이미지 기울기 자동 보정을 활성화합니다. |
| [AutoSkew(Rectangle area)](#AutoSkew-java.awt.Rectangle) | 이미지 일부의 기울기 자동 보정을 활성화합니다. |
| [Binarize()](#Binarize) | 이미지를 흑백 이미지로 변환합니다. |
| [Binarize(Rectangle area)](#Binarize-java.awt.Rectangle) | 이미지의 일부를 흑백 이미지로 변환합니다. |
| [BinarizeAndDilate()](#BinarizeAndDilate) | 팽창은 이미지 내 객체의 경계에 픽셀을 추가합니다. |
| [BinarizeAndDilate(Rectangle area)](#BinarizeAndDilate-java.awt.Rectangle) | 팽창은 이미지 일부 내 객체의 경계에 픽셀을 추가합니다. |
| [ContrastCorrection()](#ContrastCorrection) | 대비 보정 필터. |
| [ContrastCorrection(Rectangle area)](#ContrastCorrection-java.awt.Rectangle) | 이미지 일부에 대한 대비 보정 필터. |
| [Invert()](#Invert) | 문서 이미지의 색상을 자동으로 반전시킵니다. |
| [Invert(Rectangle area)](#Invert-java.awt.Rectangle) | 이미지 일부의 색상을 자동으로 반전시킵니다. |
| [Median()](#Median) | 중간값 필터는 이미지의 각 요소를 순회하며 각 픽셀을 인접 픽셀들의 중간값으로 교체합니다. |
| [Median(Rectangle area)](#Median-java.awt.Rectangle) | 중간값 필터는 이미지 일부의 각 요소를 순회하며 각 픽셀을 인접 픽셀들의 중간값으로 교체합니다. |
| [Resize(int width, int height)](#Resize-int-int) | 이미지 크기 조정 - 이미지 해상도를 확대하거나 축소합니다. |
| [Resize(int width, int height, InterpolationFilterType type)](#Resize-int-int-com.aspose.ocr.InterpolationFilterType) | 이미지 크기 조정 - 해상도를 확대하거나 축소합니다. |
| [Rotate(float angle)](#Rotate-float) | 원본 이미지를 회전합니다. |
| [Rotate(float angle, Rectangle area)](#Rotate-float-java.awt.Rectangle) | 이미지의 일부를 회전합니다. |
| [Scale(float ratio)](#Scale-float) | 이미지 크기 조정 - 이미지 해상도를 확대하거나 축소합니다. |
| [Scale(float ratio, InterpolationFilterType type)](#Scale-float-com.aspose.ocr.InterpolationFilterType) | 이미지 크기 조정 - 이미지 해상도를 확대하거나 축소합니다. |
| [Threshold(int value)](#Threshold-int) | 원본 이미지의 픽셀 강도에 임계값을 설정하여 이진 이미지를 생성합니다. |
| [Threshold(int value, Rectangle area)](#Threshold-int-java.awt.Rectangle) | 원본 이미지 일부의 픽셀 강도에 임계값을 설정하여 이진 이미지 부분을 생성합니다. |
| [ToGrayscale()](#ToGrayscale) | 이미지를 회색조 이미지로 변환합니다. |
| [add(PreprocessingFilter filter)](#add-com.aspose.ocr.PreprocessingFilter) | 새 필터를 컬렉션에 추가하여 모든 작업을 추가로 실행합니다. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### PreprocessingFilter() {#PreprocessingFilter}
```
public PreprocessingFilter()
```


### Empty {#Empty}
```
public static final PreprocessingFilter Empty
```


### AutoDenoising() {#AutoDenoising}
```
public static PreprocessingFilter AutoDenoising()
```


추가 신경망을 사용하여 이미지를 개선하고 노이즈를 감소시킵니다. 스캔 아티팩트, 왜곡, 반점, 플레어, 그라디언트, 외부 요소가 있는 이미지에 유용합니다.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDenoising(Rectangle area) {#AutoDenoising-java.awt.Rectangle}
```
public static PreprocessingFilter AutoDenoising(Rectangle area)
```


추가 신경망을 사용하여 이미지의 일부를 개선하고 노이즈를 감소시킵니다. 스캔 아티팩트, 왜곡, 반점, 플레어, 그라디언트, 외부 요소가 있는 이미지에 유용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDenoisingFilter object.
### AutoDewarping() {#AutoDewarping}
```
public static PreprocessingFilter AutoDewarping()
```


이미지의 기하학적 왜곡을 자동으로 보정합니다. 매우 많은 리소스를 사용합니다!

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoDewarpingFilter object.
### AutoSkew() {#AutoSkew}
```
public static PreprocessingFilter AutoSkew()
```


이미지 기울기 자동 보정을 활성화합니다.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### AutoSkew(Rectangle area) {#AutoSkew-java.awt.Rectangle}
```
public static PreprocessingFilter AutoSkew(Rectangle area)
```


이미지 일부의 기울기 자동 보정을 활성화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - AutoSkewFilter object.
### Binarize() {#Binarize}
```
public static PreprocessingFilter Binarize()
```


이미지를 흑백 이미지로 변환합니다. 이진 이미지는 픽셀의 강도 값이 두 가지만 가능한 이미지이며, 일반적으로 검은색과 흰색으로 표시됩니다. 수치적으로 두 값은 보통 검은색은 0, 흰색은 255입니다. 이진 이미지는 이미지에 자동 임계값을 적용하여 생성됩니다.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Binarize(Rectangle area) {#Binarize-java.awt.Rectangle}
```
public static PreprocessingFilter Binarize(Rectangle area)
```


이미지의 일부를 흑백 이미지로 변환합니다. 이진 이미지는 픽셀의 강도 값이 두 가지만 가능한 이미지이며, 일반적으로 검은색과 흰색으로 표시됩니다. 수치적으로 두 값은 보통 검은색은 0, 흰색은 255입니다. 이진 이미지는 이미지에 자동 임계값을 적용하여 생성됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### BinarizeAndDilate() {#BinarizeAndDilate}
```
public static PreprocessingFilter BinarizeAndDilate()
```


팽창은 이미지 내 객체의 경계에 픽셀을 추가합니다.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### BinarizeAndDilate(Rectangle area) {#BinarizeAndDilate-java.awt.Rectangle}
```
public static PreprocessingFilter BinarizeAndDilate(Rectangle area)
```


팽창은 이미지 일부 내 객체의 경계에 픽셀을 추가합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - DilateFilter object.
### ContrastCorrection() {#ContrastCorrection}
```
public static PreprocessingFilter ContrastCorrection()
```


대비 보정 필터.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### ContrastCorrection(Rectangle area) {#ContrastCorrection-java.awt.Rectangle}
```
public static PreprocessingFilter ContrastCorrection(Rectangle area)
```


이미지 일부에 대한 대비 보정 필터.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ContrastCorrectionFilter object.
### Invert() {#Invert}
```
public static PreprocessingFilter Invert()
```


문서 이미지의 색상을 자동으로 반전시킵니다.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Invert(Rectangle area) {#Invert-java.awt.Rectangle}
```
public static PreprocessingFilter Invert(Rectangle area)
```


이미지 일부의 색상을 자동으로 반전시킵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - InvertFilter object.
### Median() {#Median}
```
public static PreprocessingFilter Median()
```


중간값 필터는 이미지의 각 요소를 순회하며 각 픽셀을 인접 픽셀들의 중간값으로 교체합니다.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Median(Rectangle area) {#Median-java.awt.Rectangle}
```
public static PreprocessingFilter Median(Rectangle area)
```


중간값 필터는 이미지 일부의 각 요소를 순회하며 각 픽셀을 인접 픽셀들의 중간값으로 교체합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - MedianFilter object.
### Resize(int width, int height) {#Resize-int-int}
```
public static PreprocessingFilter Resize(int width, int height)
```


이미지 크기 조정 - 해상도를 확대하거나 축소합니다. InterpolationFilterType = bilinear 또는 nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 너비 | int | 이미지의 새로운 너비입니다. |
| 높이 | int | 이미지의 새로운 높이입니다. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Resize(int width, int height, InterpolationFilterType type) {#Resize-int-int-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Resize(int width, int height, InterpolationFilterType type)
```


이미지 크기 조정 - 해상도를 확대하거나 축소합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 너비 | int | 이미지의 새로운 너비입니다. |
| 높이 | int | 이미지의 새로운 높이입니다. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ResizeFilter object.
### Rotate(float angle) {#Rotate-float}
```
public static PreprocessingFilter Rotate(float angle)
```


원본 이미지를 회전합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. 값은 -360에서 360 사이입니다. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Rotate(float angle, Rectangle area) {#Rotate-float-java.awt.Rectangle}
```
public static PreprocessingFilter Rotate(float angle, Rectangle area)
```


이미지의 일부를 회전합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 각도 | float | 회전 각도. 값은 -360에서 360 사이입니다. |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - RotateFilter object.
### Scale(float ratio) {#Scale-float}
```
public static PreprocessingFilter Scale(float ratio)
```


이미지 크기 조정 - 이미지 해상도를 확대하거나 축소합니다. InterpolationFilterType 기본값은 bilinear 또는 nearest neighbor @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/)

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 비율 | float | 스케일링 계수. 축소하려면 0.1에서 1 사이의 값을 권장합니다. 확대하려면 1에서 10 사이의 값을 권장합니다. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Scale(float ratio, InterpolationFilterType type) {#Scale-float-com.aspose.ocr.InterpolationFilterType}
```
public static PreprocessingFilter Scale(float ratio, InterpolationFilterType type)
```


이미지 크기 조정 - 이미지 해상도를 확대하거나 축소합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 비율 | float | 스케일링 계수. 축소하려면 0.1에서 1 사이의 값을 권장합니다. 확대하려면 1에서 10 사이의 값을 권장합니다. |
| type | [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) | InterpolationFilterType @see [InterpolationFilterType](../../com.aspose.ocr/interpolationfiltertype/) |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - ScaleFilter object.
### Threshold(int value) {#Threshold-int}
```
public static PreprocessingFilter Threshold(int value)
```


원본 이미지의 픽셀 강도에 임계값을 설정하여 이진 이미지를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int | 최대값. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### Threshold(int value, Rectangle area) {#Threshold-int-java.awt.Rectangle}
```
public static PreprocessingFilter Threshold(int value, Rectangle area)
```


원본 이미지 일부의 픽셀 강도에 임계값을 설정하여 이진 이미지 부분을 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int | 최대값. |
| 영역 | java.awt.Rectangle | 전처리할 사각형. |

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - BinarizeFilter object.
### ToGrayscale() {#ToGrayscale}
```
public static PreprocessingFilter ToGrayscale()
```


이미지를 그레이스케일 이미지로 변환합니다. 그레이스케일 이미지는 이미지 내에 0부터 255까지 256단계의 밝기를 가집니다.

**Returns:**
[PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) - GrayscaleFilter object.
### add(PreprocessingFilter filter) {#add-com.aspose.ocr.PreprocessingFilter}
```
public void add(PreprocessingFilter filter)
```


새 필터를 컬렉션에 추가하여 모든 작업을 계속 실행합니다. 컬렉션 내 일관성이 중요합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filter | [PreprocessingFilter](../../com.aspose.ocr/preprocessingfilter/) | 필터 목록에 추가할 새 작업. |

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
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




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

