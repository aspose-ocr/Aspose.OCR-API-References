---
title: "AsposeOcr"
second_title: "Java API 레퍼런스를 통한 Python용 Aspose.OCR"
description: 
type: docs
weight: 11
url: /ko/python-java/aspose/asposeocr/
---


모듈 asposeocr
================
Aspose OCR에 대한 Python 인터페이스

**Aspose.OCR for Python via .Java** is a powerful,
사용하기 쉬운 광학 문자 인식(OCR)
귀하의 Python 애플리케이션 및 노트북을 위한 엔진.
코드 **10**줄 미만으로, 인식할 수 있습니다
라틴어, 키릴어 기반의 **28**개 언어 텍스트,
그리고 아시아 스크립트, 가장 인기 있는 형식으로 결과를 반환합니다
문서 및 데이터 교환 형식입니다.
복잡한 수학 모델을 배울 필요가 없습니다,
머신러닝 알고리즘을 구축하고 신경망을 훈련시킵니다
네트워크 — 우리의 간단하고 견고한 API가 모든 작업을 대신 수행합니다.

클래스
-------

`AsposeOcr()`
:
인식을 위한 AsposeOcr 메인 클래스입니다.
    
이 샘플은 이미지 인식 방법을 보여줍니다.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Static methods

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
RecognitionResult 객체 목록으로부터 다중 페이지 문서를 가져올 수 있습니다.
@param fullFileName: 선택한 형식으로 인식 결과를 저장하기 위한 경로가 포함된 파일 이름.
@param saveFormat: 문서 형식 (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Methods

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
이미지의 기울기 각도를 계산합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스. 소스가 포함된 컨테이너.
@return: 각도(도) 단위의 기울기 각도 리스트 - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
두 이미지에 동일한 텍스트가 포함되어 있는지 확인합니다.
@param fullPath1: 첫 번째 이미지의 경로.
@param fullPath2: 두 번째 이미지의 경로.
@param settings: 인식 설정.
@param ignoreCase: True - 대소문자를 구분하지 않는 검색을 의미합니다.
@return: 이미지에 동일한 텍스트가 있는 경우 True (유사도 90%).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
텍스트를 교정합니다 (오타 단어를 교체).
@param text: 교정할 텍스트.
@param language: SpellCheckLanguage를 사용할 사전.
@return: 교체된 단어가 포함된 텍스트.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
이미지에서 텍스트 영역을 감지합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param areasType: 반환할 사각형 유형을 결정합니다 - 라인, 단락 또는 단어.
@param isDetectAreas: 자동 텍스트 영역 감지를 활성화합니다.
@return: 감지된 텍스트 영역 또는 라인이 포함된 RectangleOutput 리스트.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
이미지에 제공된 텍스트 조각이 포함되어 있는지 확인합니다.
@param fullPath: 이미지에 대한 경로.
@param text: 이미지에서 검색할 텍스트 조각.
@param settings: 인식 설정.
@param ignoreCase: True - 대소문자를 구분하지 않는 검색을 의미합니다.
@return: 이미지에 텍스트 조각이 포함되어 있으면 True. 그렇지 않으면 False - 이미지에 텍스트 조각이 포함되어 있지 않음.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
두 이미지의 텍스트를 비교하고 유사성을 나타내는 숫자(0~1)를 반환합니다.
@param fullPath1: 첫 번째 이미지의 경로.
@param fullPath2: 두 번째 이미지의 경로.
@param settings: 인식 설정.
@param ignoreCase: True - 대소문자를 구분하지 않는 검색을 의미합니다.
@return: 0은 텍스트가 완전히 다름을 의미하고; 1은 텍스트가 동일함을 의미합니다.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings를 지정할 수 있는 기능으로 이미지를 인식합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param settings: RecognitionSettings 객체.
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
CarPlateRecognitionSettings를 지정할 수 있는 기능으로 차량 번호판을 인식합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param settings: CarPlateRecognitionSettings
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
고품질 이미지에서 텍스트를 인식합니다. 자동 이미지 기울기 보정 및 텍스트 영역을 사용하지 않습니다.
감지.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
IDCardRecognitionSettings를 지정할 수 있는 기능으로 신분증을 인식합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param settings: IDCardRecognitionSettings
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
InvoiceRecognitionSettings를 지정할 수 있는 기능으로 청구서를 인식합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param settings: InvoiceRecognitionSettings
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
RecognitionSettings를 지정할 수 있는 기능으로 단일 라인 이미지를 인식합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param settings: RecognitionSettings 객체.
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
PassportRecognitionSettings를 지정할 수 있는 기능으로 여권을 인식합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param settings: PassportRecognitionSettings
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
ReceiptRecognitionSettings를 지정할 수 있는 기능으로 영수증을 인식합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@param settings: ReceiptRecognitionSettings
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
거리 사진의 텍스트를 인식합니다.
거리 사진, 교통 카메라 이미지, 신분증, 운전 면허증 및 텍스트가 희박하고 잡음/색상이 있는 배경의 기타 이미지에서 텍스트를 추출합니다.
GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, 바이너리 배열, 폴더, 배열, zip 압축 파일, URL, base64를 지원합니다.
@param input: :py:any:`~aspose.models.OcrInput`. 인스턴스.
@return: 이미지 인식 결과가 포함된 RecognitionResult 리스트.

`shutdown(self)`
:
JVM 머신을 종료합니다.

`ImageProcessing()`
:
Aspose OCR 라이브러리용 도우미 클래스입니다. 이미지 전처리 및 저장을 허용합니다.

### Static methods

`save(images, folderPath)`
:
이미지 처리를 사용하여 OCR 정확도를 향상시킵니다.
입력 이미지에 지정한 순서대로 적용될 필터 목록을 생성합니다.
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
모두 필요하지 않습니다. 필요한 것만 설정하십시오.
@param images: 다양한 이미지를 포함하는 OcrInput 객체 OcrInput.
@param folderPath: 처리된 이미지를 저장하기 위한 이미지 이름이 없는 경로.
@return: 결과 처리된 이미지를 포함하는 OcrInput 객체 OcrInput.


### 참고

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)