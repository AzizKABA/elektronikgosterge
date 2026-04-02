
# Elektronik Gösterge Sistemleri Dersi - Dönem İçi Uygulaması

## Havacılık Kokpit Göstergeleri Simülatörü Geliştirme

Bu ödev kapsamında havacılıkta kullanılan analog veya dijital kokpit enstrümanlarından birini simüle eden bir uygulama geliştireceksiniz.

---

## 📋 Ana Başlıklar

Aşağıdaki ana başlıklar içerisinden bir enstrüman seçerek çalışmanızı yapabilirsiniz (bunlarla sınırlı kalmamak üzere):

- **Birincil uçuş enstrümanları** (Suni Ufuk, Altimetre, Hız Göstergesi, Variometre vb.)
- **Birincil uçuş ekranı** (PFD - Primary Flight Display)
- **Navigasyon ekranları** (ND, HSI, RMI, CDI vb.)
- **Motor ve sistem ekranları** (ECAM, EICAS, EPR/N1 göstergesi, yakıt göstergesi vb.)
- **Uyarı ve trafik ekranları** (TCAS, GPWS, ILS yaklaşma ekranı vb.)

### Konu Örnekleri

- **Analog enstrüman:** Altimetre — basınç değişimine göre irtifa gösterimi
- **Dijital ekran:** Navigation Display (ND) — rota, waypoint ve hava durumu gösterimi
- **Sistem ekranı:** ECAM Upper Display — motor parametreleri ve uyarı mesajları

> ⚠️ **Önemli:** Herkesin konusunun (göstergesinin) birbirinden farklı olması gerekmektedir.

---

## 👥 Grup Bilgileri

- Ödev **en fazla 5 kişilik** gruplar halinde yapılacaktır
- Grup üyelerini kendiniz belirleyeceksiniz
- Grup üyeleri **aynı sınıftan** seçilmelidir
- Her grup bir **lider** belirleyecektir

---

## 🖥️ Teknik Bilgiler

### Platform Seçenekleri

Uygulama aşağıdaki platformlardan herhangi birinde geliştirilebilir:

- **Web tabanlı:** HTML5 + CSS + JavaScript, React, Vue, p5.js, Three.js, D3.js
- **Masaüstü:** Python (Tkinter, PyQt, Pygame), C# (WPF), Java (Swing), C++ (Qt)
- **Mobil:** Android (Java/Kotlin/Flutter), iOS (Swift/Flutter)
- **Programlama dili:** Python, JavaScript, Java, Kotlin, C#, C++, Swift, Dart veya uygun herhangi bir dil

### Zorunlu Özellikler

Uygulamanın aşağıdaki özelliklerden **en az 5 tanesini** içermesi beklenmektedir:

- Göstergelerin gerçek zamanlı animasyonu
- Kullanıcı girişi ile değer değiştirme (klavye, fare, slider vb.)
- Gerçek enstrümana benzer görsel tasarım (renk, şekil, ölçek)
- Birim dönüşümü (feet/metre, knot/km-h, hPa/inHg vb.)
- Kritik değerlerde görsel veya sesli alarm/uyarı
- Simülasyon verilerinin log dosyasına kaydedilmesi
- Önceden tanımlı bir uçuş senaryosunun otomatik oynatılması
- Enstrüman arızası simülasyonu (bayrak, kırmızı çarpı vb.)

---

## 📝 Teslim Edilecek Dökümanlar

### 1. GitHub Repository
- Kaynak kodun tamamı, açıklayıcı bir `README.md`, `.gitignore`, `LICENSE` dosyaları
- Düzenli commit geçmişi (her hafta en az 3 commit, her üye en az 1 commit)

