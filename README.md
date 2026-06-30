# AI Model APIs

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

A collection of free, keyless AI model APIs for quick integration. It utilizes standard GET requests and provides JSON samples for testing. It is designed for easy implementation in any project and is released under an open-source MIT License.

## Why this exists
Building apps shouldn't require navigating complex authentication or managing hidden API keys. This project simplifies development by curating direct, open-access endpoints that are ready to use out of the box.

## The Collection

| Model Name | Endpoint URL | Status |
| :--- | :--- | :--- |
| [GPT-5](#gpt-5) | `https://gpt5.adi7ya.workers.dev/?q={query}` | ✅ Active |

---

### GPT-5
**Endpoint:** `https://gpt5.adi7ya.workers.dev/?q={query}`  
**Description:** A proxy endpoint for GPT-5 model access.

```json
{
  "status": true,
  "creator": "Ad-i7ya",
  "response": "Hey there — good to see you. What’s on your mind today?",
  "metadata": {
    "timestamp": "2026-06-30T11:47:17.159Z",
    "request_id": "82a6df39-a895-41de-887b-96ebeea84ef0",
    "response_time_seconds": 1.307,
    "dev": "[https://github.com/Ad-i7ya](https://github.com/Ad-i7ya)"
  }
}
