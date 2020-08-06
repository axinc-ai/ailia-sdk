# ailia SDK

## About ailia SDK

[ailia SDK](https://ailia.jp/en/) is a cross-platform high speed inference SDK. The ailia SDK provides a consistent C++ API on Windows, Mac, Linux, iOS, Android and Jetson. It supports Unity, Python and JNI for efficient AI implementation. The ailia SDK makes great use of the GPU via Vulkan and Metal to serve accelerated computing.

## Supporting Model Format

ONNX opset=10, CaffeModel

## Supporting Platforms

|OS|Architecture|Accelerator|Library|
|:---|:---|:---|:---|
|Windows|x86, x64, arm64|C++AMP, cuDNN|dll|
|Mac|x64|Metal|dylib, bundle|
|iOS|armv7a, arm64|Metal|a|
|Android|armv7a, arm64, x86|RenderScript, Vulkan|so, a|
|Linux|x64|OpenCL, cuDNN|so|
|Jetson|x64|cuDNN|so|

## Install ailia SDK

- [Download a free evaluation version of ailia SDK](https://ailia.jp/en/trial)
- Unzip ailia SDK
- Find the location of Python site-packages directory
```
python -c "import site; print (site.getsitepackages())"
```

- Copy the ​ailia ​folder located in the ​python f​older to site-packages
- Copy library files (dll or dylib or so) from the folder library to site-packages/ailia

## Pre-trained models

ailia MODELS : https://github.com/axinc-ai/ailia-models

## Documents

blog : https://medium.com/axinc

export to onnx : https://github.com/axinc-ai/export-to-onnx

api : https://github.com/axinc-ai/ailia-sdk/wiki

## Case

[AIはクリエイターの創作をどう助けるか？「CLIP STUDIO PAINT」の機能に見るAI活用事例【CEDEC 2019】](https://www.gamebusiness.jp/article/2019/09/25/16233.html)

[【Unite Tokyo 2019】Unityで手軽に使えるAIエンジンailia SDK](https://www.slideshare.net/UnityTechnologiesJapan002/unite-tokyo-2019unityaiailia-sdk)

[DLLAB Engineer Days : ONNX Export & Optimize](https://www.slideshare.net/KazukiKyakuno/dllab-engineer-days-onnx-export-optimize)

## Contact

ax Inc. : https://axinc.jp/en/

contact@axinc.jp
