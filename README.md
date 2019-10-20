# ailia SDK

## About ailia SDK

ailia SDK is a cross-platform high speed inference SDK. It provides a consistent C++ API on Windows, Mac, iOS and Android, and makes good use of the GPU, if available, to serve accelerated computing. We are planning to expand our support to embedded devices using OpenCL and OpenVX.

## Supporting Model Format

ONNX opset=10

## Architecture

|OS|Backend|
|:--|:--|
|Windows|C++AMP, cuDNN|
|Mac|MetalPerformanceShaders|
|iOS|MetalPerformanceShaders|
|Android|RenderScript, OpenCL|
|Linux|OpenCL, cuDNN|

WIP : DirectML, MKLDNN, OpenVX

## API

[ailia-sdk/wiki](https://github.com/axinc-ai/ailia-sdk/wiki)

## Case

[AIはクリエイターの創作をどう助けるか？「CLIP STUDIO PAINT」の機能に見るAI活用事例【CEDEC 2019】](https://www.gamebusiness.jp/article/2019/09/25/16233.html)

[【Unite Tokyo 2019】Unityで手軽に使えるAIエンジンailia SDK](https://www.slideshare.net/UnityTechnologiesJapan002/unite-tokyo-2019unityaiailia-sdk)

[DLLAB Engineer Days : ONNX Export & Optimize](https://www.slideshare.net/KazukiKyakuno/dllab-engineer-days-onnx-export-optimize)

## More Information

ax Inc. : https://axinc.jp/en/

ailia SDK : https://ailia.jp/en/

## Contact

contact@axinc.jp
