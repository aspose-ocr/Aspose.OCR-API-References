---
title: "Metered"
second_title: "Aspose.OCR para Python a través de .NET Referencia de API"
description: 
type: docs
weight: 190
url: /es/python-net/aspose.ocr/metered/
---

## Metered class

Proporciona métodos para establecer la clave medida.

El tipo Metered expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Metered() | Inicializa una nueva instancia de esta clase. |
## Methods
| Nombre | Descripción |
| :- | :- |
| set_metered_key(public_key, private_key) | Establece la clave pública y privada con medida.<br/>            Si adquiere una licencia con medida, al iniciar la aplicación, esta API debe ser llamada; normalmente, eso es suficiente. <br/>            Sin embargo, si siempre falla la carga de datos de consumo y supera las 24 horas, la licencia se cambiará a estado de evaluación, <br/>            para evitar este caso, debe comprobar regularmente el estado de la licencia; si está en estado de evaluación, llame a esta API nuevamente. |
| get_consumption_quantity() | Obtiene el tamaño del archivo de consumo. |
| get_consumption_credit() | Obtiene el crédito de consumo. |

### Ver también

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

