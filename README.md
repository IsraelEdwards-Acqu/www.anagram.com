# www.anagram.com
We Create, We Design, We Develop.
# 📱 Anagrames — Fast, Fun, and Secure Anagram Chat

Anagrames is a modern, offline-capable chat application that lets users communicate using clever anagrams. Inspired by the simplicity and reliability of WhatsApp, Anagrames adds a playful twist to messaging while maintaining robust performance and seamless cloud integration.

---

## 🚀 Features

- 🔤 **Anagram Messaging** — Every message is transformed into a witty anagram. Decode and reply in style.
- 📶 **Offline-First Architecture** — Chat anytime, anywhere. Messages sync automatically when you're back online.
- 🔐 **Secure Conversations** — End-to-end encryption ensures your chats stay private.
- 📲 **Installable PWA** — Add Anagrames to your home screen and use it like a native app.
- 🌐 **Cloud Sync** — Messages and user data are synced across devices using Firebase and Netlify Functions.
- 🧠 **Smart Refresh Logic** — Built-in service worker handles updates and refreshes without disrupting the user experience.

---

## 🛠️ Tech Stack

- **Frontend**: Blazor WebAssembly
- **Backend**: Firebase + Netlify Functions + Google Apps Script
- **Offline Support**: Service Worker with custom caching and update logic
- **Interop**: JSInterop for seamless browser-native interactions

---

## 📦 Installation

```bash
git clone https://github.com/IsraelEdwards-Acqu/anagram.com.git
cd anagram.com
dotnet build
dotnet run
