# 🇹🇷 Atatürk İlke ve İnkılapları Panosu

> Sınıf ekranlarına özel, interaktif dijital okul panosu.

**🔗 Canlı Demo:** [ata1923.netlify.app](https://ata1923.netlify.app)

---

## 📖 Hakkında

Bu proje, Atatürk'ün ilke ve inkılaplarını görsel, dinamik ve sesli bir şekilde sunan tek sayfalık bir web uygulamasıdır. Herhangi bir kurulum veya bağımlılık gerektirmez — sadece bir tarayıcı yeterlidir.

Özellikle akıllı tahta ve sınıf ekranlarında kiosk modu ile bırakılmak üzere tasarlanmıştır.

---

## ✨ Özellikler

| Özellik | Açıklama |
|---|---|
| 🕐 Canlı Saat | Türkçe tarih ve HH:MM:SS formatında gerçek zamanlı saat |
| 🖼️ Ken Burns Efekti | Tarihi fotoğraflarda yumuşak zoom + kaydırma animasyonu |
| 🔊 Sesli Okuma (TTS) | Türkçe ses sentezi ile alıntı okuma (`S` tuşu) |
| 📅 Zaman Çizelgesi | 17 tarihi olay, renk kodlu kategorilerle (zafer, reform, antlaşma…) |
| 🌙 Karanlık / Aydınlık Tema | Tek tıkla tema değiştirme, tercih kaydedilir |
| ⌨️ Klavye Kısayolları | Hızlı gezinme ve kontrol |
| 📺 Kiosk Modu | Kontrolleri gizler, 24 saatte bir otomatik yeniler |
| 💾 LocalStorage | Son konum, tema ve süre tarayıcıda saklanır |

---

## ⌨️ Klavye Kısayolları

| Tuş | İşlev |
|---|---|
| `←` / `→` | Önceki / Sonraki olay |
| `R` | Rastgele olay |
| `F` | Tam ekran |
| `O` | Otomatik oynatma aç/kapat |
| `S` | Alıntıyı sesli oku |

---

## 📅 Zaman Çizelgesi Kategorileri

- 🔴 **Dönüm Noktası** (milestone)
- 🟢 **Zafer** (victory)
- 🔵 **İnkılap / Reform** (reform)
- 🟣 **Antlaşma** (treaty)

Dönemler: *Millî Mücadele · Zafer · Cumhuriyet · İnkılaplar · Modern Türkiye*

---

## 🖥️ Kullanım

### Normal Kullanım

Dosyayı doğrudan tarayıcıda açın ya da canlı linki ziyaret edin:

```
https://ata1923.netlify.app
```

### Kiosk Modu (Sınıf Ekranı)

URL'ye `?kiosk=true` ekleyin:

```
https://ata1923.netlify.app?kiosk=true
```

Kiosk modunda:
- Tüm kontrol butonları gizlenir
- Otomatik oynatma başlar
- 24 saatte bir sayfa kendiliğinden yenilenir

---

## 🛠️ Teknik Detaylar

- **Saf HTML/CSS/JS** — framework veya build adımı yok
- **Google Fonts:** Playfair Display (alıntılar) + Inter (arayüz)
- **TTS:** `window.speechSynthesis` API, dil: `tr-TR`
- **Tema:** `data-theme` attribute + CSS custom properties
- **Animasyon:** %100 CSS (Ken Burns: `scale` + `translate`, 22s döngü)
- **Görsel fallback:** Resim yüklenemezse otomatik alternatif arka plan

---

## 📁 Dosya Yapısı

```
ata_pano/
└── index.html   # Tek dosya, tüm uygulama burada
```

---

## 👨‍🏫 Geliştirici

**Canan Akalın** — İngilizce Öğretmeni & EdTech Geliştirici

- 🌐 [Portfolio](https://canakalin.netlify.app)
- 💻 [GitHub](https://github.com/canakalin89)

---

## 📄 Lisans

MIT — Eğitim amaçlı serbestçe kullanılabilir.
