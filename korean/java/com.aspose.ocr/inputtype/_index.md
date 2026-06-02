---
title: "InputType"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "처리/인식을 위한 이미지/문서 유형"
type: docs
weight: 38
url: /ko/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

처리/인식을 위한 이미지/문서 유형.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Base64](#Base64) | 이미지를 포함한 base64 문자열 또는 base64 내용이 들어 있는 .txt 파일 경로. |
| [Directory](#Directory) | 디렉터리 경로. |
| [PDF](#PDF) | 파일 또는 InputStream에서 스캔된 PDF 문서. |
| [SingleImage](#SingleImage) | GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage를 지원합니다. |
| [TIFF](#TIFF) | 파일 또는 InputStream에서 멀티페이지 TIFF, TIF 문서. |
| [URL](#URL) | 이미지에 대한 링크. |
| [Zip](#Zip) | ZIP 압축 파일의 전체 이름. |

### Base64 {#Base64}
```
public static final InputType Base64
```


이미지를 포함한 base64 문자열 또는 base64 내용이 들어 있는 .txt 파일 경로. GIF, PNG, JPEG, BMP, TIFF를 지원합니다.

### Directory {#Directory}
```
public static final InputType Directory
```


디렉터리 경로. 중첩된 압축 파일 및 폴더는 지원되지 않습니다. GIF, PNG, JPEG, BMP, TIFF를 지원합니다. 기본 처리 이미지 수는 전체입니다.

### PDF {#PDF}
```
public static final InputType PDF
```


파일 또는 InputStream에서 스캔된 PDF 문서.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage를 지원합니다.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


파일 또는 InputStream에서 멀티페이지 TIFF, TIF 문서.

### URL {#URL}
```
public static final InputType URL
```


이미지에 대한 링크. GIF, PNG, JPEG, BMP, TIFF를 지원합니다.

### Zip {#Zip}
```
public static final InputType Zip
```


ZIP 압축 파일의 전체 이름. 중첩된 압축 파일 및 폴더는 지원되지 않습니다. GIF, PNG, JPEG, BMP, TIFF, JFIF를 지원합니다. 기본 처리 이미지 수는 전체입니다.
