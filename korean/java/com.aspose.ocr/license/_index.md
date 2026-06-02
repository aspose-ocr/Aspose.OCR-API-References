---
title: "라이선스"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "구성 요소에 라이선스를 적용하는 메서드를 제공합니다."
type: docs
weight: 21
url: /ko/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

구성 요소를 라이선스하는 메서드를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | 구성 요소에 라이선스를 적용합니다. |
| [isValid()](#isValid--) | 라이선스를 확인합니다. |
### License() {#License}
```
public License()
```


이 클래스의 새 인스턴스를 초기화합니다.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


구성 요소에 라이선스를 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseFile | java.io.File | 파일 경로 이름의 표현 |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


구성 요소에 라이선스를 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.InputStream | 라이선스를 포함하는 스트림입니다. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


구성 요소에 라이선스를 적용합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseFilePath | java.lang.String | 전체 파일 이름이거나 짧은 파일 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


라이선스를 확인합니다.

**Returns:**
boolean - 라이선스가 유효한지 여부를 나타내는 부울 값.
