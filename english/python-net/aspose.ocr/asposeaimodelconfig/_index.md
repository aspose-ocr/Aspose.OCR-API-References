---
title: AsposeAIModelConfig
second_title: Aspose.OCR for Python via .NET API Reference
description: 
type: docs
weight: 20
url: /python-net/aspose.ocr/asposeaimodelconfig/
---

## AsposeAIModelConfig class



The AsposeAIModelConfig type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|AsposeAIModelConfig()|Initializes a new instance of the AsposeAIModelConfig class|
## Properties
| Name | Description |
| :- | :- |
|hugging_face_repo_id     | ID of the model on HuggingFace (e.g., “openai/gpt2”). If specified, the model will be downloaded from HuggingFace. Default bartowski/Qwen2.5-3B-Instruct-GGUF. |
|directory_model_path     | Optional path where downloaded or processed models will be cached. If not set, a default system location will be used.                                         |
|allow_auto_download      | If true, the model will be automatically downloaded if not available locally.                                                                                  |
|hugging_face_quantization| Optional quantization type to use when downloading from HuggingFace. Examples: “int8”, “fp16”, “none”. Default q4_k_m.                                         |
|file_model_path          | Local path to the folder containing the model files. If specified, this will be used instead of downloading. Default empty.                                    |
|context_size             | Maximum number of tokens considered during inference. Default uses model’s default context.                                                                    |
|gpu_layers               | Number of GPU layers for model inference. Set 0 to run on CPU. Default: 40.                                                                                    |

### See Also

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

