---
title: "모델"
second_title: "Java API 레퍼런스를 통한 Python용 Aspose.OCR"
description: 
type: docs
weight: 271
url: /ko/python-java/aspose/models/
---

모듈 모델
=============

클래스
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   모델이 감지한 영역의 유형을 결정합니다.
get_text_areas에서 사용되어 어떤 결과가 얻어질지 표시합니다 - 단락 좌표 또는 라인 좌표.

### 조상 (MRO 내)

    * enum.Enum

### 클래스 변수

`LINES`
:   영역을 라인으로 설정합니다.

`PARAGRAPHS`
:   영역을 단락으로 설정합니다.

`WORDS`
:   영역을 단어로 설정합니다.

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   영역 감지에 사용되는 신경망 유형을 결정합니다.
RecognitionSettings에서 인식하려는 이미지 유형을 지정하는 데 사용됩니다.

### 조상 (MRO 내)

    * enum.Enum

### 클래스 변수

`COMBINE`
:   텍스트가 있는 단락을 감지하고 다른 NN 모델을 사용하여 단락 내부 영역을 감지합니다.
복잡한 구조를 가진 이미지에 더 적합합니다.

`CURVED_TEXT`
:   곡선 이미지에서 선을 감지하고 텍스트를 인식합니다.
책 및 잡지 페이지 사진에 선호되는 모드입니다.

`DOCUMENT`
:   문서에 대해 단락을 감지하고 NN 모델을 사용합니다.
다중 열 문서, 그림이 포함된 문서 또는 텍스트가 아닌 객체가 있는 문서에 더 적합합니다.

`NONE`
:   단락을 감지하지 않습니다.
그림이 없는 단순한 한 열 문서에 더 적합합니다.

`PHOTO`
:   사진에 대해 단락을 감지하고 NN 모델을 사용합니다.
많은 그림과 텍스트가 아닌 객체가 포함된 이미지에 더 적합합니다.

`TABLE`
:   텍스트가 포함된 셀을 감지합니다.
표 구조가 있는 이미지에 권장되는 모드입니다.

`TEXT_IN_WILD`
:   거리 사진, 번호판, 여권 사진, 계량기 사진 및 잡음이 많은 배경 사진과 같은 저품질 이미지에서 단어를 추출하도록 특화된 초강력 신경망입니다.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   인식 결과를 문서로 저장하기 위한 포맷입니다.

### 조상 (MRO 내)

    * enum.Enum

### 클래스 변수

`DOCX`
:   결과를 Office Open XML 워드 처리 ML 문서(DOCX, 매크로 없음)로 저장합니다.

`EPUB`
:   문서를 EPUB 파일로 저장합니다.

`HTML`
:   문서를 HTML 파일로 저장합니다.

`JSON`
:   결과를 JavaScript 객체 표기법으로 작성된 일반 텍스트로 저장합니다.

`PDF`
:   결과를 PDF (Adobe Portable Document) 문서로 저장합니다.

`PDF_NO_IMG`
:   이미지를 제외한 검색 가능한 PDF (Adobe Portable Document) 문서로 저장합니다.

`RTF`
:   문서를 rtf 파일로 저장합니다.

`TEXT`
:   결과를 일반 텍스트 형식으로 저장합니다.

`XLSX`
:   결과를 Excel (2007 이후) 워크북 문서로 저장합니다.

`XML`
:   결과를 XML 문서로 저장합니다.

`ImageData(javaClass)`
:

### 조상 (MRO 내)

    * aspose.helper.BaseJavaClass

### Methods

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   처리/인식을 위한 이미지/문서 유형입니다.

### 조상 (MRO 내)

    * enum.Enum

### 클래스 변수

`BASE64`
:   이미지가 포함된 base64 문자열 또는 base64 내용이 들어 있는 .txt 파일 경로입니다. GIF, PNG, JPEG, BMP, TIFF를 지원합니다.

`DIRECTORY`
:   디렉터리 경로입니다. 중첩된 아카이브와 폴더는 지원되지 않습니다.
GIF, PNG, JPEG, BMP, TIFF를 지원합니다.
처리되는 이미지의 기본 수량은 모두입니다.

`PDF`
:   파일 또는 바이너리 배열에서 스캔한 PDF 문서.

`SINGLE_IMAGE`
:   GIF, PNG, JPEG, BMP, TIFF, JFIF, 바이너리 배열을 지원합니다.

`TIFF`
:   파일 또는 InputStream에서 다중 페이지 TIFF, TIF 문서.

`URL`
:   이미지에 대한 링크. GIF, PNG, JPEG, BMP, TIFF를 지원합니다.

`ZIP`
:   ZIP 압축 파일의 전체 이름. 중첩된 압축 파일 및 폴더는 지원되지 않습니다.
GIF, PNG, JPEG, BMP, TIFF, JFIF를 지원합니다.
처리되는 이미지의 기본 수량은 모두입니다.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   인식용 언어 모델.

### 조상 (MRO 내)

    * enum.Enum

### 클래스 변수

`BEL`
:   벨라루스 알파벳

`BUL`
:   불가리아 알파벳

`CHI`
:   중국어 알파벳

`CYRILLIC`
:   다중 언어(키릴 알파벳) 지원

`CZE`
:   체코 알파벳

`DAN`
:   덴마크 알파벳

`DEU`
:   독일어 알파벳

`DUM`
:   네덜란드어 알파벳

`ENG`
:   영어 알파벳

`EST`
:   에스토니아어 알파벳

`FIN`
:   핀란드어 알파벳

`FRA`
:   프랑스어 알파벳

`HIN`
:   힌디어 알파벳

`ITA`
:   이탈리아어 알파벳

`KAZ`
:   카자흐어 알파벳

`LATIN`
:   다중 언어(라틴 알파벳) 지원

`LAV`
:   라트비아어 알파벳

`LIT`
:   리투아니아어 알파벳

`NONE`
:   다중 언어 지원

`NOR`
:   노르웨이 알파벳

`POL`
:   폴란드 알파벳

`POR`
:   포르투갈 알파벳

`RUM`
:   루마니아 알파벳

`RUS`
:   러시아 알파벳

`SLK`
:   슬로바키아 알파벳

`SLV`
:   슬로베니아 알파벳

`SPA`
:   스페인 알파벳

`SRP`
:   세르비아 알파벳

`SRP_HRV`
:   세르보-크로아티아 알파벳

`SWE`
:   스웨덴 알파벳

`UKR`
:   우크라이나 알파벳

`ModelsConverter()`
:

### Methods

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   이미지를 수집하기 위한 메인 클래스입니다.
    
컨테이너를 생성하고 이미지/문서 유형 및 추가 처리/인식을 위한 필터를 설정하는 생성자입니다.
@param type: 컨테이너에 추가될 이미지/문서 유형을 설정합니다.
@param filters: 추가 처리 또는 인식을 위해 적용될 처리 필터를 설정합니다.

### Methods

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   인식/처리를 위한 이미지를 포함하는 경로나 URI를 추가합니다.
이미지의 유형은 생성자에서 지정한 유형과 일치해야 합니다.
@param fullPath: 이미지/문서/폴더/아카이브의 경로입니다.
@param startPage: 처리/인식을 위한 첫 페이지/이미지입니다. 문서, zip, 폴더에 사용합니다.
@param pagesNumber: 처리/인식을 위한 페이지/이미지의 총 개수입니다. 문서, zip, 폴더에 사용합니다. 기본값 = 전체.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   인식/처리를 위한 이미지를 포함하는 InputStream을 추가합니다.
이미지의 유형은 생성자에서 지정한 유형과 일치해야 합니다.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: 이미지 또는 문서를 포함합니다.
@param startPage: 처리/인식을 위한 첫 페이지/이미지입니다. 문서, zip, 폴더에 사용합니다.
@param pagesNumber: 처리/인식을 위한 페이지/이미지의 총 개수입니다. 문서, zip, 폴더에 사용합니다. 기본값 = 전체.

`add_base64(self, base64: str)`
:   이미지 인식/처리를 위한 base64 문자열을 추가합니다.
이미지의 유형은 생성자에서 지정한 유형과 일치해야 합니다.
@param base64: 단일 이미지가 포함된 Base64 문자열.

`clear(self)`
:   처리/인식 항목 수를 0으로 설정합니다.
컬렉션을 비웁니다.

`clear_filters(self)`
:   모든 필터를 제거합니다.

`get(self, index: int) ‑> models.ImageData`
:   처리/인식된 이미지에 대한 정보를 반환합니다.
@param index: 리스트에서 이미지의 위치.
@return: ImageData 객체.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   처리/인식을 위한 항목 수.
@return: 항목 수.

`PreprocessingFilter()`
:   이미지 처리 명령의 기본 클래스.

### 조상 (MRO 내)

    * aspose.helper.BaseJavaClass

### 클래스 변수

