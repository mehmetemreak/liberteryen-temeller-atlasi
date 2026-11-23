# Liberteryen Temeller Atlası — İnteraktif Siyaset Felsefesi Haritası

**Liberteryen Temeller Atlası**, liberteryen siyaset felsefesinin kuramsal temellerini, ekoller arası iç tartışmaları ve çeperindeki fikirleri Türkçe olarak inceleyen **tek dosyalık, interaktif bir web atlasıdır**. 37 düşünürü **hakların kaynağı** ve **meşru zorlamanın kapsamı** eksenlerinde konumlandırır; **10 soruluk konum bulucu** ile kendi felsefi duruşunu harita üzerinde görmeni ve arkadaşlarınla karşılaştırmanı sağlar.

> *"Aynı sonuç, ayrı temeller"* — Özgürlükçü düşüncenin doğal haklar, sonuççuluk, sözleşmecilik, gelenekçi liberalizm ve anarko-kapitalizm gibi farklı temellerden nasıl aynı veya benzer pratik sonuçlara ulaştığını (ve nerelerde ayrıştığını) tek sayfada karşılaştır.

## Öne Çıkan Özellikler

| Özellik | Açıklama |
| :--- | :--- |
| **İki Eksenli Düşünür Haritası** | 37 düşünürü açık kodlama ölçütleriyle *(X: Hakların kaynağı, Y: Meşru zorlamanın kapsamı)* görselleştirir; Türkçe normalizasyonlu arama ve ekol filtrelemesi sunar. |
| **10 Soruluk Konum Bulucu** | Verdiğin yanıtlara göre seni en yakın düşünürlerle eşleştirir, yanıtların arasındaki felsefi gerilimleri otomatik çelişki uyarılarıyla gösterir. |
| **Sunucusuz Karşılaştırma** | Yanıtlarını URL hash'ine (`#p=...`) sıkıştırarak paylaşılabilir bağlantı üretir; en fazla 10 kişinin konumunu ve ayrıştığı soruları yan yana karşılaştırır. |
| **Felsefi Temeller ve Açık Sorunlar** | Her ekolün temel savunusunu, ana metnini, en güçlü itirazını ve ödediği kuramsal bedeli özetler. |
| **Düşünce Deneyleri ve Ampirik Notlar** | İlgili düşünce deneylerini, olgusal öncülleri ve tartışmalı iddialara tavır alma kartlarını içerir. |
| **Tartışma Kronolojisi ve Dış Eleştiriler** | Liberteryen düşüncenin tarihsel gelişimini dönem filtreleriyle takip etmeni, dış eleştirilere verilen yanıtları incelemeni sağlar. |
| **Okuma Listesi ve Kaynakça** | Konu başlıklarına göre gruplanmış temel kitaplar ve doğrulama notları sunar. |

## Atlas İçindeki Başlıca Konular ve Kavramlar

* **Ekoller ve Yaklaşımlar:** Doğal haklar liberteryenizmi, sonuççu (utilitarian) liberteryenizm, klasik liberalizm, minarşizm, anarko-kapitalizm, sol-liberteryenizm, objektivizm ve gelenekçi/evrimci yaklaşım.
* **Temel Kavramlar:** Öz-sahiplik *(self-ownership)*, saldırmazlık ilkesi *(NAP)*, mülkiyet hakları, ilk edinim *(Lockeçu koşul)*, gece bekçisi devleti, polisentrik hukuk ve federalizm.
* **İncelenen Bölüm Başlıkları:** Kodlama Ölçütleri, Konumunu Bul, Temeller, Açık Sorunlar, Ampirik Notlar, Düşünce Deneyleri, Tartışma Kronolojisi, Dış Eleştiriler, Çeper ve Okuma Listesi.

## Kullanım ve Kurulum

Proje tamamen **derleme gerektirmeyen (zero-build)** tek bir HTML dosyasından oluşur; harici bağımlılığı yalnızca Google Fonts'tur.

1. Depoyu klonla veya `index.html` dosyasını indir:

```bash
git clone https://github.com/mehmetemreak/liberteryen-temeller-atlasi.git
cd liberteryen-temeller-atlasi
```

2. `index.html` dosyasını herhangi bir modern web tarayıcısında doğrudan aç.

## Teknoloji ve Mimari

* **Tek dosya mimarisi:** HTML5, modern CSS (`light-dark()`, CSS Grid, akışkan tipografi) ve saf JavaScript (Vanilla JS).
* **Yerel kayıt:** Test yanıtları ve iddia tavırları tarayıcının `localStorage` alanında saklanır; sunucuya hiçbir veri gönderilmez.
* **Erişilebilirlik:** Anlamsal HTML5 etiketleri, dinamik bölgelerde `aria-live` desteği ve duyarlı (responsive) mobil yerleşim.

## Katkıda Bulunma

İçerik düzeltmeleri, yeni düşünür kodlamaları, okuma listesi önerileri veya erişilebilirlik iyileştirmeleri için Issue açabilir ya da Pull Request gönderebilirsin.

## Lisans

Bu projenin içeriği ve kodu **[CC BY 4.0 (Creative Commons Attribution 4.0)](https://www.google.com/search?q=https://github.com/mehmetemreak/liberteryen-temeller-atlasi/blob/main/LICENSE)** lisansı altındadır. Kaynak göstererek paylaşabilir, uyarlayabilir ve yeniden yayınlayabilirsin.
