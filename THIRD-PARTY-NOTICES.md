# Third-party notices

Snoopsie itself is proprietary (see [LICENSE](LICENSE)). It relies on the work of others, listed here with the terms each is offered under.

## Included in the application

**LiteRT-LM** 0.19.1, the runtime that runs the language model on your Mac. It is inside the app as `libCLiteRTLM_mac.dylib`.

- Copyright 2025–2026 The ODML Authors and Google LLC
- Licensed under the Apache License, Version 2.0. A copy is in [third-party/Apache-2.0.txt](third-party/Apache-2.0.txt).
- Source: https://github.com/google-ai-edge/LiteRT-LM

LiteRT-LM is built from other open-source components of its own (among them Abseil, SentencePiece, TensorFlow and minizip). Their notices are kept in its repository, under `third_party`.

## Downloaded by the application

**Gemma 4** (E2B and E4B), the language models. They are not part of the download on this page. Snoopsie fetches them, when you ask it to, from Hugging Face:

- https://huggingface.co/litert-community/gemma-4-E2B-it-litert-lm
- https://huggingface.co/litert-community/gemma-4-E4B-it-litert-lm

They are made by Google and published there under the Apache License, Version 2.0.

## Online service

If the cloud second look is left switched on in Settings → AI, very long fine print is sent, with sensitive details masked, to Google's Gemini API. That is a service and not software included in Snoopsie; Google's terms for the Gemini API apply to it.
