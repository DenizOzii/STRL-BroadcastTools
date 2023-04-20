# STRL BroadcastTools (2. Sezon)

`BroadcastHelper` programımın STRL Rocket League Türkiye ligine uyarlanmış hali. `BroadcastHelper` programı, espor vb. rekabetçi etkinliklerde 2 takım veya oyuncunun skor, isim, logo vb. değerlerinin arayüze daha kolay gösterilmesini sağlayan, Python ile yazılmış bir programdır. Yakın zamanda diğer Rocket League müsabakaları ve diğer oyunlar için uygun arayüzlere uyarlamaya çalışacağım ^^

## DİKKAT EDİLMESİ GEREKENLER

- `BroadcastHelper.exe` programının **KESİNLİKLE** `teams.txt` metin dosyası ile `Team Logos` ve `Overlays` klasörleri ile aynı klasörde bulunması gerekiyor. Aksi takdirde program bu dosyalardan takım isimlerini, takım logolarını ve arayüzün çekimini yapamaz.

- Programda herhangi bir virüs yok, ancak imzalamaları vs. yapılmadığı için Microsoft Defender'ın programı virüs olarak görme ihtimali mevcut. Dilerseniz programı virustotal.com üzerinden sorgulayabilirsiniz.

- Bu program STRL Türk RL ligimiz için geçerlidir. Scripti (`BroadcastHelper.exe`) kendisine ait GitHub deposu açılana kadar kullanabilirsiniz, ancak Team `Team Logos` ve `Overlays` klasörlerinin içinde bulunan dosyaların hak sahibi **RLTR Turnuvaları** ekibidir. Bu dosyaların bütün hakları saklıdır.

## Hangi Dosya, Ne İşe Yarıyor?

- `teams.txt` metin dosyası içine takımların isimleri eklenir, her bir satıra bir takımın adı yazılır. Programın doğru çalışması için en alt satırı boş bırakmayı unutmayın.

- `Team Logos` klasörü içine takımların logoları (varsa) konulur. Takım logolarının isimleri, dosya formatı haricinde takım isimleri ile bire bir aynı olmalıdır. Aksi taktirde program varsayılan logoyu (`Team Logos\Default.png`) kullanır.

- `Overlays` klasörü içinde kullanılan arayüze ait görseller konur. Varsayılan olarak program arayüz için `Scoreboard-Bo1.png` dosyasını, skorlar için iki takımın skorları için de `null.png` dosyasını kullanır. 
- - Skorlar, belirtilen serideki maksimum skoru geçemez. Örneğin: Best of 5 skor arayüzünü açtıysanız bir takım için belirtebileceğiniz maksimum skor 3 olabilir. Program 4. skor ışığını açmanızı engelleyecektir.

- Bu depoda aynı zamanda OBS için kullanıma hazır sahne seti mevcuttur. Programın tüm kurulumu için bu videoyu izleyebilirsiniz:
