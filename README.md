# alpha-browser
Official updates and release files for Alpha Browser.

# Alpha Browser

**Alpha Browser**, IRC Technology tarafından geliştirilen; hızlı, modern, özelleştirilebilir ve gizlilik odaklı bir masaüstü internet tarayıcısıdır.

Bu depo, Alpha Browser’ın resmi Windows kurulum dosyalarını ve sürüm paketlerini barındırır.

> Bu depo kaynak kod deposu değildir. Yalnızca resmi Alpha Browser sürümleri ve güncelleme dosyaları paylaşılır.

---

## İndirme

Alpha Browser’ın en güncel sürümünü indirmek için aşağıdaki bağlantıyı kullanabilirsiniz:

**[Son sürümü indir](../../releases/latest)**

Releases sayfasındaki şu dosyayı indirmeniz yeterlidir:

```text
Alpha-Browser-Setup-x.x.x-x64.exe
```

Dosya adındaki `x.x.x` kısmı yayınlanan Alpha Browser sürümünü belirtir.

Örnek:

```text
Alpha-Browser-Setup-0.4.0-x64.exe
```

Aşağıdaki dosyalar normal kullanıcı kurulumu için gerekli değildir:

```text
Alpha-Browser-Setup-x.x.x-x64.exe.blockmap
latest.yml
```

Bu dosyalar Alpha Browser’ın güncelleme altyapısında kullanılır.

---

## Sistem Gereksinimleri

- Windows 10 veya Windows 11
- 64-bit işletim sistemi
- İnternet bağlantısı
- En az 4 GB RAM
- En az 500 MB boş depolama alanı

---

## Öne Çıkan Özellikler

- Sekmeli internet gezintisi
- Sürükle-bırak ile sekme sıralama
- Sabitlenebilir sekmeler
- Çalışma alanları
- Renkli sekme grupları
- Favoriler ve favori klasörleri
- Favori çubuğu
- Geçmiş sistemi
- Gizli gezinme
- Panik modu
- Alpha Shield reklam ve takipçi engelleme
- Focus Mode
- Okuma modu
- Sayfa çevirisi
- Ekran görüntüsü alma
- Bölünmüş ekran
- Gelişmiş indirme yöneticisi
- İnternet trafik ve hız göstergesi
- Aktif sekme hız önceliği
- Şifreli parola kasası
- Güvenli otomatik doldurma
- Kullanıcı adı ve parola kaydetme önerisi
- Profil sistemi
- Gemini destekli Alpha AI
- Eklenti yöneticisi
- Alpha Store
- Açık ve koyu tema seçenekleri
- Özelleştirilebilir sidebar uygulamaları

---

## Şifre Kasası ve Otomatik Doldurma

Alpha Browser, kullanıcı adı ve parola bilgilerini şifreli parola kasasında saklayabilir.

Bir internet sitesine giriş yaptığınızda Alpha Browser size şu bildirimi gösterebilir:

```text
Bu giriş bilgileri Alpha Kasası’na kaydedilsin mi?
```

Kayıtlı bir internet sitesini tekrar ziyaret ettiğinizde:

- Kullanıcı adı ve parola alanlarını doldurma
- Birden fazla kayıtlı hesap arasından seçim yapma
- Doldur ve giriş yap
- Her zaman otomatik doldur

seçenekleri kullanılabilir.

Gizli sekmelerde parola kaydetme ve otomatik doldurma özellikleri devre dışıdır.

---

## Gizlilik

Alpha Browser, geliştiriciye gezinme geçmişi gönderen yerleşik bir telemetri sistemi içermez.

Aşağıdaki veriler varsayılan olarak kullanıcının kendi bilgisayarında saklanır:

- Favoriler
- Geçmiş
- Notlar
- Çalışma alanları
- Profiller
- Tarayıcı ayarları
- İndirme geçmişi
- Parola kasası kayıtları

Şifre kasası kayıtları ana parola ile korunur ve şifrelenmiş olarak saklanır.

Ziyaret edilen internet siteleri, kullanıcının yüklediği eklentiler ve isteğe bağlı yapay zekâ hizmetleri kendi gizlilik politikaları kapsamında veri işleyebilir.

Alpha AI kullanıldığında kullanıcı tarafından gönderilen soru ve izin verilen sayfa içeriği Gemini API hizmetine iletilebilir.

