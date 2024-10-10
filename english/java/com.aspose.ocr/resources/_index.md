---
title: Resources
second_title: Aspose.OCR for Java API Reference
description: Manage downloadable resources that enhance Aspose.OCR recognition capabilities
type: docs
weight: 30
url: /java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Manage downloadable resources that enhance Aspose.OCR recognition capabilities.
## Constructors

| Constructor | Description |
| --- | --- |
| [Resources()](#Resources) |  |
## Methods

| Method | Description |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Allow (true) or block (false) automatic downloading of required resources from the online repository. |
| [FetchAll()](#FetchAll) | Download all compatible resources from the online repository. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Download the resource specified in the name parameter from the online repository. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Download the resources specified in the names parameter from the online repository. |
| [GetLocalPath()](#GetLocalPath) | Return the full path to the directory where the resources will be downloaded. |
| [GetRepository()](#GetRepository) | Return the URL of the online repository from which Aspose.OCR resources are downloaded. |
| [ListLocal()](#ListLocal) | List all Aspose.OCR resources stored in the local directory. |
| [ListRemote()](#ListRemote) | List all compatible resources from the online repository. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Removes the locally stored Aspose.OCR resource. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Specify an absolute or relative path to the directory where the resources will be downloaded. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Specify an absolute or relative path to the directory where the resources will be downloaded. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Specify the URL of the online repository from which Aspose.OCR resources will be downloaded. |
| [equals(Object arg0)](#equals-java.lang.Object) |  |
| [getClass()](#getClass) |  |
| [hashCode()](#hashCode) |  |
| [notify()](#notify) |  |
| [notifyAll()](#notifyAll) |  |
| [toString()](#toString) |  |
| [wait()](#wait) |  |
| [wait(long arg0)](#wait-long) |  |
| [wait(long arg0, int arg1)](#wait-long-int) |  |
### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Allow (true) or block (false) automatic downloading of required resources from the online repository. By default, a resource is automatically downloaded when a method that depends on it is called.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allow | java.lang.Boolean | Boolean value to allow or block automatic downloading of required resources. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Download all compatible resources from the online repository. The existing resource files will be overwritten.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Download the resource specified in the name parameter from the online repository. If the resource is already downloaded, it will be overwritten. You can omit the .OCR extension and use file name only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | String with resource name. See the ListRemote method. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Download the resources specified in the names parameter from the online repository. If one or more resources are already downloaded, they will be overwritten. You can omit the .OCR extension and use file names only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| names | java.lang.String[] | Array with resources names. See the ListRemote method. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Return the full path to the directory where the resources will be downloaded.

**Returns:**
java.lang.String - String with the path to the resources directory.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Return the URL of the online repository from which Aspose.OCR resources are downloaded.

**Returns:**
java.lang.String - URL of the online repository.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


List all Aspose.OCR resources stored in the local directory.

**Returns:**
java.util.List<java.lang.String> - List all Aspose.OCR resources stored in the local directory.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


List all compatible resources from the online repository.

**Returns:**
java.util.List<java.lang.String> - List of resources names.
### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Removes the locally stored Aspose.OCR resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Specify an absolute or relative path to the directory where the resources will be downloaded. If the directory does not exist, it will be created automatically. By default, the resources are downloaded to aspose\_data directory in the application's working directory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Absolute or relative path to the directory. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Specify an absolute or relative path to the directory where the resources will be downloaded. Pass false to the create parameter to prevent the directory from being created automatically. If the provided directory does not exist and creation is not allowed, the resources will be loaded into the aspose\_data directory in the application's working directory.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Absolute or relative path to the directory. |
| create | java.lang.Boolean | Parameter to prevent the directory from being created automatically. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Specify the URL of the online repository from which Aspose.OCR resources will be downloaded. By default, the resources are downloaded from https://github.com/aspose-ocr/resources/.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL of the online repository. |

### equals(Object arg0) {#equals-java.lang.Object}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify}
```
public final native void notify()
```




### notifyAll() {#notifyAll}
```
public final native void notifyAll()
```




### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait}
```
public final void wait()
```




### wait(long arg0) {#wait-long}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

