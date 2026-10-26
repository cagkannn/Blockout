# Block Out — Level 88

Windows bilgisayarda kurulum gerektirmeden açılabilen ilk deneme sürümü.

## iPhone ve telefonda oynama

Safari'den açılabilmesi için GitHub Pages üzerinden yayınlanmaya hazır web sürümü `docs/` klasöründedir.

Depo sahibi için bir kez yapılacak ayar:

1. [GitHub Pages ayarlarını aç](https://github.com/cagkannn/Blockout/settings/pages).
2. **Build and deployment** altında **Source** seçeneğini **Deploy from a branch** yap.
3. **Branch** bölümünde **main**, klasör olarak **/docs** seç ve **Save** düğmesine bas.
4. GitHub'ın sayfayı hazırlaması genellikle birkaç dakika sürer. Ayarlarda görünen **Visit site** düğmesiyle oyunu aç.
5. Açılan web adresini iPhone'da Safari'ye yapıştır. **Bölümü başlat** düğmesine bas ve blokları parmağınla sürükle.

İstersen Safari'de **Paylaş** → **Ana Ekrana Ekle** ile oyun için bir simge oluşturabilirsin. Bu sürüm için App Store kurulumu gerekmez. Web sayfasının ilk açılışında internet bağlantısı gerekir.

**Durum:** GitHub Pages yayını etkindir. iPhone’da dokunma kesildiğinde seçimin takılı kalmasına karşı düzeltme eklendi. En güncel sürümü açmak için Safari’de oyun sayfasını yeniden aç.

## Oyunu indir ve aç

1. **[Oyunu ZIP olarak indir](https://github.com/cagkannn/Blockout/archive/refs/heads/main.zip)** bağlantısına tıkla.
2. Bilgisayarındaki **İndirilenler** klasörünü aç.
3. **Blockout-main.zip** dosyasına sağ tıkla → **Tümünü ayıkla** → **Ayıkla** seç.
4. Açılan klasörün içinde **Block-Out-Oyna.html** dosyasına çift tıkla. Windows dosya uzantılarını gizliyorsa adı yalnızca **Block-Out-Oyna** olarak görünebilir.
5. Oyun ekranındaki **Bölümü başlat** düğmesine bas.

Dosya Edge veya Chrome tarayıcısında açılır. Yazı düzenleyicide açılırsa dosyaya sağ tıkla → **Birlikte aç** → **Microsoft Edge** veya **Google Chrome** seç.

## Nasıl oynanır?

- Bir bloğun üzerinde farenin sol tuşunu basılı tutarak sürükle.
- Dış rengini, aynı renkteki açık kapıya taşı. Bütün şeklin çıkış yolu boş olmalıdır.
- Çift renkli bloklarda önce dış katman çıkar, iç katman tahtada kalır.
- Her çıkan renk, kilitli kapıların sayacını bir azaltır.
- Üreticiler, çıkacak parçanın alanı boşalınca yeni blok üretir.
- Süre 3 dakikadır; duraklatma ve yardım ekranında süre durur.
- Alt sıradaki dönen ok yeniden başlatır; iki dikey çizgi duraklatır; hoparlör sesi açar/kapatır.

## Bu sürüm hakkında

Bu, Level 88 üzerine bir eğitim ve tasarım çalışmasının ilk deneme sürümüdür. Görseller özgün olarak oluşturulmuştur. Oyunun tamamlanmış veya referansla birebir doğrulanmış bir kopyası değildir. İlk 8 renk katmanının temizlenmesi test edilmiştir; tüm bölümün çözülebilirliği henüz doğrulanmamıştır.

Oyunu açmak için kod yazmak, ek bir program kurmak veya internet bağlantısını açık tutmak gerekmez.
