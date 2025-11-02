# Mercek Projesine Katkıda Bulunma Rehberi

Mercek tarayıcısını geliştirme misyonumuza ortak olmak istemeniz bizi heyecanlandırdı. Bu proje, **Duruluk Vakfı**'nın dijital gizlilik ve şeffaflık vizyonunun stratejik bir parçasıdır.

Yapacağınız her katkı, Google'ın kapalı ekosistemlerine karşı felsefi olarak bağımsız ve açık kaynaklı bir alternatifi desteklemek anlamına gelir.

## 🧭 Felsefi Çerçevemiz

Lütfen katkıda bulunmadan önce projemizin temel felsefesini anladığınızdan emin olun:

1.  **Neden Firefox/Gecko?**
    `Mercek`, Chromium (Blink) motorunu kullanmayı **felsefi olarak reddeder**. İnternet ekosisteminde motor çeşitliliğinin (engine diversity) kritik olduğuna inanıyoruz. Bu nedenle, teknik olarak daha zorlu bir yol olsa da Mozilla'nın **Gecko motorunu** temel alıyoruz.
2.  **Ekosistem Entegrasyonu:**
    `Mercek`, Vakfın diğer projeleri olan `Berrak` (Arama), `Pusula` (Harita) ve `Kasa Paketi` (Depolama/E-posta) ile sorunsuz çalışacak şekilde tasarlanmaktadır.
3.  **Kullanıcı Güvenliği:**
    Önceliğimiz, kullanıcıları takip eden mekanizmaları varsayılan olarak engellemek ve verilerini korumaktır.

## 🤝 Katkı Yöntemleri

### 1. Hata Bildirimi ve Fikir Paylaşımı (Issues)

Bir hata bulduysanız veya bir güvenlik açığı keşfettiyseniz, lütfen "Issues" (Sorunlar) sekmesini kullanarak bir bildirim oluşturun.

* **Açık Başlık:** Sorunu veya öneriyi özetleyen net bir başlık kullanın.
* **Detaylı Açıklama:**
    * **Hata Bildirimi İçin:** Hatayı nasıl tekrarlayabileceğimize dair adımları (Steps to reproduce), beklenen davranışı ve mevcut davranışı açıklayın. Kullandığınız işletim sistemi ve Mercek sürümünü belirtin.
    * **Öneri/Fikir İçin:** Önerinizin hangi sorunu çözeceğini ve ekosistemin felsefesine nasıl uyduğunu açıklayın.

### 2. Kod Katkısı (Pull Requests)

Kod ile katkıda bulunmak, projemize yapabileceğiniz en değerli desteklerden biridir.

1.  **Projeyi Çatallayın (Fork):** Projenin GitHub deposunu kendi hesabınıza çatallayın.
2.  **Yeni Bir Dal Oluşturun (Branch):** Değişiklikleriniz için açıklayıcı bir isme sahip yeni bir dal oluşturun (Örn: `feature/daha-guclu-izleyici-korumasi` veya `fix/gecko-derleme-hatasi`).
3.  **Değişikliklerinizi Yapın (Commit):** Değişikliklerinizi net ve açıklayıcı "commit" mesajları kullanarak kaydedin.
4.  **Katkı Talebi Gönderin (Pull Request - PR):** Değişikliklerinizi ana depoya göndermek için bir Pull Request açın.
    * PR açıklamasında, ne yaptığınızı, neden gerekli olduğunu ve felsefemize nasıl uyduğunu net bir şekilde açıklayın.
    * Eğer mevcut bir "Issue" ile ilgiliyse, `Closes #123` gibi bir ifadeyle ilgili sorunu etiketleyin.

### 3. Geliştirme ve Derleme

Bu proje, **Gecko motoru** üzerine kurulu `mozilla-central` deposunun bir çatallanmasıdır. Bu, derleme ve geliştirme süreçlerinin standart web projelerinden çok daha karmaşık olduğu anlamına gelir.

Katkıda bulunmadan önce Mozilla'nın resmi geliştirici belgelerine aşina olmanız beklenmektedir:

* [Firefox Kaynak Kod Derleme Talimatları (İngilizce)](https://firefox-source-docs.mozilla.org/setup/index.html)
* [Mozilla Kodlama Standartları (İngilizce)](https://firefox-source-docs.mozilla.org/code-quality/coding-style/index.html)

Öncelikli katkı alanlarımız, temel Gecko motorunu değiştirmekten ziyade, **güvenlik yamaları uygulamak, gizlilik ayarlarını sıkılaştırmak ve takip edicileri engellemek** üzerine yoğunlaşmıştır.

### 4. Belgelendirme ve Çeviri

İyi bir kod kadar, iyi bir belgelendirme de önemlidir. `README.md` dosyasını iyileştirmek, özellikleri belgelemek veya arayüz metinlerini çevirmek için de katkıda bulunabilirsiniz.

---

Misyonumuza ortak olduğunuz ve daha güvenli bir internet için zaman ayırdığınız için teşekkür ederiz.
