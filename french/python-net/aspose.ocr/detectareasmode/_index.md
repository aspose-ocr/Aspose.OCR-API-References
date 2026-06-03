---
title: "DetectAreasMode"
second_title: "Référence de l'API Aspose.OCR pour Python via .NET"
description: 
type: docs
weight: 540
url: /fr/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

Détermine le type de réseau neuronal utilisé pour la détection des zones.

## Members
| Nom du membre | Description |
| :- | :- |
| LEAN | Priorise la vitesse et réduit la consommation de ressources en omettant la prise en charge des mises en page complexes. Convient uniquement aux images simples contenant quelques lignes de texte sans illustrations ni formatage. |
| MULTICOLUMN | Détecte de grands blocs de texte formatés en colonnes. Le meilleur choix pour les mises en page multi‑colonnes telles que les pages de livres, les articles ou les contrats. |
| UNIVERSAL | Détecte tous les blocs de texte dans l’image, y compris le texte clairsemé et irrégulier sur les photos. Une option polyvalente pour la plupart des images, sauf pour les tableaux et les mises en page multi‑colonnes. |
| TABLE | Détecte les structures tabulaires dans l’image et extrait le texte des cellules individuelles. Recommandé pour les feuilles de calcul numérisées, les rapports et autres documents basés sur des tableaux. |
| CURVED_TEXT | Redresse automatiquement les lignes de texte courbes dans l’image, améliorant la précision de reconnaissance et permettant de récupérer et d’extraire davantage de texte. Nécessite une puissance de traitement et une RAM importantes. |
| FORMULA |  |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

