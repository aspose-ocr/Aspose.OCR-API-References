---
title: Resources
second_title: Aspose.OCR for Python via .NET API Reference
description: 
type: docs
weight: 380
url: /python-net/aspose.ocr/resources/
---

## Resources class

Manage downloadable resources that enhance Aspose.OCR recognition capabilities.

The Resources type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Resources()|Initializes a new instance of the Resources class|
## Methods
| Name | Description |
| :- | :- |
|set_local_path(path)|Specify an absolute or relative path to the directory where the resources will be downloaded.<br/>            If the directory does not exist, it will be created automatically.<br/>            By default, the resources are downloaded to aspose_data directory in the application's working directory.|
|set_local_path(path, create)|Specify an absolute or relative path to the directory where the resources will be downloaded.<br/>            Pass `false` to the `create` parameter to prevent the directory from being created automatically.<br/>            If the provided directory does not exist and creation is not allowed, the resources will be loaded into the aspose_data directory in the application's working directory.|
|set_repository(url)|Specify the URL of the online repository from which Aspose.OCR resources will be downloaded.<br/>            By default, the resources are downloaded from https://github.com/aspose-ocr/resources/.|
|get_repository()|Return the URL of the online repository from which Aspose.OCR resources are downloaded.|
|list_remote()|List all compatible resources from the online repository.|
|get_local_path()|Return the full path to the directory where the resources will be downloaded.|
|list_local()|List all Aspose.OCR resources stored in the local directory.|
|allow_automatic_downloads(allow)|Allow (true) or block (false) automatic downloading of required resources from the online repository.<br/>             By default, a resource is automatically downloaded when a method that depends on it is called.|
|fetch_resources(names)|Download the resources specified in the `names` parameter from the online repository. If one or more resources are already downloaded, they will be overwritten.<br/>            You can omit the .OCR extension and use file names only.|
|fetch_resource(name)|Download the resources specified in the `names` parameter from the online repository. If one or more resources are already downloaded, they will be overwritten.<br/>            You can omit the .OCR extension and use file names only.|
|fetch_all()|Download all compatible resources from the online repository. The existing resource files will be overwritten.|
|remove_local(name)|Removes the locally stored Aspose.OCR resource.|
|release_memory()|Unload OCR modules to free up memory. The downloaded module files will remain intact.|

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

