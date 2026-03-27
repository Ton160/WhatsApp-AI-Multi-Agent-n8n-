
# 🤖 WhatsApp AI Multi-Agent (n8n)

An intelligent **multi-agent AI system** built with n8n that automates WhatsApp conversations using text, voice, and images.

---

## ⚡ What it does

* 💬 Handles text messages
* 🎤 Converts voice → text → AI response
* 🖼 Understands images
* 🧠 Routes tasks using an AI Orchestrator
* ⚡ Replies automatically on WhatsApp

---

## 🧠 How it works

1. WhatsApp message received (Webhook)
2. Detect message type:

   * Text
   * Voice
   * Image
3. Process input:

   * Voice → Transcription
   * Image → AI Analysis
4. Send to AI Orchestrator
5. Execute action (reply / task)
6. Send response back to WhatsApp

---

## 🛠 Tech

* n8n
* OpenAI
* Evolution API (WhatsApp)

---

## 🚀 Setup

1. Open n8n
2. Import `workflow.json`
3. Add your credentials:

   * OpenAI API
   * Evolution API
4. Activate the workflow

---

## 📸 Preview

(Add screenshot here)

---

## 💡 Why this project?

This project demonstrates how to build a **real-world AI automation system** using:

* Multi-agent architecture
* Multi-modal input (text, voice, image)
* WhatsApp integration

---

## ⚠️ Notes

* API keys are not included
* Configure credentials inside n8n

---

## 📜 License

MIT
