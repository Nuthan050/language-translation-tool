# 🌍 Language Translation Tool

A modern, responsive web application for translating text between multiple languages using Google Cloud Translation API or Microsoft Translator API.

---

## ✨ Features

- 🌐 Translate text between multiple languages
- 🔍 Auto Detect source language
- 🔄 Swap source and target languages
- 📋 Copy translated text
- 🔊 Text-to-Speech support
- 💾 Translation history
- ⭐ Favorite languages
- 🕒 Recent language pairs
- 📥 Download translation as TXT
- 🌙 Dark / Light Mode
- 📱 Fully Responsive UI
- ⚡ Fast and lightweight
- ♿ Accessibility support

---

## 🛠 Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Axios
- Lucide React
- Google Translate API / Microsoft Translator API
- Local Storage

---

## 📂 Folder Structure

```
src/
│
├── assets/
├── components/
├── constants/
├── context/
├── hooks/
├── pages/
├── services/
├── types/
├── utils/
├── App.tsx
├── main.tsx
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/language-translation-tool.git
```

Navigate to the project

```bash
cd language-translation-tool
```

Install dependencies

```bash
npm install
```

Create a `.env` file

For Google Cloud

```env
VITE_GOOGLE_TRANSLATE_API_KEY=YOUR_API_KEY
```

or Microsoft Translator

```env
VITE_TRANSLATOR_API_KEY=YOUR_API_KEY
VITE_TRANSLATOR_REGION=YOUR_REGION
```

Start development server

```bash
npm run dev
```

---

## 🔑 API Setup

### Google Cloud Translation API

1. Create a Google Cloud Project
2. Enable Translation API
3. Create API Key
4. Add the key to `.env`

### Microsoft Translator

1. Create Azure Translator resource
2. Copy Key
3. Copy Region
4. Add both to `.env`

---

## 🎯 Features Included

- Translate text
- Auto language detection
- Language swapping
- Copy translation
- Speech synthesis
- Download TXT
- History management
- Favorite languages
- Recent translations
- Dark mode
- Responsive UI
- Error handling
- Loading animations

---

## ⚠ Error Handling

- Invalid API key
- Empty input
- Network errors
- Timeout
- Rate limits
- Unsupported language

---

## 📱 Responsive Design

Supports

- Desktop
- Tablet
- Mobile

---

## ♿ Accessibility

- Keyboard navigation
- ARIA labels
- High contrast support
- Screen reader compatibility

---

## 📦 Build

```bash
npm run build
```

Preview production build

```bash
npm run preview
```

---

## 🚀 Deployment

Deploy easily on:

- Vercel
- Netlify
- GitHub Pages
- Firebase Hosting

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss your ideas.

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Developed with ❤️ using React, TypeScript, and Tailwind CSS.
