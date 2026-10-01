# COP31 Uyum Radarı

Türkiye ETS, TSRS, AB CBAM (SKDM) ve CSRD kapsamında kurumsal hazırlık boşluklarını görünür kılan, tarayıcıda çalışan ücretsiz öz-değerlendirme aracı.

**Araç burada:** https://omniuscreative.com/surdurulebilirlik/cop31-uyum-radari/arac/

Bu depo aracın kaynak kodunu, mevzuat parametre dosyasını ve değişiklik kaydını barındırır. GitHub Pages adresi Ekim 2026'dan itibaren yönlendirme sayfasıdır; eski bağlantılar çalışmaya devam eder.

> **Tek canlı sürüm vardır.** Depodaki kopya referans ve şeffaflık içindir; çalışan sürüm yukarıdaki adrestedir. İkisi arasında fark görürseniz canlı sürüm geçerlidir.

---

## Ne yapar

Şirket profiline göre hangi mevzuatın hangi koşulda devreye girdiğini gösterir; hazırlık eksiklerini, kanıt ihtiyaçlarını ve yaklaşan tarihleri listeler. Çıktıyı PDF ve CSV olarak verir.

**Ne yapmaz:** kapsam kararı vermez, karbon muhasebesi veya ürün yaşam döngüsü analizi yapmaz, resmî uygunluk denetimi veya hukuki görüş yerine geçmez. Kesin kapsam için ürün kodu, tesis faaliyeti, şirket yapısı ve geçerli dönem güncel kaynaklarla ayrıca incelenmelidir.

## Nasıl çalışır

- Tek dosya HTML, vanilla JavaScript, harici bağımlılık yok.
- Kayıt, üyelik veya e-posta istemez.
- Değerlendirme verisi cihazdan çıkmaz. Yanıtlar, skor ve çıktılar sunucuya gönderilmez; telemetri, analitik veya üçüncü taraf script bulunmaz.
- Çevrimdışı çalışır. Dosyayı indirip internet bağlantısı olmadan da kullanabilirsiniz.

## Mevzuat parametreleri

Tarih, eşik, oran ve kapsam bilgileri `mevzuat-parametreleri.json` dosyasında tutulur; uygulama akışı bu dosyadan okur. Her kayıt üç durumdan biriyle etiketlenir:

| Etiket | Anlamı |
|---|---|
| Yürürlükte | Yayımlanmış ve yürürlükte olan düzenleme |
| Kurul kararı ile belirlendi | Yetkili kurul kararıyla belirlenmiş kapsam veya uygulama |
| Öneri — yasama süreci devam ediyor | Henüz yürürlüğe girmemiş; izleme listesi kaydı |

Son etiketi taşıyan hiçbir kayıt kullanıcıya mevcut yükümlülük olarak gösterilmez. Her kayıt kaynağı ve son kontrol tarihiyle birlikte saklanır; böylece bir sonucun hangi düzenlemeye dayandığı geriye dönük izlenebilir.

Mevzuat değiştiğinde yalnızca bu dosya güncellenir.

## Depo içeriği

```
index.html                      GitHub Pages yönlendirme sayfası
src/cop31-uyum-radari.html      Aracın arşiv kopyası (tek dosya)
mevzuat-parametreleri.json      Mevzuat kayıtları, kaynaklar, takvim
CHANGELOG.md                    Sürüm geçmişi
LISANS-NOTU.md                  Kod ve içerik lisanslarının ayrımı
_config.yml                     Pages yapılandırması
screenshots/                    Ekran görüntüleri
```

## Metodoloji ve sınırlar

Kapsam kurallarının hangi koşulda hangi modülü tetiklediği, ağırlıkların nasıl atandığı ve skorun nasıl hesaplandığı metodoloji sayfasında açıklanır:
https://omniuscreative.com/surdurulebilirlik/cop31-uyum-radari/metodoloji/

Ağırlıklar mevzuatta tanımlı değildir; tarafımızca atanmıştır. Skor bir uyum derecesi değil, hazırlık görünürlüğü ölçüsüdür. Yüksek puan uyumlu olmak anlamına gelmez.

## Katkı ve bildirim

Yanlış bir kayıt, eskimiş bir tarih veya hatalı bir kapsam sinyali gördüyseniz issue açın. Mevzuat bildirimlerinde kaynak bağlantısı eklemeniz değerlendirmeyi hızlandırır.

## Lisans

İçerik ve kod için ayrı lisanslar planlanmaktadır; ayrıntı için `LISANS-NOTU.md` dosyasına bakın. Bağlayıcı metin `LICENSE` dosyasıdır (CC BY-NC 4.0).

## İletişim

Omnius Creative · İzmir
https://omniuscreative.com
