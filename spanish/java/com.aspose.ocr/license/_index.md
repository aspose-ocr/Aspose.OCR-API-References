---
title: "Licencia"
second_title: "Referencia de API de Aspose.OCR para Java"
description: "Proporciona métodos para licenciar el componente"
type: docs
weight: 21
url: /es/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Proporciona métodos para licenciar el componente.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [License()](#License) | Inicializa una nueva instancia de esta clase. |
## Métodos

| Método | Descripción |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Licencia el componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Licencia el componente. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Licencia el componente. |
| [isValid()](#isValid--) | Verificar licencia. |
### License() {#License}
```
public License()
```


Inicializa una nueva instancia de esta clase.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Licencia el componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseFile | java.io.File | representación de la ruta del archivo |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Licencia el componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Un flujo que contiene la licencia. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Licencia el componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Puede ser un nombre de archivo completo o corto. Use una cadena vacía para cambiar al modo de evaluación. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Verificar licencia.

**Returns:**
boolean - Valor booleano que indica si la licencia es válida.
