## 🖥️ Termux Native Desktop XFCE4 Installer

🔥 by **Fuad** / [cryptofinderid](https://t.me/cryptofinderid)

---

## 📸 Screenshot

<div align="center">

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/cryptofinderid/Termux-Native-Dekstop-Setup/refs/heads/main/screenshoot/Screenshot_2025-07-10-15-17-27-984_com.termux.x11.jpg" width="260"/></td>
    <td><img src="https://raw.githubusercontent.com/cryptofinderid/Termux-Native-Dekstop-Setup/refs/heads/main/screenshoot/Screenshot_2025-07-10-15-18-01-863_com.termux.x11.jpg" width="260"/></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/cryptofinderid/Termux-Native-Dekstop-Setup/refs/heads/main/screenshoot/Screenshot_2025-07-10-15-18-17-009_com.termux.x11.jpg" width="260"/></td>
    <td><img src="https://raw.githubusercontent.com/cryptofinderid/Termux-Native-Dekstop-Setup/refs/heads/main/screenshoot/Screenshot_2025-07-10-15-19-54-996_com.termux.x11.jpg" width="260"/></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/cryptofinderid/Termux-Native-Dekstop-Setup/refs/heads/main/screenshoot/Screenshot_2025-07-10-15-22-41-407_com.termux.x11.jpg" width="260"/></td>
    <td><img src="https://raw.githubusercontent.com/cryptofinderid/Termux-Native-Dekstop-Setup/refs/heads/main/screenshoot/Screenshot_2025-07-10-15-27-16-258_com.termux.x11.jpg" width="260"/></td>
  </tr>
</table>

</div>

### 📋 Prasyarat

Sebelum memulai instalasi, pastikan Anda sudah memiliki:

| Aplikasi                         | Tautan Unduh                                                                                                          |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| 📱 **Termux** | [`.apk` dari F-Droid](https://f-droid.org/repo/com.termux_1022.apk)                                                   |
| 🪟 **Termux X11**                | [`.apk` dari GitHub Releases](https://github.com/termux/termux-x11/releases/download/nightly/app-universal-debug.apk) |

---

### ⚙️ Langkah Instalasi

#### 1. Buka Termux dan pastikan Anda terhubung ke internet

Kemudian jalankan perintah berikut untuk menginstal `wget` (jika belum tersedia):

```bash
apt-get update -y && apt-get upgrade -y && pkg install wget -y
```

Kalau ada pertanyaan dalam terminal, tekan enter saja (Default)

#### 2. Unduh skrip installer `install.sh` dari GitHub Releases

```bash
wget https://github.com/xrpobo/Termux-Native-Dekstop-Setup/releases/download/v2/install.sh
```

#### 3. Beri izin eksekusi

```bash
chmod +x install.sh
```

---

#### 4. Jalankan proses instalasi

```bash
./install.sh
```

Proses ini akan secara otomatis:

- Membersihkan dan memperbarui sistem
- Menginstal repository dan dependensi penting:
  - x11-repo
  - termux-x11-nightly
  - pulseaudio
  - xfce4
  - tur-repo
- Membuat file `run.sh`
- Menyediakan opsi instalasi tambahan:
  - Chromium Browser
  - Telegram Desktop

Apabila muncul pertanyaan selama proses instalasi, cukup tekan Enter untuk melanjutkan dengan opsi default.

---

### ✅ Menjalankan Desktop

#### 🪟 Rekomendasi pengaturan Termux X11

##### 🔧 Output Settings

- **Resolution Mode:** custom  
- **Resolution:** 1280x720  (Aku di poco F5 pake 1600x720 biar pas layar skala 16:9)
- **Adjust resolution to fit orientation:** OFF  
- **Stretch to fit display:** OFF  
- **Reseed screen when keyboard is open:** OFF  
- **PIP mode:** OFF  
- **Fullscreen:** ON  
- **Orientation:** landscape  
- **Hide display cutout:** OFF  
- **Keep screen on:** ON  

---

##### 🖱️ Pointer Settings

- Nothing has changed  

---

##### ⌨️ Keyboard Settings

- **Show additional keyboard:** OFF  
- **Show IME with external keyboard:** ON  
- **Prefer scancodes when possible:** OFF  
- **Hardware keyboard scancodes workaround:** ON  
- **Accessibility shortcut interception:** UNCHANGED  
- **Enforce char-based input:** OFF  

---

##### ⚙️ Other Settings

- Nothing has changed

---

Setelah proses instalasi selesai, dan pengaturan sudah pas, Anda dapat langsung menjalankan XFCE4 Desktop dengan perintah berikut:

```bash
./run.sh
```

### 🙏 Terima Kasih

---
