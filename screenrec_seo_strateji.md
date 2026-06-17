# ScreenRec – Kapsamlı SEO Stratejisi (2026)
> Online ekran kaydedici / Bandicam alternatifi için organik trafik rehberi

---

## 1. Teknik SEO – Yapılan Değişiklikler (HTML Dosyasında)

### ✅ Düzeltilen / Eklenen Meta Etiketler

| Alan | Önceki | Sonraki |
|------|--------|---------|
| `<html lang>` | `en` | `tr` (varsayılan Türkçe) |
| `<title>` | "ScreenRec – Free Online Screen Recorder…" | **"Online Ekran Kaydedici – Ücretsiz, Programsız \| ScreenRec"** |
| `<meta description>` | İngilizce ağırlıklı | Türkçe birincil, anahtar kelime yoğun |
| `<meta robots>` | `index, follow` | `index, follow, max-snippet:-1, max-image-preview:large` |
| `<meta theme-color>` | Yok | `#13151A` eklendi |
| `og:locale` | `en_US` | `tr_TR` (10 alternatif locale eklendi) |
| hreflang | Yok | **11 dil için hreflang eklendi** |
| Schema: WebApplication | Temel | AggregateRating + availability eklendi |
| Schema: FAQPage | **Yok** | **7 soru-cevap ile eklendi** |
| Schema: BreadcrumbList | **Yok** | **Eklendi** |

### ✅ Eklenen SEO İçerik Bölümleri (Sayfa Altı)
- **Hero açıklama** – "Online ekran kaydedici nedir?" (Featured Snippet hedefli)
- **Özellikler listesi** – 5 madde, anahtar kelimelerle zenginleştirilmiş
- **Nasıl kullanılır** – 3 adımlı (HowTo Schema uyumlu yapı)
- **SSS bölümü** – 6 soru, `<details>` etiketiyle interaktif, FAQPage schema ile senkronize

---

## 2. hreflang Yapısı – 10 Dil

```html
<link rel="alternate" hreflang="tr" href="https://screenrec.app/?lang=tr">
<link rel="alternate" hreflang="en" href="https://screenrec.app/?lang=en">
<link rel="alternate" hreflang="zh" href="https://screenrec.app/?lang=zh">
<link rel="alternate" hreflang="hi" href="https://screenrec.app/?lang=hi">
<link rel="alternate" hreflang="es" href="https://screenrec.app/?lang=es">
<link rel="alternate" hreflang="fr" href="https://screenrec.app/?lang=fr">
<link rel="alternate" hreflang="ar" href="https://screenrec.app/?lang=ar">
<link rel="alternate" hreflang="bn" href="https://screenrec.app/?lang=bn">
<link rel="alternate" hreflang="pt" href="https://screenrec.app/?lang=pt">
<link rel="alternate" hreflang="ru" href="https://screenrec.app/?lang=ru">
<link rel="alternate" hreflang="ur" href="https://screenrec.app/?lang=ur">
<link rel="alternate" hreflang="x-default" href="https://screenrec.app/">
```

> **Not:** URL yapınızı `?lang=tr` yerine `/tr/`, `/en/` alt dizin yapısına taşırsanız SEO etkisi daha güçlü olur.

---

## 3. robots.txt Önerisi

Sitenizin kökünde `robots.txt` dosyası oluşturun:

```
User-agent: *
Allow: /

User-agent: Googlebot
Allow: /

Sitemap: https://screenrec.app/sitemap.xml

# Gereksiz parametreleri tara
Disallow: /?utm_*
Disallow: /?fbclid=*
```

---

## 4. sitemap.xml Önerisi

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"
        xmlns:xhtml="http://www.w3.org/1999/xhtml">

  <!-- Ana Sayfa – 11 dil versiyonu -->
  <url>
    <loc>https://screenrec.app/</loc>
    <xhtml:link rel="alternate" hreflang="tr" href="https://screenrec.app/?lang=tr"/>
    <xhtml:link rel="alternate" hreflang="en" href="https://screenrec.app/?lang=en"/>
    <xhtml:link rel="alternate" hreflang="zh" href="https://screenrec.app/?lang=zh"/>
    <xhtml:link rel="alternate" hreflang="hi" href="https://screenrec.app/?lang=hi"/>
    <xhtml:link rel="alternate" hreflang="es" href="https://screenrec.app/?lang=es"/>
    <xhtml:link rel="alternate" hreflang="fr" href="https://screenrec.app/?lang=fr"/>
    <xhtml:link rel="alternate" hreflang="ar" href="https://screenrec.app/?lang=ar"/>
    <xhtml:link rel="alternate" hreflang="bn" href="https://screenrec.app/?lang=bn"/>
    <xhtml:link rel="alternate" hreflang="pt" href="https://screenrec.app/?lang=pt"/>
    <xhtml:link rel="alternate" hreflang="ru" href="https://screenrec.app/?lang=ru"/>
    <xhtml:link rel="alternate" hreflang="ur" href="https://screenrec.app/?lang=ur"/>
    <xhtml:link rel="alternate" hreflang="x-default" href="https://screenrec.app/"/>
    <lastmod>2026-06-18</lastmod>
    <changefreq>weekly</changefreq>
    <priority>1.0</priority>
  </url>

  <!-- Blog sayfaları (ileride eklenecek) -->
  <!-- <url>
    <loc>https://screenrec.app/blog/online-ekran-kaydedici-nasil-kullanilir</loc>
    <lastmod>2026-06-18</lastmod>
    <changefreq>monthly</changefreq>
    <priority>0.8</priority>
  </url> -->

