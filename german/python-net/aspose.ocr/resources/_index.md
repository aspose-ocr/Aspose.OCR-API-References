---
title: "Resources"
second_title: "Aspose.OCR für Python via .NET API-Referenz"
description: 
type: docs
weight: 360
url: /de/python-net/aspose.ocr/resources/
---

## Resources class

Verwalten Sie herunterladbare Ressourcen, die die Erkennungsfähigkeiten von Aspose.OCR verbessern.

Der Typ Resources stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Resources() | Initialisiert eine neue Instanz der Klasse Resources |
## Methoden
| Name | Beschreibung |
| :- | :- |
| set_local_path(path) | Geben Sie einen absoluten oder relativen Pfad zu dem Verzeichnis an, in das die Ressourcen heruntergeladen werden sollen.<br/>            Wenn das Verzeichnis nicht existiert, wird es automatisch erstellt.<br/>            Standardmäßig werden die Ressourcen in das Verzeichnis aspose_data im Arbeitsverzeichnis der Anwendung heruntergeladen. |
| set_local_path(path, create) | Geben Sie einen absoluten oder relativen Pfad zu dem Verzeichnis an, in das die Ressourcen heruntergeladen werden sollen.<br/>            Übergeben Sie `false` an den Parameter `create`, um zu verhindern, dass das Verzeichnis automatisch erstellt wird.<br/>            Wenn das angegebene Verzeichnis nicht existiert und das Erstellen nicht erlaubt ist, werden die Ressourcen in das Verzeichnis aspose_data im Arbeitsverzeichnis der Anwendung geladen. |
| set_repository(url) | Geben Sie die URL des Online-Repositorys an, von dem Aspose.OCR-Ressourcen heruntergeladen werden.<br/>            Standardmäßig werden die Ressourcen von https://github.com/aspose-ocr/resources/ heruntergeladen. |
| get_repository() | Gibt die URL des Online-Repositorys zurück, von dem Aspose.OCR-Ressourcen heruntergeladen werden. |
| list_remote() | Listet alle kompatiblen Ressourcen aus dem Online-Repository auf. |
| get_local_path() | Gibt den vollständigen Pfad zu dem Verzeichnis zurück, in das die Ressourcen heruntergeladen werden. |
| list_local() | Listet alle Aspose.OCR-Ressourcen auf, die im lokalen Verzeichnis gespeichert sind. |
| allow_automatic_downloads(allow) | Erlaubt (true) oder blockiert (false) das automatische Herunterladen erforderlicher Ressourcen aus dem Online-Repository.<br/>             Standardmäßig wird eine Ressource automatisch heruntergeladen, wenn eine Methode, die davon abhängt, aufgerufen wird. |
| fetch_resources(names) | Lädt die im Parameter `names` angegebenen Ressourcen aus dem Online-Repository herunter. Wenn eine oder mehrere Ressourcen bereits heruntergeladen wurden, werden sie überschrieben.<br/>            Sie können die .OCR-Erweiterung weglassen und nur Dateinamen verwenden. |
| fetch_resource(name) | Lädt die im Parameter `names` angegebenen Ressourcen aus dem Online-Repository herunter. Wenn eine oder mehrere Ressourcen bereits heruntergeladen wurden, werden sie überschrieben.<br/>            Sie können die .OCR-Erweiterung weglassen und nur Dateinamen verwenden. |
| fetch_all() | Lädt alle kompatiblen Ressourcen aus dem Online-Repository herunter. Die vorhandenen Ressourcendateien werden überschrieben. |
| remove_local(name) | Entfernt die lokal gespeicherte Aspose.OCR-Ressource. |
| release_memory() |  |

### Siehe auch

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

