---
title: "DetectAreasMode"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: 
type: docs
weight: 28
url: /ko/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | 이미지에서 곡선 형태의 텍스트 라인을 자동으로 바로잡아 인식 정확도를 높이고 더 많은 텍스트를 복구 및 추출할 수 있게 합니다. |
| [FORMULA](#FORMULA) | 수학 공식이 포함된 모든 블록을 감지합니다. |
| [LEAN](#LEAN) | 복잡한 레이아웃 지원을 생략하여 속도를 우선시하고 리소스 소비를 줄입니다. |
| [MULTICOLUMN](#MULTICOLUMN) | 열 형식으로 배치된 큰 텍스트 블록을 감지합니다. |
| [TABLE](#TABLE) | 이미지에서 표 구조를 감지하고 개별 셀의 텍스트를 추출합니다. |
| [UNIVERSAL](#UNIVERSAL) | 사진에 있는 희박하고 불규칙한 텍스트를 포함한 이미지의 모든 텍스트 블록을 감지합니다. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


이미지에서 곡선 형태의 텍스트 라인을 자동으로 바로잡아 인식 정확도를 높이고 더 많은 텍스트를 복구 및 추출할 수 있게 합니다. 상당한 처리 능력과 RAM이 필요합니다.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


수학 공식이 포함된 모든 블록을 감지합니다.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


복잡한 레이아웃 지원을 생략하여 속도를 우선시하고 리소스 소비를 줄입니다. 일러스트나 서식이 없는 몇 줄의 텍스트만 있는 단순 이미지에만 적합합니다.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


열 형식으로 배치된 큰 텍스트 블록을 감지합니다. 책 페이지, 기사, 계약서와 같은 다중 열 레이아웃에 가장 적합합니다.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


이미지에서 표 구조를 감지하고 개별 셀의 텍스트를 추출합니다. 스캔한 스프레드시트, 보고서 및 기타 표 기반 문서에 권장됩니다.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


사진에 있는 희박하고 불규칙한 텍스트를 포함한 이미지의 모든 텍스트 블록을 감지합니다. 표와 다중 열 레이아웃을 제외한 대부분의 이미지에 다용도로 사용할 수 있습니다.

