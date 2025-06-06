# EpicZx - Telegram Private Channel MP3 Downloader

**EpicZx** is a simple Chrome extension that helps you download **MP3 audio files** from **Telegram Web private channels**.

Telegram Web streams audio using short-lived `progressive/document` URLs that are hard to download directly.  
EpicZx makes it easy — download any audio by entering its document ID, or let the extension auto-detect it.

---

## 🚀 Features

✅ Auto-detect current playing Telegram Web audio  
✅ Download full MP3 with chunked downloading  
✅ Works in private Telegram channels/groups (if you are logged in)  
✅ No need to type document ID manually (auto-find from page)  

---

## 📝 How to use

1️⃣ Open [https://web.telegram.org](https://web.telegram.org)  
2️⃣ Play the audio you want → this will load the `progressive/document` URL  
3️⃣ Click the extension icon → it will auto-download the full MP3  
4️⃣ Enjoy your audio 🎵  

---

## ⚠️ Notes

- You must be logged in and able to play the audio.
- Document URLs are **short-lived** → play the audio first!
- The extension runs in **page context** → your session & cookies are used → no 404 errors.

---

## 🛠️ How it works

EpicZx uses **chunked downloading** with `Range` headers, just like the official Telegram Web player.  
It injects a small script in the page context → auto-detects the audio URL → downloads the full file.

---

## License

MIT License.
