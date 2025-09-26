# Airbnb Veri Analizi Projesi 🏠

## 🎯 Proje Hakkında

Bu proje, Airbnb konaklama verilerini analiz ederek:
- Fiyat dağılımlarını inceler
- Bölgesel farklılıkları ortaya çıkarır
- Konaklama türlerine göre trendleri belirler
- Coğrafi dağılımları görselleştirir

Gerekli paketler için
pip install -r requirements.txt

📊 Veri Seti

Veri seti aşağıdaki sütunları içermektedir:
id: Konaklama ID'si
host_id: Ev sahibi ID'si
price: Gecelik fiyat
neighbourhood_group: Bölge grubu
room_type: Oda türü
latitude, longitude: Konum bilgileri
number_of_reviews: Yorum sayısı
minimum_nights: Minimum konaklama süresi
availability_365: Yıllık müsaitlik
beds: Yatak sayısı

📈 Analizler

1. Veri Temizleme

Eksik değerlerin kaldırılması
Tekrar eden kayıtların silinmesi
Aykırı değerlerin tespiti ve işlenmesi
2. Tek Değişkenli Analiz

Fiyat dağılımı histogramı
Bölgelere göre ortalama fiyatlar
3. Çift Değişkenli Analiz

Bölge-Fiyat-Oda türü ilişkisi
Yorum sayısı-Fiyat ilişkisi
Değişkenler arası korelasyon
4. Coğrafi Analiz

Konaklama yerlerinin harita üzerinde dağılımı
📊 Örnek Görselleştirmeler

Proje aşağıdaki görselleştirmeleri içerir:

Fiyat dağılımı box plot'ları
Bölgesel fiyat karşılaştırmaları
Korelasyon ısı haritası
Coğrafi dağılım haritası
