# Zehra UYSAL — Okul Takip Sistemi

## GitHub'a yükleme ve yayınlama

1. GitHub'da yeni bir depo oluşturun.
2. Bu `sunucu` klasörünün **içindeki dosyaları** deponun ana dizinine yükleyin. `index.html` doğrudan ana dizinde olmalıdır.
3. Depoda **Settings → Pages** sayfasını açın.
4. **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)** seçip **Save** düğmesine basın.
5. Yayınlama tamamlandığında aynı sayfada sitenin adresi görünür.

Resmî kılavuz: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Dosyalar

- `index.html`: Tasarım, stiller ve uygulama kodunun tamamı.
- `.nojekyll`: Statik dosyalar için GitHub Pages ayarı.
- `README.md`: Bu kurulum ve kullanım açıklaması.

Paket kurulumu, derleme, API anahtarı veya ayrı bir sunucu gerekmez. Bilgisayarınızda denemek için `index.html` dosyasını güncel bir tarayıcıda açabilirsiniz.

## Kullanım

- Öğrencilerim: öğrenci ekleme, takip notu yazma ve düzenleme.
- Proje atölyesi: TEKNOFEST, eTwinning ve TÜBİTAK taslakları oluşturma ve düzenleme.
- Bağlantıları düzenle: Notlarım, Dosyalarım ve Yıllık planlarım bağlantılarını ekleme.
- Kendime bir not: kısa notları otomatik kaydetme.

## Verilerin saklanması

Bu sürüm bir arayüz ve tarayıcıda çalışan kişisel takip uygulamasıdır. Giriş sistemi, sunucu veritabanı ve cihazlar arası eşitleme içermez. Öğrenciler, taslaklar, notlar ve bağlantılar yalnızca kullanılan tarayıcının localStorage alanında saklanır. Tarayıcı verileri temizlenirse kayıtlar silinir. Başka cihazda, başka tarayıcıda veya farklı site adresinde bu kayıtlar görünmez. Mevcut yerel HTML'deki kayıtlar GitHub Pages adresine kendiliğinden taşınmaz.

Kaynak dosyalarında öğrenci kaydı veya şifre bulunmaz. GitHub'a yüklemek mevcut tarayıcı kayıtlarını yüklemez. Drive bağlantıları, ilgili belgenin Drive paylaşım izinlerine göre açılır. Proje alanı yazma ve taslak kaydetme içindir; yapay zekâ ile otomatik üretim içermez.