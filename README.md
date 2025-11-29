# 🌐 Kişisel Portfolio Website

Modern ve responsive tasarıma sahip, full-stack developer için hazırlanmış profesyonel kişisel portfolio websitesi.

## 📋 Proje Hakkında

Bu proje, yeteneklerimi, projelerimi ve iletişim bilgilerimi sergilemek için tasarlanmış tek sayfalık (single-page) bir portfolio websitesidir. Temiz kod yapısı, modern tasarım prensipleri ve kullanıcı dostu arayüzü ile dikkat çekmektedir.

### ✨ Özellikler

- 📱 **Responsive Tasarım**: Tüm cihazlarda mükemmel görünüm
- 🎨 **Modern UI/UX**: Gradient renkler ve smooth animasyonlar
- 🚀 **Performans**: Optimize edilmiş ve hızlı yükleme
- 📊 **İnteraktif Elementler**: Animasyonlu skill bar'lar ve counter'lar
- 📝 **İletişim Formu**: Validasyon ve bildirim sistemi ile
- 🎯 **Smooth Navigation**: Akıcı scroll ve active link tracking
- 💼 **Proje Vitrine**: Hover efektleri ile proje kartları
- 📈 **İstatistik Kartları**: Animasyonlu sayaç gösterimi

## 🛠️ Kullanılan Teknolojiler

### Frontend
- **HTML5**: Semantik ve erişilebilir yapı
- **CSS3**: Modern styling, flexbox, grid, animasyonlar
- **JavaScript (ES6+)**: Vanilla JS ile interaktif özellikler

### Öne Çıkan Teknikler
- CSS Variables (Custom Properties)
- CSS Grid & Flexbox
- Intersection Observer API
- Smooth Scrolling
- Form Validation
- LocalStorage (opsiyonel kullanım için hazır)
- Responsive Design (Mobile-First Approach)


## 🚀 Nasıl Çalıştırılır?

### 1. Projeyi İndirin

```bash
# Repository'yi klonlayın
git clone https://github.com/kullaniciadi/portfolio-website.git

# Proje klasörüne gidin
cd portfolio-website
```

### 2. Projeyi Açın

#### Yöntem 1: Doğrudan Tarayıcıda
- `index.html` dosyasına çift tıklayın
- Veya dosyayı sürükleyip tarayıcıya bırakın

#### Yöntem 2: Live Server ile (Önerilen)
- VS Code kullanıyorsanız, **Live Server** extension'ını yükleyin
- `index.html` dosyasına sağ tıklayıp "Open with Live Server" seçin
- Otomatik olarak `http://localhost:5500` adresinde açılacaktır

#### Yöntem 3: Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Ardından tarayıcıda `http://localhost:8000` adresine gidin.

### 3. Özelleştirme

#### Kendi Bilgilerinizi Ekleyin:

**index.html dosyasında:**
- İsim ve meslek bilgisi (line 22-24)
- Hakkımda metni (line 48-60)
- Yetenekler ve yüzdeleri (line 76-139)
- Proje bilgileri (line 153-277)
- İletişim bilgileri (line 297-319)

**style.css dosyasında:**
- Renk şeması (CSS variables, line 9-17)
- Font ailesi (line 23)
- Spacing ve sizing ayarları

**script.js dosyasında:**
- Animasyon süreleri
- Form gönderim endpoint'i (gerçek kullanım için)

## 🌐 GitHub Pages ile Yayınlama

1. GitHub'da yeni bir repository oluşturun
2. Dosyalarınızı yükleyin:
```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/kullaniciadi/portfolio-website.git
git push -u origin main
```
3. Repository Settings → Pages bölümüne gidin
4. Source: `main` branch seçin ve Save
5. Siteniz `https://kullaniciadi.github.io/portfolio-website/` adresinde yayında!


## 📝 Lisans

Bu proje eğitim amaçlıdır ve özgürce kullanılabilir.


## 🙏 Teşekkürler

Bu projeyi incelediğiniz için teşekkür ederim! Sorularınız veya önerileriniz için issue açabilir veya pull request gönderebilirsiniz.

---

⭐ **Projeyi beğendiyseniz yıldız vermeyi unutmayın!**