</urlset>
```

---

## 5. Hedef Anahtar Kelimeler – Türkçe

### Birincil Anahtar Kelimeler (Yüksek Öncelik)

| Anahtar Kelime | Arama Niyeti | Zorluk |
|----------------|-------------|--------|
| online ekran kaydedici | Araçsal | Orta |
| ücretsiz ekran kayıt programı | Araçsal | Orta |
| programsız ekran kaydı | Araçsal | Düşük |
| ekran video kaydedici | Araçsal | Orta |
| tarayıcıdan ekran kaydı | Araçsal | Düşük |

### Long-tail Anahtar Kelimeler (Hızlı Sıralama İçin)

**Türkçe:**
- "bilgisayar ekranını ücretsiz kaydet"
- "ekran kaydı programsız nasıl yapılır"
- "online ekran kaydedici hesapsız"
- "chrome ile ekran kaydı nasıl yapılır"
- "ekran videosu çekme ücretsiz"
- "bandicam alternatifi ücretsiz online"
- "obs olmadan ekran kaydı"
- "zoom toplantısı ekran kaydı ücretsiz"
- "youtube için ekran kaydı nasıl alınır"
- "ders anlatımı için ekran kaydı"
- "uzaktan çalışma ekran kaydı"
- "presentation ekran kaydı"

**İngilizce (EN):**
- "record screen without software"
- "browser screen recorder no download"
- "free screen recorder no watermark no account"
- "online screen recorder chrome extension alternative"
- "record screen and microphone free"
- "how to record screen without bandicam"
- "best free online screen recorder 2026"

**İspanyolca (ES):**
- "grabador de pantalla online gratis sin instalar"
- "capturar pantalla gratis sin programas"

**Fransızca (FR):**
- "enregistreur d'écran en ligne gratuit sans logiciel"
- "capturer écran navigateur gratuitement"

**Rusça (RU):**
- "запись экрана онлайн бесплатно без установки"
- "бесплатный рекордер экрана в браузере"

**Hintçe (HI):**
- "मुफ्त स्क्रीन रिकॉर्डर ऑनलाइन"
- "बिना सॉफ्टवेयर स्क्रीन रिकॉर्ड करें"

**Portekizce (PT):**
- "gravador de tela online grátis sem instalar"
- "como gravar tela sem programa"

**Arapça (AR):**
- "تسجيل الشاشة مجاناً بدون تحميل"
- "مسجل شاشة أونلاين مجاني"

---

## 6. Blog Konu Önerileri (Organik Trafik İçin)

### Türkçe Blog Yazıları

1. **"Ekran Kaydı Nasıl Yapılır? 2026 Rehberi"**
   - Hedef KW: "ekran kaydı nasıl yapılır"
   - Format: Adım adım rehber + ekran görüntüleri
   - Trafik potansiyeli: Yüksek

2. **"Bandicam Alternatifi Ücretsiz Programlar (2026)"**
   - Hedef KW: "bandicam alternatifi", "bandicam ücretsiz"
   - Format: Karşılaştırma tablosu
   - Not: Rakip marka trafiğini çekme fırsatı

3. **"OBS Kullanmadan Ekran Kaydı: 5 Kolay Yol"**
   - Hedef KW: "OBS olmadan ekran kaydı"
   - Format: Listicle

4. **"Zoom Toplantısını Nasıl Kaydederim? (İzinsiz Araçlar)"**
   - Hedef KW: "zoom toplantısı kayıt", "zoom ekran kaydı"
   - Trafik potansiyeli: Çok yüksek

5. **"YouTube için Ekran Kaydı Nasıl Çekilir?"**
   - Hedef KW: "youtube ekran kaydı", "youtube ders anlatımı"
   - Format: Video + yazı

6. **"Chrome'da Ekran Kaydı – Eklenti Gerekmez"**
   - Hedef KW: "chrome ekran kaydı", "chrome screen recorder"
   - Hızlı sıralama potansiyeli

7. **"Uzaktan Çalışanlar İçin En İyi Ekran Kayıt Araçları"**
   - Hedef KW: "uzaktan çalışma araçları"
   - Bağlantı kurma potansiyeli yüksek

8. **"WebM vs MP4: Ekran Kaydı İçin Hangi Format Daha İyi?"**
   - Hedef KW: "webm mp4 fark", "ekran kaydı formatı"
   - Uzmanlık içeriği – E-E-A-T için güçlü

### İngilizce Blog Yazıları (Yüksek Trafik Potansiyelli)

1. "Best Free Screen Recorder 2026 – No Watermark, No Account"
2. "How to Record Your Screen on Chrome Without Extensions"
3. "Bandicam vs OBS vs Online Recorder: Which Should You Use?"
4. "Record Zoom Meetings for Free (Legal Methods)"
5. "Screen Recording for Remote Teams: Complete Guide"

---

## 7. Core Web Vitals Değerlendirmesi

### Mevcut Güçlü Yönler
- ✅ `prefers-reduced-motion` desteği var (CLS için iyi)
- ✅ Font preconnect etiketi var
- ✅ `aspect-ratio: 16/9` kullanılmış (CLS önler)
- ✅ Responsive tasarım, 380px'e kadar kırılım noktaları var
- ✅ Animasyonlar CSS-only (JS render blocking yok)

### Önerilen İyileştirmeler

**LCP (Largest Contentful Paint):**
```html
<!-- Google Fonts'u font-display:swap ile yükleyin -->
<link href="https://fonts.googleapis.com/css2?family=...&display=swap" rel="stylesheet">
<!-- ✅ Zaten var – iyi -->

