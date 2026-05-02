markdown
# 🤖 WhatsApp PDF Bot

<p align="center">
  <img src="pastpapaer.jpg" alt="WhatsApp PDF Bot Banner" width="800" style="border-radius: 15px;">
</p>

A simple WhatsApp bot that sends PDF files automatically when users request them 📄✨

---

## 🚀 Features

- 📚 **Auto PDF List** – Users can get a full list of available PDFs.
- 🔢 **Number-Based Selection** – Just reply with a number to receive a file.
- ⚡ **Fast Response** – Instantly sends requested PDFs.
- 🛠️ **Error Handling** – Handles missing files & issues smoothly.

---

## 📦 Setup Guide

### 1️⃣ Install Dependencies
```bash
npm install whatsapp-web.js qrcode-terminal
```

### 2️⃣ Add Your PDF Files
Create a folder named `files/` and add your PDFs:
```
files/
├── Lesson 03.pdf
├── Lesson 04.pdf
├── Lesson 05.pdf
├── Lesson 10.pdf
├── Lesson 08.pdf
└── Teachers Guide.pdf
```

### 3️⃣ Run the Bot
```bash
node whatsapp-pdf-bot.js
```

### 4️⃣ Connect WhatsApp
- A QR code will appear in your terminal 📱.
- Scan it using WhatsApp.
- Bot will be ready ✅.

---

## 💡 How It Works

### 📥 Step 1 – Request List
User sends: `pdf` or `files`

### 📤 Step 2 – Bot Reply
```
📚 Available PDF Files:

1. Lesson 03.pdf
2. Lesson 04.pdf
3. Lesson 05.pdf
...
👉 Reply with the number to get the file.
```

### 📨 Step 3 – Get File
User replies with a number (e.g., `5`), and the bot sends the corresponding PDF instantly.

---

## 🗂️ Project Structure
```
├── whatsapp-pdf-bot.js
├── pastpapaer.jpg
├── files/
│   ├── Lesson 03.pdf
│   ├── Lesson 04.pdf
│   └── ...
└── README.md
```

---

## ⚙️ Customize PDFs
Edit your file list inside `whatsapp-pdf-bot.js`:
```javascript
const pdfs = {
  "1": "files/Lesson 03.pdf",
  "2": "files/Lesson 04.pdf",
  "3": "files/Lesson 05.pdf"
};
```

---

## 🧪 Tips
- ✔ File names must match exactly.
- ✔ Keep all PDFs inside the `files/` folder.
- ✔ Ensure a stable internet connection.

---

## ⭐ Simple & Powerful
Perfect for sharing lessons 📘, distributing notes 📝, and automating file delivery ⚡.

<p align="center"> <b>Simple & Powerful ⚡</b> </p>
```
