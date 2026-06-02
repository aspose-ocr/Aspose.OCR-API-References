---
title: "리소스"
second_title: "Aspose.OCR for Java API 레퍼런스"
description: "Aspose.OCR 인식 기능을 향상시키는 다운로드 가능한 리소스를 관리합니다"
type: docs
weight: 32
url: /ko/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Aspose.OCR 인식 기능을 향상시키는 다운로드 가능한 리소스를 관리합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Resources()](#Resources) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | 온라인 저장소에서 필요한 리소스의 자동 다운로드를 허용(true)하거나 차단(false)합니다. |
| [FetchAll()](#FetchAll) | 온라인 저장소에서 모든 호환 가능한 리소스를 다운로드합니다. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | 온라인 저장소에서 name 매개변수에 지정된 리소스를 다운로드합니다. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | 온라인 저장소에서 names 매개변수에 지정된 리소스들을 다운로드합니다. |
| [GetLocalPath()](#GetLocalPath) | 리소스가 다운로드될 디렉터리의 전체 경로를 반환합니다. |
| [GetRepository()](#GetRepository) | Aspose.OCR 리소스가 다운로드되는 온라인 저장소의 URL을 반환합니다. |
| [ListLocal()](#ListLocal) | 로컬 디렉터리에 저장된 모든 Aspose.OCR 리소스를 나열합니다. |
| [ListRemote()](#ListRemote) | 온라인 저장소에서 호환 가능한 모든 리소스를 나열합니다. |
| [ReleaseMemory()](#ReleaseMemory) | 메모리를 확보하기 위해 OCR 모듈을 언로드합니다. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | 로컬에 저장된 Aspose.OCR 리소스를 제거합니다. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | 리소스가 다운로드될 디렉터리의 절대 경로나 상대 경로를 지정합니다. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | 리소스가 다운로드될 디렉터리의 절대 경로나 상대 경로를 지정합니다. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Aspose.OCR 리소스가 다운로드될 온라인 저장소의 URL을 지정합니다. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


온라인 저장소에서 필요한 리소스의 자동 다운로드를 허용(true)하거나 차단(false)합니다. 기본적으로, 해당 리소스에 의존하는 메서드가 호출될 때 리소스가 자동으로 다운로드됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 허용 | java.lang.Boolean | 필요한 리소스의 자동 다운로드를 허용하거나 차단하기 위한 Boolean 값입니다. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


온라인 저장소에서 모든 호환 가능한 리소스를 다운로드합니다. 기존 리소스 파일은 덮어쓰기됩니다.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


온라인 저장소에서 name 매개변수에 지정된 리소스를 다운로드합니다. 이미 다운로드된 경우에는 덮어쓰기됩니다. .OCR 확장자를 생략하고 파일 이름만 사용할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 리소스 이름이 포함된 문자열입니다. ListRemote 메서드를 참조하십시오. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


온라인 저장소에서 names 매개변수에 지정된 리소스를 다운로드합니다. 하나 이상의 리소스가 이미 다운로드된 경우에는 덮어쓰기됩니다. .OCR 확장자를 생략하고 파일 이름만 사용할 수 있습니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| names | java.lang.String[] | 리소스 이름이 포함된 배열입니다. ListRemote 메서드를 참조하십시오. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


리소스가 다운로드될 디렉터리의 전체 경로를 반환합니다.

**Returns:**
java.lang.String - 리소스 디렉터리 경로를 포함하는 문자열입니다.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Aspose.OCR 리소스가 다운로드되는 온라인 저장소의 URL을 반환합니다.

**Returns:**
java.lang.String - 온라인 저장소의 URL입니다.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


로컬 디렉터리에 저장된 모든 Aspose.OCR 리소스를 나열합니다.

**Returns:**
java.util.List<java.lang.String> - 로컬 디렉터리에 저장된 모든 Aspose.OCR 리소스를 나열합니다.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


온라인 저장소에서 호환 가능한 모든 리소스를 나열합니다.

**Returns:**
java.util.List<java.lang.String> - 리소스 이름 목록.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


메모리를 확보하기 위해 OCR 모듈을 언로드합니다. 다운로드된 모듈 파일은 그대로 유지됩니다.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


로컬에 저장된 Aspose.OCR 리소스를 제거합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


리소스가 다운로드될 디렉터리의 절대 경로나 상대 경로를 지정합니다. 디렉터리가 존재하지 않으면 자동으로 생성됩니다. 기본적으로 리소스는 애플리케이션 작업 디렉터리의 aspose\_data 디렉터리에 다운로드됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 디렉터리의 절대 경로나 상대 경로. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


리소스가 다운로드될 디렉터리의 절대 경로나 상대 경로를 지정합니다. create 매개변수에 false를 전달하면 디렉터리가 자동으로 생성되는 것을 방지합니다. 제공된 디렉터리가 존재하지 않고 생성이 허용되지 않으면, 리소스는 애플리케이션 작업 디렉터리의 aspose\_data 디렉터리에 로드됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| path | java.lang.String | 디렉터리의 절대 경로나 상대 경로. |
| create | java.lang.Boolean | 디렉터리가 자동으로 생성되는 것을 방지하는 매개변수. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Aspose.OCR 리소스를 다운로드할 온라인 저장소의 URL을 지정합니다. 기본적으로 리소스는 https://github.com/aspose-ocr/resources/ 에서 다운로드됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| url | java.lang.String | 온라인 저장소의 URL. |


