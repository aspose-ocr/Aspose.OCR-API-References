---
title: "Resources"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 360
url: /es/python-net/aspose.ocr/resources/
---

## Resources class

Gestiona los recursos descargables que mejoran las capacidades de reconocimiento de Aspose.OCR.

El tipo Resources expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Resources() | Inicializa una nueva instancia de la clase Resources |
## Methods
| Nombre | Descripción |
| :- | :- |
| set_local_path(path) | Especifica una ruta absoluta o relativa al directorio donde se descargarán los recursos.<br/>            Si el directorio no existe, se creará automáticamente.<br/>            Por defecto, los recursos se descargan al directorio aspose_data en el directorio de trabajo de la aplicación. |
| set_local_path(path, create) | Especifica una ruta absoluta o relativa al directorio donde se descargarán los recursos.<br/>            Pasa `false` al parámetro `create` para evitar que el directorio se cree automáticamente.<br/>            Si el directorio proporcionado no existe y no se permite su creación, los recursos se cargarán en el directorio aspose_data en el directorio de trabajo de la aplicación. |
| set_repository(url) | Especifique la URL del repositorio en línea desde el cual se descargarán los recursos de Aspose.OCR.<br/>            Por defecto, los recursos se descargan de https://github.com/aspose-ocr/resources/. |
| get_repository() | Devuelve la URL del repositorio en línea desde el cual se descargan los recursos de Aspose.OCR. |
| list_remote() | Enumera todos los recursos compatibles del repositorio en línea. |
| get_local_path() | Devuelve la ruta completa al directorio donde se descargarán los recursos. |
| list_local() | Enumera todos los recursos de Aspose.OCR almacenados en el directorio local. |
| allow_automatic_downloads(allow) | Permite (true) o bloquea (false) la descarga automática de los recursos requeridos del repositorio en línea.<br/>             Por defecto, un recurso se descarga automáticamente cuando se llama a un método que depende de él. |
| fetch_resources(names) | Descarga los recursos especificados en el parámetro `names` del repositorio en línea. Si uno o más recursos ya están descargados, se sobrescribirán.<br/>            Puede omitir la extensión .OCR y usar solo los nombres de archivo. |
| fetch_resource(name) | Descarga los recursos especificados en el parámetro `names` del repositorio en línea. Si uno o más recursos ya están descargados, se sobrescribirán.<br/>            Puede omitir la extensión .OCR y usar solo los nombres de archivo. |
| fetch_all() | Descarga todos los recursos compatibles del repositorio en línea. Los archivos de recursos existentes se sobrescribirán. |
| remove_local(name) | Elimina el recurso Aspose.OCR almacenado localmente. |
| release_memory() |  |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

