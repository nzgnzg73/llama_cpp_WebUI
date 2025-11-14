---
license: apache-2.0
tags:
- Image-Text-to-Text Models
- Audio-Text-to-Text
- text-to-Text
- llama_cpp
- any to any
---
nzgnzg73

llama_cpp_WebUI

## Image-Text-to-Text Models

## Gemma-3

CPU.  RAM 20GB
OR
GPU.  4 VRAM


<img width="1913" height="965" alt="1" src="https://github.com/user-attachments/assets/879f59ad-39b8-4fc8-8920-72d984691926" />



1. gemma-3-12b-it-Q4_K_S.gguf
2. mmproj-model-f16-12B.gguf


## Qwen3


CPU.  RAM 25GB
OR
GPU.  4 VRAM


1. Qwen3-VL-2B-Instruct-Q8_0.gguf
2. mmproj-Qwen3-VL-2B-Instruct-Q8_0.gguf


<img width="1283" height="607" alt="2" src="https://github.com/user-attachments/assets/14ae3781-d218-400d-a738-586d35349c23" />




## Qwen2.5-Omni


CPU.  RAM 40GB
OR
GPU.  8 VRAM

1. Qwen2.5-Omni-7B-BF16.gguf  
2. mmproj-F16.gguf           2GB




<img width="1301" height="673" alt="4" src="https://github.com/user-attachments/assets/e321dfc4-fdac-453b-b5f6-3bfd25cc676f" />









## Audio-Text-to-Text


## Llama-3.2


CPU.  RAM 10GB



<img width="1395" height="873" alt="3" src="https://github.com/user-attachments/assets/d6682b09-79a2-4be4-8f34-2318e2d2751d" />




1. Llama-3.2-1B-Instruct-Q4_K_M.gguf
2. Llama-3.2-1B-Instruct-Q8_0.gguf
3. mmproj-ultravox-v0_5-llama-3_2-1b-f16.gguf



## run.bat




Local Server

llama-server.exe --n-gpu-layers 2 --ctx-size 111192 -m ".\models\mistralai\mistralai_Voxtral-Mini-3B-2507-Q8_0.gguf" --mmproj ".\models\mistralai\mmproj-mistralai_Voxtral-Mini-3B-2507-bf16.gguf" --host 0.0.0.0 --port 8005


public URL

llama-server --n-gpu-layers 15 --ctx-size 8192 -m models/ollma/Llama-3.2-1B-Instruct-Q8_0.gguf --mmproj models/ollma/mmproj-ultravox-v0_5-llama-3_2-1b-f16.gguf --host 127.0.0.1 --port 8083
