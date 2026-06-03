---
title: "Resources"
second_title: "Aspose.OCR for Python via .NET API Reference"
description: 
type: docs
weight: 360
url: /ko/python-net/aspose.ocr/resources/
---

## Resources class

Aspose.OCR 인식 기능을 향상시키는 다운로드 가능한 리소스를 관리합니다.

Resources 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Resources() | Resources 클래스의 새 인스턴스를 초기화합니다. |
## Methods
| 이름 | 설명 |
| :- | :- |
| set_local_path(path) | 리소스가 다운로드될 디렉터리의 절대 경로나 상대 경로를 지정합니다.<br/>            디렉터리가 존재하지 않으면 자동으로 생성됩니다.<br/>            기본적으로 리소스는 애플리케이션 작업 디렉터리의 aspose_data 디렉터리에 다운로드됩니다. |
| set_local_path(path, create) | 리소스가 다운로드될 디렉터리의 절대 경로나 상대 경로를 지정합니다.<br/>            `create` 매개변수에 `false`를 전달하면 디렉터리가 자동으로 생성되는 것을 방지합니다.<br/>            제공된 디렉터리가 존재하지 않고 생성이 허용되지 않으면, 리소스는 애플리케이션 작업 디렉터리의 aspose_data 디렉터리에 로드됩니다. |
| set_repository(url) | Aspose.OCR 리소스를 다운로드할 온라인 저장소의 URL을 지정합니다.<br/>            기본적으로 리소스는 https://github.com/aspose-ocr/resources/ 에서 다운로드됩니다. |
| get_repository() | Aspose.OCR 리소스가 다운로드되는 온라인 저장소의 URL을 반환합니다. |
| list_remote() | 온라인 저장소에서 호환 가능한 모든 리소스를 나열합니다. |
| get_local_path() | 리소스가 다운로드될 디렉터리의 전체 경로를 반환합니다. |
| list_local() | 로컬 디렉터리에 저장된 모든 Aspose.OCR 리소스를 나열합니다. |
| allow_automatic_downloads(allow) | 필요한 리소스를 온라인 저장소에서 자동으로 다운로드하도록 허용(true)하거나 차단(false)합니다.<br/>             기본적으로 해당 리소스에 의존하는 메서드가 호출될 때 리소스가 자동으로 다운로드됩니다. |
| fetch_resources(names) | `names` 매개변수에 지정된 리소스를 온라인 저장소에서 다운로드합니다. 하나 이상의 리소스가 이미 다운로드된 경우 해당 파일이 덮어쓰기됩니다.<br/>            .OCR 확장자를 생략하고 파일 이름만 사용할 수 있습니다. |
| fetch_resource(name) | `names` 매개변수에 지정된 리소스를 온라인 저장소에서 다운로드합니다. 하나 이상의 리소스가 이미 다운로드된 경우 해당 파일이 덮어쓰기됩니다.<br/>            .OCR 확장자를 생략하고 파일 이름만 사용할 수 있습니다. |
| fetch_all() | 온라인 저장소에서 호환 가능한 모든 리소스를 다운로드합니다. 기존 리소스 파일은 덮어쓰기됩니다. |
| remove_local(name) | 로컬에 저장된 Aspose.OCR 리소스를 제거합니다. |
| release_memory() |  |

### 참조

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

