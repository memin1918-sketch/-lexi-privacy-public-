Lexi Avukat Asistanı iOS · Android
Gizlilik Politikası
Yürürlük tarihi: 13 Mayıs 2026 · Son güncelleme: 13 Mayıs 2026

Kısa özet
Lexi tamamen sıfır-sunucu çalışır. Hiçbir müvekkil, dosya, tebligat veya belge verisi geliştiriciye veya üçüncü taraf bir sunucuya gönderilmez. Veriler yalnız
cihazınızda
ve isteğe bağlı olarak
sizin kendi bulut hesabınızda
(iCloud Drive / Google Drive) saklanır. Geliştirici hiçbir kişisel verinize erişemez.
1. Veri Sorumlusu
Uygulama: Lexi Avukat Asistanı
Geliştirici iletişim: av.eminzorlu@gmail.com

Lexi bireysel avukatların kendi müvekkil verilerini yönettiği bir araçtır. Avukat-kullanıcı, kendi müvekkillerine ait verilerin veri sorumlusu sıfatını taşır. Uygulama geliştiricisi, bu verilerin işleneceği bir sunucu işletmediği için veri işleyen sıfatını da taşımaz.

2. Toplanan ve İşlenen Veriler
Lexi, aşağıdaki verileri yalnız cihazınızda, yerel SQLite veritabanında saklar:

Müvekkil bilgileri: ad-soyad, T.C. kimlik no, telefon, e-posta, adres
Dosya bilgileri: mahkeme, esas/karar no, dava türü, tarihler
Tebligat ve süre takibi kayıtları
Duruşma, masraf, ücret, ödeme, karar arşivi kayıtları
Eklenen evraklar (vekâletname, dilekçe vb.) — yalnız cihaz dosya sisteminde
Uygulama tercihleri (tema, biyometrik kilit, bildirim saati)
Hassas alanlar (T.C. kimlik, telefon, e-posta, adres, vekâletname içeriği vb.) cihazda AES-256-GCM ile şifrelenir; şifre çözme anahtarı yalnız cihazın güvenli hafızasında (iOS Keychain / Android Keystore) tutulur.

3. Geliştiriciye Gönderilen Veriler
Hiçbir veri gönderilmez. Uygulamada analitik, telemetri, çökme raporlama (crash reporting), reklam SDK'sı veya üçüncü taraf izleme aracı bulunmamaktadır.

Tek istisna: Kullanıcı "Geri Bildirim" ekranından kendi e-posta uygulamasını açtığında, gönderdiği iletinin içeriği yalnız av.eminzorlu@gmail.com adresine ulaşır ve bu posta kutusu standart e-posta güvenliği ile işlenir.

4. Bulut Senkronizasyonu (İsteğe Bağlı)
Açılış ekranında üç seçenek sunulur:

Google Drive ile devam et — Yedekler Drive hesabınızdaki LEXİ klasörüne yazılır. Kapsam drive.file ile sınırlıdır; Lexi yalnız kendi oluşturduğu dosyalara erişebilir, Drive'ınızın geri kalanını göremez.
iCloud Drive ile devam et (iOS) — Yedekler iCloud Drive'daki LEXİ klasörüne yazılır.
Bulutsuz devam et — Hiçbir bulut hesabıyla bağlantı kurulmaz, hiçbir veri cihaz dışına çıkmaz. Bu mod seçildiğinde uygulama yalnız yerel modda çalışır.
Bulut seçildiğinde dahi veriler doğrudan sizin bulut hesabınıza gider; geliştiriciye veya Lexi'nin işlettiği bir sunucuya asla aktarılmaz.

5. İzinler
Kamera / Fotoğraflar — Yalnız belge çekmek/eklemek için, kullanıcı bizzat başlattığında.
Bildirimler — Tebligat süresi, duruşma ve yedekleme hatırlatmaları için. Tüm bildirimler cihaz üzerinde yerel olarak planlanır; sunucu push servisi kullanılmaz.
Biyometrik (Face ID / Touch ID / Parmak izi) — Yalnız uygulamayı açarken kilit doğrulaması için. Biyometrik veri uygulamaya ulaşmaz; doğrulama tamamen işletim sistemi tarafında yapılır.
Dosyalar — Yedek dışa aktarma / geri yükleme sırasında, kullanıcının seçtiği dosyaya erişim için.
6. Çocukların Verileri
Lexi profesyonel avukatlık kullanımı için tasarlanmıştır ve 18 yaş altındaki bireylere yönelik değildir. 18 yaş altı kullanıcılardan bilinçli olarak veri toplanmaz.

7. Veri Saklama Süresi
Veriler kullanıcı silene kadar cihazda kalır. Uygulamanın silinmesi cihazdaki tüm verileri kaldırır. Bulut yedekleri yalnız kullanıcının kendi Drive / iCloud hesabında olduğundan, ilgili yedeklerin silinmesi veya saklanma süresi kullanıcının tasarrufundadır.

8. Kullanıcı Hakları (KVKK m. 11 / GDPR Madde 15-22)
Verileriniz yalnız sizin cihazınızda ve sizin bulutunuzda olduğundan, KVKK ve GDPR'da yer alan haklara doğrudan uygulama içinden ulaşabilirsiniz:

Verilerinizi görüntüleme: Müvekkil / Dosya / Tebligat ekranları
Düzeltme: "Düzenle" akışları
Silme: Liste ekranlarındaki kaydırma silme ve "Arşiv" akışı
Taşınabilirlik: "Daha → Dışa Aktarma" PDF / DOCX
Yedek alma / geri yükleme: "Daha → Yedekleme"
Uygulamanın işleyişine dair soru ve talepleriniz için: av.eminzorlu@gmail.com

9. Güvenlik
Hassas alanlar cihaz üzerinde AES-256-GCM ile şifrelidir.
Anahtar yalnız iOS Keychain / Android Keystore içinde tutulur.
Uygulama arka plana alındığında ekran içeriği bulanıklaştırılır (App Switcher önizlemesinde müvekkil bilgisi görünmez).
İsteğe bağlı biyometrik kilit (Face ID / Touch ID / parmak izi) açılışta doğrulama ister.
Uygulama hiçbir TLS/HTTPS olmayan bağlantı kullanmaz; bulut sağlayıcılarına yalnız resmi SDK / OAuth uçları üzerinden bağlanır.
10. Üçüncü Taraf Hizmetleri
Lexi yalnız kullanıcının bizzat seçtiği bulut sağlayıcılarına bağlanır:

Google Drive — Google Gizlilik Politikası
iCloud Drive — Apple Gizlilik Politikası
Bu sağlayıcıları kullanmadığınız sürece üçüncü tarafa hiçbir veri aktarımı yapılmaz.

11. Politika Değişiklikleri
Bu politika güncellenirse, yeni sürüm aynı GitHub adresinde yayımlanır ve sayfanın üst kısmındaki "Son güncelleme" tarihi yenilenir. Köklü değişiklikler uygulama içinden ayrıca duyurulur.

12. İletişim
Bu gizlilik politikası veya Lexi hakkında her türlü soru için:
av.eminzorlu@gmail.com

© 2026 Lexi Avukat Asistanı. Tüm hakları saklıdır.