### 2. Demo Videosu
- **Süre:** 3–5 dakika
- **İçerik:** Uygulamanın çalışır hali + kısa teknik anlatım
- **Format:** MP4 veya YouTube/Drive linki (README'ye eklenecek)

### 3. Sunum Dosyası
- **Slayt sayısı:** 10–15 slayt
- **İçerik:** Enstrüman tanıtımı, yazılım mimarisi, özellikler, demo, zorluklar, AI kullanım raporu

### 4. AI Kullanım Raporu
- **Sayfa sayısı:** 1–2 sayfa
- **İçerik:** Hangi AI araçları kullanıldı, hangi amaçla, çıktı koda nasıl uyarlandı, AI'nın yetersiz kaldığı durumlar
- **Dil:** Türkçe veya İngilizce

---

## 🤖 AI ve Kaynak Kullanım Politikası

AI araçları ve internet kaynakları bu projede **serbest** olarak kullanılabilir. Ancak **kopyala-yapıştır kesinlikle yasaktır.**

### Serbest Olanlar
- Kavramları anlamak için AI araçlarından açıklama almak
- Algoritma mantığını sorup kodu kendiniz yazmak
- Hata ayıklama için AI'dan yardım almak
- Stack Overflow, MDN, resmi dokümantasyon gibi kaynakları kullanmak
- Açık kaynak kütüphaneleri import etmek (atıf yapılmalı)

### Yasak Olanlar
- AI tarafından üretilen kodu anlamadan doğrudan yapıştırmak
- Başka bir gruptan veya internetten hazır kod kopyalamak
- GitHub'daki hazır simülatör projelerini klonlayıp teslim etmek

> ⚠️ **Önemli:** Sunum sırasında her üyeye kodun herhangi bir kısmı hakkında teknik soru sorulacaktır. Tespit edilen ihlallerde tüm grup sıfır alır.

---

## 📊 Değerlendirme

| Kriter | Puan |
|--------|------|
| Havacılık doğruluğu (enstrüman gerçekçiliği, teknik bilgi) | 20 |
| Teknik kalite (kod kalitesi, mimari, performans) | 25 |
| Arayüz ve kullanıcı deneyimi tasarımı | 15 |
| Özellik zenginliği | 15 |
| Dokümantasyon (README, AI raporu, kod yorumları) | 10 |
| Sunum ve canlı demo | 10 |
| GitHub süreç yönetimi (commit geçmişi, katkı dağılımı) | 5 |
| **Toplam** | **100** |

---

## 📅 Önemli Tarihler

| Tarih | Saat | Etkinlik |
|-------|------|----------|
| **[ ]** | 23:59 | Takım bilgilerinin ve enstrüman seçiminin forma girilmesi (son tarih) |
| **[ ]** | 23:59 | Ara teslim — GitHub repo linki + %30 ilerleme |
| **[ ]** | 23:59 | Final teslimi — GitHub repo + AI raporu + sunum dosyası |
| **[ ]** | [ ] | Sunumlar (yüz yüze) |

---

## 🔗 Önemli Linkler

- 📋 **Takım Bilgileri Formu:** [Buraya tıklayarak takım bilgilerinizi girin]()
- 📊 **Seçilmiş Enstrüman Listesi:** [Daha önce seçilmiş enstrümanları buradan kontrol edin]()
- 📄 **Rapor Formatı:** [Rapor format şablonu]()
- 📚 **Sunum Şablonu:** [Sunum format şablonu]()

---

## ✅ Yapılacaklar Listesi

- [ ] Grup arkadaşlarınızı belirleyin (aynı sınıftan, en fazla 5 kişi)
- [ ] Ana başlıklardan bir enstrüman seçin
- [ ] Seçilmiş enstrüman listesinden konunuzun müsait olduğunu kontrol edin
- [ ] Takım bilgilerini belirtilen tarihe kadar forma girin
- [ ] GitHub repository oluşturun ve ilk commit'i yapın
- [ ] Araştırma ve tasarım aşamasını tamamlayın (wireframe/mockup)
- [ ] Ara teslim tarihinde en az %30 ilerleme sağlayın
- [ ] Tüm zorunlu özellikleri kodlayın ve test edin
- [ ] Demo videosunu kaydedin
- [ ] AI kullanım raporunu yazın
- [ ] Sunum dosyasını hazırlayın
- [ ] Final teslim tarihinde tüm dökümanları yükleyin
- [ ] Sunum gününe hazır olun

---

## 📞 İletişim

Sorularınız için ders sorumlusu ile iletişime geçebilirsiniz.
