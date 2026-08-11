---
title: "Resources"
linktitle: "Resources"
second_title: "Aspose.OCR for Python via Java"
description: "Manage downloadable resources that enhance Aspose.OCR recognition capabilities."
type: docs
weight: 10
url: /python-java/asposeocr/resources/
---

## Resources class

**Module:** `asposeocr`


Manage downloadable resources that enhance Aspose.OCR recognition capabilities.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [allow_automatic_downloads](#allow_automatic_downloads) |  | Yes | Allow (true) or block (false) automatic downloading of required resources from the online repository. By default, a resource is automatically downloaded when a method that depends on it is called. |
| [fetch_all](#fetch_all) |  | Yes | Download all compatible resources from the online repository. The existing resource files will be overwritten. |
| [fetch_resources](#fetch_resources) |  | Yes | Download the resources specified in the names parameter from the online repository. If one or more resources are already downloaded, they will be overwritten. You can omit the .OCR extension and use file names only. |
| [get_local_path](#get_local_path) |  | Yes | Return the full path to the directory where the resources will be downloaded. |
| [get_repository](#get_repository) |  | Yes | Return the URL of the online repository from which Aspose.OCR resources are downloaded. |
| [list_local](#list_local) | `[str]` | Yes | List all Aspose.OCR resources stored in the local directory. |
| [list_remote](#list_remote) | `[str]` | Yes | List all compatible resources from the online repository. |
| [set_local_path](#set_local_path) |  | Yes | Specify an absolute or relative path to the directory where the resources will be downloaded. Pass false to the create parameter to prevent the directory from being created automatically. If the provided directory does not exist and creation is not allowed, the resources will be loaded into the aspose_data directory in the application's working directory. |
| [set_repository](#set_repository) |  | Yes | Specify the URL of the online repository from which Aspose.OCR resources will be downloaded. By default, the resources are downloaded from https://github.com/aspose-ocr/resources/. |

### Resources Constructor {#constructor}

```python
__init__()
```

### Resources.allow_automatic_downloads (static) {#allow_automatic_downloads}

```python
allow_automatic_downloads(bool allow)
```

Allow (true) or block (false) automatic downloading of required resources from the online repository. By default, a resource is automatically downloaded when a method that depends on it is called.

| Parameter | Type | Description |
| --- | --- | --- |
| `allow` | `bool` | Boolean value to allow or block automatic downloading of required resources. |

### Resources.fetch_all (static) {#fetch_all}

```python
fetch_all()
```

Download all compatible resources from the online repository. The existing resource files will be overwritten.

### Resources.fetch_resources (static) {#fetch_resources}

```python
fetch_resources([] names)
```

Download the resources specified in the names parameter from the online repository. If one or more resources are already downloaded, they will be overwritten. You can omit the .OCR extension and use file names only.

| Parameter | Type | Description |
| --- | --- | --- |
| `names` | `[]` | Array with resources names. See the ListRemote method. |

### Resources.get_local_path (static) {#get_local_path}

```python
get_local_path()
```

Return the full path to the directory where the resources will be downloaded.

### Resources.get_repository (static) {#get_repository}

```python
get_repository()
```

Return the URL of the online repository from which Aspose.OCR resources are downloaded.

### Resources.list_local (static) {#list_local}

```python
list_local() -> [str]
```

List all Aspose.OCR resources stored in the local directory.

**Return Type:** `[str]` — List all Aspose.OCR resources stored in the local directory.

### Resources.list_remote (static) {#list_remote}

```python
list_remote() -> [str]
```

List all compatible resources from the online repository.

**Return Type:** `[str]` — List of resources names.

### Resources.set_local_path (static) {#set_local_path}

```python
set_local_path(str path, bool create)
```

Specify an absolute or relative path to the directory where the resources will be downloaded. Pass false to the create parameter to prevent the directory from being created automatically. If the provided directory does not exist and creation is not allowed, the resources will be loaded into the aspose_data directory in the application's working directory.

| Parameter | Type | Description |
| --- | --- | --- |
| `path` | `str` | Absolute or relative path to the directory. |
| `create` | `bool` | Parameter to prevent the directory from being created automatically. |

### Resources.set_repository (static) {#set_repository}

```python
set_repository(str url)
```

Specify the URL of the online repository from which Aspose.OCR resources will be downloaded. By default, the resources are downloaded from https://github.com/aspose-ocr/resources/.

| Parameter | Type | Description |
| --- | --- | --- |
| `url` | `str` | URL of the online repository. |

