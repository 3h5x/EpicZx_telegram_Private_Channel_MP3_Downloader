# EpicZx - Telegram Private Channel MP3 Downloader

**EpicZx** is a simple Chrome extension that helps you download **MP3 audio files** from **Telegram Web private channels**.

Telegram Web streams audio using short-lived `progressive/document` URLs that are hard to download directly.  
EpicZx makes it easy — download any audio by entering its document ID.

---

## 🚀 Features

✅ Download full MP3 with chunked downloading  
✅ Works in private Telegram channels/groups (if you are logged in)  
✅ Uses your Telegram session & cookies automatically for safe download  
✅ 100% Open Source — no tracking, no malicious code

---

## 📝 How to use
( first you need to download the zip file and add the extention folder to chrome: a simple video[https://www.youtube.com/watch?v=oswjtLwCUqg] )

1️⃣ Open [https://web.telegram.org](https://web.telegram.org)  
2️⃣ Play the audio you want → this will load the `progressive/document` URL  
3️⃣ Open the **Network tab** in DevTools → you will see a URL like:  
   `https://web.telegram.org/a/progressive/document000000000000000`  
4️⃣ Copy the full part: `document000000000000000`  
5️⃣ Paste it into the EpicZx extension → click **Download** → full MP3 will be saved  
6️⃣ Enjoy your audio 🎵  

---

## ⚠️ Notes

- You must be logged in and able to play the audio.
- Document URLs are **short-lived** → always play the audio first.
- The extension uses **page injection** to access your active Telegram session — so your cookies are used safely.
- There is **no tracking, no analytics, no external servers** — this is a 100% open-source project.  
  You can inspect all the code yourself.

---

## 🛠️ How it works

EpicZx uses **chunked downloading** with `Range` headers, just like the official Telegram Web player.  
It injects a small script into the Telegram Web page → auto-uses your valid session → downloads the full file securely.

---

## 📹 More info

Coming soon:  
- Demo video of how to use the extension  
- Example screenshots  

---

## License

MIT License.
