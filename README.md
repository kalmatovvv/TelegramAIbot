# ChatGPT Telegram Bot
![python-version](https://img.shields.io/badge/python-3.9-blue.svg)
[![openai-version](https://img.shields.io/badge/openai-0.27.8-orange.svg)](https://openai.com/)
[![license](https://img.shields.io/badge/License-GPL%202.0-brightgreen.svg)](LICENSE)
[![Publish Docker image](https://github.com/n3d1117/chatgpt-telegram-bot/actions/workflows/publish.yaml/badge.svg)](https://github.com/n3d1117/chatgpt-telegram-bot/actions/workflows/publish.yaml)

A [Telegram bot](https://core.telegram.org/bots/api) that integrates with OpenAI's _official_ [ChatGPT](https://openai.com/blog/chatgpt/), [DALL·E](https://openai.com/product/dall-e-2) and [Whisper](https://openai.com/research/whisper) APIs to provide answers. Ready to use with minimal configuration required.

## Features
- [x] Support markdown in answers
- [x] Reset conversation with the `/reset` command
- [x] Typing indicator while generating a response
- [x] Access can be restricted by specifying a list of allowed users
- [x] Docker and Proxy support
- [x] Image generation using DALL·E via the `/image` command
- [x] Transcribe audio and video messages using Whisper (may require [ffmpeg](https://ffmpeg.org))
- [x] Automatic conversation summary to avoid excessive token usage
- [x] Track token usage per user - by [@AlexHTW](https://github.com/AlexHTW)
- [x] Get personal token usage statistics via the `/stats` command - by [@AlexHTW](https://github.com/AlexHTW)
- [x] User budgets and guest budgets - by [@AlexHTW](https://github.com/AlexHTW)
- [x] Stream support
- [x] GPT-4 support
  - If you have access to the GPT-4 API, simply change the `OPENAI_MODEL` parameter to `gpt-4`
- [x] Localized bot language
  - Available languages :gb: :de: :ru: :tr: :it: :finland: :es: :indonesia: :netherlands: :cn: :taiwan: :vietnam: :iran: :brazil: :ukraine:
