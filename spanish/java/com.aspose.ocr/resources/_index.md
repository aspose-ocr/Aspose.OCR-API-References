---
title: "Recursos"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Administre recursos descargables que mejoran las capacidades de reconocimiento de Aspose.OCR"
type: docs
weight: 32
url: /es/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Administre recursos descargables que mejoren las capacidades de reconocimiento de Aspose.OCR.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Resources()](#Resources) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Permitir (true) o bloquear (false) la descarga automática de recursos requeridos del repositorio en línea. |
| [FetchAll()](#FetchAll) | Descargue todos los recursos compatibles del repositorio en línea. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Descargue el recurso especificado en el parámetro name del repositorio en línea. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Descargue los recursos especificados en el parámetro names del repositorio en línea. |
| [GetLocalPath()](#GetLocalPath) | Devuelva la ruta completa al directorio donde se descargarán los recursos. |
| [GetRepository()](#GetRepository) | Devuelva la URL del repositorio en línea desde el cual se descargan los recursos de Aspose.OCR. |
| [ListLocal()](#ListLocal) | Enumere todos los recursos de Aspose.OCR almacenados en el directorio local. |
| [ListRemote()](#ListRemote) | Enumere todos los recursos compatibles del repositorio en línea. |
| [ReleaseMemory()](#ReleaseMemory) | Descargue los módulos OCR para liberar memoria. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Elimina el recurso Aspose.OCR almacenado localmente. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Especifique una ruta absoluta o relativa al directorio donde se descargarán los recursos. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Especifique una ruta absoluta o relativa al directorio donde se descargarán los recursos. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Especifique la URL del repositorio en línea desde el cual se descargarán los recursos de Aspose.OCR. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Permita (true) o bloquee (false) la descarga automática de los recursos requeridos del repositorio en línea. Por defecto, un recurso se descarga automáticamente cuando se llama a un método que depende de él.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| permitir | java.lang.Boolean | Valor booleano para permitir o bloquear la descarga automática de los recursos requeridos. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Descargue todos los recursos compatibles del repositorio en línea. Los archivos de recursos existentes se sobrescribirán.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Descargue el recurso especificado en el parámetro name del repositorio en línea. Si el recurso ya está descargado, se sobrescribirá. Puede omitir la extensión .OCR y usar solo el nombre del archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Cadena con el nombre del recurso. Vea el método ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Descargue los recursos especificados en el parámetro names del repositorio en línea. Si uno o más recursos ya están descargados, se sobrescribirán. Puede omitir la extensión .OCR y usar solo los nombres de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| names | java.lang.String[] | Arreglo con los nombres de los recursos. Vea el método ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Devuelva la ruta completa al directorio donde se descargarán los recursos.

**Returns:**
java.lang.String - Cadena con la ruta al directorio de recursos.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Devuelva la URL del repositorio en línea desde el cual se descargan los recursos de Aspose.OCR.

**Returns:**
java.lang.String - URL del repositorio en línea.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Enumere todos los recursos de Aspose.OCR almacenados en el directorio local.

**Returns:**
java.util.List<java.lang.String> - Enumere todos los recursos de Aspose.OCR almacenados en el directorio local.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Enumere todos los recursos compatibles del repositorio en línea.

**Returns:**
java.util.List<java.lang.String> - Lista de nombres de recursos.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Descargar los módulos OCR para liberar memoria. Los archivos de módulos descargados permanecerán intactos.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Elimina el recurso Aspose.OCR almacenado localmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Especifique una ruta absoluta o relativa al directorio donde se descargarán los recursos. Si el directorio no existe, se creará automáticamente. Por defecto, los recursos se descargan en el directorio aspose\_data del directorio de trabajo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | Ruta absoluta o relativa al directorio. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Especifique una ruta absoluta o relativa al directorio donde se descargarán los recursos. Pase false al parámetro create para evitar que el directorio se cree automáticamente. Si el directorio proporcionado no existe y no se permite su creación, los recursos se cargarán en el directorio aspose\_data del directorio de trabajo de la aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | Ruta absoluta o relativa al directorio. |
| create | java.lang.Boolean | Parámetro para evitar que el directorio se cree automáticamente. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Especifique la URL del repositorio en línea desde el cual se descargarán los recursos de **Aspose.OCR**. Por defecto, los recursos se descargan de https://github.com/aspose-ocr/resources/.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del repositorio en línea. |


