# PriceLens Product Backlog

Bu Product Backlog, PriceLens projesinin geliştirme sürecinde planlanan kullanıcı ihtiyaçlarını, teknik görevleri, öncelikleri ve sprint dağılımını göstermektedir.

## Backlog Durumları

- **Product Backlog:** Henüz sprinte alınmamış görev
- **Planlandı:** İlgili sprintte yapılması planlanan görev
- **Devam Ediyor:** Üzerinde çalışılan görev
- **Tamamlandı:** Kabul kriterleri karşılanan görev
- **Gelecek Sürüme Aktarıldı:** MVP kapsamı dışında bırakılan görev

## Product Backlog Tablosu

| ID | User Story / Görev | Öncelik | Story Point | Planlanan Sprint | Durum |
|---|---|---:|---:|---|---|
| PL-01 | Kullanıcı olarak PriceLens platformunun amacını ve hangi problemi çözdüğünü görebilmek istiyorum. | Yüksek | 2 | Sprint 1 | Tamamlandı |
| PL-02 | Takım olarak ürünün hedef kitlesini ve temel özelliklerini belirlemek istiyoruz. | Yüksek | 3 | Sprint 1 | Tamamlandı |
| PL-03 | Takım olarak projenin Product Backlog’unu oluşturmak istiyoruz. | Yüksek | 3 | Sprint 2 | Tamamlandı |
| PL-04 | Geliştirici olarak ürün ve fiyat geçmişi için kullanılacak veri yapısını oluşturmak istiyorum. | Yüksek | 5 | Sprint 2 | Planlandı |
| PL-05 | Geliştirici olarak örnek ürünlere ait geçmiş fiyat verilerini hazırlamak istiyorum. | Yüksek | 3 | Sprint 2 | Planlandı |
| PL-06 | Kullanıcı olarak takip etmek istediğim ürünü sisteme ekleyebilmek istiyorum. | Yüksek | 5 | Son Sprint | Product Backlog |
| PL-07 | Kullanıcı olarak bir ürünün geçmiş fiyat hareketlerini grafik üzerinde görebilmek istiyorum. | Yüksek | 5 | Son Sprint | Product Backlog |
| PL-08 | Kullanıcı olarak ürünün en düşük, en yüksek ve ortalama fiyat bilgilerini görebilmek istiyorum. | Yüksek | 3 | Son Sprint | Product Backlog |
| PL-09 | Kullanıcı olarak fiyat değişiminin normal veya anormal olduğunu görebilmek istiyorum. | Yüksek | 8 | Son Sprint | Product Backlog |
| PL-10 | Geliştirici olarak hareketli ortalama, standart sapma ve Z-score yöntemlerini kullanarak fiyat anomalilerini tespit etmek istiyorum. | Yüksek | 8 | Son Sprint | Product Backlog |
| PL-11 | Kullanıcı olarak kampanyanın gerçek indirim veya şüpheli indirim şeklinde etiketlenmesini istiyorum. | Yüksek | 5 | Son Sprint | Product Backlog |
| PL-12 | Kullanıcı olarak ürünün fiyat geçmişi hakkında doğal dilde soru sorabilmek istiyorum. | Orta | 8 | Son Sprint | Product Backlog |
| PL-13 | Kullanıcı olarak sade ve anlaşılır bir web arayüzü üzerinden ürün analizine ulaşmak istiyorum. | Yüksek | 5 | Son Sprint | Product Backlog |
| PL-14 | Kullanıcı olarak anlamlı bir fiyat düşüşü gerçekleştiğinde bildirim almak istiyorum. | Düşük | 8 | Gelecek Sürüm | Gelecek Sürüme Aktarıldı |
| PL-15 | Kullanıcı olarak aynı ürünün farklı e-ticaret platformlarındaki fiyatlarını karşılaştırmak istiyorum. | Düşük | 13 | Gelecek Sürüm | Gelecek Sürüme Aktarıldı |
| PL-16 | Kullanıcı olarak takip ettiğim ürünleri favoriler listesinde saklamak istiyorum. | Düşük | 5 | Gelecek Sürüm | Gelecek Sürüme Aktarıldı |
| PL-17 | Kullanıcı olarak geçmiş sorgularımı ve analiz sonuçlarımı görüntülemek istiyorum. | Düşük | 5 | Gelecek Sürüm | Gelecek Sürüme Aktarıldı |

## User Story Detayları

### PL-06 — Ürün Ekleme

**User Story**

Bir kullanıcı olarak takip etmek istediğim ürünün bağlantısını veya bilgilerini sisteme eklemek istiyorum; böylece ürünün fiyat geçmişini analiz edebilirim.

**Kabul Kriterleri**

- Kullanıcı ürün adı veya ürün bağlantısı girebilmelidir.
- Girilen ürün bilgisi sistem tarafından kaydedilmelidir.
- Eksik veya geçersiz veri girildiğinde kullanıcıya uyarı gösterilmelidir.

---

### PL-07 — Fiyat Geçmişi Grafiği

**User Story**

Bir kullanıcı olarak ürünün geçmiş fiyat değişimlerini grafik üzerinde görmek istiyorum; böylece fiyatın zaman içerisindeki hareketini anlayabilirim.

**Kabul Kriterleri**

- Fiyat verileri tarih sırasına göre gösterilmelidir.
- Grafik üzerinde tarih ve fiyat değerleri okunabilmelidir.
- En düşük ve en yüksek fiyat noktaları gösterilmelidir.

---

### PL-09 — Fiyat Anomalisi Tespiti

**User Story**

Bir kullanıcı olarak ürün fiyatındaki olağan dışı değişikliklerin sistem tarafından tespit edilmesini istiyorum; böylece şüpheli fiyat hareketlerini anlayabilirim.

**Kabul Kriterleri**

- Sistem geçmiş fiyat verilerini analiz etmelidir.
- Olağan dışı fiyat artışları veya düşüşleri işaretlenmelidir.
- Kullanılan analiz yöntemi dokümantasyonda açıklanmalıdır.
- Analiz sonucu kullanıcıya anlaşılır biçimde gösterilmelidir.

---

### PL-11 — Gerçek veya Şüpheli İndirim Etiketi

**User Story**

Bir kullanıcı olarak mevcut kampanyanın gerçek bir indirim mi yoksa şüpheli bir fiyat hareketi mi olduğunu görmek istiyorum.

**Kabul Kriterleri**

- Sistem geçmiş fiyatlar ile kampanya fiyatını karşılaştırmalıdır.
- Sonuç “Gerçek İndirim”, “Şüpheli İndirim” veya “Yeterli Veri Yok” şeklinde gösterilmelidir.
- Sonucun hangi verilere dayanarak üretildiği kullanıcıya açıklanmalıdır.

---

### PL-12 — Yapay Zekâ Destekli Soru-Cevap

**User Story**

Bir kullanıcı olarak ürünün fiyat geçmişi hakkında doğal dilde soru sormak istiyorum; böylece teknik grafik bilgisine ihtiyaç duymadan sonuçları anlayabilirim.

**Örnek Sorular**

- Bu ürün son üç ayda ne zaman en ucuzdu?
- Mevcut fiyat gerçek bir indirim mi?
- Ürünün ortalama fiyatı nedir?
- Fiyat son bir ayda yükseldi mi?

**Kabul Kriterleri**

- Sistem kullanıcının temel fiyat sorularını anlayabilmelidir.
- Yanıtlar mevcut fiyat verilerine dayanmalıdır.
- Veri bulunmadığında sistem bunu açıkça belirtmelidir.
- Sistem gerçek veriye dayanmayan fiyat bilgisi üretmemelidir.

## MVP Kapsamı

İki aktif ekip üyesinin mevcut zamanı ve teknik kapasitesi dikkate alınarak PriceLens MVP’sinde aşağıdaki temel kullanıcı akışına odaklanılacaktır:

1. Örnek veya toplanmış ürün fiyat verilerinin sisteme alınması
2. Fiyat geçmişinin grafik üzerinde gösterilmesi
3. En düşük, en yüksek ve ortalama fiyatların hesaplanması
4. Z-score veya hareketli ortalama tabanlı anomali tespiti yapılması
5. Fiyat hareketinin gerçek veya şüpheli indirim olarak etiketlenmesi
6. Kullanıcıya analiz sonucunun sade bir arayüz üzerinden sunulması
7. Zaman yeterli olursa fiyat geçmişine dayalı temel soru-cevap özelliğinin eklenmesi

## Gelecek Sürüme Aktarılan Özellikler

Aşağıdaki özellikler mevcut takım kapasitesi ve Bootcamp süresi nedeniyle ilk MVP kapsamının dışında bırakılmıştır:

- E-posta veya anlık bildirim sistemi
- Kullanıcı üyelik sistemi
- Favori ürün listesi
- Gelişmiş geçmiş arama sistemi
- Trendyol ve Hepsiburada arasında otomatik çoklu platform karşılaştırması
- Çok sayıda ürünün kesintisiz ve otomatik şekilde takip edilmesi

## Önceliklendirme Mantığı

Backlog görevleri aşağıdaki kriterlere göre önceliklendirilmiştir:

1. Kullanıcıya doğrudan değer sağlaması
2. Çalışan bir MVP için zorunlu olması
3. Diğer görevlerin başlaması için teknik bağımlılık oluşturması
4. İki kişilik ekip tarafından mevcut sürede tamamlanabilir olması
5. Yapay zekâ ve veri analizi yetkinliklerini gösterebilmesi

Bu nedenle ilk olarak veri yapısı, fiyat geçmişi analizi, grafik oluşturma ve anomali tespiti görevlerine odaklanılması kararlaştırılmıştır.
