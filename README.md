# Hexlume Software — GitHub Pages sitesi

Bu klasör, derleme veya kurulum gerektirmeyen statik web sitesidir. `index.html` doğrudan ana sayfadır; `privacy.html` ise gizlilik politikası taslağıdır.

## Yayınlamadan önce

1. `privacy.html` içindeki köşeli parantezli alanları, uygulamanızın gerçek veri uygulamalarına göre doldurun. Uygulamayı doğrulamadan SDK, reklam ağı veya veri toplama bilgisi eklemeyin.
2. `APP_ADS_TXT_SETUP.md` dosyasındaki adımları gerçek AppLovin satırınız elinizdeyse uygulayın.

## GitHub Pages ile yayınlama

1. GitHub'da örneğin `hexlume-software.github.io` adında **public** bir depo oluşturun. Kişisel web adresiniz bu depoda `https://hexlume-software.github.io/` olur. Farklı depo adı da kullanabilirsiniz; adres `https://KULLANICI_ADI.github.io/DEPO_ADI/` olur.
2. Bu klasörün içindeki tüm dosyaları deponun en üst seviyesine yükleyin (`index.html` doğrudan kökte olmalı).
3. Depoda **Settings → Pages** bölümünü açın. **Build and deployment** altında kaynak olarak **Deploy from a branch**, dal olarak `main` ve klasör olarak `/(root)` seçin; ardından **Save** deyin.
4. GitHub'ın gösterdiği bağlantı birkaç dakika içinde aktif olur. Bu adresi Google Play Console ve AppLovin MAX'teki Website alanına yazabilirsiniz.

## Yerel kontrol

`index.html` dosyasını çift tıklayarak tarayıcıda açmanız yeterlidir.