<!-- Kritik CSS'i inline alın (ilk 14KB) -->
<!-- Şu an tüm CSS <style> bloğunda inline – bu aslında LCP için olumlu -->
```

**CLS (Cumulative Layout Shift):**
```css
/* Önizleme canvas için min-height ekleyin */
.preview-frame {
  min-height: 200px; /* Yükleme sırasında layout kaymasını önler */
}
```

**INP (Interaction to Next Paint – FID'in yerini aldı):**
- Buton tıklama handler'ları zaten senkron değil, async await kullanıyor ✅
- `mediaDevices.getUserMedia` async ✅

**Önerilen Ek Optimizasyonlar:**
```html
<!-- DNS prefetch ekleyin -->
<link rel="dns-prefetch" href="https://fonts.googleapis.com">

<!-- Resource hints -->
<link rel="preload" as="style" href="https://fonts.googleapis.com/css2?...">
```

---

## 8. Mobil Uyumluluk Değerlendirmesi

### ✅ Mevcut Durumu İyi
- Viewport meta etiketi doğru
- 560px ve 380px breakpoint'leri var
- `flex-wrap` kullanımı yaygın
- Touch-friendly buton boyutları (`min-height: 46px`)

### ⚠️ Dikkat Edilmesi Gereken Noktalar
- `<select>` elementi mobilde native görünür — iOS'ta styling kısıtlıdır
- `backdrop-filter: blur(6px)` eski Android tarayıcılarında çalışmayabilir (fallback ekleyin)
- Ekran kaydı API'si mobil tarayıcılarda **desteklenmez** — kullanıcıyı bilgilendirin

```html
<!-- Mobil kullanıcı uyarısı ekleyin -->
<div id="mobileWarning" style="display:none; padding:12px; background:rgba(255,176,32,.1); border:1px solid rgba(255,176,32,.3); border-radius:10px; font-size:13px; color:#FFD79A; margin-bottom:14px">
  Ekran kaydı özelliği mobil cihazlarda desteklenmemektedir. Lütfen masaüstü tarayıcı kullanın.
</div>
<script>
if (/Mobi|Android/i.test(navigator.userAgent)) {
  document.getElementById('mobileWarning').style.display = 'block';
}
</script>
```

---

## 9. Featured Snippet Stratejisi

Google'da "çerçeveli sonuç" (featured snippet) almak için önerimiz:

### Paragraf Snippet (Definition Box)
Sayfanızda şu yapıyı kullanın:
```html
<h2>Online ekran kaydedici nedir?</h2>
<p>Online ekran kaydedici, bilgisayarınıza herhangi bir program kurmadan, 
yalnızca web tarayıcısı üzerinden ekranınızı kaydetmenizi sağlayan bir 
araçtır. Tarayıcı izni alındıktan sonra kayıt anında başlar.</p>
```

### Liste Snippet (How-to)
"Ekran kaydı nasıl yapılır" sorusu için:
```html
<h2>Ekran kaydı nasıl yapılır?</h2>
<ol>
  <li>screenrec.app adresine gidin</li>
  <li>"Kaydı Başlat" butonuna tıklayın</li>
  <li>Hangi ekranı kaydedeceğinizi seçin</li>
  <li>Kaydı durdurup WebM/MP4 olarak indirin</li>
