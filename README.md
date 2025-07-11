# ailia SDK

SDK for optimized running of many popular neural networks on multiple platform

<img src="ailia_logo.png" width=256px>

## About ailia SDK

[ailia SDK](https://ailia.jp/en/) is a cross-platform high speed inference SDK. The ailia SDK provides a consistent C++ API on Windows, Mac, Linux, iOS, Android, Jetson and RaspberryPi. It supports Unity, Python and JNI for efficient AI implementation. The ailia SDK makes great use of the GPU via Vulkan and Metal to serve accelerated computing.

## Install ailia SDK

- [Download a free evaluation version of ailia SDK](https://axip-console.appspot.com/trial/terms/AILIA?lang=en)

## Core Library Documentation

The core library is a standard package of the ailia SDK. Make some basic inferences.

### Python

- [API (EN)](https://axinc-ai.github.io/ailia-sdk/api/python/en/)
- [Tutorial (EN)](https://medium.com/axinc-ai/ailia-sdk-tutorial-python-ea29ae990cf6) [(JP)](https://medium.com/axinc/ailia-sdk-%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB-python-28379dbc9649)
- [Models](https://github.com/axinc-ai/ailia-models)

### C++

- [API (EN)](https://axinc-ai.github.io/ailia-sdk/api/cpp/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/api/cpp/jp/)
- [Tutorial (EN)](https://medium.com/axinc-ai/ailia-sdk-tutorial-c-75e59bbefffe) [(JP)](https://medium.com/axinc/ailia-sdk-%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB-c-dc949d9dcd28)
- [Models](https://github.com/axinc-ai/ailia-models-cpp)
- [Xcode Sample Project](https://github.com/axinc-ai/ailia-xcode)
- [Android NDK Sample Project](https://github.com/axinc-ai/ailia-android-ndk)

### Unity

- [API (EN)](https://axinc-ai.github.io/ailia-sdk/api/unity/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/api/unity/jp/)
- [Tutorial (EN)](https://medium.com/axinc-ai/ailia-sdk-tutorial-unity-54f2a8155b8f) [(JP)](https://medium.com/axinc/ailia-sdk-%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB-unity-257fa1e98777)
- [Models](https://github.com/axinc-ai/ailia-models-unity)

### Flutter

- [API (EN)](https://axinc-ai.github.io/ailia-sdk/api/flutter/en/)
- [Tutorial (EN)](https://medium.com/axinc-ai/ailia-sdk-now-available-through-flutter-pubspec-7e859dad842d) [(JP)](https://medium.com/axinc/ailia-sdk%E3%81%8Cflutter%E3%81%AEpubspec%E3%81%8B%E3%82%89%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E5%8F%AF%E8%83%BD%E3%81%AB-f008229f7862)
- [Models](https://github.com/axinc-ai/ailia-models-flutter)

### JNI

- [API (EN)](https://axinc-ai.github.io/ailia-sdk/api/java/en/)
- [Tutorial (EN)](https://medium.com/axinc-ai/ailia-sdk-tutorial-jni-92b797725e08) [(JP)](https://medium.com/axinc/ailia-sdk-%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB-jni-7a11c1da08dc)
- [Android Studio Sample Project (Java)](https://github.com/axinc-ai/ailia-android-studio)
- [Android Studio Sample Project (Kotlin)](https://github.com/axinc-ai/ailia-android-studio-kotlin)

## Supplemental and Specific Library Documentation

### ailia Tokenizer

ailia Tokenizer is a library for encode NLP text and decode NLP tokens. ailia Tokenizer supports tokenization without Python transformers.

- [C++ API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/tokenizer/cpp/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/tokenizer/cpp/jp/)
- [Unity API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/tokenizer/unity/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/tokenizer/unity/jp/)
- [Python API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/tokenizer/python/en/)
- [Flutter API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/tokenizer/flutter/en/)

### ailia Speech

ailia Speech is a library for speech recognition. It uses ailia SDK and ailia.audio for doing Speech2Text.

- [C++ API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/speech/cpp/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/speech/cpp/jp/)
- [Unity API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/speech/unity/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/speech/unity/jp/)
- [Python API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/speech/python/en/)
- [Flutter API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/speech/flutter/en/)

### ailia Voice

ailia AI Voice is a library generating speech from text. Using ailia AI Voice, you can easily integrate AI powered text-to-speech into your applications.

- [C++ API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/voice/cpp/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/voice/cpp/jp/)
- [Unity API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/voice/unity/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/voice/unity/jp/)
- [Python API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/voice/python/en/)
- [Flutter API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/voice/flutter/en/)

### ailia LLM

ailia LLM is a library for running local LLMs. It can load GGUF and easily implement chat functionality.

- [C++ API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/llm/cpp/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/llm/cpp/jp/)
- [Unity API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/llm/unity/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/llm/unity/jp/)
- [Python API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/llm/python/en/)
- [Flutter API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/llm/flutter/en/)

### ailia Tracker

ailia Tracker is a library for tracking the movement of objects based on object detection results. 

- [C++ API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/tracker/cpp/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/tracker/cpp/jp/)
- [Unity API (EN)](https://axinc-ai.github.io/ailia-sdk/supplemental/tracker/unity/en/) [(JP)](https://axinc-ai.github.io/ailia-sdk/supplemental/tracker/unity/jp/)

## Videos

- [youtube](https://www.youtube.com/channel/UCN-KzWACywDpBNOQ6FkIm0g)

## Contact

- [ax Inc.](https://axinc.jp/en/)

