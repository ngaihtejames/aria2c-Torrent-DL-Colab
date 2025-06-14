
# 📥 Colab Torrent Downloader

Download torrent files directly to your Google Drive using a simple Google Colab notebook — **no complex setup, no coding skills required!**

---

## 🚀 Features

✅ **User-friendly:** Paste your magnet link in a text field — no need to edit any code.  
✅ **Direct to Google Drive:** Saves downloaded files in a folder inside your Drive.  
✅ **No seeding:** Downloads only — no background seeding to drain your bandwidth.  
✅ **Fully automated:** Mounts Drive, installs `aria2c`, creates folders, and handles everything step-by-step.

---

## 📂 How it works

This notebook uses [aria2c](https://aria2.github.io/) — a lightweight, fast downloader — to fetch torrent content using a magnet link. It saves all files into a folder named `Colab_Torrent_Downloads` in your Google Drive.

---

## ⚙️ How to use

1. **Open in Google Colab:**  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ngaihtejames/colab-torrent-downloader/blob/main/Colab_Torrent_Downloader.ipynb)

2. **Run each cell in order:**  
   - **Mount Google Drive**  
   - **Install aria2c**  
   - **Create download folder**  
   - **Paste your magnet link**  
   - **Start the download**

3. **Find your files in Google Drive:**  
   All downloaded files will appear in `My Drive/Colab_Torrent_Downloads`.

---

## 📌 Notes & Tips

⚠️ **This is for personal use only — respect copyright laws.**  
🔒 Your Google account storage quota applies — make sure you have enough space.  
🚫 This notebook disables seeding to avoid unnecessary bandwidth usage.

---

## 📎 Repository Contents

```
.
├── Colab_Torrent_Downloader.ipynb  # The ready-to-use Colab notebook
├── README.md                       # This file
├── LICENSE                         # MIT License
```

---

## 📜 License

This project is released under the [MIT License](LICENSE).  
Use responsibly — **downloading copyrighted content is illegal in many countries.**

---

## 🙌 Credits

Built with ❤️ using [aria2](https://aria2.github.io/) and [Google Colab](https://colab.research.google.com/).

---

## ⭐️ Show your support

If you find this useful, give the repo a ⭐️ and share it with others!