</ol>
```

---

## 10. 10 Dil İçin Title ve Description Şablonları

| Dil | Title | Meta Description |
|-----|-------|-----------------|
| 🇹🇷 TR | Online Ekran Kaydedici – Ücretsiz, Programsız \| ScreenRec | Tarayıcıdan ücretsiz ekran kaydı. Kurulum yok, hesap yok. Chrome, Edge ve Firefox'ta çalışır. |
| 🇺🇸 EN | Free Online Screen Recorder – No Download, No Account \| ScreenRec | Record your screen for free in your browser. No software, no signup. Works on Chrome, Edge and Firefox instantly. |
| 🇨🇳 ZH | 免费在线录屏工具 – 无需下载 \| ScreenRec | 直接在浏览器中录制屏幕，无需安装软件，无需注册账户。支持Chrome、Edge和Firefox。 |
| 🇮🇳 HI | मुफ्त ऑनलाइन स्क्रीन रिकॉर्डर – डाउनलोड नहीं \| ScreenRec | अपने ब्राउज़र में मुफ्त स्क्रीन रिकॉर्ड करें। कोई सॉफ्टवेयर नहीं, कोई अकाउंट नहीं। |
| 🇪🇸 ES | Grabador de Pantalla Online Gratis – Sin Instalar \| ScreenRec | Graba tu pantalla gratis desde el navegador. Sin descargas, sin cuenta. Funciona en Chrome, Edge y Firefox. |
| 🇫🇷 FR | Enregistreur d'Écran en Ligne Gratuit – Sans Logiciel \| ScreenRec | Enregistrez votre écran gratuitement dans le navigateur. Sans téléchargement, sans compte. Compatible Chrome, Edge, Firefox. |
| 🇸🇦 AR | مسجل شاشة أونلاين مجاني – بدون تحميل \| ScreenRec | سجّل شاشتك مجاناً من المتصفح. لا يلزم تنزيل أي برنامج أو إنشاء حساب. |
| 🇧🇩 BN | বিনামূল্যে অনলাইন স্ক্রিন রেকর্ডার – ডাউনলোড নেই \| ScreenRec | ব্রাউজার থেকে বিনামূল্যে স্ক্রিন রেকর্ড করুন। কোনো সফটওয়্যার বা অ্যাকাউন্ট দরকার নেই। |
| 🇧🇷 PT | Gravador de Tela Online Grátis – Sem Instalar \| ScreenRec | Grave sua tela de graça pelo navegador. Sem downloads, sem cadastro. Funciona no Chrome, Edge e Firefox. |
| 🇷🇺 RU | Бесплатный Онлайн Рекордер Экрана – Без Установки \| ScreenRec | Запишите экран бесплатно прямо в браузере. Без загрузок, без регистрации. Работает в Chrome, Edge и Firefox. |

---

## 11. Backlink Fırsatları

### Hızlı Backlink Kaynakları
- **Product Hunt** – Ürününüzü listeleyin (DA: yüksek)
- **AlternativeTo.net** – "Bandicam alternative", "OBS alternative" olarak ekleyin
- **G2 / Capterra** – Ücretsiz araç olarak listeleyin
- **Reddit** – r/software, r/productivity, r/Turkey topluluklarında organik paylaşım
- **GitHub** – Açık kaynak değilse bile "awesome-screen-recorders" listelerine PR atın

### İçerik Temelli Backlink
- "Ücretsiz ekran kayıt araçları" listeleme makaleleri yazan Türkçe tech bloglarına ulaşın
- Eğitim teknolojisi sitelerine misafir yazı teklifi yapın

---

## Özet Öncelik Listesi

| Öncelik | Görev | Etki |
|---------|-------|------|
| 🔴 Acil | robots.txt oluştur | Teknik |
| 🔴 Acil | sitemap.xml ekle ve Google Search Console'a gönder | Teknik |
| 🟠 Yüksek | Optimize edilmiş HTML'i yayınla | SEO |
| 🟠 Yüksek | Google Search Console'a domain ekle ve doğrula | İzleme |
| 🟡 Orta | Blog bölümü oluştur (ilk 3 yazı) | Trafik |
| 🟡 Orta | AlternativeTo ve ProductHunt'a ekle | Backlink |
| 🟢 Uzun vadeli | 10 dil için ayrı blog yazıları | Uluslararası |
