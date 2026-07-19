# Sprint 2

## Sprint Bilgileri

- **Sprint Tarihleri:** 6 Temmuz 2026 – 19 Temmuz 2026
- **Takım:** Takım 66
- **Ürün:** PriceLens
- **Product Owner:** Yaren Köse
- **Scrum Master:** Şevval Tanğlay

## Sprint Hedefi

Sprint 2'nin temel hedefi, PriceLens projesinin ürün kapsamını netleştirmek,
iki aktif ekip üyesinin mevcut kapasitesine uygun bir MVP belirlemek,
Product Backlog'u oluşturmak ve projenin teknik geliştirme sürecinde
kullanılacak veri analizi yaklaşımını planlamaktır.

Bu sprintte aşağıdaki çıktılara odaklanılmıştır:

- PriceLens problem tanımının netleştirilmesi
- Hedef kitlenin belirlenmesi
- Ürün özelliklerinin önceliklendirilmesi
- Product Backlog'un hazırlanması
- MVP kapsamının belirlenmesi
- Fiyat anomalisi tespitinde kullanılabilecek yöntemlerin araştırılması
- Son sprintte geliştirilecek temel kullanıcı akışının planlanması

## Takım Katılım Durumu

Takım başlangıçta beş kişiden oluşmasına rağmen Bootcamp sürecinde yalnızca
iki ekip üyesi aktif olarak iletişim ve çalışma sürecine katılmıştır.

### Aktif Takım Üyeleri

- **Yaren Köse:** Product Owner / Developer
- **Şevval Tanğlay:** Scrum Master / Developer

Diğer takım üyelerinin aktif katılım sağlamaması, takımın geliştirme
kapasitesini ve sprint planını doğrudan etkilemiştir.

Bu nedenle aktif ekip üyeleri tarafından ürün kapsamının daraltılması ve
çalışan bir MVP'ye odaklanılması kararlaştırılmıştır.

## Sprint Backlog

| ID | Görev | Sorumlu | Story Point | Durum |
|---|---|---|---:|---|
| S2-01 | Ürün problemini ve çözüm önerisini netleştirmek | Yaren Köse | 2 | Tamamlandı |
| S2-02 | Hedef kitleyi belirlemek | Yaren Köse | 2 | Tamamlandı |
| S2-03 | Ürün özelliklerini önceliklendirmek | Yaren Köse / Şevval Tanğlay | 3 | Tamamlandı |
| S2-04 | Product Backlog'u oluşturmak | Şevval Tanğlay | 3 | Tamamlandı |
| S2-05 | MVP kapsamını belirlemek | Yaren Köse / Şevval Tanğlay | 3 | Tamamlandı |
| S2-06 | Fiyat verisi için kullanılacak veri yapısını planlamak | Şevval Tanğlay | 5 | Devam Ediyor |
| S2-07 | Anomali tespit yöntemlerini araştırmak | Yaren Köse / Şevval Tanğlay | 5 | Devam Ediyor |
| S2-08 | Örnek fiyat geçmişi veri seti hazırlamak | Şevval Tanğlay | 3 | Sonraki Sprinte Aktarıldı |
| S2-09 | Fiyat grafiği prototipi geliştirmek | Yaren Köse | 5 | Sonraki Sprinte Aktarıldı |
| S2-10 | Sprint dokümantasyonunu GitHub'a eklemek | Şevval Tanğlay | 3 | Tamamlandı |

## Tahmini Puanlama

Sprint 2 için toplam **34 Story Point** değerinde görev değerlendirilmiştir.

- **Tamamlanan:** 13 Story Point
- **Devam Eden:** 10 Story Point
- **Sonraki Sprinte Aktarılan:** 8 Story Point
- **Dokümantasyon ve planlama:** 3 Story Point

Story Point değerleri görevlerin zorluk seviyesi, süresi, teknik belirsizliği
ve diğer görevlere olan bağımlılıkları dikkate alınarak belirlenmiştir.

## Backlog Dağıtma Mantığı

Görevlerin önceliklendirilmesinde aşağıdaki kriterler kullanılmıştır:

1. Çalışan bir MVP için gerekli olması
2. Kullanıcıya doğrudan değer sağlaması
3. Diğer teknik görevlerin başlaması için gerekli olması
4. İki aktif ekip üyesiyle tamamlanabilir olması
5. Yapay zekâ ve veri analizi yetkinliklerini gösterebilmesi

Öncelikli geliştirme sırası aşağıdaki şekilde belirlenmiştir:

1. Fiyat geçmişi veri yapısının oluşturulması
2. Örnek fiyat verilerinin hazırlanması
3. Fiyat değişimlerinin grafik üzerinde gösterilmesi
4. Anomali tespit algoritmasının geliştirilmesi
5. Gerçek veya şüpheli indirim etiketinin oluşturulması
6. Zaman yeterli olursa yapay zekâ destekli soru-cevap özelliğinin eklenmesi

Bildirim sistemi, üyelik sistemi ve gelişmiş çoklu platform karşılaştırması
MVP kapsamının dışında bırakılmıştır.

## Teknik Yaklaşım

PriceLens için planlanan temel veri akışı aşağıdaki gibidir:

1. Ürün adı, ürün bağlantısı ve fiyat bilgilerinin alınması
2. Fiyatların tarih bilgisiyle birlikte saklanması
3. Ürün bazında fiyat geçmişinin oluşturulması
4. En düşük, en yüksek ve ortalama fiyatların hesaplanması
5. Hareketli ortalama, standart sapma ve Z-score yöntemleriyle fiyat
   değişimlerinin analiz edilmesi
6. Olağan dışı fiyat hareketlerinin işaretlenmesi
7. Sonucun kullanıcıya “Gerçek İndirim”, “Şüpheli İndirim” veya
   “Yeterli Veri Yok” şeklinde gösterilmesi
