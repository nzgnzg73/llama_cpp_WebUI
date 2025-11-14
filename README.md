# -llama_cpp_WebUI
 llama_cpp_WebUI

---
license: apache-2.0
tags:
- Image-Text-to-Text Models
- Audio-Text-to-Text
- text-to-Text
- llama_cpp
---
nzgnzg73

llama_cpp_WebUI

## Image-Text-to-Text Models

## Gemma-3


![1](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/qoYFWiyKbxfec608p3AbF.png)

1. gemma-3-12b-it-Q4_K_S.gguf
2. mmproj-model-f16-12B.gguf


## Qwen3

1. Qwen3-VL-2B-Instruct-Q8_0.gguf
2. mmproj-Qwen3-VL-2B-Instruct-Q8_0.gguf



![2](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/jmba7H290hQTPhBVL-v5Q.png)




## Audio-Text-to-Text


## Llama-3.2




![3](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/VJ9-OMFQYX8x-4HhhtknP.png)


1. Llama-3.2-1B-Instruct-Q4_K_M.gguf
2. Llama-3.2-1B-Instruct-Q8_0.gguf
3. mmproj-ultravox-v0_5-llama-3_2-1b-f16.gguf



## run.bat




Local Server

llama-server.exe --n-gpu-layers 2 --ctx-size 111192 -m ".\models\mistralai\mistralai_Voxtral-Mini-3B-2507-Q8_0.gguf" --mmproj ".\models\mistralai\mmproj-mistralai_Voxtral-Mini-3B-2507-bf16.gguf" --host 0.0.0.0 --port 8005


public URL

llama-server --n-gpu-layers 15 --ctx-size 8192 -m models/ollma/Llama-3.2-1B-Instruct-Q8_0.gguf --mmproj models/ollma/mmproj-ultravox-v0_5-llama-3_2-1b-f16.gguf --host 127.0.0.1 --port 8083
