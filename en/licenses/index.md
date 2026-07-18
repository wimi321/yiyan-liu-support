---
layout: page
title: Third-Party Licenses
permalink: /en/licenses/
---

# Third-Party Software and Model Licenses

Durian Lens uses the following third-party open-source software and model for on-device processing. All names and trademarks belong to their respective owners. Their appearance here does not imply sponsorship or endorsement of Durian Lens.

## Gemma 4 E4B instruction-tuned model

- Project and rights holder: Gemma, Google
- Packaged version used by the app: `gemma-4-E4B-it.litertlm`
- Distribution source: [pinned litert-community/gemma-4-E4B-it-litert-lm revision](https://huggingface.co/litert-community/gemma-4-E4B-it-litert-lm/tree/f7ad3343bd6ebc9607f4dc3bc4f2398bd5749bc5)
- Pinned source revision: `f7ad3343bd6ebc9607f4dc3bc4f2398bd5749bc5`
- License: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

The model is used locally to interpret visible exterior evidence in durian photos. Model-generated content may be incomplete or incorrect. The app limits the scope of its conclusions, but its output should not be treated as a measurement or guarantee of internal fruit quality.

## LiteRT-LM

- Project and rights holder: LiteRT-LM, Google
- Upstream source: [google-ai-edge/LiteRT-LM v0.13.1](https://github.com/google-ai-edge/LiteRT-LM/tree/v0.13.1)
- Base version of the Swift wrapper source: `v0.13.1` (with local changes required by this app, clearly marked in the modified files)
- On-device binary framework: [v0.13.0 release](https://github.com/google-ai-edge/LiteRT-LM/releases/tag/v0.13.0)
- License: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

Durian Lens uses LiteRT-LM to run local model inference on supported Apple devices. The source copy used by the app retains upstream license notices and identifies local changes in the modified files. The complete Apache License 2.0 text is also included with the app.

## Apache License 2.0 notice

The components above are licensed under the Apache License 2.0 and are provided on an “as is” basis, without warranties or conditions of any kind. The rights, restrictions, and NOTICE requirements in each project’s included files and in the [full Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) control.

Except for the third-party content expressly identified above, this page does not place the Durian Lens name, interface, copy, or original visual assets under the Apache License 2.0.
