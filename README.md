# 🏠 EmlakPro — Emlak Yönetim Sistemi

Emlak danışmanları için tasarlanmış, kurulum gerektirmeyen, tarayıcıda çalışan portföy ve müşteri yönetim sistemi.

## Kullanım

`index.html` dosyasını herhangi bir tarayıcıda (Chrome, Edge, Firefox...) açmanız yeterlidir. İnternet bağlantısı gerekmez, tüm veriler tarayıcınızda güvenle saklanır.

## Özellikler

### 📊 Özet Paneli
- Aktif portföy sayısı (satılık / kiralık dağılımı)
- Toplam satılık portföy değeri
- Müşteri ve talep sayıları
- Otomatik eşleşme sayısı ve kapanan işlemler
- Son eklenen portföyler ve müşteriler

### 🏘 Portföy Yönetimi
- Satılık / kiralık ilan ekleme, düzenleme, silme
- Kategori: Daire, Villa, Müstakil Ev, Arsa, İşyeri, Ofis, Tarla
- Konum (il / ilçe / mahalle), m², oda sayısı, bina yaşı, kat bilgisi
- Mülk sahibi adı ve telefonu (tek dokunuşla arama)
- Arama, filtreleme (işlem tipi, kategori, durum) ve fiyata göre sıralama
- "Satıldı / Kiralandı" işaretleme ile işlem takibi

### 👥 Müşteri / Talep Yönetimi
- Alıcı ve kiracı taleplerini kaydetme
- Bütçe aralığı, tercih edilen bölge, minimum oda sayısı, notlar
- İsim, telefon ve bölgeye göre arama

### 🤝 Otomatik Eşleştirme
Her müşterinin talebi (işlem tipi, kategori, bütçe, bölge, oda sayısı) aktif portföylerle otomatik karşılaştırılır; hangi müşteriye hangi ilanı sunabileceğinizi anında görürsünüz.

### 🧮 Komisyon Hesaplayıcı
Satış veya kiralama işlemleri için komisyon + KDV hesabı, alıcı+satıcı toplamı dahil.

### 💾 Yedekleme
- **Yedek Al**: Tüm verileri `.json` dosyası olarak indirir
- **Yedek Yükle**: Başka bir bilgisayara taşımak veya geri dönmek için yedeği geri yükler

## Veriler Nerede Saklanıyor?

Veriler tarayıcının `localStorage` alanında, yalnızca sizin cihazınızda saklanır. Tarayıcı geçmişini/verilerini temizlerseniz silinebilir — bu yüzden düzenli olarak **Yedek Al** butonunu kullanmanız önerilir.
