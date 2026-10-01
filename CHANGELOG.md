# Değişiklik Kaydı

Bu dosya COP31 Uyum Radarı'nın sürüm geçmişini tutar. Mevzuat kayıtlarının tamamı `mevzuat-parametreleri.json` dosyasındadır; her kayıt kaynağı ve son kontrol tarihiyle birlikte saklanır.

Sürüm numarası aracın kendisine, metodoloji sürümü kullanılan değerlendirme yöntemine, "son mevzuat kontrolü" ise parametrelerin en son hangi tarihte doğrulandığına işaret eder. Üçü birbirinden bağımsız ilerleyebilir.

---

## v0.2.2 — 1 Ekim 2026
**Metodoloji 2026.10 · Son mevzuat kontrolü: 1 Ekim 2026 · Parametre dosyası 2026.10.03**

- AB CSRD modülünün kaynak doğrulaması tamamlandı. Modül artık Direktif (AB) 2026/470 (Omnibus I) referansını, Resmî Gazete ve yürürlük tarihlerini taşıyor.
- CSRD kapsam metni netleştirildi: 1.000'den fazla çalışan **ve** 450 milyon avrodan fazla net ciro ölçütlerinin birlikte aşılması gerektiği, yeni kapsamın mali yıl 2027'den itibaren uygulandığı ve borsada işlem gören KOBİ'lerin zorunlu kapsam dışında olduğu açıkça yazıldı.
- Türkiye bağlantısı notu eklendi: Türkiye merkezli bir şirket CSRD'ye doğrudan tabi olmasa da AB'deki ana şirketi veya kurumsal müşterisi üzerinden değer zinciri bilgi talebi alabilir.
- Revize ESRS yürürlük tarihi (10 Kasım 2026) CSRD modülüne eklendi; ana takvim kartına eklenmedi.
- Gönüllü çerçeveler modülündeki "kaynak doğrulaması bekliyor" notu kaldırıldı. GRI, CDP, SBTi ve ISSB mevzuat olmadığı için modül artık yükümlülük doğurmadığını belirten bir notla açılıyor.

## v0.2.1 — 1 Ekim 2026
**Metodoloji 2026.10 · Son mevzuat kontrolü: 1 Ekim 2026 · Parametre dosyası 2026.10.02**

- TR ETS modül girişindeki metin hatası düzeltildi. Sistem yılı cümleleri yıl etiketleri olmadan birleştiği için "fiyat mekanizması başlatılır" ifadesinin hangi yıla ait olduğu kayboluyordu; ücretsiz tahsisat cümlesi de tekrarlanıyordu. İki alan tek bir alanda birleştirildi.
- Profil tamamlanma kontrolü düzeltildi. Kapsam sonucunu etkilemeyen alanlar (şirket adı) zorunluluktan çıkarıldı; kapsam sinyali artık belirleyici sorular yanıtlandığı anda görünüyor.
- CBAM varsayılan değer artışları eklendi: 2026 için %10, 2027 için %20, 2028 ve sonrası için %30.
- CBAM çeyreklik sertifika tutma oranı (%50) eklendi.

## v0.2.0 — 1 Ekim 2026
**Metodoloji 2026.10 · Son mevzuat kontrolü: 1 Ekim 2026 · Parametre dosyası 2026.10.01**

- **Kapsam düzeltmesi.** TR ETS pilot kapsamı, KPK/2026/1 (3 Eylül 2026) kararına göre yeniden kuruldu: elektrik üretimi, çimento, demir-çelik, alüminyum ve gübre sektörlerinde yalnızca Kategori B ve C tesisleri. Kategori A tesisleri kapsam dışı. Cam, seramik, kireç, kâğıt, rafineri ve kimya gibi EK-1 faaliyetleri birinci uygulama döneminde (2028–2035) kapsama giriyor. Önceki sürüm pilot kapsamı SKDM sektörleriyle eşitliyordu; bu varsayım yanlıştı.
- Mevzuat parametreleri koddan ayrıldı. Tarih, eşik, oran ve kapsam bilgileri tek bir parametre bloğunda toplandı; akış kodu artık bu bloktan okuyor.
- Üç durum etiketi getirildi: *Yürürlükte*, *Kurul kararı ile belirlendi*, *Öneri — yasama süreci devam ediyor*. Son etiketi taşıyan hiçbir kayıt mevcut yükümlülük olarak gösterilmiyor.
- Yaklaşan tarihler bloğu eklendi. Kullanıcı profiline uyan en yakın üç tarih, dayanak maddesi ve kalan gün sayısıyla gösteriliyor. İlk İzleme Metodolojisi Planı teslim tarihi 27 Ekim 2026 (Geçici Madde 3/1) bu blokta yer alıyor.
- CBAM aşağı akış genişlemesi izleme listesi olarak eklendi. Avrupa Parlamentosu 15 Eylül 2026'da müzakere pozisyonunu kabul etti; nihai ürün listesi ve eşikler trilog sonucunda belirlenecek. Alüminyum için önerilen eşik düşüşü (50 → 5 ton/yıl) ayrı satırda, öneri olduğu belirtilerek gösteriliyor.
- TSRS eşikleri güncellendi (16 Ocak 2026 Kurul Kararı) ve TSRS 2'de 31 Temmuz 2026 tarihinde yayımlanan sera gazı açıklama değişiklikleri not olarak eklendi.
- Her PDF/CSV çıktısına sürüm, metodoloji sürümü ve son mevzuat kontrol tarihi eklendi.

## v0.1.0 — Eylül 2026
**Metodoloji 2026.09**

- İlk yayın. Türkiye ETS, TSRS, AB CBAM, CSRD ve gönüllü çerçeveler için tarayıcı tabanlı öz-değerlendirme.
- Tek dosya HTML, kayıt gerektirmeyen kullanım, cihazda kalan değerlendirme verisi, PDF/CSV dışa aktarma.

---

## Barındırma geçmişi

Araç başlangıçta GitHub Pages üzerinde yayımlandı. Ekim 2026 itibarıyla Omnius Creative sitesine taşındı ve tek canlı sürüm orada tutuluyor:
`https://omniuscreative.com/surdurulebilirlik/cop31-uyum-radari/arac/`

GitHub Pages adresi, eski bağlantıların çalışmaya devam etmesi için yönlendirme sayfası olarak korunuyor. Bu depo kaynak kodu, parametre dosyası ve metodoloji belgelerini barındırmayı sürdürüyor.
