---
title: "DefectType"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "이미지 결함 유형"
type: docs
weight: 22
url: /ko/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

이미지 결함 유형.
## 필드

| 필드 | 설명 |
| --- | --- |
| [ALL](#ALL) | 지원되는 모든 이미지 결함. |
| [BLUR](#BLUR) | 이미지가 초점이 맞지 않았습니다. |
| [GLARE](#GLARE) | 불균일한 조명(스포트라이트나 플래시 등)으로 인해 이미지에 발생하는 영역. |
| [LOW_CONTRAST](#LOW-CONTRAST) | 곡선 페이지에 일반적으로 나타나는 하이라이트와 그림자. |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | 영역 전체에 무작위로 흩어진 흰색 및 검은색 픽셀. |

### ALL {#ALL}
```
public static final DefectType ALL
```


지원되는 모든 이미지 결함.

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


이미지가 초점이 맞지 않습니다. 이 탐지 알고리즘은 전체 이미지를 흐릿하게 인식할 수만 있으며, 특정 영역은 감지할 수 없습니다.

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


불균일한 조명(스포트라이트나 플래시 등)으로 인해 이미지에 발생하는 영역.

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


곡선 페이지에 일반적으로 나타나는 하이라이트와 그림자.

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


영역 전체에 무작위로 흩어진 흰색 및 검은색 픽셀. 디지털 사진에서 자주 발생합니다.

