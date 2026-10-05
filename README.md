# Kurgu Canavarı — MP4 sürümü

GitHub Pages üzerinde çalışan, dosyaları cihazda işleyen PWA.

## MP4
- Önce Canvas + ses ile WebM ara çıktısı oluşturulur.
- Seçim MP4 ise FFmpeg.wasm ile H.264 video + AAC ses içeren gerçek `.mp4` dosyasına dönüştürülür.
- MP4 motoru ilk dışa aktarmada CDN üzerinden yüklenir; bu nedenle ilk MP4 işleminde internet gerekir.
- Görsel/video, SRT, altyazı stilleri, hareket, fade, efekt, çözünürlük ve FPS korunur.

## GitHub Pages
Dosyaların tamamını repo köküne yükleyip Settings → Pages → Deploy from branch → main → /(root) seç.
