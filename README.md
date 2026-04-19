# Araba Trafik Oyunu

Bu proje düz (static) HTML/CSS/JS oyundur.

## Lokal çalıştırma

```bash
python3 -m http.server 8080
```

Sonra `http://localhost:8080` aç.

## Vercel deploy notları

- Proje `index.html` tabanlıdır.
- `vercel.json` içindeki rewrite ayarı, Vercel'de route kaynaklı `404 Not Found` sorununu engeller.

## GitHub'da sadece `.gitkeep` görünüyorsa

Yerel commit'ler remote'a gönderilmemiş olabilir:

```bash
git add .
git commit -m "Add game files"
git push origin <branch-adi>
```

GitHub üzerinde doğru branch'i açtığından emin ol.
