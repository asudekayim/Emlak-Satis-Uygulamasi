OTEL REZERVASYON SİSTEMİ
-

Bu proje, staj süresi boyunca yazılım geliştirme adımları takip edilerek uygulamalı bir şekilde öğrenmeyi amaçlamaktadır. Otellerin online rezervasyon yapabilmesini, kullanıcıların oda seçimi, müsaitlik kontrolü ve ödeme simülasyonu yapabildiği web tabanlı bir sistemdir. Kullanıcı dostu bir arayüze sahip olarak temel rezervasyon ihtiyaçlarının kolaylıkla karşılanabileceği bir sistem olmayı hedefler.

Kullanılacak Teknolojiler:
-
Frontend: HTML, CSS, JavaScript

Backend: Node.js

Veri Tabanı: PostgreSQL

Kullanıcı Rolleri ve Senaryoları
-
1.Müşteri

- Siteye kayıt olur / giriş yapar.
- Belirli kriterlere göre(tarih, kişi sayısı) oda araması yapar, müsait odaları görüntüler.
- Oda rezervasyonu yapar ve ödeme simülasyonu yapar.

2.Otel Yöneticisi

- Sisteme giriş yapar.
- Oda ekler, siler, düzenler. Müsaitlik durumunu kontrol eder.
- Fiyat düzenlemesi yapar.
- Rezervasyonları görüntüler.

3.Admin

- Genel sistemi yönetir, denetler.

Use Case Diagram
-
<img width="732" height="572" alt="usecase" src="https://github.com/user-attachments/assets/f82b01a9-53b0-4c6d-b3e6-5a7bb0b268b1" />

İşlevsel Gereksinimler
-
- Kullanıcı kayıt olabilir ve sisteme giriş yapabilir.
- Kullanıcı, tarih ve kişi sayısına göre oda araması yapabilir.
- Kullanıcı, oda araması sonucunda müsait odaları görüntüleyebilir.
- Kullanıcı, oda rezervasyonu yapabilir ve ödeme simülasyonu yapabilir.
- Yönetici, oda ekleyebilir, silebilir, düzenleyebilir, fiyat güncellemesi yapabilir.
- Yönetici, rezervasyonları görüntüleyebilir.
- Admin, sistemi yönetebiliri denetleyebilir.

İşlevsel Olmayan Gereksinimler
-
- Sistem responsive tasarıma sahip olmalıdır.
- Kullanıcı bilgileri güvenli bir şekilde saklanmalıdır.
- Arayüz, kullanıcı dostu ve sade olmalıdır.
- Gerçek ödeme entegrasyonu değil, simülasyon yapılmalıdır.
- Sadece web üzerinde kullanılmalıdır.
- Node.js ve PostgreSQL ile geliştirilmelidir.

SWOT ANALİZİ
-
| Güçlü Yönler (Strengths) | Zayıf Yönler (Weaknesses) |
|--------------------------|---------------------------|
| Modern web teknolojileri kullanıldı. | Gerçek ödeme sistemi yoktur. |
| Basit ve kullanıcı dostu arayüze sahiptir. | Yalnızca tek bir otel yönetilebiliyor. |

| Fırsatlar (Opportunities) | Tehditler (Threats) |
|--------------------------|----------------------|
| Gerçek projeye dönüşebilir. | Güvenlik açıkları olabilir. |
| Mobil uygulama olarak genişletilebilir. | Artan teknik borç ve bakım maliyeti artabilir. |

Veri Tabanı Tasarımı
-

Tablolar ve Temel Alanlar:

<img width="547" height="576" alt="image" src="https://github.com/user-attachments/assets/75fa8adb-ac8a-424e-9078-2318ca51acfe" />
