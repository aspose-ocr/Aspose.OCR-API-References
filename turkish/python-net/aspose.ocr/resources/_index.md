---
title: "Resources"
second_title: "Aspose.OCR Python için .NET API Referansı"
description: 
type: docs
weight: 360
url: /tr/python-net/aspose.ocr/resources/
---

## Resources class

Aspose.OCR tanıma yeteneklerini artıran indirilebilir kaynakları yönetin.

Resources türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Resources() | Resources sınıfının yeni bir örneğini başlatır |
## Methods
| Ad | Açıklama |
| :- | :- |
| set_local_path(path) | Kaynakların indirileceği dizine mutlak ya da göreli bir yol belirtin.<br/>            Dizin mevcut değilse, otomatik olarak oluşturulacaktır.<br/>            Varsayılan olarak, kaynaklar uygulamanın çalışma dizinindeki aspose_data dizinine indirilir. |
| set_local_path(path, create) | Kaynakların indirileceği dizine mutlak ya da göreli bir yol belirtin.<br/>            Dizin otomatik olarak oluşturulmasını önlemek için `create` parametresine `false` geçirin.<br/>            Sağlanan dizin mevcut değil ve oluşturulmasına izin verilmiyorsa, kaynaklar uygulamanın çalışma dizinindeki aspose_data dizinine yüklenecektir. |
| set_repository(url) | Aspose.OCR kaynaklarının indirileceği çevrimiçi depolamanın URL'sini belirtin.<br/>            Varsayılan olarak, kaynaklar https://github.com/aspose-ocr/resources/ adresinden indirilir. |
| get_repository() | Aspose.OCR kaynaklarının indirildiği çevrimiçi depolamanın URL'sini döndürür. |
| list_remote() | Çevrimiçi depolamadan tüm uyumlu kaynakları listele. |
| get_local_path() | Kaynakların indirileceği dizinin tam yolunu döndürür. |
| list_local() | Yerel dizinde depolanan tüm Aspose.OCR kaynaklarını listele. |
| allow_automatic_downloads(allow) | Gerekli kaynakların çevrimiçi depolamadan otomatik indirilmesine izin ver (true) veya engelle (false).<br/>             Varsayılan olarak, bir kaynak ona bağımlı bir yöntem çağrıldığında otomatik olarak indirilir. |
| fetch_resources(names) | `names` parametresinde belirtilen kaynakları çevrimiçi depolamadan indir. Bir veya daha fazla kaynak zaten indilmişse, üzerine yazılacak.<br/>            .OCR uzantısını atlayabilir ve sadece dosya adlarını kullanabilirsiniz. |
| fetch_resource(name) | `names` parametresinde belirtilen kaynakları çevrimiçi depolamadan indir. Bir veya daha fazla kaynak zaten indilmişse, üzerine yazılacak.<br/>            .OCR uzantısını atlayabilir ve sadece dosya adlarını kullanabilirsiniz. |
| fetch_all() | Çevrimiçi depolamadan tüm uyumlu kaynakları indir. Mevcut kaynak dosyalarının üzerine yazılacak. |
| remove_local(name) | Yerel olarak depolanan Aspose.OCR kaynağını kaldırır. |
| release_memory() |  |

### Ayrıca Bakınız

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

