# Duruluk Vakfı (Duruluk Foundation)

`README.md` | [Teknik Doküman (Whitepaper)](./WHITE PAPER.md) | [Katkıda Bulunma Rehberi](./CONTRIBUTING.md) | [Davranış Kuralları](./CODE_OF_CONDUCT.md)

**Misyonumuz:** İnternetin "gözetim kapitalizmi" ve "kara kutu" algoritmalarıyla yönetilen kapalı bahçelerine (walled gardens) karşı; herkesin gizlilik, şeffaflık ve kontrol hakkına sahip olduğu, açık kaynaklı, güvenli ve merkezi olmayan bir dijital ekosistem inşa etmek.

Biz, Google'a bir alternatif değil, Google'ın modeline bir **cevap** geliştiriyoruz.

-----

## 🏛️ Duruluk Modeli: Hibrit Bir Vakıf

`Duruluk`, sürdürülebilirliği sağlamak için iki kollu, hibrit bir modelle çalışır:

1.  **Kâr Amacı Gütmeyen Kol (Misyon):** Tamamen ücretsiz, açık kaynaklı ve topluluk odaklı temel hizmetler sunar. Bu kol, bağışlar ve ticari koldan gelen kârlarla finanse edilir.
2.  **Ticari Kol (Finansman):** Profesyonel altyapı (depolama, sunucu) gerektiren, yüksek güvenlikli, ücretli (SaaS) hizmetler sunar. Bu koldan elde edilen **tüm kâr**, misyonumuzu (Kâr Amacı Gütmeyen Kolu) finanse etmek için Vakfa aktarılır.

Paranız, bir CEO'yu zenginleştirmek için değil, internetin özgürleşmesini finanse etmek için kullanılır.

-----

## 🌱 Ekosistem Projelerimiz

Tüm projelerimiz, `Duruluk` organizasyonu altında farklı depolarda (repository) geliştirilmektedir.

### 1\. Kâr Amacı Gütmeyen Kol (Ücretsiz & Açık Kaynak)

Bu projeler misyonumuzun kalbidir ve daima ücretsiz kalacaktır.

#### 🔎 Proje: `Berrak` (Google Search Alternatifi)

  * **Felsefe:** Radikal Şeffaflık.
  * **Ne Yapar:** Aramalarınızı asla kaydetmeyen, Common Crawl gibi "bağışlanmış" verileri kullanan bir arama motoru. Sıralaması, Google'ın "kara kutu" algoritmasının aksine, herkesin denetleyebileceği açık kaynaklı `BerrakRank` algoritmasına dayanır.
  * **Depo:** `duruluk/berrak`

#### 🗺️ Proje: `Pusula` (Google Maps Alternatifi)

  * **Felsefe:** Mutlak Anonimlik ve Çevrimdışı Öncelik.
  * **Ne Yapar:** OpenStreetMap (OSM) verisini temel alan bir harita uygulaması. Konumunuzu veya rotalarınızı *asla* sunuculara göndermez. Tüm harita, arama ve rota verilerini telefonunuza indirerek internetin çekmediği yerlerde bile çalışır.
  * **Depo:** `duruluk/pusula`

### 2\. Ticari Kol (Ekosistemi Finanse Eden Hizmetler)

Bu projeler, profesyonel hizmetler sunar ve elde ettikleri kârla `Berrak` ve `Pusula`'yı ayakta tutar.

#### 📦 Proje: `Kasa Paketi` (Google Drive + Gmail Alternatifi)

  * **Felsefe:** "Sıfır Bilgi" (Zero-Knowledge) Mimarisi.
  * **Ne Yapar:** Dosyalarınızı (`Kasa`) ve E-postalarınızı (`Zarf`) tek bir ücretli abonelik altında, birleşik depolama havuzunda saklar. Tüm veriler (dosyalar, e-postalar, takvimler) sunucuya yüklenmeden *önce* cihazınızda şifrelenir. Biz dahil hiç kimse verilerinizi okuyamaz.
  * **Depolar:**
      * `duruluk/kasa-client` (Public - Şifrelemeyi denetleyin)
      * `duruluk/zarf-client` (Public - Şifrelemeyi denetleyin)
      * `duruluk/kasa-server` (Private - Ticari altyapı)

#### 🧠 Proje: `BilgeDefter` (NotebookLM Alternatifi)

  * **Felsefe:** Modüler ve Gizli RAG (Yapay Zeka).
  * **Ne Yapar:** Belgelerinizle (PDF, Notlar) konuşmanızı sağlayan yapay zeka aracı.
      * **Ücretsiz Sürüm:** %100 yerel (local-first) çalışır, açık kaynaklı modelleri (Ollama vb.) kullanır. Verileriniz asla cihazınızdan çıkmaz. (Depo: `duruluk/bilgedefter`)
      * **Pro Sürüm:** Gelişmiş, tescilli modelleri API üzerinden kullanır. Bu hizmet, Vakıf tarafından size (+kâr) ile satılır. (Depo: `duruluk/model-api`)

### 3\. Stratejik Projeler (Uzun Vadeli Hedef)

Bu projeler, `Kasa Paketi`'nden elde edilen kâr yeterli seviyeye ulaştığında finanse edilecektir.

#### 🔭 Proje: `Mercek` (Google Chrome Alternatifi)

  * **Felsefe:** Felsefi Bağımsızlık.
  * **Ne Yapar:** Google'ın Chromium motoruna olan tereddütümüz nedeniyle, Mozilla'nın **Gecko motorunu** (Firefox) temel alan bir tarayıcı. `Berrak`, `Kasa` ve `Pusula` ile tam entegre çalışacak şekilde tasarlanacaktır.
  * **Depo:** `duruluk/mercek`

-----

## 🔄 Finansal Döngü (Param Nereye Gidiyor?)

1.  Kullanıcılar `Kasa Paketi`'ne (Ticari Kol) abone olur.
2.  Elde edilen gelir, `Kasa` sunucularının maliyetini ve ekibin maaşlarını karşılar.
3.  Kalan **Kâr**, `Duruluk Vakfı`'na aktarılır.
4.  Vakıf, bu kârı (ve bağışları), `Berrak`, `Pusula` ve `Mercek` gibi **Kâr Amacı Gütmeyen** projelerin geliştirilmesi ve sunucu maliyetleri için kullanır.

## 🤝 Bize Katılın\! (Nasıl Katkıda Bulunurum?)

Bu, sadece bir yazılım projesi değil, bir dijital bağımsızlık hareketidir.

  * **Geliştiriciler:** `duruluk/vakif` deposundaki [CONTRIBUTING.md](./CONTRIBUTING.md) belgesini okuyun. Özellikle Rust, Go, C++ (Gecko), Python, React/JS ve DevOps/Sistem Mühendisliği konularında yardıma ihtiyacımız var.
  * **Topluluk:** Projelerimizi kullanın, hataları bildirin ve felsefemizi yayın.
  * **Bağışçılar:** (Buraya Vakfın bağış linki gelecek).

-----

**Lisans:** Bu organizasyondaki tüm açık kaynaklı projeler [MIT Lisansı](./LICENSE) (veya [Apache 2.0]) altında lisanslanmıştır.
