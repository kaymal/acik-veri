# Katkı Sağlama Rehberi

Bu projeye katkı sağlamak istediğiniz için teşekkür ederiz! Türkiye'deki açık veri kaynaklarını listelemek için topluluk desteğine ihtiyacımız var.

## Nasıl Katkı Sağlayabilirim?

### 1. Proje Repository'sini Fork Edin

- Ana repository adresine gidin: <https://github.com/kaymal/acik-veri>
- Sayfanın sağ üst köşesindeki "Fork" butonuna tıklayın
- Kendi GitHub hesabınıza bir kopyasını oluşturun

### 2. Değişikliklerinizi Yapın

- Forkladığınız repository'yi bilgisayarınıza klonlayın
- Yeni bir branch oluşturun: `git checkout -b yeni-veri-kaynagi`
- Değişikliklerinizi yapın (detaylar aşağıda)

### 3. Pull Request Açın

- Değişikliklerinizi commit edin ve push yapın
- GitHub'da ana repository'ye Pull Request açın
- Açıklamada hangi veri kaynağını eklediğinizi belirtin

## Düzenleme Kuralları

### Alfabetik Sıralama

**ÖNEMLİ**: Yeni veri kaynakları eklerken veya mevcut kaynakları düzenlerken, lütfen alfabetik sıralamayı koruyun.

#### Sıralama Kuralları

- **Kurum/Organizasyon adına göre** alfabetik sıralama yapın
- Türkçe karakterler dikkate alınarak sıralama yapın (ç, ğ, ı, ö, ş, ü)
- "The", "A", "An" gibi belirli tanımlık artikelleri göz ardı edin

#### Örnek

```markdown
- [Ankara Büyükşehir Belediyesi Açık Veri Portalı](...)
- [Balıkesir Büyükşehir Belediyesi Açık Veri Platformu](...)
- [Bursa Büyükşehir Belediyesi Açık Veri Platformu](...)
```

### Link Formatı

Tüm linkler aşağıdaki formatı takip etmelidir:

```markdown
- [Kurum/Organizasyon Adı - Açıklama](https://link-url.com)
```

### Alt Kategoriler

Bir kurum/organizasyonun alt birimleri varsa girintili liste kullanın:

```markdown
- [Ana Kurum](https://ana-kurum.com)
  - [Alt Birim 1](https://alt-birim1.com)
  - [Alt Birim 2](https://alt-birim2.com)
```

### Şehir ve İlçe Verileri

**Önemli**: Bir şehirin hem büyükşehir belediyesinin hem de ilçe belediyelerinin açık veri kaynakları varsa, önce şehrin ana kaynağını, sonra alt kırılım olarak ilçe verilerini ekleyin. Yoksa şehir adını başlık olarak yazıp ilçeleri altında listeleyin.

#### Örnek Düzenleme

```markdown
- [İstanbul Büyükşehir Belediyesi Açık Veri Portalı](https://data.ibb.gov.tr/)

  - [Beyoğlu Belediyesi Açık Veri Setleri](https://acikveri.beyoglu.bel.tr/)
  - [Kadıköy Belediyesi Açık Veri Portalı](https://acikveri.kadikoy.bel.tr/)
  - [Küçükçekmece Belediyesi Açık Veri Platformu](https://acikveri.kucukcekmece.bel.tr)

- Mersin Büyükşehir Belediyesi
  - [Mersin Yenişehir Belediyesi Açık Veri Portalı](https://acikveri.yenisehir.bel.tr/)
```

#### Kurallar

- İlçe belediyesi verileri ana şehrin altında girintili olarak yazılmalı
- İlçe belediyeleri kendi aralarında alfabetik sırayla sıralanmalı
- Eğer ana şehir belediyesinin açık veri portalı yoksa, şehir adını başlık olarak yazıp ilçeleri altında listeleyin

### Kategoriler

Yeni veri kaynakları eklerken uygun kategoriye yerleştirin:

- **Resmi Kurumlar**: Devlet kurumları ve kamu kuruluşları
- **Belediyeler ve Şehirler**: Yerel yönetimler
- **Üniversiteler**: Akademik kurumlar
- **Uluslararası Kurumlar**: Dünya Bankası, AB, BM vb.
- **COVID**: COVID-19 ile ilgili veri kaynakları
- **Piyasalar**: Finansal ve borsa verileri
- **Türkçe Doğal Dil İşleme (NLP)**: Dil ve metin verileri
- **API'ler**: Programatik erişim sağlayan kaynaklar
- **Diğer**: Yukarıdaki kategorilere uymayan kaynaklar

### Kalite Kontrol

Eklediğiniz veri kaynakları:

- **Aktif** olmalı (erişilebilir linkler)
- **Açık veri** sunmalı (ücretsiz ve kamuya açık)
- **Türkiye** ile ilgili olmalı
- **Güvenilir** kaynaklardan olmalı

## Geliştirme Ortamı

### VS Code Ayarları

Projeyi VS Code ile geliştiriyorsanız, repository'de bulunan `.vscode` klasöründeki ayarları kullanın. Bu ayarlar:

- Markdown linting kurallarını uygular
- Tutarlı formatlamayı sağlar
- Türkçe karakter desteğini optimize eder

### Markdown Linting

Markdown dosyalarını düzenlerken lütfen aşağıdaki kurallara uyun:

- Başlık seviyelerini doğru kullanın
- Linkler kırık olmamalı
- Boş satırları tutarlı kullanın
- İndentasyon için 2 boşluk kullanın

## Yardım

Herhangi bir sorunuz varsa:

- Issue açabilirsiniz
- Mevcut tartışmalara katılabilirsiniz
- Ana repository'deki README.md dosyasını inceleyebilirsiniz

Katkılarınız için teşekkürler! 🙏
