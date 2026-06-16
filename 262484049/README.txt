# PROJE TESLİM DOSYASI İÇERİĞİ

Bu teslim dosyası içerisinde aşağıdaki belgeler ve proje bileşenleri bulunmaktadır:

* Proje Sunumu (.pptx)
* Proje Raporu (.docx / .pdf)
* Android Studio Kaynak Kodları
* Uygulamaya ait APK dosyası
* Uygulamanın tanıtım ve kullanım videosu

# KAYNAK KODLARIN ÇALIŞTIRILMASI

1. Android Studio uygulamasını açınız.
2. Sıkıştırılmış dosyadan çıkardığınız "Wisdom_of_Luna" isimli proje klasörünü Android Studio ile açınız.
3. Gradle senkronizasyonunun tamamlanmasını bekleyiniz.
4. Senkronizasyon işlemi otomatik olarak başlamazsa, Android Studio üzerinde bulunan **"Sync Project with Gradle Files"** seçeneğini kullanınız.
5. İnternet hızınıza bağlı olarak Gradle dosyalarının indirilmesi ve senkronizasyon işlemi 1-10 dakika arasında sürebilir.
6. Senkronizasyon tamamlandıktan sonra projeyi Build/Run ederek çalıştırabilirsiniz.

# FİZİKSEL ANDROID CİHAZ ÜZERİNDE ÇALIŞTIRMA

Uygulamayı Android Studio üzerinden fiziksel bir Android cihazda çalıştırmak için aşağıdaki adımları uygulayınız:

1. Android telefonunuzu USB veri kablosu ile bilgisayarınıza bağlayınız.
2. Telefonunuzda **Geliştirici Seçenekleri** menüsünü aktif hale getiriniz.
3. Geliştirici Seçenekleri içerisinden **USB Hata Ayıklama (USB Debugging)** özelliğini etkinleştiriniz.
4. Telefonu bilgisayara bağladıktan sonra ekrana gelen **"Bu bilgisayara USB hata ayıklama izni verilsin mi?"** sorusunu onaylayınız.
5. Android Studio üzerinde cihazınızın algılandığını kontrol ediniz.
6. Run (▶) butonuna basarak uygulamayı telefon üzerinde çalıştırınız.

## Geliştirici Seçeneklerini Açma

1. Telefonunuzda **Ayarlar** menüsünü açınız.
2. **Telefon Hakkında** bölümüne giriniz.
3. **Yapım Numarası (Build Number)** seçeneğine art arda 7 kez dokununuz.
4. Ekranda "Artık geliştiricisiniz" benzeri bir mesaj görüntülenecektir.
5. Ayarlar menüsüne geri dönerek **Geliştirici Seçenekleri** bölümünü açınız.
6. **USB Hata Ayıklama (USB Debugging)** seçeneğini aktif hale getiriniz.

# APK KURULUMU

APK dosyası Android cihazlara doğrudan kurulabilir.
APK dosyasını kendi telefonunuza wp üzerinden rahatca gönderebilirsiniz.
Kurulum sırasında cihazınız "Bilinmeyen Kaynaklar" veya "Bu Kaynaktan Yüklemeye İzin Ver" uyarısı gösterirse, ilgili izni etkinleştirerek kuruluma devam edebilirsiniz.

# VERİTABANI BİLGİSİ

Uygulama çevrimiçi (online) veritabanı altyapısı kullanmaktadır. Bu nedenle uygulamanın çalıştırılması için herhangi bir veritabanı kurulumu veya ek yapılandırma yapılmasına gerek yoktur.

Hem Android cihaz üzerinde APK kurulumu ile hem de Android Studio üzerinden kaynak kodlar kullanılarak uygulama sorunsuz şekilde çalıştırılabilir.
