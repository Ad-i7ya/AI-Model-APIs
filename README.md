<p align="center">
  <img src="https://i.pinimg.com/736x/c2/db/62/c2db6244e9b408ab0dc2450a29addf77.jpg" alt="Chainsaw Man Banner" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/github/last-commit/Ad-i7ya/AI-Model-APIs?style=for-the-badge" />
  <a href="https://github.com/Ad-i7ya/AI-Model-APIs/stargazers">
    <img src="https://img.shields.io/github/stars/Ad-i7ya/AI-Model-APIs?style=for-the-badge" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
</p>

## About
<details>
  <summary><b>Click to see the philosophy behind this repo</b></summary>
  Building apps shouldn't require navigating complex API keys. This project simplifies development by curating direct, open-access endpoints that are ready to use out of the box.
</details>

## The Collection
| Model Name | Endpoint URL | Status |
| :--- | :--- | :--- |
| [GPT-5](#gpt-5) | `https://gpt5.adi7ya.workers.dev/?q={query}` | ✅ Active |
| [Copilot](#copilot) | `https://copilot.adi7ya.workers.dev/?q={query}` | ✅ Active |
| [Llama](#llama) | `https://llama.adi7ya.workers.dev/?q={query}` | ✅ Active |
| [Gemini](#gemini) | `https://gemini.adi7ya.workers.dev/?q={query}` | ✅ Active |
| [GPT-3](#gpt-3) | `https://gpt3.adi7ya.workers.dev/?q={query}` | ✅ Active |

---

### 🤖 GPT-5
**Endpoint:** `https://gpt5.adi7ya.workers.dev/?q={query}`  

```json
{
  "query": "hello",
  "status": true,
  "creator": "Ad-i7ya",
  "response": "Hey there — good to see you. What’s on your mind today?",
  "metadata": {
    "timestamp": "2026-06-30T11:47:17.159Z",
    "request_id": "82a6df39-a895-41de-887b-96ebeea84ef0",
    "response_time_seconds": 1.307,
    "dev": "https://github.com/Ad-i7ya"
  }
}
```
---

### 🤖 Copilot
**Endpoint:** `https://copilot.adi7ya.workers.dev/?q={query}`

```json
{
  "query": "hello",
  "status": true,
  "creator": "Ad-i7ya",
  "response": {
    "text": "Hey there — good to see you. What’s on your mind this afternoon?",
    "citations": []
  },
  "metadata": {
    "timestamp": "2026-06-30T13:13:51.283Z",
    "request_id": "a9f9a3c5-1e2e-4c37-afaa-dfc01cea8962",
    "response_time_seconds": 1.569,
    "dev": "https://github.com/Ad-i7ya"
  }
}
```
---

###🤖 Llama
**Endpoint:** `https://llama.adi7ya.workers.dev/?q={query}`

```json
{
  "status": true,
  "model": "llama-3.1-8b-instant",
  "creator": "Ad-i7ya",
  "response": {
    "text": "Hello — good to see you.  \nWhat’s on your mind today?",
    "citations": []
  },
  "metadata": {
    "timestamp": "2026-07-01T10:41:24.655Z",
    "request_id": "50aee445-0e01-4a35-bc0f-ab5748e0f32a",
    "response_time_seconds": 2.145,
    "dev": "https://github.com/Ad-i7ya"
  }
}
```
---

###🤖 Gemini
**Endpoint:** `https://gemini.adi7ya.workers.dev/?q={query}`

```json
{
  "status": true,
  "creator": "Ad-i7ya",
  "response": "Hello! How can I assist you today?",
  "metadata": {
    "timestamp": "2026-07-01T10:55:34.688Z",
    "request_id": "58d32a3d-c70f-4108-8ad3-6fa7b44c9e26",
    "response_time_seconds": 1.828,
    "dev": "https://github.com/Ad-i7ya"
  }
}
```
---

###GPT-3
**Endpoint:** `https://gpt3.adi7ya.workers.dev/?q={query}`
```json
{
  "query": "hello",
  "status": true,
  "creator": "Ad-i7ya",
  "response": "Hello! How can I assist you today?",
  "metadata": {
    "timestamp": "2026-07-02T10:15:01.570Z",
    "request_id": "04ef8c06-47c0-4c25-9ce1-99699c8adc2a",
    "response_time_seconds": 1.437,
    "dev": "[https://github.com/Ad-i7ya](https://github.com/Ad-i7ya)"
  }
}
```
---

## Usage & Feedback
This is a personal collection. Please do not open Pull Requests or suggest edits. If you find this collection useful, feel free to **Fork** this repository to your own account and **Star** It to show your support!

**Have a question?** Please use the [Discussions](https://github.com/Ad-i7ya/AI-Model-APIs/discussions) tab to ask questions or share feedback!

## License
Distributed under the MIT License. See [LICENSE](https://github.com/Ad-i7ya/AI-Model-APIs?tab=MIT-1-ov-file) for more information.
