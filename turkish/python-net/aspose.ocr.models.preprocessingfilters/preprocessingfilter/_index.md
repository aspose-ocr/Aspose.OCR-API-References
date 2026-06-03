---
title: "PreprocessingFilter"
second_title: "Aspose.OCR Python için .NET API Referansı"
description: 
type: docs
weight: 10
url: /tr/python-net/aspose.ocr.models.preprocessingfilters/preprocessingfilter/
---

## PreprocessingFilter class

Görüntü işleme komutları için temel sınıf.

PreprocessingFilter türü aşağıdaki üyeleri içerir:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PreprocessingFilter() | PreprocessingFilter sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| varsayılan | Varsayılan filtre koleksiyonu AutoSkew filtresini içerir |
| empty | Boş filtre koleksiyonu |
## Methods
| Ad | Açıklama |
| :- | :- |
| binarize() | Görüntüyü siyah-beyaz görüntüye dönüştürür.<br/>            İkili görüntüler, piksellerinin yalnızca iki olası yoğunluk değerine sahip olduğu görüntülerdir. <br/>            Normalde siyah ve beyaz olarak gösterilirler. Sayısal olarak, iki değer genellikle siyah için 0, beyaz için 255'tir.<br/>            İkili görüntüler, bir görüntünün otomatik eşikleme ile üretilir. |
| binarize(area) | Bir görüntünün bir bölümünü siyah-beyaz görüntüye dönüştürür.<br/>            İkili görüntüler, piksellerinin yalnızca iki olası yoğunluk değerine sahip olduğu görüntülerdir. <br/>            Normalde siyah ve beyaz olarak gösterilirler. Sayısal olarak, iki değer genellikle siyah için 0, beyaz için 255'tir.<br/>            İkili görüntüler, bir görüntünün otomatik eşikleme ile üretilir. |
| resize(width, height, type) | Görüntüyü yeniden ölçeklendir - Görüntü çözünürlüğünü artırır veya azaltır. |
| resize(width, height) | Görüntüyü yeniden ölçeklendir - Görüntü çözünürlüğünü artırır veya azaltır. |
| dilate() | Genişletme, bir görüntüdeki nesnelerin sınırlarına piksel ekler. |
| dilate(area) | Genişletme, görüntünün bir bölümündeki nesnelerin sınırlarına piksel ekler. |
| invert() | Belge görüntüsündeki renkleri otomatik olarak tersine çevirir. |
| invert(area) | Görüntünün bir bölümündeki renkleri otomatik olarak tersine çevirir. |
| rotate(angle) | Orijinal görüntüyü döndür. |
| rotate(angle, area) | Görüntünün bir bölümünü döndür. |
| scale(ratio) | Görüntüyü yeniden ölçekle - Görüntü çözünürlüğünü artır veya azalt.<br/>            InterpolationFilterType = Lanczos8 |
| scale(ratio, type) | Görüntüyü yeniden ölçeklendir - Görüntü çözünürlüğünü artırır veya azaltır. |
| threshold(value) | Orijinal görüntünün piksel yoğunluğuna bir eşik değeri ayarlayarak ikili bir görüntü oluştur. |
| threshold(value, area) | Orijinal görüntü parçasının piksel yoğunluğuna bir eşik değeri ayarlayarak görüntünün ikili bir bölümünü oluştur. |
| median() | Median filtresi görüntünün her öğesinden geçer ve her pikseli komşu piksellerin medyanı ile değiştirir. |
| median(area) | Median filtresi görüntü parçasının her öğesinden geçer ve her pikseli komşu piksellerin medyanı ile değiştirir. |
| auto_denoising() | Görüntüyü iyileştirmek için ek bir sinir ağı kullanımını etkinleştirir - gürültüyü azaltır.<br/>            Tarama artefaktları, bozulma, lekeler, parlamalar, gradyanlar, yabancı öğeler içeren görüntüler için faydalıdır. |
| auto_denoising(area) | Görüntü parçasını iyileştirmek için ek bir sinir ağı kullanımını etkinleştirir - gürültüyü azaltır.<br/>            Tarama artefaktları, bozulma, lekeler, parlamalar, gradyanlar, yabancı öğeler içeren görüntüler için faydalıdır. |
| auto_skew() | Otomatik görüntü eğimi düzeltmesini etkinleştirir. |
| auto_skew(area) | Otomatik görüntü parçası eğimi düzeltmesini etkinleştirir. |
| contrast_correction_filter() | Kontrast düzeltme filtresi. |
| contrast_correction_filter(area) | Görüntünün parçası için kontrast düzeltme filtresi. |
| to_grayscale() | Bir görüntüyü gri tonlamalı görüntüye dönüştürür.<br/>            Gri tonlamalı görüntü, görüntüde 256 ışık seviyesi (0'dan 255'e) içerir. |
| auto_dewarping() | Görüntüdeki geometrik bozulmaları otomatik olarak düzeltir.<br/>            Son derece kaynak yoğun! |
| add(filter) | Yeni filtreyi koleksiyona ekleyerek tüm işlemleri daha da çalıştırın.<br/>            Koleksiyondaki tutarlılık önemlidir. |

### Ayrıca Bakınız

* namespace [aspose.ocr.models.preprocessingfilters](/ocr/python-net/aspose.ocr.models.preprocessingfilters/)
* assembly [Aspose.ocr](/ocr/python-net/)

