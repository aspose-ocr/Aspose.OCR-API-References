---
title: Metered
second_title: Aspose.OCR for Java API Reference
description: Provides methods to set metered key
type: docs
weight: 10
url: /java/com.aspose.ocr.metered/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods to set metered key.
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered) | Initializes a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [getConsumptionCredit()](#getConsumptionCredit) | Gets consumption credit |
| [getConsumptionQuantity()](#getConsumptionQuantity) | Gets consumption file size |
| [getProductName()](#getProductName) | Gets Product name |
| [isMeteredLicensed()](#isMeteredLicensed) | Check whether metered is licensed |
| [resetMeteredLicense()](#resetMeteredLicense) | Resets metered license state and switches metered licensing to evaluation mode. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String) | Sets metered public and private key. |

### Metered() {#Metered}
```
public Metered()
```


Initializes a new instance of this class.
### getConsumptionCredit() {#getConsumptionCredit}
```
public static double getConsumptionCredit()
```


Gets consumption credit

**Returns:**
double - consumption quantity
### getConsumptionQuantity() {#getConsumptionQuantity}
```
public static double getConsumptionQuantity()
```


Gets consumption file size

**Returns:**
double - consumption quantity
### getProductName() {#getProductName}
```
public String getProductName()
```


Gets Product name

**Returns:**
java.lang.String - Product name

### isMeteredLicensed() {#isMeteredLicensed}
```
public static boolean isMeteredLicensed()
```


Check whether metered is licensed

**Returns:**
boolean - True or false name




### resetMeteredLicense() {#resetMeteredLicense}
```
public static void resetMeteredLicense()
```


Resets metered license state and switches metered licensing to evaluation mode.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String |  |
| privateKey | java.lang.String |  |