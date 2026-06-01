---
title: "Licenza"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Fornisce metodi per licenziare il componente."
type: docs
weight: 21
url: /it/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Fornisce metodi per licenziare il componente.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License) | Inizializza una nuova istanza di questa classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Licenzia il componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Licenzia il componente. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Licenzia il componente. |
| [isValid()](#isValid--) | Verifica licenza. |
### License() {#License}
```
public License()
```


Inizializza una nuova istanza di questa classe.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Licenzia il componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseFile | java.io.File | rappresentazione del percorso del file |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Licenzia il componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Uno stream che contiene la licenza. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Licenzia il componente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Può essere un nome file completo o breve. Usa una stringa vuota per passare alla modalità di valutazione. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Verifica licenza.

**Returns:**
boolean - Valore booleano che indica se la licenza è valida.
