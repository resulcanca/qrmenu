# QR Menü Sistemi (Tek Sayfa Web Uygulaması)

Bu proje, restoran/cafe gibi işletmeler için hazırlanmış **QR kod ile açılabilen**, tek dosyada çalışan (**HTML + CSS + JavaScript**) bir **dijital menü** uygulamasıdır.  
Kullanıcı tarafında kategori bazlı menü görüntüleme, arama, tema seçimi ve çoklu dil desteği bulunur. Admin tarafında ise ürün, kampanya ve genel ayarlar yönetilebilir.

> Proje herhangi bir kurulum gerektirmez; tarayıcıda doğrudan çalışır.

---

## Özellikler

### Müşteri Tarafı (Menü)
- **Kategori Navigasyonu:** Yemekler / İçecekler / Tatlılar
- **Ürün Arama:** İsim ve açıklama üzerinden gerçek zamanlı filtreleme
- **Ürün Kartları:**
  - Görsel + başlık + açıklama + fiyat
  - İndirimli ürünlerde “% indirim” rozeti ve çizili eski fiyat
- **Görsel Galeri (Modal):**
  - Ürüne tıklayınca büyük görsel + detay + fiyat gösterimi
- **Tema Seçimi:**
  - Mavi, Karanlık, Yeşil, Mor, Turuncu, Kırmızı
- **Dil Seçimi:**
  - Türkçe / English / Deutsch
- **Kampanya Banner’ı:**
  - Aktif edildiğinde üstte duyuru bandı (ör. “%20 indirim”)

### Admin Panel
- **Giriş Ekranı (Basit Doğrulama)**
  - Varsayılan: `admin / 123456`
- **Sekmeler:**
  - Ürünler
  - Kampanyalar
  - Ayarlar
- **Ürün Yönetimi:**
  - Ürün ekleme/düzenleme/silme
  - Kategori seçimi
  - Fiyat ve indirim oranı girme
  - Ürün açıklaması girme
  - Görsel yükleme (dosya seçme + sürükle-bırak)
  - Görsel önizleme
- **Kampanya Yönetimi:**
  - Kampanya aktif/pasif toggle
  - Kampanya metni
  - Kampanya kategorisi (tüm ürünler veya belirli kategori)
  - Kampanya indirim oranı
- **Genel Ayarlar:**
  - Restoran adı
  - Alt başlık
  - WiFi şifresi

---

## Kullanılan Teknolojiler

- **HTML5**
- **CSS3**
  - CSS değişkenleri ile tema yönetimi (`:root`, `[data-theme]`)
  - Responsive tasarım (Media Queries)
  - Modern UI (glass effect, shadows, rounded corners)
- **JavaScript (Vanilla)**
  - Dinamik DOM render
  - Filtreleme/arama
  - Modal yönetimi
  - Admin CRUD işlemleri (in-memory)


