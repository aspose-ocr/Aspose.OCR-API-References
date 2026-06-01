---
title: "DefectType"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "画像欠陥の種類"
type: docs
weight: 22
url: /ja/java/com.aspose.ocr.models/defecttype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DefectType extends Enum<DefectType>
```

画像欠陥のタイプ。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ALL](#ALL) | サポートされているすべての画像欠陥。 |
| [BLUR](#BLUR) | 画像がピントが合っていません。 |
| [GLARE](#GLARE) | スポットライトやフラッシュなど、不均一な照明によって画像内に生じる領域。 |
| [LOW_CONTRAST](#LOW-CONTRAST) | 曲がったページに通常現れるハイライトとシャドウ。 |
| [SALT_PEPPER_NOISE](#SALT-PEPPER-NOISE) | 領域全体に散在するランダムな白黒ピクセル。 |

### ALL {#ALL}
```
public static final DefectType ALL
```


サポートされているすべての画像欠陥。

### BLUR {#BLUR}
```
public static final DefectType BLUR
```


画像がピントが合っていません。この検出アルゴリズムは画像全体がぼやけていることしか識別できず、特定の領域は検出できません。

### GLARE {#GLARE}
```
public static final DefectType GLARE
```


スポットライトやフラッシュなど、不均一な照明によって画像内に生じる領域。

### LOW_CONTRAST {#LOW-CONTRAST}
```
public static final DefectType LOW_CONTRAST
```


曲がったページに通常現れるハイライトとシャドウ。

### SALT_PEPPER_NOISE {#SALT-PEPPER-NOISE}
```
public static final DefectType SALT_PEPPER_NOISE
```


領域全体に散在するランダムな白黒ピクセル。デジタル写真で頻繁に発生します。

