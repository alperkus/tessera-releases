# Tessera

**Windows için ücretsiz SSH istemcisi** · **Free SSH client for Windows**

Sunucularınızı klasör ağacında düzenleyin, parolalarınızı ve SSH anahtarlarınızı şifreli bir kasada saklayın, oturumları tek sekmede yan yana açın.
Organize your servers in a folder tree, keep passwords and SSH keys in an encrypted vault, and open sessions side by side in a single tab.

## İndir · Download

### [⬇ Tessera-Setup.exe](https://github.com/alperkus/tessera-releases/releases/latest/download/Tessera-Setup.exe)

Bu bağlantı her zaman en son sürümü indirir. Tüm sürümler ve sürüm notları: [Releases](https://github.com/alperkus/tessera-releases/releases).
This link always downloads the latest version. All versions and release notes: [Releases](https://github.com/alperkus/tessera-releases/releases).

| | |
|---|---|
| İşletim sistemi · OS | Windows 10 (2004+) / Windows 11 |
| Mimari · Architecture | x64 ve ARM64 tek kurulumda · x64 and ARM64 in one installer |
| Yönetici izni · Admin rights | Gerekmez (kullanıcıya kurulur) · Not required (per-user install) |
| Fiyat · Price | Ücretsiz · Free |

Tessera kurulduktan sonra yeni sürümleri kendisi bildirir; imzası doğrulanan güncelleme tek tıkla kurulur.
Once installed, Tessera notifies you about new versions; updates are installed with one click after their signature is verified.

## Özellikler · Features

- Klasör ağacında sunucular; prod / test / lab ortam renkleri · Server tree with prod / test / lab environment colors
- Mozaik bölmeler ve toplu komut gönderimi · Mosaic panes and broadcast input
- SFTP dosya aktarımı (sürükle-bırak) · SFTP file transfer (drag and drop)
- Şifreli kasa (AES-256-GCM, Argon2id), 24 kelimelik kurtarma anahtarı, Windows Hello · Encrypted vault, 24-word recovery key, Windows Hello
- Parola, SSH anahtarı, Windows OpenSSH Agent, OTP · Password, SSH key, Windows OpenSSH Agent, OTP
- Atlama sunucusu (jump host), sunucu anahtarı doğrulaması · Jump host, host key verification
- Eski ağ cihazlarıyla uyumluluk · Compatibility with older network devices
- Türkçe ve İngilizce arayüz, koyu / açık tema · Turkish and English UI, dark / light theme
- Veri toplamaz, telemetri yok · No data collection, no telemetry

## Güvenlik uyarısı · SmartScreen

Kurulum dosyası şu an kod imzası taşımadığı için Windows SmartScreen ilk çalıştırmada uyarı gösterebilir: **Ek bilgi → Yine de çalıştır**.
The installer is not code-signed yet, so Windows SmartScreen may show a warning on first run: **More info → Run anyway**.

Dosyanın bütünlüğünü sürümle birlikte yayınlanan `SHA256SUMS.txt` ile doğrulayabilirsiniz · You can verify the file with the `SHA256SUMS.txt` published with each release:

```powershell
Get-FileHash .\Tessera-Setup.exe -Algorithm SHA256
```

## Lisans · License

Tessera ücretsiz yazılımdır (freeware). Kullanım koşulları kurulum sırasında gösterilir ve uygulamada **Ayarlar → Hakkında ve yasal bilgiler** bölümündedir. Bu repo yalnız kurulum dosyalarını içerir.
Tessera is freeware. The license terms are shown during installation and are available in the app under **Settings → About and legal information**. This repository contains installer files only.

© 2026 XSECURE BİLGİ VE İLETİŞİM TEKNOLOJİLERİ LİMİTED ŞİRKETİ · İstanbul / Türkiye
