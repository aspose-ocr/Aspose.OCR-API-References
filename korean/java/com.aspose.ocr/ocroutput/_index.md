---
title: "OcrOutput"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: 
type: docs
weight: 21
url: /ko/java/com.aspose.ocr/ocroutput/
---

**Inheritance:**
java.lang.Object, java.util.AbstractCollection, java.util.AbstractList, java.util.ArrayList
```
public class OcrOutput extends ArrayList<RecognitionResult>
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OcrOutput()](#OcrOutput) | 빈 컬렉션을 가진 OcrOutput 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |

| [getTableData()](#getTableData) | 인식된 모든 페이지에서 추출된 구조화된 테이블 데이터를 반환합니다. |
| [save(OutputStream stream)](#save-java.io.OutputStream) | 지정된 형식으로 모든 인식 결과를 메모리 스트림에 저장합니다. |
| [save(OutputStream stream, Format saveFormat)](#save-java.io.OutputStream-com.aspose.ocr.models.Format) | 지정된 형식으로 모든 인식 결과를 메모리 스트림에 저장합니다. |
| [save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 지정된 형식으로 모든 인식 결과를 메모리 스트림에 저장합니다. |
| [save(String fullFileName)](#save-java.lang.String) | 인식 결과를 모두 파일에 저장합니다. |
| [save(String fullFileName, Format saveFormat)](#save-java.lang.String-com.aspose.ocr.models.Format) | 인식 결과를 모두 파일에 저장합니다. |
| [save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 인식 결과를 모두 파일에 저장합니다. |
| [savePdf(OutputStream stream)](#savePdf-java.io.OutputStream) | 인식 결과를 모두 메모리 내 검색 가능한 PDF 문서에 저장하고, 원본 이미지를 배경으로 삽입합니다. |
| [savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 인식 결과를 모두 메모리 내 검색 가능한 PDF 문서에 저장하고, 원본 이미지를 배경으로 삽입합니다. |
| [savePdf(String fullFileName)](#savePdf-java.lang.String) | 인식 결과를 모두 검색 가능한 PDF 파일에 저장하며, 원본 이미지를 배경으로 설정합니다. |
| [savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | 인식 결과를 모두 검색 가능한 PDF 파일에 저장하며, 원본 이미지를 배경으로 설정합니다. |

### getTableData() {#getTableData}
```
public OCRTable getTableData()
```


인식된 모든 페이지에서 추출된 구조화된 테이블 데이터를 반환합니다.

각 페이지는 행을 포함하고, 각 행은 인식된 텍스트와 선택적인 위치 정보를 가진 셀을 포함합니다.

**Returns:**
[OCRTable](../../com.aspose.ocr.models/ocrtable/) - an [OCRTable](../../com.aspose.ocr.models/ocrtable/) structure representing all tables in the document


### save(OutputStream stream) {#save-java.io.OutputStream}
```
public void save(OutputStream stream)
```


지정된 형식으로 모든 인식 결과를 메모리 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |

### save(OutputStream stream, Format saveFormat) {#save-java.io.OutputStream-com.aspose.ocr.models.Format}
```
public void save(OutputStream stream, Format saveFormat)
```


지정된 형식으로 모든 인식 결과를 메모리 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.io.OutputStream-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(OutputStream stream, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


지정된 형식으로 모든 인식 결과를 메모리 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | 옵션. 사용자 글꼴에 대한 전체 경로입니다. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 배경 이미지 품질을 낮춰 PDF 파일 크기를 줄입니다. 기본적으로 원본 이미지 품질이 유지됩니다. |

### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


인식 결과를 모두 파일에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |

### save(String fullFileName, Format saveFormat) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format saveFormat)
```


인식 결과를 모두 파일에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |

### save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format saveFormat, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


인식 결과를 모두 파일에 저장합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | 문서 형식 (Docx, Txt, Pdf, Xlsx, Rtf, Json, Xml, Epub). |
| embeddedFontPath | java.lang.String | 옵션. 사용자 글꼴에 대한 전체 경로입니다. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 배경 이미지 품질을 낮춰 PDF 파일 크기를 줄입니다. 기본적으로 원본 이미지 품질이 유지됩니다. |

### savePdf(OutputStream stream) {#savePdf-java.io.OutputStream}
```
public void savePdf(OutputStream stream)
```


인식 결과를 모두 메모리 내 검색 가능한 PDF 문서에 저장하고, 원본 이미지를 배경으로 삽입합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |

### savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.io.OutputStream-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(OutputStream stream, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


인식 결과를 모두 메모리 내 검색 가능한 PDF 문서에 저장하고, 원본 이미지를 배경으로 삽입합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 선택한 형식으로 인식 결과를 저장하기 위한 OutputStream. |
| embeddedFontPath | java.lang.String | 옵션. 사용자 글꼴에 대한 전체 경로입니다. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 배경 이미지 품질을 낮춰 PDF 파일 크기를 줄입니다. 기본적으로 원본 이미지 품질이 유지됩니다. |

### savePdf(String fullFileName) {#savePdf-java.lang.String}
```
public void savePdf(String fullFileName)
```


인식 결과를 모두 검색 가능한 PDF 파일에 저장하며, 원본 이미지를 배경으로 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |

### savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#savePdf-java.lang.String-java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public void savePdf(String fullFileName, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


인식 결과를 모두 검색 가능한 PDF 파일에 저장하며, 원본 이미지를 배경으로 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fullFileName | java.lang.String | 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름. |
| embeddedFontPath | java.lang.String | 옵션. 사용자 글꼴에 대한 전체 경로입니다. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | 배경 이미지 품질을 낮춰 PDF 파일 크기를 줄입니다. 기본적으로 원본 이미지 품질이 유지됩니다. |

### size() {#size}
```
public int size()
```




**Returns:**
int
