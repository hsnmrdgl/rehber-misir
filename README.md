# Mısır Cep Rehberi

Tek dosyalık (`index.html`) bir gezi rehberi. Derleme veya sunucu gerekmez.

## GitHub Pages'e yükleme
1. GitHub'da yeni bir depo aç (örn. `misir-rehber`).
2. `index.html` ve `README.md` dosyalarını depoya yükle.
3. **Settings > Pages** bölümünde Source olarak `Deploy from a branch`, branch olarak `main`, klasör olarak `/ (root)` seç ve kaydet.
4. Birkaç dakika sonra `https://KULLANICIADIN.github.io/misir-rehber/` adresinde yayında olur.

Sayfa `#` tabanlı bağlantı kullandığı için ekstra ayar gerekmez.

## Fotoğraflar
Fotoğraflar indirilmez. Sayfa açıldığında her konunun fotoğrafı Wikipedia'dan (Wikimedia Commons) çevrimiçi olarak çekilir ve altında kaynak bağlantısı gösterilir. İnternet yoksa ya da fotoğraf bulunamazsa o kısım sessizce gizlenir. Bu özellik yalnızca kendi alan adında (GitHub Pages) çalışır.

Hangi konu hangi Wikipedia sayfasından fotoğraf alır, `index.html` içindeki `WT` listesinde yazar; istersen oradan değiştirebilirsin.

## Kur hesaplama
Sayfanın altındaki hesaplayıcı EGP/USD/EUR kurlarını ücretsiz bir döviz API'sinden çeker. İnternet yoksa son çekilen kuru gösterir. Kurlar piyasa kurudur; döviz bürosu kuru farklı olabilir.
