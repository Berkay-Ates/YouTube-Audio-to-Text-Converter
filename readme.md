# YouTube Video Sesinden Metin Çıkarma Projesi

Bu proje, kullanıcıların bir YouTube video URL'si girdiğinde, o videodaki sesin metin halini çıkarmak için tasarlanmıştır. Projede, YouTube API'si ve ses tanıma (speech-to-text) teknikleri kullanılmıştır.

## Nasıl Kullanılır

### Gereksinimler
- Python 3.x
- İnternet bağlantısı
- YouTube API erişim anahtarı ([YouTube Developer Console](https://developers.google.com/youtube/registering_an_application) üzerinden alınabilir)

### Proje Kurulumu
1. Proje dosyalarını bilgisayarınıza indirin veya klonlayın.
2. Gerekli Python paketlerini yüklemek için terminal veya komut istemcisinde şu komutu çalıştırın:
   ```
   pip install -r requirements.txt
   ```

### YouTube API Anahtarı
- YouTube API erişim anahtarınızı `config.py` dosyasında `YOUTUBE_API_KEY` değişkenine atayın.

### Kullanım
1. Terminal veya komut istemcisinde şu komutu çalıştırarak programı başlatın:
   ```
   python main.py
   ```
2. Program başladığında, bir YouTube video URL'si istenecektir. URL'yi girin ve Enter tuşuna basın.
3. Program, videodaki sesi alacak ve metin haline dönüştürecektir.
4. Sonuç, terminal veya komut istemcisinde görüntülenecektir.

## Örnekler

### Örnek Kullanım
```
$ python main.py

YouTube Video URL'sini girin: https://www.youtube.com/watch?v=dQw4w9WgXcQ

Metin çıkarma işlemi başladı...

Metin:
"Never gonna give you up, never gonna let you down, never gonna run around and desert you..."
```

## Katkıda Bulunma

- Bu projeyi geliştirmek için önerileriniz varsa veya hata raporları ile karşılaşırsanız, lütfen GitHub'da bir konu açın veya bir istek gönderin.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasını inceleyin.
