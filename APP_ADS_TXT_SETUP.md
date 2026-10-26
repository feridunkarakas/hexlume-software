# app-ads.txt kurulum notu

Bu proje kasıtlı olarak bir `app-ads.txt` kaydı içermez: gerçek AppLovin satırındaki seller/publisher ID bilinmeden böyle bir kayıt uydurmak doğrulamanın başarısız olmasına yol açabilir.

Gerçek bilgiyi AppLovin MAX hesabınızdaki **app-ads.txt** yönergelerinden kopyalayın. Ardından:

1. Bu klasörün en üst seviyesinde tam olarak `app-ads.txt` adında yeni bir dosya oluşturun.
2. AppLovin'in size verdiği satırı, değişiklik yapmadan bu dosyanın tek satırı olarak yapıştırın. Örnek biçim yalnızca şablondur; buradaki değerleri kullanmayın: `applovin.com, SIZIN_GERCEK_SELLER_ID, DIRECT, SIZIN_GERCEK_SERTIFIKA_ID`
3. Dosyayı diğer site dosyalarıyla birlikte GitHub'a yükleyin/yayınlayın.
4. Tarayıcıda `https://SITENIZ/app-ads.txt` adresini açarak satırın herkese açık ve doğru göründüğünü kontrol edin.
5. GitHub Pages adresinizi AppLovin MAX'teki Website alanına ekleyin. Sistem yeni dosyayı algılamak için zaman isteyebilir.

`app-ads.txt` yalnızca AppLovin yönergelerinde size açıkça verildiyse ve gerekli olduğunda eklenmelidir.
