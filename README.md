# 🇹🇷 Türkiye Hangi Ayhan Bozkurt Kitabını Arıyor?

### 📚 2019–2026 | Türkiye'nin Yapay Zekâ ve Kitap Merakının İnteraktif Haritası

Türkiye'nin 81 ilinde, Ayhan Bozkurt'un kitapları ve yapay zekâ projeleri etrafındaki arama terimlerini konu alan, animasyonlu ve etkileşimli bir Türkiye haritası.

Yıllar ilerledikçe harita renk değiştiriyor, arama terimleri arasındaki dağılımlar yeniden şekilleniyor ve her yılın öne çıkan başlıkları dinamik grafiklerle görselleştiriliyor.

Bu proje, coğrafi veri görselleştirmesini animasyon, etkileşim ve dijital hikâye anlatıcılığıyla bir araya getiren özgün bir web uygulamasıdır.

> **Önemli:** Bu çalışma temsili bir veri görselleştirmesidir. İl bazlı dağılımlar gerçek Google arama hacmi veya doğrulanmış Google Trends sonuçları değildir. Görselleştirme amacıyla hazırlanan örnek veri senaryosuna dayanmaktadır.

---

## ✨ Özellikler

- 🗺️ **81 İlin İnteraktif Haritası:** Türkiye'nin tüm illeri SVG tabanlı olarak görselleştirilir.
- 📅 **2019–2026 Zaman Çizelgesi:** Sekiz yıllık dönemde arama terimlerinin haritadaki temsili dağılımı izlenebilir.
- 🎬 **Otomatik Animasyon:** Yıllar arasında akıcı geçişler ve dinamik renk değişimleri.
- ⏯️ **Oynat / Duraklat:** Animasyon kullanıcı tarafından kontrol edilebilir.
- 🎯 **İl Bazında Etkileşim:** Fareyle illerin üzerine gelerek veya illere tıklayarak ilgili yılın öne çıkan terimi görüntülenebilir.
- 📊 **Dinamik Sıralama Grafikleri:** Her arama teriminin kaç ilde lider olduğunu gösteren animasyonlu çubuk grafikler.
- 🏆 **Yılın Lideri:** Seçili yılda en fazla ilde öne çıkan arama terimi.
- 🔄 **Lideri Değişen İller:** Önceki yıla kıyasla lider arama terimi değişen illerin sayısı.
- 🎨 **Renk Kodlu Görselleştirme:** Her arama terimi ayrı bir renkle temsil edilir.
- 📱 **Duyarlı Tasarım:** 1080 × 1350 piksel (4:5) oranındaki sahne, ekran boyutuna göre ölçeklenir.
- ⚡ **Tek HTML Dosyası:** Ek yazılım, derleme işlemi veya framework kurulumu gerektirmez.

---

## 📚 Görselleştirilen Kitaplar ve Arama Terimleri

Projede yedi farklı arama terimi bulunmaktadır:

1. **Ayhan Bozkurt Yapay Zeka**
2. **AI'Han Academy**
3. **Çocuklar İçin Yapay Zeka**
4. **Python ve Yapay Zeka**
5. **Herkes İçin Yapay Zeka**
6. **Algori ve Logi**
7. **Bilgi Muhafızları**

Her terim, Türkiye haritasında kendine özgü bir renkle temsil edilir.

---

## 🎮 Nasıl Çalışır?

Uygulama açıldığında 2019 yılına ait temsili dağılım görüntülenir.

Animasyon başladığında:

1. Yıllar otomatik olarak ilerler.
2. İllerin renkleri ilgili yılın dağılımına göre değişir.
3. Sıralama grafikleri eş zamanlı olarak güncellenir.
4. Yılın lider arama terimi belirlenir.
5. Lideri değişen il sayısı hesaplanır.
6. Animasyon 2026 yılına ulaştığında yeniden 2019'dan başlar.

Kullanıcı dilediği yılı seçebilir, animasyonu durdurabilir ve harita üzerindeki illeri inceleyebilir.

Varsayılan animasyon hızı, yıl başına **1,8 saniyedir**.

---

## 🛠️ Kullanılan Teknolojiler

Proje herhangi bir JavaScript framework'üne ihtiyaç duymadan geliştirilmiştir.

| Teknoloji | Kullanım Amacı |
|-----------|----------------|
| HTML5 | Uygulama yapısı |
| CSS3 | Arayüz, animasyon ve geçiş efektleri |
| JavaScript | Veri işleme ve etkileşim |
| SVG | Türkiye haritası ve il sınırları |
| Google Fonts | Inter ve Bricolage Grotesque yazı tipleri |

### Teknik Mimari

Uygulamanın temel bileşenleri:

- `TERMS`: Arama terimleri ve renk tanımları.
- `YEARS`: 2019–2026 yılları.
- `PROV`: İl adları, SVG harita koordinatları ve yıllık lider terim kodları.
- `SPEED`: Animasyonun geçiş süresi.
- `render()`: Harita, istatistikler ve grafiklerin güncellenmesi.
- `schedule()`: Otomatik oynatma mekanizması.
- `fit()`: Ekran boyutuna göre ölçeklendirme.

