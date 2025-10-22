#  Öğrenci Bilgi Sistemi (ÖBS)

**Hazırlayan:** 404NotFound Team  
**Tarih:** 16/11/2025  

**Grup Üyeleri:**
1. Muhammed Emin Alan  
2. Eren Gültekin  
3. Batuhan Cengiz  
4. Eren Karataş  
5. Mustafa Can  

---

##  1. Proje Tanımı ve Kapsamı

### 1.1. Problem veya Fırsatın Tanımı
Günümüzde üniversitelerde öğrenci, öğretim elemanı ve yönetim arasındaki bilgi akışı çoğunlukla farklı sistemlerde yürütülmektedir. Bu da veri tutarsızlıkları, erişim zorlukları ve zaman kayıplarına yol açmaktadır.  

Manuel işlemler veya dağınık dijital araçlar, öğrenci notlarının, ders programlarının, devamsızlık bilgilerinin ve sınav sonuçlarının düzenli bir şekilde takip edilmesini zorlaştırmaktadır.  

**Öğrenci Bilgi Sistemi (ÖBS)** projesi, öğrenci ve öğretim elemanlarının akademik süreçlerdeki bilgiye hızlı, güvenli ve kullanıcı dostu bir şekilde erişmesini sağlamak amacıyla geliştirilmiştir. Proje, yönetim yükünü azaltmak ve dijitalleşme sürecine katkı sunmak için bir fırsat doğurmaktadır.

---

### 1.2. Projenin Kapsamı

####  Yapacakları
- Öğrencilerin kullanıcı hesabı oluşturup giriş yapabilmesi  
- Öğrenci profillerinin görüntülenmesi ve düzenlenmesi  
- Not, devamsızlık ve ders bilgilerine erişim  
- Öğretim elemanlarının ders, not ve yoklama işlemlerini yönetebilmesi  
- Yönetici paneli üzerinden öğrenci, öğretim elemanı ve ders bilgilerinin kontrolü  
- Verilerin güvenli şekilde saklanması ve yönetimi  
- Kullanıcı dostu, **responsive (mobil uyumlu)** arayüz  

####  Yapmayacakları
- Online sınav yapma veya otomatik değerlendirme  
- Finansal işlemler (harç ödeme vb.)  
- Canlı iletişim (chat veya video konferans) özellikleri  

---

##  2. TELOS Fizibilite Analizi

### 2.1. Teknik Fizibilite
Proje, mevcut yazılım teknolojileriyle teknik olarak uygulanabilir durumdadır.  
Frontend kısmı **Flutter** ile geliştirilecek ve tek kod tabanından **iOS** ve **Android** sürümleri yönetilecektir.  
Backend kısmında **Firebase** kullanılacaktır. Veri tabanı olarak **Cloud Firestore** tercih edilecektir.  

Proje ekibinin bu teknolojilere hakim olması nedeniyle teknik açıdan herhangi bir engel bulunmamaktadır.  

---

### 2.2. Ekonomik Fizibilite
Proje bir öğrenci ödevi kapsamında geliştirileceği için büyük yatırım maliyeti bulunmamaktadır.  
Yalnızca düşük ölçekli bir sunucu veya Firebase kullanımı için sınırlı bir maliyet (yaklaşık **100-200 TL**) söz konusudur.  

Buna karşılık, projenin sağlayacağı **verimlilik artışı**, **zaman tasarrufu** ve **yönetim kolaylığı**, bu maliyetin çok üzerindedir.  

**Sonuç:** Ekonomik olarak uygulanabilir.  

---

### 2.3. Yasal Fizibilite
Proje, **KVKK (Kişisel Verilerin Korunması Kanunu)** hükümlerine uygun şekilde geliştirilecektir.  
Öğrenci bilgileri kişisel veri kapsamında olduğundan, sistemde **yetkilendirme**, **kimlik doğrulama** ve **veri gizliliği** önlemleri uygulanacaktır.  

Veriler Türkiye Cumhuriyeti yasalarına uygun biçimde saklanacaktır.  
**Sonuç:** Yasal açıdan uygun.  

---

### 2.4. Operasyonel Fizibilite
Sistem, hedef kullanıcılar (öğrenciler, öğretim elemanları ve yöneticiler) için kolay kullanılabilir olacaktır.  
Kullanıcı arayüzü sade ve mobil uyumlu tasarlanacaktır. Ek eğitim gerekmeden kullanılabilir.  

İlerleyen dönemlerde sistem modüler olarak genişletilebilir.  
**Sonuç:** Operasyonel olarak uygun.  

---

### 2.5. Zamanlama Fizibilitesi

**Proje Süresi:** 10 hafta  

| Hafta | Aşama |
|-------|--------|
| 1–2 | Gereksinim analizi ve tasarım |
| 3–6 | Arayüz ve backend geliştirme |
| 7–8 | Test ve hata düzeltmeleri |
| 9–10 | Son revizyon ve raporlama |

Bu plan gerçekçi ve uygulanabilirdir.  
**Sonuç:** Zaman açısından fizibildir.  

---

##  3. Sonuç ve Tavsiye
Yapılan analizler sonucunda **Öğrenci Bilgi Sistemi (ÖBS)** projesi teknik, ekonomik, yasal, operasyonel ve zamanlama açısından uygulanabilir durumdadır.  

Proje, öğrenciler ve öğretim elemanları için pratik bir çözüm sunmaktadır.  
Geliştirme sürecinde **güvenlik** ve **veri gizliliğine** özel önem verilmelidir.  

**Sonuç olarak, projenin mevcut haliyle geliştirme sürecine devam edilmesi tavsiye edilmektedir.**

---