---

## Alpha Shield

Alpha Shield, bilinen reklam ve takip sistemlerine ait bazı ağ isteklerini engellemeye yardımcı olur.

Alpha Shield:

- Reklam isteklerini engelleyebilir
- Bilinen takip alan adlarını engelleyebilir
- Engellenen istek sayısını gösterebilir
- Kullanıcı tarafından açılıp kapatılabilir

Alpha Shield tam kapsamlı bir güvenlik veya antivirüs sistemi değildir.

---

## Eklentiler

Alpha Browser, uyumlu unpacked Chromium eklentilerinin yüklenmesini destekler.

Eklenti yüklemek için seçilen klasörün içinde doğrudan şu dosyanın bulunması gerekir:

```text
manifest.json
```

Her Chromium veya Chrome eklentisinin Alpha Browser ile tam uyumlu çalışacağı garanti edilmez.

Yalnızca güvenilir geliştiricilerden alınan eklentilerin kurulması önerilir. Eklentiler, sahip oldukları izinlere bağlı olarak ziyaret edilen internet sitelerindeki verilere erişebilir.

---

## Güncellemeler

Alpha Browser’ın yeni sürümleri bu deponun **Releases** bölümünde yayınlanır.

Yeni sürüm yayınlandığında kurulum dosyasının adı şu biçimde olur:

```text
Alpha-Browser-Setup-x.x.x-x64.exe
```

Örnek sürüm geçişi:

```text
0.4.0 → 0.4.1 → 0.4.2 → 0.5.0
```

Yeni sürümü yüklemeden önce önemli tarayıcı verilerinizin yedeğini almanız önerilir.

---

## Güvenlik Uyarısı

Alpha Browser’ı yalnızca bu deponun resmi **Releases** bölümünden indirin.

Başka internet sitelerinden indirilen, değiştirilmiş veya yeniden paketlenmiş Alpha Browser kurulumlarının güvenliği garanti edilmez.

Uygulama henüz dijital kod imzalama sertifikasına sahip değilse Windows şu uyarıyı gösterebilir:

```text
Windows bilgisayarınızı korudu
Bilinmeyen yayıncı
```

Bu durumda kurulum dosyasını resmi IRC Technology GitHub deposundan indirdiğinizden emin olun.

---

## Hata Bildirimi

Bir hata bulduysanız GitHub üzerindeki **Issues** bölümünden bildirebilirsiniz.

Hata bildirirken mümkünse şu bilgileri ekleyin:

- Alpha Browser sürümü
- Windows sürümü
- Hatanın ekran görüntüsü
- Hatanın oluştuğu internet sitesi
- Hatayı oluşturmak için izlenen adımlar
- Görünen hata mesajı
- Sorunun sürekli mi yoksa aralıklı mı oluştuğu

---

## Özellik Önerileri

Yeni bir özellik önermek için GitHub üzerindeki **Issues** bölümünü kullanabilirsiniz.

Önerinizde özelliğin:

- Ne işe yarayacağını
- Kullanıcıya nasıl fayda sağlayacağını
- Arayüzde nerede bulunacağını
- Benzer uygulamalardaki örneklerini

belirtebilirsiniz.

---

## Geliştirici

**Developer:** Engin Şenaydın  
**Organization:** IRC Technology  
**Product:** Alpha Browser  
**Platform:** Windows x64  
**Technology:** Electron, React ve TypeScript  

---

## Resmî Depo

Bu depo Alpha Browser’ın resmî sürüm ve kurulum dosyalarını barındırır.

```text
github.com/IRC-Technology/alpha-browser
```

---

## Lisans ve Dağıtım

Alpha Browser uygulamasının, logosunun, tasarımının ve marka varlıklarının tüm hakları IRC Technology’ye aittir.

Aşağıdaki işlemlere izin verilmez:

- Kurulum dosyalarının izinsiz değiştirilmesi
- Uygulamanın farklı bir marka adıyla yayınlanması
- Değiştirilmiş kurulum paketlerinin dağıtılması
- Alpha Browser logosunun izinsiz ticari kullanımı
- Kurulum dosyasının zararlı yazılımlarla birlikte dağıtılması
- IRC Technology adına sahte sürüm yayınlanması

---

© 2026 IRC Technology. All rights reserved.
