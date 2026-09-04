<div align="center">

<img src="screenshots/hero.png" alt="COP31 Uyum Radarı" width="100%">

# COP31 Uyum Radarı
### Compliance Radar

**Türkiye İklim Kanunu (ETS) · TSRS · AB SKDM (CBAM) için ücretsiz, interaktif hazırlık aracı**
**A free, interactive readiness tool for the Turkish Climate Law (ETS), TSRS, and EU CBAM**

[**▶ Aracı çevrimiçi aç / Open the tool**](https://burakdelibacak.github.io/cop31-uyum-radari/)

[![Sürüm](https://img.shields.io/badge/s%C3%BCr%C3%BCm-v0.1.0-0E7A70)](https://github.com/BurakDelibacak/cop31-uyum-radari/releases)
[![Lisans](https://img.shields.io/badge/lisans-CC%20BY--NC%204.0-A9743A)](LICENSE)
[![Tek dosya](https://img.shields.io/badge/tek%20dosya-%C3%A7evrimd%C4%B1%C5%9F%C4%B1%20%C3%A7al%C4%B1%C5%9F%C4%B1r-1B242A)](#)

[Türkçe](#-türkçe) · [English](#-english)

</div>

---

## 🇹🇷 Türkçe

### Nedir?

COP31, Türkiye'nin ev sahipliğinde **9–20 Kasım 2026**'da Antalya'da yapılıyor — tam olarak Türk şirketlerini doğrudan etkileyen üç ayrı mevzuatın (İklim Kanunu/ETS, TSRS güvence denetimi, AB SKDM/CBAM) yürürlüğe girdiği döneme denk geliyor.

**COP31 Uyum Radarı**, bir şirketin bu rejimlerden hangileriyle muhatap olduğunu birkaç soruyla tespit eden, her biri için ayrıntılı kontrol listesi sunan ve yönetim kuruluna gösterilebilecek bir hazırlık raporu üreten ücretsiz bir öz-değerlendirme aracıdır.

### Nasıl çalışır?

Araç üç adımda ilerler:

**1 · Profil** — 8 soru: yasal merkez, Ek-1 sektörü, emisyon kategorisi, AB'ye ihracat, halka açıklık, TSRS kapsam değerlendirmesi, AB iştiraki, gönüllü hedefler.

**2 · Sinyal** — Yanıtlarınıza göre beş rejim için ayrı sonuç üretilir: MRV kapsamı, muhtemel kapsam, ticari etki, doğrulayın, fırsat. Bilgi eksikse araç kesin bir sonuç uydurmak yerine *"Profili tamamlayın"* uyarısı verir.

**3 · Eylem** — 55 maddelik ağırlıklı kontrol listesi, hazırlık skoru ve öncelik sıralı aksiyon listesi.

<table>
<tr>
<td width="50%"><img src="screenshots/exposure-map.png" alt="Maruziyet Haritası"></td>
<td width="50%"><img src="screenshots/dashboard.png" alt="Hazırlık Paneli"></td>
</tr>
<tr>
<td><b>Maruziyet Haritası</b> — hangi rejimler sizi kapsıyor</td>
<td><b>Hazırlık Paneli</b> — ağırlıklı skor ve aksiyon listesi</td>
</tr>
</table>

### Kontrol listesi

| Modül | Madde sayısı |
|---|:--:|
| Türkiye ETS / MRV | 17 |
| TSRS | 15 |
| AB SKDM (CBAM) | 11 |
| AB CSRD / ESRS | 6 |
| Gönüllü çerçeveler / COP31 | 6 |
| **Toplam** | **55** |

Her madde **w1–w3** öncelik ağırlığı taşır. Kontrol durumları: Başlanmadı, Devam ediyor, Hazır, Doğrulandı, Uygulanamaz (N/A). N/A işaretlenen maddeler hem paydan hem paydadan çıkarılır. Genel skora yalnızca aktif kapsam sinyali veren modüller katılır; ETS, TSRS ve CBAM yüksek, CSRD orta, gönüllü modül düşük aciliyet ağırlığı taşır.

<img src="screenshots/checklist.png" alt="Kontrol listesi modülü" width="100%">

### Özellikler

- **Otomatik maruziyet haritası** — 8 soru, 5 rejim
- **55 maddelik ağırlıklı kontrol listesi**, kategori bazlı ilerleme takibi
- **Hazırlık paneli** — ağırlıklandırılmış skor, öncelik sıralı aksiyon listesi
- **Tek tıkla PDF indirme** — sertifika ve tam hazırlık raporu (tarayıcı yazdırma penceresi gerekmez)
- **CSV dışa aktarma**
- **Türkçe / İngilizce** arayüz, koyu / kağıt tema
- **Tamamen çevrimdışı çalışır** — tek bir HTML dosyası, kurulum yok, sunucu yok, veri hiçbir yere gönderilmez; her şey yalnızca kendi tarayıcınızda (localStorage) saklanır

### Nasıl kullanılır?

**Seçenek 1 — Tarayıcıda açın:** [burakdelibacak.github.io/cop31-uyum-radari](https://burakdelibacak.github.io/cop31-uyum-radari/)

**Seçenek 2 — Bilgisayarınıza indirin:**

1. [`index.html`](index.html) dosyasını indirin (sağ tık → Farklı kaydet)
2. Herhangi bir tarayıcıda (Chrome, Edge, Safari, Firefox) çift tıklayarak açın — kuruluma gerek yok
3. Kurum profilinizi doldurun, ilgili modülleri işaretleyin, hazırlık raporunuzu indirin

Kurumsal kullanım için bu dosyayı kendi web sitenizde veya intranetinizde barındırabilirsiniz.

### Kapsanan kritik tarihler

| Tarih | Olay |
|---|---|
| 01.01.2024 | TSRS 1 ve TSRS 2 yürürlük |
| 09.07.2025 | 7552 sayılı İklim Kanunu |
| 01.01.2026 | AB CBAM kesin dönem başlangıcı |
| 27.08.2026 | Türkiye ETS Yönetmeliği (RG 33353) |
| 27.10.2026 | Pilot dönem Ek-4 planı temel tarihi |
| 09–20.11.2026 | **COP31, Antalya** |
| 30.09.2027 | 2026 ithalatı ilk CBAM yıllık beyanı |
| 09.07.2028 | Kategori B/C ETS izin dosyası temel geçiş tarihi |

Metodoloji sürümü **2026.09** · Mevzuat inceleme tarihi **2 Eylül 2026**

### Yasal uyarı

Bu araç yalnızca kurum içi öz-değerlendirme ve hazırlık planlaması amacıyla hazırlanmıştır; hukuki, mali veya denetim görüşü niteliği taşımaz ve resmî bir uygunluk beyanı ya da güvence denetimi yerine geçmez. Eşik değerleri, kapsam listeleri ve tarihler ilgili mevzuatın güncellenmesiyle değişebilir — nihai karar öncesi ilgili resmî kurumun güncel metnini doğrulayın.

**Resmî kaynaklar:** [UNFCCC COP31](https://cop31.tr) · [İklim Değişikliği Başkanlığı](https://iklim.gov.tr) · [KGK — TSRS](https://www.kgk.gov.tr) · [Ticaret Bakanlığı — SKDM](https://ticaret.gov.tr) · [European Commission — CBAM](https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism_en)

### Lisans

[Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/deed.tr) — ücretsiz kullanabilir, kopyalayabilir ve paylaşabilirsiniz; **Omnius Creative'e atıf yapılması** ve **ticari amaçla satılmaması** şartıyla. Ayrıntılar için [`LICENSE`](LICENSE) dosyasına bakın.

### İletişim

**Omnius Creative** · İzmir, Türkiye
burak.delibacak@omniuscreative.com · [omniuscreative.com](https://omniuscreative.com/)

---

## 🇬🇧 English

### What is this?

COP31, hosted by Türkiye, takes place in Antalya on **9–20 November 2026** — the exact window in which three regulatory regimes affecting Turkish companies come into force: the Turkish Climate Law (ETS), TSRS assurance audits, and the EU Carbon Border Adjustment Mechanism (CBAM).

**COP31 Compliance Radar** is a free self-assessment tool that determines which of these regimes apply to a given company, provides a detailed checklist for each, and generates a board-ready readiness report.

### How it works

**1 · Profile** — 8 questions: legal headquarters, Annex 1 sector, emissions category, EU exports, public listing, TSRS scope assessment, EU parent or subsidiary, voluntary targets.

**2 · Signal** — Your answers drive a separate result for each of five regimes: MRV scope, likely scope, commercial impact, verify, opportunity. Where information is missing, the tool returns a *"complete your profile"* prompt rather than inventing a false-certainty answer.

**3 · Action** — A 55-item weighted checklist, readiness score and prioritised action list.

### Checklist

| Module | Items |
|---|:--:|
| Turkish ETS / MRV | 17 |
| TSRS | 15 |
| EU CBAM | 11 |
| EU CSRD / ESRS | 6 |
| Voluntary frameworks / COP31 | 6 |
| **Total** | **55** |

Each item carries a **w1–w3** priority weight. Statuses: Not started, In progress, Ready, Verified, Not applicable (N/A). Items marked N/A are removed from both numerator and denominator. Only modules with an active scope signal count toward the overall score; ETS, TSRS and CBAM carry high urgency, CSRD medium, the voluntary module low.

### Features

- **Automatic exposure map** — 8 questions, 5 regimes
- **55-item weighted checklist** with category-level progress tracking
- **Readiness dashboard** — weighted score, prioritised action list
- **One-click PDF export** — certificate and full readiness report (no print dialog required)
- **CSV export**
- **Turkish / English** interface, dark / paper theme
- **Fully offline** — a single HTML file, no install, no server, no data ever leaves your browser (everything is stored locally via localStorage)

### How to use

**Option 1 — Open in your browser:** [burakdelibacak.github.io/cop31-uyum-radari](https://burakdelibacak.github.io/cop31-uyum-radari/)

**Option 2 — Download it:**

1. Download [`index.html`](index.html) (right click → Save as)
2. Double-click to open in any browser (Chrome, Edge, Safari, Firefox) — no installation needed
3. Fill in your company profile, work through the relevant modules, download your readiness report

For institutional use, you're welcome to host this file on your own website or intranet.

### Disclaimer

This tool is provided solely for internal self-assessment and readiness planning; it does not constitute legal, financial, or audit opinion and is not a substitute for a formal compliance statement or assurance audit. Thresholds, scope lists, and dates may change as the underlying legislation is updated — verify against the relevant official authority's current text before making final decisions.

**Official sources:** [UNFCCC COP31](https://cop31.tr) · [Turkish Presidency of Climate Change](https://iklim.gov.tr) · [KGK — TSRS](https://www.kgk.gov.tr) · [Turkish Ministry of Trade — CBAM](https://ticaret.gov.tr) · [European Commission — CBAM](https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism_en)

### License

[Creative Commons BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — free to use, copy, and share, provided you **credit Omnius Creative** and **do not sell it commercially**. See [`LICENSE`](LICENSE) for details.

### Contact

**Omnius Creative** · İzmir, Türkiye
burak.delibacak@omniuscreative.com · [omniuscreative.com](https://omniuscreative.com/)
