# Aksu Köyü Web Sitesi

Sakarya'nın Hendek ilçesine bağlı Aksu köyünün resmi web sitesi. Modern ve kullanıcı dostu bir arayüz ile köy hakkında bilgiler sunar.

## 🚀 Özellikler

### 📱 Responsive Tasarım
- Mobil, tablet ve masaüstü uyumlu
- Modern ve temiz arayüz
- Yeşil renk teması

### 🏠 Sayfalar
- **Anasayfa** - Köy tanıtımı ve hızlı linkler
- **Köyümüz** - Tarihçe, coğrafi konum, nüfus ve muhtarlık bilgileri
- **Yaşam** - Kültür ve gelenekler, doğal güzellikler, yöresel lezzetler
- **Galeri** - Fotoğraf galerisi
- **İletişim** - İletişim bilgileri

### 🗺️ Harita Entegrasyonu
- OpenStreetMap entegrasyonu
- Aksu köyü koordinatları: 40°42'15.1"N 30°51'08.5"E
- Haritada açma özelliği

### 📸 Galeri Sistemi
- Otomatik görsel yükleme
- Responsive grid düzeni
- Lazy loading desteği

## 🛠️ Teknolojiler

- **Framework:** Astro
- **Styling:** Tailwind CSS
- **Language:** TypeScript
- **Build Tool:** Vite

## 📦 Kurulum

### Gereksinimler
- Node.js (v16 veya üzeri)
- npm veya yarn

### Adımlar

1. **Projeyi klonlayın:**
```bash
git clone [repository-url]
cd aksu
```

2. **Bağımlılıkları yükleyin:**
```bash
npm install
```

3. **Geliştirme sunucusunu başlatın:**
```bash
npm run dev
```

4. **Tarayıcıda açın:**
```
http://localhost:4321
```

## 📁 Proje Yapısı

```
aksu/
├── public/                 # Statik dosyalar
│   ├── galeri/            # Galeri görselleri
│   ├── logo-*.png         # Logo dosyaları
│   └── ...
├── src/
│   ├── components/        # Astro bileşenleri
│   │   ├── Hero.astro
│   │   ├── Features.astro
│   │   ├── Testimonial.astro
│   │   ├── CTA.astro
│   │   └── Footer.astro
│   ├── layouts/           # Sayfa düzenleri
│   │   └── Layout.astro
│   └── pages/             # Sayfa dosyaları
│       ├── index.astro    # Anasayfa
│       ├── koyumuz.astro  # Köyümüz sayfası
│       ├── yasam.astro    # Yaşam sayfası
│       ├── galeri.astro   # Galeri sayfası
│       └── iletisim.astro # İletişim sayfası
├── package.json
├── tailwind.config.cjs
└── README.md
```

## 🖼️ Galeri Kullanımı

### Görselleri Ekleme

1. **Galeri klasörünü oluşturun:**
```bash
mkdir public/galeri
```

2. **Görselleri yükleyin:**
```bash
# public/galeri/ klasörüne görsellerinizi kopyalayın
cp your-images/* public/galeri/
```

3. **Kodu güncelleyin:**
`src/pages/galeri.astro` dosyasındaki `galeriGorselleri` dizisini güncelleyin:

```javascript
const galeriGorselleri = [
    'gorsel1.jpg',
    'gorsel2.jpg',
    'gorsel3.jpg',
    // ... diğer görseller
];
```

### Desteklenen Formatlar
- JPG/JPEG
- PNG
- WebP
- GIF

## 🎨 Özelleştirme

### Renk Teması
Yeşil renk teması `tailwind.config.cjs` dosyasında tanımlanmıştır:

```javascript
colors: {
  green: {
    50: '#f0fdf4',
    100: '#dcfce7',
    // ... diğer tonlar
    600: '#16a34a', // Ana yeşil renk
  }
}
```

### İçerik Güncelleme
Tüm içerikler ilgili `.astro` dosyalarında hardcoded olarak bulunur. Değişiklik yapmak için:

1. İlgili dosyayı açın
2. İçeriği güncelleyin
3. Sunucu otomatik olarak yeniden yüklenecektir

## 📱 Responsive Breakpoint'ler

- **Mobile:** < 768px
- **Tablet:** 768px - 1024px
- **Desktop:** > 1024px

## 🚀 Production Build

### Build oluşturun:
```bash
npm run build
```

### Preview:
```bash
npm run preview
```

## 📞 İletişim Bilgileri

**HP-Hanauer Pflegedienst GmbH**
- **Adres:** Kanaltorplatz 7, 63450 Hanau
- **Telefon:** 06181 / 21 0 26
- **Faks:** 06181 / 25 88 71
- **E-posta:** leitung@hanauer-pflegedienst.de
- **Web:** www.hanauer-pflegedienst.de

## 📄 Lisans

Bu proje özel kullanım için geliştirilmiştir.

## 🤝 Katkıda Bulunma

1. Projeyi fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun

## 📝 Changelog

### v1.0.0 (2024)
- ✅ Anasayfa oluşturuldu
- ✅ Köyümüz sayfası eklendi
- ✅ Yaşam sayfası eklendi
- ✅ Galeri sayfası eklendi
- ✅ İletişim sayfası eklendi
- ✅ Responsive tasarım tamamlandı
- ✅ Harita entegrasyonu yapıldı
- ✅ Footer linkleri güncellendi

---

**Aksu Köyü Web Sitesi** - Hendek, Sakarya

