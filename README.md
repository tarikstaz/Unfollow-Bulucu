# 📸 Instagram Unfollow & Ghost Tracker

Bu araç, Instagram hesabınızda sizi geri takip etmeyenleri ve dondurulmuş/kapatılmış (hayalet) hesapları güvenli bir şekilde tespit etmeniz için geliştirilmiştir. **Şifreniz asla istenmez**, tüm işlemler tarayıcınızda gerçekleşir.

---

## 🚀 Nasıl Kullanılır? (Adım Adım)

### 1. Adım: Instagram Verilerinizi İndirin
Instagram'ın güncel verilerinizi size göndermesi gerekir:
1. Instagram profilinizden **Ayarlar ve Gizlilik** > **Hesaplar Merkezi** kısmına gidin.
2. **Bilgilerin ve İzinlerin** > **Bilgilerini İndir** seçeneğine tıklayın.
3. **İndirme veya Aktarma Yap** dedikten sonra **Bazı Bilgiler**'i seçin.
4. Listeden sadece **"Takipçiler ve Takip Edilenler"** kutucuğunu işaretleyin.
5. **Cihaza İndir**'i seçin.
6. **ÖNEMLİ:** Formatı **JSON** olarak seçin (HTML çalışmaz). Medya kalitesini "Düşük" yapabilirsiniz (daha hızlı iner).
7. Talep oluşturun. Instagram dosyanız hazır olduğunda size bildirim gönderecektir (Genelde 15-30 dk sürer).

### 2. Adım: Dosyaları Hazırlayın
Instagram'dan gelen `.zip` dosyasını bilgisayarınıza indirin ve klasöre çıkartın. Klasörün içinde şu iki dosyayı bulun:
* `followers_1.json`
* `following.json`

### 3. Adım: Analiz Edin
1. Bu web sitesini (GitHub Pages linkinizi) açın.
2. Mavi kesikli alana tıklayarak yukarıdaki iki dosyayı aynı anda seçin.
3. Liste anında karşınıza dökülecektir.

---

## 🛠 Özellikler
* **Arama Çubuğu:** Listede spesifik bir kullanıcıyı arayabilirsiniz.
* **Görsel Takip:** Profili kontrol edilen hesaplar grileşir ve üzeri çizilir.
* **Hayalet Hesap İşaretleme:** "Kapalı Hesap" butonu ile hata veren hesapları listenin sonuna taşıyabilirsiniz.
* **Veri Güvenliği:** Kodlar tamamen açık kaynaklıdır; verileriniz sunucuya yüklenmez, sadece sizin bilgisayarınızda işlenir.

---

## ⚠️ Önemli Uyarılar
* **Limitler:** Instagram, hızlı takipten çıkma işlemlerini engelleyebilir. Güvenliğiniz için **saatte 20-30 kişiden fazla** işlem yapmamaya özen gösterin.
* **Doğruluk:** Eğer "0 kişi" veya yanlış rakamlar görüyorsanız, Instagram verileri henüz güncellenmemiş olabilir veya dosyaları yanlış seçmiş olabilirsiniz.
