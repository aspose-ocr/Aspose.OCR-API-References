---
title: AsposeAIModelConfig
second_title: Aspose.OCR for Python via .NET API Reference
description: 
type: docs
weight: 30
url: /python-net/aspose.ocr.ai/asposeaimodelconfig/
---

## AsposeAIModelConfig class

Represents configuration settings for loading an LLM model.

The AsposeAIModelConfig type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|AsposeAIModelConfig()|Initializes a new instance of the AsposeAIModelConfig class|
## Properties
| Name | Description |
| :- | :- |
|hugging_face_repo_id|ID of the model on HuggingFace (e.g., "openai/gpt2"). If specified, the model can be loaded from the local cache<br/>            or downloaded from HuggingFace when|
|directory_model_path|Optional directory where HuggingFace models will be searched for and cached.<br/>            Use|
|allow_auto_download|If true, the model will be automatically downloaded if it is not available locally.<br/>            The default value is false. When|
|hugging_face_file_name|Optional model's name to use when downloading from HuggingFace.<br/>            Examples: "TableGPT2-7B.Q4_K_S.gguf". <br/>            Default for table AI - TableGPT2-7B.Q4_K_S.gguf.|
|file_model_path|Local path to the model file. If specified, this file will be used instead of downloading the model.<br/>            Default empty.|
|context_size|Defines the maximum number of tokens the LLM can use as context during inference. <br/>            If null, the default context size defined by the model will be used.<br/>            Larger values allow the model to consider more text but may require more memory.|
|gpu_layers|Number of GPU layers to use for the model. If not specified, the default value (40) will be used. Set to 0 to run entirely on the CPU.|

### See Also

* namespace [aspose.ocr.ai](/ocr/python-net/aspose.ocr.ai/)
* assembly [Aspose.ocr](/ocr/python-net/)

