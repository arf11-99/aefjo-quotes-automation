# 🌿 n8n Telegram Quote Bot  
Automated *Quote of the Day* bot powered by **n8n**, **AI translation**, and **Telegram Bot API**.

## 📌 Overview
Proyek ini adalah bot otomatis yang:

- Mengambil kutipan acak dari **Quotable API**
- Menerjemahkan kutipan ke bahasa Indonesia menggunakan **AI (Google Gemini)**
- Mengirim hasil terjemahan ke **Telegram Bot**
- Berjalan otomatis setiap **10 jam** melalui *Schedule Trigger*

Proyek ini menunjukkan kemampuan dalam:
- Workflow automation (n8n)
- Integrasi API Publik
- Integrasi AI (Gemini Chat Model)
- Bot Automation
- End-to-end automation pipeline

---

## 🧠 How It Works

```
Schedule Trigger (Setiap 10 jam)
        ↓
HTTP Request (Ambil random quote berdasarkan tag)
        ↓
AI Agent (Gemini – menerjemahkan quote ke Bahasa Indonesia)
        ↓
Telegram Send Message (Mengirim quote yang telah diterjemahkan)
```

---

## 🚀 Features
✔ Mengambil kutipan acak dari API publik  
✔ Penerjemahan otomatis menggunakan AI  
✔ Mengirim quote ke Telegram secara otomatis  
✔ Mudah dimodifikasi untuk kategori quote lain  
✔ Workflow sangat bersih & mudah dipahami  

---

## 🗂 Technologies Used
- **n8n** Workflow Automation  
- **Telegram Bot API**  
- **Google Gemini AI Model**  
- **Quotable API**  
- JavaScript Expressions di n8n  

---

## 📁 Repository Structure
```
AefjoQuotesBot - 10.json    → Workflow utama (export dari n8n)
README.md                   → Dokumentasi proyek
/screenshots (opsional)     → Tangkapan layar workflow & output Telegram
```

---

## 📬 Sample Output (Telegram)

```
🌿 Quote of the Day

“Cinta adalah bahasa universal yang hanya dapat dirasakan oleh hati.”

👤 Author: John Doe
```

---

## 🛠 Setup Instructions

### 1. Import Workflow
- Buka n8n → *Import from File*
- Pilih file: `AefjoQuotesBot - 10.json`

### 2. Set Your Credentials
Pastikan kamu sudah mengatur:

- Telegram Bot API  
- Google Gemini API Key  

### 3. Aktifkan Schedule Trigger  
- Atur interval sesuai kebutuhan (default: 10 jam)

### 4. Jalankan Workflow  
Bot akan otomatis mengirimkan quote ke Telegram.

---

## 🖼️ Recommended Screenshots
Agar repo terlihat profesional, tambahkan screenshot:

- Tampilan workflow dalam n8n  
- Preview pesan Telegram  
- Node AI saat menerjemahkan quote  

Letakkan dalam folder `/screenshots`.

---

## 🤝 Contribution
Pull request terbuka untuk fitur tambahan seperti:

- Pilihan kategori kutipan  
- Multi-language version  
- Integrasi OpenAI / Claude  

---

## 👤 Author
**Arfan Fadillah**  
Programmer & Automation Enthusiast  
- Instagram: [@aefjocode](https://www.instagram.com/aefjocode)  
- YouTube: [@AefjoCode](https://www.youtube.com/@AefjoCode)

---

## ⭐ Support
Jika proyek ini bermanfaat, jangan lupa memberikan ⭐ pada repository GitHub.
