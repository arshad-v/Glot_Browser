# Glot Browser

**Glot Browser** is an experimental, privacy-first desktop web browser built on Chromium, designed to integrate local AI capabilities directly into the browsing experience. It allows users to interact with the web using AI assistance while keeping full control over data, models, and execution.

![Glot Browser Screenshot](https://i.postimg.cc/Wpq7tN3J/Screenshot-2026-01-20-222117.png)

---

## Overview

Glot Browser combines a modern Chromium-based browsing engine with a locally running AI backend. Unlike cloud-dependent AI browsers, Glot Browser is designed to:

- Run AI locally on the user’s machine
- Avoid mandatory accounts or telemetry
- Give users freedom to choose their own AI models
- Maintain strict separation between browser data and external services

This project is currently in **active development** and should be considered **experimental**.

---

## Key Principles

- **Privacy-first**: No forced data collection, tracking, or analytics
- **Local execution**: AI processing runs on the user’s device
- **User control**: Choose your own AI models and providers
- **Transparent architecture**: Clear separation between browser, launcher, and AI runtime
- **Open-source friendly**: Designed for inspection, modification, and contribution

---

## Features

- Chromium-based browsing engine
- Built-in AI sidebar and browser extension
- Local AI backend runtime (no cloud dependency by default)
- Support for multiple AI providers and local model runtimes (e.g. OpenAI-compatible APIs, Gemini, Ollama)
- Custom launcher for process and lifecycle management
- Secure local profile and runtime storage
- Extension-based UI integration

---

## Architecture (High-Level)