8. Fiyat geçmişinin grafik üzerinden görselleştirilmesi

## Daily Scrum ve İletişim Durumu

Sprint 2 sürecinde takım üyelerinin çoğuna ulaşılamaması nedeniyle düzenli
Daily Scrum toplantıları gerçekleştirilememiştir.

Aktif iki ekip üyesi arasındaki iletişim sonucunda aşağıdaki durum
değerlendirmesi yapılmıştır.

### Yapılan Çalışmalar

- Ürün problemi ve çözüm önerisi netleştirildi.
- Hedef kitle belirlendi.
- Ürün özellikleri listelendi.
- Özellikler MVP ve gelecek sürüm olarak ayrıldı.
- Product Backlog oluşturuldu.
- Son sprintte geliştirilecek temel fonksiyonlar belirlendi.

### Devam Eden Çalışmalar

- Veri yapısının hazırlanması
- Örnek fiyat verilerinin oluşturulması
- Anomali tespit yöntemlerinin değerlendirilmesi
- Teknik mimarinin netleştirilmesi

### Blocker'lar

- Üç takım üyesinin aktif katılım sağlamaması
- Sprint 1 sürecinin ve dokümantasyonunun kaçırılmış olması
- Takım kapasitesinin iki kişiyle sınırlı kalması
- İlk ürün kapsamının mevcut zamana göre fazla geniş olması
- Gerçek e-ticaret platformlarından düzenli veri toplamanın teknik olarak
  beklenenden daha karmaşık olması

## Sprint Board Durumu

Sprint görevlerinin takibi için GitHub üzerindeki Product Backlog belgesi
kullanılmıştır.

Product Backlog:

[PriceLens Product Backlog](../PRODUCT_BACKLOG.md)

Son sprint başlangıcında görevlerin GitHub Projects üzerinden
“Product Backlog”, “Todo”, “In Progress” ve “Done” sütunlarıyla takip
edilmesi planlanmıştır.

## Ürün Durumu

Sprint 2 sonunda PriceLens'in:

- Ürün problemi
- Hedef kitlesi
- Temel özellikleri
- Product Backlog'u
- MVP kapsamı
- Teknik analiz yaklaşımı
- Son sprint geliştirme öncelikleri

belirlenmiştir.

Teknik geliştirme henüz tamamlanmamıştır. Örnek fiyat veri seti, fiyat
grafiği, anomali tespit sistemi ve kullanıcı arayüzü son sprintte
geliştirilecektir.

## Sprint Review

Sprint 2 sonunda aşağıdaki çıktılar elde edilmiştir:

- PriceLens'in çözdüğü problem açık biçimde tanımlanmıştır.
- Hedef kullanıcı kitlesi belirlenmiştir.
- Ürün özellikleri önceliklendirilmiştir.
- Product Backlog oluşturulmuştur.
- İki kişilik ekip kapasitesine uygun MVP belirlenmiştir.
- Fiyat analizinde kullanılacak temel istatistiksel yöntemler seçilmiştir.
- Son sprint için geliştirme sırası oluşturulmuştur.
- GitHub repository dokümantasyonu güncellenmiştir.

Sprint hedefinin ürün planlama ve dokümantasyon bölümü tamamlanmıştır.
Teknik geliştirme görevleri ise son sprinte aktarılmıştır.

## Sprint Retrospective

### İyi Gidenler

- Gerçek bir kullanıcı problemine odaklanılması
- Proje fikrinin veri analitiği ve yapay zekâ kullanımına uygun olması
- Ürün kapsamının iki kişilik ekibe göre yeniden değerlendirilmesi
- Öncelikli özelliklerin belirlenmesi
- Product Backlog'un oluşturulması
- Aktif iki ekip üyesi arasında iletişimin sürdürülmesi

### İyileştirilmesi Gerekenler

- Takım üyelerine sprintin başında daha erken ulaşılmalıydı.
- Sprint dokümantasyonu süreç boyunca düzenli tutulmalıydı.
- Teknik geliştirme görevlerine daha erken başlanmalıydı.
- İlk ürün kapsamı daha dar oluşturulmalıydı.
- Her görev için başlangıçta kabul kriterleri belirlenmeliydi.
- Görevler bir sprint board üzerinden düzenli takip edilmeliydi.

### Sonraki Sprint İçin Alınan Aksiyonlar

- Sadece çalışan MVP için gerekli özelliklere odaklanılacak.
- Görevler iki aktif ekip üyesi arasında açık biçimde paylaşılacak.
- Her anlamlı değişiklik GitHub'a ayrı commit olarak eklenecek.
- GitHub Projects üzerinde sprint board oluşturulacak.
- Önce örnek fiyat verisi ve veri yapısı tamamlanacak.
- Ardından fiyat grafiği ve anomali tespit sistemi geliştirilecek.
- Chatbot özelliği temel ürün akışı tamamlandıktan sonra değerlendirilecek.
- README ve sprint belgeleri düzenli olarak güncellenecek.

## Son Sprint Hedefi

Son sprint sonunda aşağıdaki temel kullanıcı akışının çalışır hale
getirilmesi hedeflenmektedir:

1. Kullanıcı bir ürün seçer.
2. Ürüne ait geçmiş fiyat verileri görüntülenir.
3. En düşük, en yüksek ve ortalama fiyatlar hesaplanır.
4. Fiyat geçmişi grafik üzerinde gösterilir.
5. Olağan dışı fiyat hareketleri tespit edilir.
6. Sistem kampanyayı gerçek veya şüpheli indirim olarak etiketler.
7. Analiz sonucu kullanıcıya sade ve anlaşılır biçimde sunulur.
