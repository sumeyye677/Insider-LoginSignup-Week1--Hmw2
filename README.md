# 🔐 İnteraktif Login ve Signup Sayfaları

Modern ve kullanıcı dostu login/signup sayfaları projesi. HTML ve CSS kullanılarak oluşturulmuş, responsive tasarım ve interaktif özellikler içerir.

## 📋 Proje Hakkında

Bu proje, kullanıcıların giriş yapabileceği ve yeni hesap oluşturabileceği iki ayrı sayfa içerir. Modern web tasarım standartlarına uygun olarak geliştirilmiştir.

## 🚀 Özellikler

### ✨ Temel Özellikler
- **Login Sayfası** - Kullanıcı giriş formu
- **Signup Sayfası** - Yeni kullanıcı kayıt formu
- **Responsive Tasarım** - Tüm cihazlarda uyumlu
- **Form Validasyonu** - Gerekli alanların kontrolü
- **Sayfalar Arası Geçiş** - Kolay navigasyon

### 🎨 Tasarım Özellikleri
- **Modern UI/UX** - Temiz ve kullanıcı dostu arayüz
- **Google Fonts** - Inter yazı tipi ailesi
- **Hover Efektleri** - Buton ve input etkileşimleri
- **Focus Efektleri** - Input alanları için görsel geri bildirim
- **Smooth Animasyonlar** - Yumuşak geçiş efektleri
- **Glassmorphism** - Modern cam efekti

### 🔧 Bonus Özellikler
- ✅ "Beni Hatırla" checkbox'ı
- ✅ "Şifreyi Onayla" alanı
- ✅ Placeholder metinler
- ✅ Required field validasyonu
- ✅ Hover ve focus efektleri

## 📁 Dosya Yapısı

```
proje-klasoru/
├── login.html          # Giriş sayfası
├── signup.html         # Kayıt sayfası
├── style.css           # Tek CSS dosyası (ortak stil)
└── README.md           # Proje dokümantasyonu
```

## 🛠️ Teknolojiler

- **HTML5** - Sayfa yapısı ve form elemanları
- **CSS3** - Styling ve animasyonlar
- **Google Fonts** - Yazı tipi (Inter)
- **Responsive Design** - Mobil uyumlu tasarım

## 🎯 Kullanım

1. **Dosyaları İndirin:**
   ```bash
   git clone [repo-url]
   ```

2. **Dosyaları Yerleştirin:**
   - Tüm dosyaları aynı klasöre kaydedin
   - `login.html`, `signup.html` ve `style.css` aynı dizinde olmalı

3. **Tarayıcıda Açın:**
   - `login.html` dosyasını çift tıklayarak açın
   - Veya favori tarayıcınızla dosyayı açın

## 📱 Responsive Tasarım

Proje farklı ekran boyutlarında optimize edilmiştir:
- **Desktop** - Tam özellikli görünüm
- **Tablet** - Orta boy ekranlar için optimize
- **Mobile** - Mobil cihazlar için uyarlanmış

## 🎨 Renk Paleti

- **Arka Plan:** `#f0f4f8` (Soluk mavi-gri)
- **Form Kutusu:** `#ffffff` (Beyaz)
- **Başlık:** `#333333` (Koyu gri)
- **Vurgu Rengi:** `#667eea` (Mavi)
- **Hover Rengi:** `#5a67d8` (Koyu mavi)

## 🔧 Özelleştirme

### Renkleri Değiştirmek
`style.css` dosyasında ilgili CSS değişkenlerini düzenleyin:
```css
/* Ana renk değişkenleri */
:root {
  --primary-color: #667eea;
  --secondary-color: #764ba2;
  --background-color: #f0f4f8;
}
```

### Yazı Tipini Değiştirmek
HTML dosyalarında Google Fonts linkini güncelleyin:
```html
<link href="https://fonts.googleapis.com/css2?family=YeniFont:wght@300;400;500;600&display=swap" rel="stylesheet">
```

## 📋 Form Alanları

### Login Formu
- E-posta adresi (required)
- Şifre (required)
- Beni Hatırla (checkbox)

### Signup Formu
- Ad Soyad (required)
- E-posta adresi (required)
- Şifre (required)
- Şifreyi Onayla (required)

## 🔒 Güvenlik Notları

- Bu proje sadece frontend tasarımını içerir
- Gerçek bir uygulamada backend validasyonu gereklidir
- Şifreler güvenli şekilde hashlenmeli
- HTTPS kullanılmalı
