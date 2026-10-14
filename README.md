# ARC Mail Arşiv

Eski Yandex e-postalarınızı kendi bilgisayarınıza yedekleyen program. Yedek bilgisayarınızda kalır ve Thunderbird ile açıp içinde arama yapabilirsiniz. Eski postalar yeni Microsoft 365 hesabına taşınmayacak, bu arşivden okunacak.

## 1. İndirin

**[İndirme sayfası (en son sürüm)](https://github.com/alisencerefeturk/ARC-Mail-Arsiv/releases/latest)**

Sayfanın altındaki **Assets** bölümünden bilgisayarınıza uygun dosyayı indirin:

| Bilgisayarınız | İndireceğiniz dosya |
|---|---|
| Windows | `ARC-Mail-Arsiv-...-Windows.exe` |
| Mac (Apple M1/M2/M3/M4 çipli) | `ARC-Mail-Arsiv-...-Mac-Apple-Silicon.dmg` |

Mac'inizin çipini görmek için: sol üstteki Apple menüsü → **Bu Mac Hakkında**. "Çip: Apple M…" yazıyorsa DMG'yi indirin. "İşlemci: Intel" yazıyorsa IT'ye haber verin.

## 2. Açın

### Windows
Kurulum gerekmez, indirdiğiniz `.exe` dosyası programın kendisidir.

1. Dosyayı **İndirilenler** klasöründen çift tıklayarak açın.
2. Tarayıcı "yaygın olarak indirilmiyor" uyarısı verirse: dosyanın yanındaki **…** → **Sakla** → **Yine de sakla**.
3. Mavi **"Windows bilgisayarınızı korudu"** penceresi çıkarsa: **Ek bilgi** → **Yine de çalıştır**.

### Mac
1. İndirdiğiniz `.dmg` dosyasını çift tıklayın.
2. Açılan pencerede **ARC Mail Arsiv** simgesini yanındaki **Applications** (Uygulamalar) klasörüne sürükleyin.
3. **Uygulamalar** klasöründe **ARC Mail Arsiv**'i çift tıklayarak açın.
4. "İnternetten indirilmiş bir uygulama, açmak istediğinizden emin misiniz?" sorusu çıkarsa **Aç**'a basın. Bu soru yalnız ilk açılışta görünür.

Windows'taki uyarılar programın Microsoft'a ücretli olarak imzalatılmamasından kaynaklanır; yalnız ilk açılışta görünür.

## 3. Yedeği alın

1. **E-posta adresinizi** ve Yandex'e web'den girdiğiniz **normal şifrenizi** yazıp **Devam**'a basın.
   - Program "uygulama şifresi" isterse ekrandaki adımları izleyin. Takılırsanız IT'ye haber verin.
2. Arşivin kaydedileceği konum ekranda görünür. Değiştirmenize gerek yoktur.
   - Windows: `C:\ARC-Mail-Arsivi\<e-posta adresiniz>`
   - Mac: ana klasörünüzde `ARC-Mail-Arsivi`
   - Masaüstü, Belgeler, OneDrive, iCloud, harici disk ve ağ diskleri kabul edilmez.
3. **Neyi arşivleyelim?** bölümünde hangi yılları ve klasörleri alacağınızı seçebilirsiniz. **Emin değilseniz hepsini seçili bırakın**; seçmedikleriniz daha sonra hiçbir yerde olmayacak.
4. **Arşivlemeyi başlat**'a basın.
   - Posta kutunuzun büyüklüğüne göre birkaç dakikadan birkaç saate kadar sürebilir.
   - Bu sürede bilgisayarı kapatmayın. Dizüstü bilgisayarı şarja takın. Program bilgisayarın uykuya geçmesini kendisi engeller.
   - Ara vermeniz gerekirse **Durdur**'a basın. Programı yeniden açıp aynı e-posta ve şifreyle girdiğinizde **kaldığı yerden devam eder**; indirilenler tekrar inmez.
5. Ekranda **"Yandex'te şu an okunamayan: N ileti"** görebilirsiniz. Yandex'teki arıza nedeniyle bazı eski iletiler şu an sunucudan okunamıyor. Program bunları atlayıp listeye alır. Yandex düzelince programı tekrar açıp **Eksikleri tamamla**'ya basmanız yeterli olacak.

## 4. Thunderbird'e ekleyin

Arşivi okumak için Thunderbird kullanılır.

1. Thunderbird yüklü değilse [thunderbird.net/tr](https://www.thunderbird.net/tr/) adresinden yükleyin, **bir kez açıp kapatın**.
2. Thunderbird **kapalıyken** ARC Mail Arşiv'in son ekranında **Thunderbird'e ekle**'ye basın.
3. Thunderbird'ü açın. Sol tarafta **Yerel Klasörler** altında **Yandex Arsivi - <adınız>** klasöründe eski postalarınız görünür.

## Önemli

- **Yandex hesabınızı kapatmayın** ve postalarınızı Yandex'ten silmeyin. Okunamayan iletiler daha sonra oradan indirilecek.
- **Arşiv klasörünü silmeyin, taşımayın, adını değiştirmeyin.** Thunderbird postaları doğrudan bu klasörden okur.
- **Thunderbird'de arşivdeki bir postayı silerseniz arşivden de kalıcı olarak silinir.**
- Şifreniz hiçbir dosyaya kaydedilmez. Program Yandex'teki postalarınızı değiştirmez ve silmez, yalnız okur.

## Sorun olursa

Programdaki **Destek paketi oluştur** düğmesine basın. Masaüstünüze bir ZIP dosyası kaydedilir; bu dosyayı IT'ye gönderin. ZIP'te şifreniz ve e-postalarınızın içeriği bulunmaz.
