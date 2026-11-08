# O2 — Freediving Training

O2, serbest dalış yapanların tamamlanmış antrenman ölçümlerini, dalış hazırlığını ve kişisel kayıt geçmişini takip etmeleri için hazırlanmış statik bir web uygulamasıdır.

## Özellikler

- Nefes aldıktan sonra tutma ve nefes verdikten sonra tutma ölçümlerini ayrı kaydetme
- Kişisel kayıt özeti ve iki ölçüm türü için ayrı en iyi sonuç
- Son ölçümlerin gelişim grafiği ve seans geçmişi
- Dalış öncesi güvenlik kontrol listesi
- Freediving eğitimi, fizyoloji ve güvenlik bilgilendirmeleri
- Kayıtlar tarayıcının `localStorage` alanında tutulur; sunucuya gönderilmez.
- Önceki kayıtlar yeni kayıt formatına taşınarak korunur.

## Güvenlik

O2 bir nefes tutma zamanlayıcısı, antrenman reçetesi, meydan okuma veya tıbbi cihaz değildir. Ölçüm alanları yalnızca tamamlanmış seansların sonuçlarını sonradan kaydetmek içindir; uygulama süre hedefi, nefes protokolü veya otomatik seans başlatma sunmaz.

Nefes tutma; hipoksik bayılma ve boğulma riski taşır. Suda asla tek başına çalışılmamalı; su içi faaliyetler uygun eğitim, yetkin buddy/gözetmen ve kabul görmüş güvenlik prosedürleriyle yapılmalıdır. Hiperventilasyon yapılmamalı, hiçbir performans hedefi güvenliğin önüne geçmemelidir. Yetkin bir freediving eğitmeninden uygulamalı eğitim alın.

## Yayın

GitHub Pages için statik HTML olarak hazırlanmıştır. `main` dalındaki `index.html` yayınlanır. Özel alan adı `CNAME` dosyasında tanımlıdır.
