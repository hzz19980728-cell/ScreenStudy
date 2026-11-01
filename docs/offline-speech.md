# 随包离线日语语音

使用 sherpa-onnx / Next-gen Kaldi TTS Engine 1.13.8，包名 `com.k2fsa.sherpa.onnx.tts.engine`；与掌机已安装 APK 一致。APK 原样分发，没有修改或重新签名，也不包含掌机的设置或个人数据。

- [官方安装包目录](https://k2-fsa.github.io/sherpa/onnx/tts/apk-engine.html)
- [对应官方安装文件](https://huggingface.co/csukuangfj2/sherpa-onnx-apk/resolve/main/tts-engine-new/1.13.8/sherpa-onnx-1.13.8-arm64-v8a-jpn-tts-engine-sherpa-onnx-supertonic-3-tts-int8-2026-05-11.apk)
- [引擎源码与许可](https://github.com/k2-fsa/sherpa-onnx/tree/master/android/SherpaOnnxTtsEngine)
- SHA-256：`ac65bfeba3b82d05303b153ee830d5c347858c02765254ef4bcf9b00e07ca22a`
- 签名证书 SHA-256：`030a90bdd6e4c5eef1e161acfa6455a912c45cb2423b64df449ca88fdee097bb`

内置 Supertonic 3 INT8 日语模型、语音及其 MIT 许可原文。模型版权为 Copyright (c) 2025 Supertone Inc.，许可文件随原 APK 的 assets 目录保留。sherpa-onnx 引擎代码按 Apache-2.0 许可提供；其余依赖保留上游声明。

本 APK 不声明联网权限；已在专用模拟器新安装，选择随包引擎后断网生成日语音频，并通过 ScreenStudy 实际朗读检查；无需额外语音下载。
