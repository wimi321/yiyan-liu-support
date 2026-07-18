---
layout: page
title: 第三方许可
permalink: /licenses/
---

# 第三方软件与模型许可

一眼榴在设备端使用以下第三方开源软件与模型。所列名称和商标归各自权利人所有；其出现不表示权利人对一眼榴的赞助或背书。

## Gemma 4 E4B 指令模型

- 项目与权利人：Gemma，Google
- 应用所用打包版本：`gemma-4-E4B-it.litertlm`
- 发布来源：[litert-community/gemma-4-E4B-it-litert-lm](https://huggingface.co/litert-community/gemma-4-E4B-it-litert-lm)
- 固定来源修订：`f7ad3343bd6ebc9607f4dc3bc4f2398bd5749bc5`
- 许可：[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

模型在本地用于解释照片中可见的榴莲外观证据。模型生成内容可能不完整或出错，应用会限制结论边界，但不应把输出视为对内部品质的测量或保证。

## LiteRT-LM

- 项目与权利人：LiteRT-LM，Google
- 上游来源：[google-ai-edge/LiteRT-LM](https://github.com/google-ai-edge/LiteRT-LM)
- Swift 封装源码基础版本：`v0.13.1`（含本应用所需的本地修改，修改文件内有明确标注）
- 设备端二进制框架版本：`v0.13.0`
- 许可：[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

一眼榴使用 LiteRT-LM 在支持的 Apple 设备上运行本地模型推理。应用所使用的源码副本保留了上游许可声明，并在修改文件中标注了本地变更；Apache License 2.0 的完整文本也随应用提供。

## Apache License 2.0 提示

上述组件按 Apache License 2.0 授权，并按“原样”提供，不附带明示或默示担保。完整权利、限制与 NOTICE 要求以各项目随附文件和 [Apache License 2.0 正文](https://www.apache.org/licenses/LICENSE-2.0)为准。

除明确列出的第三方内容外，一眼榴的名称、界面、文案和原创视觉资产不因本页而改以 Apache License 2.0 授权。