Her il için sekiz yıllık temsili dağılım kodun içerisinde saklanır.

Örnek veri yapısı:

```javascript
[ilAdi, svgYolu, "2019dan2026yaSekizTerimKodu"]
```

Sekiz haneli kodun her karakteri, ilgili yılın lider arama teriminin `TERMS` dizisindeki indeksini ifade eder.

Bu yapı sayesinde haritanın verileri, ayrı bir sunucuya veya veritabanına ihtiyaç duyulmadan işlenebilir.

---

## 🚀 Kurulum ve Çalıştırma

### 1. Projeyi indirin

GitHub deposunu bilgisayarınıza indirin veya klonlayın.

### 2. HTML dosyasını açın

Ana HTML dosyasını `index.html` olarak kaydedin ve Chrome, Firefox, Safari veya Edge gibi güncel bir tarayıcıda açın.

### 3. Haritayı keşfedin

- Animasyonu oynatın.
- Yıllar arasında geçiş yapın.
- İllerin üzerine gelerek arama terimlerini görüntüleyin.
- Grafiklerin değişimini takip edin.

Herhangi bir paket kurulumu veya yerel sunucu gerekli değildir.

**Not:** Google Fonts yazı tiplerinin yüklenebilmesi için internet bağlantısı gerekir. İnternet olmadığında tarayıcının sistem yazı tipleri kullanılabilir.

---

## 🌐 GitHub Pages ile Yayınlama

Projeyi GitHub Pages üzerinden ücretsiz olarak yayımlayabilirsiniz.

1. `index.html` ve `README.md` dosyalarını GitHub deposuna yükleyin.
2. Deponun **Settings** bölümüne girin.
3. **Pages** sekmesini açın.
4. **Deploy from a branch** seçeneğini belirleyin.
5. Yayınlanacak dalı ve `/(root)` klasörünü seçin.
6. GitHub Pages tarafından oluşturulan bağlantıdan uygulamanızı açın.

---

## 📊 Veri Görselleştirme Yaklaşımı

Türkiye'nin 81 ili, seçili yılda öne çıkan arama terimine göre renklendirilmektedir.

Her il için tek bir lider terim bulunmaktadır.

Sistem aşağıdaki bilgileri hesaplar:

**Yılın Lideri**

En fazla ilde temsil edilen arama terimidir.

**Zirvede Olduğu İl Sayısı**

İlgili terimin lider olarak atandığı toplam il sayısıdır.

**Lideri Değişen İl Sayısı**

Önceki yıla göre farklı bir arama teriminin lider olduğu il sayısıdır.

**Dinamik Grafikler**

Yedi arama teriminin yıllara göre temsil edildiği il sayılarını gösterir.

### Veri Hakkında

Bu projede kullanılan arama dağılımları temsili olarak oluşturulmuştur.

Bu nedenle:

- Gerçek arama sayıları değildir.
- Google Trends tarafından doğrulanmış sonuçlar değildir.
- Arama hacmini veya yüzdelik popülerliği ifade etmez.
- Kitapların gerçek yayın tarihleri veya satış performansları hakkında veri sunmaz.

Mevcut sürümde Google Trends API bağlantısı, CSV içe aktarma veya otomatik veri güncelleme özelliği bulunmamaktadır.

Gerçek Google Trends verileriyle hazırlanacak bir sürümde, il bazında karşılaştırılabilir sonuçların elde edilmesi ve veri kaynaklarının açıkça belirtilmesi gerekir.

---

## 💡 Projenin Amacı

Bu çalışmanın amacı yalnızca bir Türkiye haritası oluşturmak değil; zaman, coğrafya ve veriyi etkileşimli bir dijital anlatıya dönüştürmektir.

Proje şu yaklaşımları bir araya getirir:

- Coğrafi veri görselleştirme
- Zaman tabanlı animasyon
- Etkileşimli infografik tasarımı
- Dijital hikâye anlatıcılığı
- Eğitim teknolojileri
- Yapay zekâ ve kitap temalı yaratıcı web deneyimleri

---

## 👨‍💻 Geliştirici

**Ayhan Bozkurt**

📚 Yazar

🤖 Yapay Zekâ ve Eğitim Teknolojileri

🎓 AI'Han Academy

Kitaplar, yapay zekâ eğitimi ve yenilikçi dijital öğrenme deneyimlerini bir araya getiren çalışmalar.

---

## 📄 Lisans

Bu proje için henüz bir açık kaynak lisansı belirtilmemiştir.

Yeniden kullanım ve dağıtım koşullarının açıklanması için depoya ayrıca bir `LICENSE` dosyası eklenebilir.

---

**Ayhan Bozkurt | AI'Han Academy**

*Yapay zekâ, kitaplar ve dijital hikâye anlatıcılığı.*
