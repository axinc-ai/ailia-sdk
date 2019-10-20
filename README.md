# ailia SDK

## About ailia SDK

ailia SDK is a cross-platform high speed inference SDK. It provides a consistent C++ API on Windows, Mac, iOS and Android, and makes good use of the GPU, if available, to serve accelerated computing. We are planning to expand our support to embedded devices using OpenCL and OpenVX.

## Supporting Model Format

ONNX opset=10, CaffeModel

## Supporting Platform

|OS|Architecture|Accelerator|Library|
|:---|:---|:---|:---|
|Windows|x86, x64|C++AMP, cuDNN|dll|
|Mac|x64|MetalPerformanceShaders|dylib, bundle|
|iOS|armv7a, arm64|MetalPerformanceShaders|a|
|Android|armv7a, arm64,x86|RenderScript, OpenCL|so, a|
|Linux|x64|OpenCL, cuDNN|so|

WIP : DirectML, MKLDNN, OpenVX

## API

[ailia-sdk/wiki](https://github.com/axinc-ai/ailia-sdk/wiki)

## Case

[AIはクリエイターの創作をどう助けるか？「CLIP STUDIO PAINT」の機能に見るAI活用事例【CEDEC 2019】](https://www.gamebusiness.jp/article/2019/09/25/16233.html)

[【Unite Tokyo 2019】Unityで手軽に使えるAIエンジンailia SDK](https://www.slideshare.net/UnityTechnologiesJapan002/unite-tokyo-2019unityaiailia-sdk)

[DLLAB Engineer Days : ONNX Export & Optimize](https://www.slideshare.net/KazukiKyakuno/dllab-engineer-days-onnx-export-optimize)

## More Information

ailia models : https://github.com/axinc-ai/ailia-models

export to onnx : https://github.com/axinc-ai/export-to-onnx

ax Inc. : https://axinc.jp/en/

ailia SDK : https://ailia.jp/en/

## Contact

contact@axinc.jp
