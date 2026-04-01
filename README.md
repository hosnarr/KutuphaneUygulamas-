# Kütüphane Takip & Barkod Yönetim Sistemi

**📚 Kütüphane Takip & Barkod Yönetim Sistemi**
Bu uygulama; kütüphaneler, okul kulüpleri veya kişisel koleksiyonlar için geliştirilmiş, kitap kayıtlarından ödünç verme süreçlerine kadar tüm akışı yöneten PyQt5 tabanlı bir masaüstü yazılımıdır. SQLite veritabanı altyapısı sayesinde tüm verileri yerel olarak (offline) güvenle saklar.

**✨ Temel Özellikler**
- Dinamik Kitap Kaydı: Kitap adı, yazar ve kategori bilgileriyle sisteme hızlı giriş.
- Otomatik EAN-13 Barkod Üretimi: Her yeni kitap için benzersiz bir barkod numarası oluşturulur ve barkodlar/ klasörüne görsel (PNG) olarak kaydedilir.
- Excel Entegrasyonu: Mevcut öğrenci listelerini .xlsx veya .xls formatında topluca sisteme aktarma.
- Gelişmiş Arama: Kitap adı, barkod numarası veya zimmetli kişi bilgisine göre anlık filtreleme.
- Zimmet & İade Takibi: Kitapları 15 günlük süreyle öğrencilere atama ve iade durumunu tek tıkla güncelleme.
- Modern Tasarım: Temiz, anlaşılır ve kullanıcı dostu arayüz.

**🛠 Kullanılan Teknolojiler**
- Dil: Python 3.x
- Arayüz: PyQt5 (GUI)
- Veritabanı: SQLite3
- Veri Yönetimi: Pandas (Excel işlemleri için)
- Barkod: python-barcode & Pillow

**🚀 Kurulum**
- Depoyu klonlayın:
- Bash
- git clone https://github.com/hosnarr/KutuphaneUygulamasi.git
- cd KutuphaneUygulamasi

**Gerekli kütüphaneleri yükleyin:**
- Bash
- pip install PyQt5 pandas openpyxl python-barcode Pillow
  
**Uygulamayı çalıştırın:**
- Bash
- python main.py

**📂 Proje Yapısı**
- main.py: Uygulamanın tüm mantığını ve arayüzünü içeren ana dosya.
- kutuphane.db: Kitap, öğrenci ve ödünç kayıtlarını tutan veritabanı.
- barkodlar/: Sistemin otomatik ürettiği barkod görsellerinin saklandığı dizin.
