# 💪 Fitness Tracker Pro

**Arkadaşlarla birlikte antrenman yapın ve fitness hedeflerinize ulaşın!**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-blue?style=for-the-badge)](https://stark4280.github.io/siteantrenman/)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg?style=for-the-badge)](https://github.com/stark4280/siteantrenman)

## 🚀 Özellikler

### 🏋️ **Set Bazlı Takip Sistemi**
- Her egzersiz için ayrı set checkbox'ları
- Otomatik set sayısı algılama (4x10-12 → 4 checkbox)
- Set bazlı ilerleme ve haftalık hedef (Pzt-Çrş-Cuma tamamlanınca sıfırlama teklifi)
- LocalStorage + Firestore (bulut senkron)

### ⏰ **Akıllı Dinlenme Timer'ı**
- Set tamamlandığında otomatik başlar
- Son set sonrası egzersiz arası daha uzun dinlenme
- Arka planda çalışmaya devam eder (ses yok, sadece vibrasyon)
- Progress bar ile görsel geri bildirim

### 📱 **Mobil Optimizasyon**
- Responsive, dokunma dostu arayüz
- PWA (Ana ekrana ekle banner’ı – Android prompt, iOS yönerge)
- Offline çalışma (service worker önbelleği)

### 🎯 **Egzersiz Detayları**
- Uzun basınca (0.5 sn) açılır
- Detaylı nasıl yapılır açıklamaları
- Kas grupları ve Türkçe+İngilizce karşılıklar
- Önemli ipuçları ve güvenlik uyarıları

## 🎨 **Tasarım Özellikleri**

- **Minimal siyah-gri** tema, yüksek kontrast
- Net tipografi (Inter + JetBrains Mono zamanlayıcı)
- Daha geniş dokunma hedefleri ve ferah boşluklar

## 📱 **Kullanım**

### 1. **Program Seçimi**
- ABA veya BAB düzeni seçin
- Antrenman gününü belirleyin

### 2. **Set Takibi**
- Egzersizi tamamlayın
- İlgili set checkbox'ını işaretleyin
- Timer otomatik başlar

### 3. **Egzersiz Detayları**
- Egzersize kısa süre (0.5 sn) basılı tutun
- Detaylı açıklamaları okuyun
- Kas gruplarını öğrenin

### 4. **Dinlenme Timer'ı**
- Timer arka planda çalışır
- Bittiğinde vibrasyon bildirimi
- İsterseniz iptal edebilirsiniz

## 🛠️ **Teknik Detaylar**

- **Vanilla JavaScript**, **HTML5**, **CSS3**
- **LocalStorage** + **Firestore** (anonim oturum, bulut senkron)
- **Web APIs** – Vibrasyon
- **PWA** – manifest + service worker, A2HS banner

## 🚀 **GitHub Pages'de Yayınlama**

### 1. **Repository Ayarları**
```bash
# Repository'yi klonlayın
git clone https://github.com/stark4280/siteantrenman.git
cd siteantrenman

# GitHub Pages'i aktif edin
# Settings > Pages > Source: Deploy from a branch
# Branch: main, Folder: / (root)
```

### 2. **Deploy**
```bash
# Değişiklikleri commit edin
git add .
git commit -m "🚀 Initial release"
git push origin main

# GitHub Pages otomatik deploy eder
# https://stark4280.github.io/siteantrenman/
```

## 📁 **Dosya Yapısı**

```
siteantrenman/
├── index.html          # Ana sayfa
├── README.md           # Bu dosya
├── .gitignore          # Git ignore
├── sw.js               # Service worker (PWA)
├── manifest.webmanifest# PWA manifest
└── icons/              # PWA ikonları (ekleyin)
    ├── icon-192.png
    ├── icon-512.png
    └── maskable-512.png
```

## 🎯 **Gelecek Özellikler**

- [ ] Haftalık/aylık istatistikler ve grafikler
- [ ] Hedef belirleme
- [ ] Push bildirimleri (isteğe bağlı)

## 🤝 **Katkıda Bulunma**

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit yapın (`git commit -m 'Add some AmazingFeature'`)
4. Push yapın (`git push origin feature/AmazingFeature`)
5. Pull Request açın

## 📄 **Lisans**

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 🙏 **Teşekkürler**

- **Fitness topluluğu** - İlham ve geri bildirim için
- **GitHub** - Ücretsiz hosting için
- **Modern web teknolojileri** - Güçlü araçlar için

## 📞 **İletişim**

- **GitHub**: [@stark4280](https://github.com/stark4280)
- **Proje**: [Fitness Tracker](https://github.com/stark4280/siteantrenman)

---

⭐ **Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!** ⭐

**Made with ❤️ for fitness enthusiasts**
