# muhammedemincoskun.com

Muhammed Emin Coşkun'un kişisel portfolyo sitesi. Tek bir `index.html` dosyası; derleme adımı yok, GitHub Pages'te olduğu gibi çalışır.

## Klasörler

```
index.html        site (HTML, CSS ve JavaScript tek dosyada)
assets/emin.webp  fotoğraf
assets/mortis/    Mortis Loop fragmanı, oynanış döngüsü ve ekran görüntüleri
assets/firuze/    FIRUZE fragmanı, oynanış döngüsü ve ekran görüntüleri
CNAME             alan adı
```

## İçeriği düzenlemek

- **Oyunlar:** `index.html` içinde `GAMES` listesi (Türkçe) ve `GAMES_EN` (İngilizce).
- **Öne çıkan oyun:** Hangi oyunda `featured: true` yazıyorsa büyük alanda o görünür.
- **Sabit metinler:** Türkçesi HTML'in içinde, İngilizcesi `EN` sözlüğünde. İkisi `data-t` anahtarıyla eşleşir.

## Dil

Site ziyaretçinin tarayıcı diline göre açılır, sağ üstteki EN/TR düğmesiyle değişir. Belirli bir dille link vermek için:

- `https://muhammedemincoskun.com/?lang=en`
- `https://muhammedemincoskun.com/?lang=tr`

Bir projeyi doğrudan açmak için: `https://muhammedemincoskun.com/?lang=en#mortis-loop`