`JAVA_CLASS_NAME`
:

### Static methods

`auto_denoising()`
:   이미지를 개선하고 노이즈를 줄이기 위해 추가 신경망 사용을 활성화합니다.
스캔 아티팩트, 왜곡, 잡티, 플레어, 그라디언트, 외부 요소가 있는 이미지에 유용합니다.
@return: AutoDenoisingFilter 객체.

`auto_dewarping()`
:   이미지의 기하학적 왜곡을 자동으로 보정합니다.
매우 많은 리소스를 사용합니다!
@return: AutoDewarpingFilter 객체.

`auto_skew()`
:   자동 이미지 기울기 보정을 활성화합니다.
@return: AutoSkewFilter 객체.

`binarize()`
:   이미지를 흑백 이미지로 변환합니다.
이진 이미지는 픽셀이 두 가지 가능한 강도 값만 갖는 이미지입니다.
이들은 일반적으로 흑백으로 표시됩니다. 수치적으로 두 값은 보통 검은색은 0, 흰색은 255입니다.
이진 이미지는 자동 임계값 설정을 통해 생성됩니다.
@return: BinarizeFilter 객체.

`binarize_and_dilate()`
:   팽창은 이미지 내 객체 경계에 픽셀을 추가합니다.
@return: DilateFilter 객체.

`contrast_correction()`
:   대비 보정 필터.
@return: ContrastCorrectionFilter 객체.

`invert()`
:   문서 이미지의 색상을 자동으로 반전시킵니다.
@return: InvertFilter 객체.

`median()`
:   중앙값 필터는 이미지의 각 요소를 순회하며 각 픽셀을 주변 픽셀의 중앙값으로 교체합니다.
@return: MedianFilter 객체.

`resize(width: int, height: int)`
:   이미지를 재스케일합니다 - 해상도를 확대하거나 축소합니다.
@param width: 이미지의 새로운 너비.
@param height: 이미지의 새로운 높이.
@return: ResizeFilter 객체.

`rotate(angle: float)`
:   원본 이미지를 회전합니다.
@param angle: 회전 각도. 값은 -360에서 360 사이입니다.
@return: RotateFilter 객체.

`scale(ratio: float)`
:   이미지 크기를 재조정합니다 - 이미지 해상도를 확대하거나 축소합니다.
InterpolationFilterType bilinear 또는 nearest neighbor.
@param ratio: 스케일링 팩터. 축소하려면 0.1에서 1 사이, 확대하려면 1에서 10 사이의 값을 권장합니다.
@return: ScaleFilter 객체.

`threshold(value: int)`
:   원본 이미지의 픽셀 강도에 임계값을 설정하여 이진 이미지를 생성합니다.
@param value: 최대값.
@return: BinarizeFilter 객체.

`to_grayscale()`
:   이미지를 그레이스케일 이미지로 변환합니다.
그레이스케일 이미지는 이미지 내에 256 단계의 밝기를 가집니다 (0~255).
@return: GrayscaleFilter 객체.

### Methods

`add(self, filter)`
:   추가 전처리를 위해 필터를 컬렉션에 추가합니다.
@param filter: PreprocessingFilter 객체.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   추가 데이터를 포함한 맞춤법 오류 단어를 나타냅니다.

### 조상 (MRO 내)

    * aspose.helper.BaseJavaClass

### Methods

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   맞춤법 교정을 위한 사전 언어.

### 조상 (MRO 내)

    * enum.Enum

### 클래스 변수

`CZE`
:   체코어 사전

`DAN`
:   덴마크어 사전

`DEU`
:   독일어 사전

`DUM`
:   네덜란드어 사전

`ENG`
:   영어 사전

`EST`
:   에스토니아어 사전

`FIN`
:   핀란드어 사전

`FRA`
:   프랑스어 사전

`ITA`
:   이탈리아어 사전

`LAV`
:   라트비아어 사전

`LIT`
:   리투아니아어 사전

`POL`
:   폴란드어 사전

`POR`
:   포르투갈어 사전

`RUM`
:   루마니아어 사전

`SLK`
:   슬로바키아어 사전

`SLV`
:   슬로베니아어 사전

`SPA`
:   스페인어 사전

`SWE`
:   스웨덴어 사전

`SuggestedWord(javaClass)`
:   get_spell_check_error_list에서 반환된 맞춤법 제안.

### 조상 (MRO 내)

    * aspose.helper.BaseJavaClass

### Methods

`initParams(self)`
:


### 참고

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)