---
title: "Resources Class"
linktitle: "Resources"
articleTitle: "Resources"
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
| [__init__](./resources/) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [allow_automatic_downloads](./allow_automatic_downloads/) |  | Yes | Allow (true) or block (false) automatic downloading of required resources from the online repository. By default, a resource is automatically downloaded when a method that depends on it is called. |
| [fetch_all](./fetch_all/) |  | Yes | Download all compatible resources from the online repository. The existing resource files will be overwritten. |
| [fetch_resources](./fetch_resources/) |  | Yes | Download the resources specified in the names parameter from the online repository. If one or more resources are already downloaded, they will be overwritten. You can omit the .OCR extension and use file names only. |
| [get_local_path](./get_local_path/) |  | Yes | Return the full path to the directory where the resources will be downloaded. |
| [get_repository](./get_repository/) |  | Yes | Return the URL of the online repository from which Aspose.OCR resources are downloaded. |
| [list_local](./list_local/) | `[str]` | Yes | List all Aspose.OCR resources stored in the local directory. |
| [list_remote](./list_remote/) | `[str]` | Yes | List all compatible resources from the online repository. |
| [set_local_path](./set_local_path/) |  | Yes | Specify an absolute or relative path to the directory where the resources will be downloaded. Pass false to the create parameter to prevent the directory from being created automatically. If the provided directory does not exist and creation is not allowed, the resources will be loaded into the aspose_data directory in the application's working directory. |
| [set_repository](./set_repository/) |  | Yes | Specify the URL of the online repository from which Aspose.OCR resources will be downloaded. By default, the resources are downloaded from https://github.com/aspose-ocr/resources/. |
