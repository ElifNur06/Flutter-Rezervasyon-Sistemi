# 📅 Flutter Rezervasyon Sistemi

Modern, çok dilli destekli ve tam donanımlı bir randevu yönetim platformu. Bu proje, hem müşterilerin kolayca randevu alabileceği bir mobil arayüzü hem de yöneticilerin tüm trafiği yönetebileceği kapsamlı bir web/masaüstü panelini içerir.

## 🚀 Öne Çıkan Özellikler

### 📱 Müşteri Paneli
* **Çok Dilli Deneyim:** Giriş ekranından itibaren seçilebilen Türkçe, İngilizce, Almanca ve İspanyolca dil desteği.
* **Akıllı Takvim:** API üzerinden anlık sorgulama ile sadece uygun olan saatlerin gösterilmesi ve Pazar günü kısıtlaması.
* **Esnek Randevu Yönetimi:** Farklı hizmet türleri seçimi (Danışmanlık, Teknik Destek vb.) ve özel not ekleme imkanı.
* **UX Detayları:** Randevuların cihazın yerel takvimine otomatik eklenmesi ve sadece "Bekliyor" durumundaki randevular için iptal yetkisi.

### 💻 Yönetici (Admin) Paneli
* **Responsive Tasarım:** Masaüstü ve mobil cihazlar için optimize edilmiş, ekran genişliğine göre uyum sağlayan profesyonel arayüz.
* **Analitik Dashboard:** Toplam müşteri sayısı, günlük randevu trafiği ve bekleyen onaylar için anlık istatistik kartları.
* **Operasyonel Kontrol:** Randevu taleplerini onaylama/reddetme, e-posta ile hızlı arama ve filtreleme.
* **Raporlama:** Tüm randevu verilerinin tek tıkla Excel uyumlu CSV formatında dışa aktarılması.
* **CRM Araçları:** Müşteri geçmişini görüntüleme ve müşteriye doğrudan e-posta gönderme entegrasyonu.

## 🛠 Teknik Altyapı

| Kategori | Teknoloji / Paket |
| :--- | :--- |
| **Framework** | Flutter (Dart) - Responsive UI Layout |
| **Backend / Auth** | Supabase Entegrasyonu |
| **Hızlı İletişim** | url_launcher (E-posta ve Linkler için) |
| **Takvim & Saat** | table_calendar, intl, add_2_calendar |
| **Dosya İşlemleri** | csv, path_provider (Raporlama için) |

## 🔑 Teknik Detaylar
* **Admin Giriş Mantığı:** Sistem, giriş yapılan e-posta adresinde "admin" ifadesini kontrol ederek kullanıcıyı otomatik olarak yetkili paneline yönlendirir.
* **REST API:** Harici bir API üzerinden anlık uygunluk kontrolü ve rezervasyon durum güncellemeleri yapılır.

## Görseller

<img width="337" height="598" alt="image" src="https://github.com/user-attachments/assets/35763e3a-4629-4881-ad4f-44ab661ab7a4" />
<img width="342" height="598" alt="image" src="https://github.com/user-attachments/assets/5f0b1dd4-e020-46a2-9141-2b072fb922e2" />
<img width="333" height="596" alt="image" src="https://github.com/user-attachments/assets/4cd84422-bd37-40c8-bbb8-1ed442960512" />
<img width="335" height="595" alt="image" src="https://github.com/user-attachments/assets/e2908552-187b-475f-81d1-546029ac49ca" />
<img width="337" height="601" alt="image" src="https://github.com/user-attachments/assets/b232cb00-a943-404b-83df-b8ec662d72e3" />
<img width="337" height="595" alt="image" src="https://github.com/user-attachments/assets/36bfce43-19f0-4ecf-80de-59a99e79c790" />
<img width="340" height="597" alt="image" src="https://github.com/user-attachments/assets/714db57a-5655-4f6c-9165-c5b85540eb28" />
<img width="336" height="598" alt="image" src="https://github.com/user-attachments/assets/bf00f6d7-705e-424a-87ba-f11b3b3cce96" />
<img width="338" height="600" alt="image" src="https://github.com/user-attachments/assets/cbd58ff2-e0b0-4bc9-af11-333aa833a435" />
<img width="338" height="597" alt="image" src="https://github.com/user-attachments/assets/5c7f51c9-fe56-4e9c-bee9-9215519e1e83" />
<img width="338" height="597" alt="image" src="https://github.com/user-attachments/assets/18953772-225d-42b5-8d2e-3807868994e8" />

## 📂 Proje Dökümantasyonu
Projenin detaylı analizine ve görsel rehberine aşağıdaki dosyalardan ulaşabilirsiniz:
* [Teknik Dökümantasyon (PDF)](./Rezervasyon_Sistemi_Dokumantasyonu_Guncel.pdf)
* [Görsel Kullanım Kılavuzu (PDF)](./Rezervasyon.pdf)

---
*Bu proje Elif Nur Ayhan tarafından geliştirilmiştir.*
