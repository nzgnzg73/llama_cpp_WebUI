---
license: apache-2.0
tags:
- Image-Text-to-Text Models
- Audio-Text-to-Text
- text-to-Text
- llama_cpp
- any to any
- Multimodal AI
- video-Text-to-Text
- Llama Model Switcher
---
nzgnzg73

llama_cpp_WebUI

Github
https://github.com/nzgnzg73/llama_cpp_WebUI

## Want to talk or ask something?
Just click the YouTube link below! You'll find my 📧 email there and can message me easily. 👇

🎥 YouTube Channel: @nzg73
🔗 https://youtube.com/@NZG73


## Contact Email 👇👇👀
E-mail:-
nzgnzg73@gmail.com





![Gemini_Generated_Image_rx1z0erx1z0erx1z](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/7Cjp8zMEtdftA0lfJzKZL.png)


## Llama Model Switcher

CMD
model_switcher.py

pip install flask

pip install flask psutil GPUtil

![1](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/PUekE98unK4E-wCue-Dle.png)



![2](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/CZvP7V61-SE4o4_Pu38_s.png)

## Image-Text-to-Text Models

## Gemma-3

CPU.  RAM 20GB
OR
GPU.  4 VRAM


![1](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/qoYFWiyKbxfec608p3AbF.png)

1. gemma-3-12b-it-Q4_K_S.gguf
2. mmproj-model-f16-12B.gguf


## -Text-to-Text Models
## GPT OSS 20




![2](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/lYXBozCQV-SmpXDk4ca9I.png)





![Picsart_25-11-30_03-51-56-362](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/II21vWhc6UJwMwAqw1qaQ.png)




## Qwen3


CPU.  RAM 25GB
OR
GPU.  4 VRAM


1. Qwen3-VL-2B-Instruct-Q8_0.gguf
2. mmproj-Qwen3-VL-2B-Instruct-Q8_0.gguf



![2](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/jmba7H290hQTPhBVL-v5Q.png)


## Qwen2.5-Omni


CPU.  RAM 40GB
OR
GPU.  8 VRAM

1. Qwen2.5-Omni-7B-BF16.gguf  
2. mmproj-F16.gguf           2GB



![4](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/v0ACCIgBmFUmcMH5rTjj_.png)









## Audio-Text-to-Text


## Llama-3.2


CPU.  RAM 10GB




![3](https://cdn-uploads.huggingface.co/production/uploads/68edac11571026107ce50f6c/VJ9-OMFQYX8x-4HhhtknP.png)


1. Llama-3.2-1B-Instruct-Q4_K_M.gguf
2. Llama-3.2-1B-Instruct-Q8_0.gguf
3. mmproj-ultravox-v0_5-llama-3_2-1b-f16.gguf



## run.bat




Local Server

llama-server.exe --n-gpu-layers 2 --ctx-size 111192 -m ".\models\mistralai\mistralai_Voxtral-Mini-3B-2507-Q8_0.gguf" --mmproj ".\models\mistralai\mmproj-mistralai_Voxtral-Mini-3B-2507-bf16.gguf" --host 0.0.0.0 --port 8005


public URL

llama-server --n-gpu-layers 15 --ctx-size 8192 -m models/ollma/Llama-3.2-1B-Instruct-Q8_0.gguf --mmproj models/ollma/mmproj-ultravox-v0_5-llama-3_2-1b-f16.gguf --host 127.0.0.1 --port 8083