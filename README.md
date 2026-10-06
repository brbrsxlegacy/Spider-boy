# Spider-Man · Şehir Devriyesi

BRBRS Games için hazırlanmış Türkçe, birinci şahıs 3D tarayıcı fan oyunu.

## Oynama

ZIP'i çıkarıp `dist/index.html` dosyasını güncel Chrome veya Edge ile aç. Dosyalar aynı klasörde kalmalı. İnternet ve ücretli API gerekmez.

Alternatif olarak proje klasöründe `python -m http.server 8080` çalıştır ve `http://localhost:8080/dist/` adresini aç.

## İçerik

- Gün batımında 320 binalı şehir; çatılar, park, sahil, yollar, ağaçlar, trafik ve sokak lambaları.
- Birinci şahıs el animasyonları, gerçek bina yüzeylerine tutunan ağ ve momentumla sallanma.
- Ağla kendini çekme, duvara tırmanma, zıplama ve kaçınma.
- Ağla düşman sarma ve yakın dövüş; nişancılar, çete üyeleri ve zırhlı lider.
- 4 görev ve toplam 18 düşman; görevlerden sonra serbest devriye.
- Radar, can/ağ yenilenmesi, kombo, ses efektleri, duraklatma ve yeniden başlatma.
- Telefon için sol hareket çubuğu, sağ tarafta kaydırarak bakış ve dokunmatik eylem tuşları.

## PC kontrolleri

| Tuş | Eylem |
| --- | --- |
| WASD | Hareket |
| Fare | Bakış |
| Shift | Koş |
| Sağ tık veya E basılı | Ağla sallan; bıraktığında momentum korunur |
| R | Baktığın binaya ağla çekil |
| Sol tık | Ağ at; sıradan düşmanda 3 isabet sarar |
| F | Yakındaki düşmana yumruk at |
| Space | Zıpla; duvar yanında basılı tutarak tırman |
| Q | Yana kaçın |
| Esc / P | Duraklat |

Mavi nişangâh bir bina bağlantısını, kırmızı nişangâh bir düşman hedefini gösterir. Yüksekten düşmek can götürmez. Can, hasar almadan 5 saniye sonra; ağ, sallanmadığında yenilenir.

## Doğrulama

JavaScript sözdizimi ve yerel dosya referansları kontrol edildi. Gerçek Three.js sahnesiyle çalışan başsız mantık kontrolünde çatıya iniş, zıplama, duvar çarpışması, ağın tutunması ve bırakılması, dört görevin gerçek saldırı eylemleriyle tamamlanması ve toplam 18 düşmanın yenilmesi doğrulandı. WebGL görüntüsü ve telefon/masaüstü performansı fiziksel cihazda henüz doğrulanmadı.

## Sınırlar

Bu bir oynanabilir ilk sürümdür; ticari AAA üretim değildir. Şehir ve karakterler prosedürel 3D modellerdir. Çok oyunculu ve kayıt sistemi yoktur. Dokunmatik kullanımda yatay ekran daha uygundur. WebGL 2 ve donanım hızlandırması gerekir.

## Lisans

Three.js 0.180.0 MIT lisansıyla birlikte gelir; `dist/THREE-LICENSE.txt` dosyasına bak. Spider-Man ilgili hak sahiplerine aittir. Bu proje hayran yapımıdır, resmi Marvel/Insomniac ürünü değildir.
