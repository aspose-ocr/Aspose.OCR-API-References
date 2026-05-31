---
title: "Ressources"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Gérez les ressources téléchargeables qui améliorent les capacités de reconnaissance d'Aspose.OCR"
type: docs
weight: 32
url: /fr/java/com.aspose.ocr/resources/
---

**Inheritance:**
java.lang.Object
```
public class Resources
```

Gérez les ressources téléchargeables qui améliorent les capacités de reconnaissance d'Aspose.OCR.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Resources()](#Resources) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [AllowAutomaticDownloads(Boolean allow)](#AllowAutomaticDownloads-java.lang.Boolean) | Autorisez (true) ou bloquez (false) le téléchargement automatique des ressources requises depuis le référentiel en ligne. |
| [FetchAll()](#FetchAll) | Téléchargez toutes les ressources compatibles depuis le référentiel en ligne. |
| [FetchResource(String name)](#FetchResource-java.lang.String) | Télécharger la ressource spécifiée dans le paramètre name depuis le référentiel en ligne. |
| [FetchResources(String[] names)](#FetchResources-java.lang.String) | Télécharger les ressources spécifiées dans le paramètre names depuis le référentiel en ligne. |
| [GetLocalPath()](#GetLocalPath) | Retourner le chemin complet du répertoire où les ressources seront téléchargées. |
| [GetRepository()](#GetRepository) | Retourner l'URL du référentiel en ligne depuis lequel les ressources Aspose.OCR sont téléchargées. |
| [ListLocal()](#ListLocal) | Lister toutes les ressources Aspose.OCR stockées dans le répertoire local. |
| [ListRemote()](#ListRemote) | Lister toutes les ressources compatibles du référentiel en ligne. |
| [ReleaseMemory()](#ReleaseMemory) | Décharger les modules OCR pour libérer de la mémoire. |
| [RemoveLocal(String name)](#RemoveLocal-java.lang.String) | Supprime la ressource Aspose.OCR stockée localement. |
| [SetLocalPath(String path)](#SetLocalPath-java.lang.String) | Spécifier un chemin absolu ou relatif vers le répertoire où les ressources seront téléchargées. |
| [SetLocalPath(String path, Boolean create)](#SetLocalPath-java.lang.String-java.lang.Boolean) | Spécifier un chemin absolu ou relatif vers le répertoire où les ressources seront téléchargées. |
| [SetRepository(String url)](#SetRepository-java.lang.String) | Spécifier l'URL du référentiel en ligne depuis lequel les ressources Aspose.OCR seront téléchargées. |

### Resources() {#Resources}
```
public Resources()
```


### AllowAutomaticDownloads(Boolean allow) {#AllowAutomaticDownloads-java.lang.Boolean}
```
public static void AllowAutomaticDownloads(Boolean allow)
```


Autoriser (true) ou bloquer (false) le téléchargement automatique des ressources requises depuis le référentiel en ligne. Par défaut, une ressource est téléchargée automatiquement lorsqu'une méthode qui en dépend est appelée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autoriser | java.lang.Boolean | Valeur booléenne pour autoriser ou bloquer le téléchargement automatique des ressources requises. |

### FetchAll() {#FetchAll}
```
public static void FetchAll()
```


Télécharger toutes les ressources compatibles du référentiel en ligne. Les fichiers de ressources existants seront écrasés.

### FetchResource(String name) {#FetchResource-java.lang.String}
```
public static void FetchResource(String name)
```


Télécharger la ressource spécifiée dans le paramètre name depuis le référentiel en ligne. Si la ressource est déjà téléchargée, elle sera écrasée. Vous pouvez omettre l'extension .OCR et n'utiliser que le nom de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Chaîne contenant le nom de la ressource. Voir la méthode ListRemote. |

### FetchResources(String[] names) {#FetchResources-java.lang.String}
```
public static void FetchResources(String[] names)
```


Télécharger les ressources spécifiées dans le paramètre names depuis le référentiel en ligne. Si une ou plusieurs ressources sont déjà téléchargées, elles seront écrasées. Vous pouvez omettre l'extension .OCR et n'utiliser que les noms de fichiers.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| names | java.lang.String[] | Tableau contenant les noms des ressources. Voir la méthode ListRemote. |

### GetLocalPath() {#GetLocalPath}
```
public static String GetLocalPath()
```


Retourner le chemin complet du répertoire où les ressources seront téléchargées.

**Returns:**
java.lang.String - Chaîne contenant le chemin du répertoire des ressources.
### GetRepository() {#GetRepository}
```
public static String GetRepository()
```


Retourner l'URL du référentiel en ligne depuis lequel les ressources Aspose.OCR sont téléchargées.

**Returns:**
java.lang.String - URL du référentiel en ligne.
### ListLocal() {#ListLocal}
```
public static List<String> ListLocal()
```


Lister toutes les ressources Aspose.OCR stockées dans le répertoire local.

**Returns:**
java.util.List<java.lang.String> - Lister toutes les ressources Aspose.OCR stockées dans le répertoire local.
### ListRemote() {#ListRemote}
```
public static List<String> ListRemote()
```


Lister toutes les ressources compatibles du référentiel en ligne.

**Returns:**
java.util.List<java.lang.String> - Liste des noms de ressources.
### ReleaseMemory() {#ReleaseMemory}
```
public static void ReleaseMemory()
```


Décharger les modules OCR pour libérer de la mémoire. Les fichiers de modules téléchargés resteront intacts.

### RemoveLocal(String name) {#RemoveLocal-java.lang.String}
```
public static void RemoveLocal(String name)
```


Supprime la ressource Aspose.OCR stockée localement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

### SetLocalPath(String path) {#SetLocalPath-java.lang.String}
```
public static void SetLocalPath(String path)
```


Spécifiez un chemin absolu ou relatif vers le répertoire où les ressources seront téléchargées. Si le répertoire n'existe pas, il sera créé automatiquement. Par défaut, les ressources sont téléchargées dans le répertoire aspose\_data du répertoire de travail de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Chemin absolu ou relatif vers le répertoire. |

### SetLocalPath(String path, Boolean create) {#SetLocalPath-java.lang.String-java.lang.Boolean}
```
public static void SetLocalPath(String path, Boolean create)
```


Spécifiez un chemin absolu ou relatif vers le répertoire où les ressources seront téléchargées. Passez false au paramètre create pour empêcher la création automatique du répertoire. Si le répertoire fourni n'existe pas et que la création n'est pas autorisée, les ressources seront chargées dans le répertoire aspose\_data du répertoire de travail de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Chemin absolu ou relatif vers le répertoire. |
| create | java.lang.Boolean | Paramètre pour empêcher la création automatique du répertoire. |

### SetRepository(String url) {#SetRepository-java.lang.String}
```
public static void SetRepository(String url)
```


Spécifiez l'URL du dépôt en ligne à partir duquel les ressources Aspose.OCR seront téléchargées. Par défaut, les ressources sont téléchargées depuis https://github.com/aspose-ocr/resources/.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du dépôt en ligne. |


