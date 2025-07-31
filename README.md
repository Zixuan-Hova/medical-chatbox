# medical-chatbox
# Preoperative Consent Form and Medical Term Explanation Chatbot

This is a domain-specific healthcare chatbot MVP built using **AnythingLLM** and **Ollama** to assist patients in understanding complex terms on surgical preoperative consent forms.

---

## 🩺 Project Scenario

In Halifax, Nova Scotia, patients often receive preoperative consent forms that contain medical terms like **arrhythmia** or **ASA II**, which can be confusing or anxiety-inducing. This chatbot helps users by providing plain-language explanations of these terms and encouraging them to seek professional medical support when necessary.

---

## ✅ Features

- Answers common pre-op medical questions in simple, friendly language
- Uses a custom knowledge base curated from reputable health education sources
- Follows ethical guidelines with built-in disclaimers and crisis redirection
- Runs locally using **Ollama** + **AnythingLLM**

---

## 📂 Project Structure

```
/preop-chatbot
├─ knowledge_base/
│  ├─ knowledge_document_1.md  # Arrhythmia
│  ├─ knowledge_document_2.md  # ASA II Classification
├─ prompt/
│  └─ system_prompt.txt
├─ documentation/
│  ├─ scenario_pack.md
│  └─ use_case_description.md
├─ demo/
│  ├─ demo_video.mp4
│  └─ chat_transcript.txt
└─ README.md
```

---

## ⚠ Disclaimer

> **This chatbot does not provide medical advice.**
>
> It is for educational purposes only and should not be used to diagnose or treat any medical condition.
> Always consult a licensed healthcare provider for professional guidance.

---

## 🧪 Local Setup Instructions

1. Install [Ollama](https://ollama.com) and run a model such as `llama3`:
   ```bash
   ollama run llama3
   ```

2. Clone this repo and open [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm)

3. Upload the files from this project folder into your AnythingLLM workspace

4. Start chatting!

---

## 👤 Author

Zixuan Li  
Saint Mary’s University  
July 2025
