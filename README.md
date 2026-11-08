# O2 — Kuru Ortam Nefes Tutma Günlüğü

O2, serbest dalış hazırlığı kapsamında **kuru ortamda ve yalnızca uyanıkken tamamlanmış** nefes tutma kayıtlarını sonradan arşivlemek için hazırlanmış statik bir web uygulamasıdır.

## Özellikler

- Nefes aldıktan ve nefes verdikten sonraki tamamlanmış ölçümleri ayrı kaydetme
- Kuru ortam kayıtları için ayrı kişisel istatistik ve gelişim grafiği
- Nefes alma dürtüsünü yalnızca öznel bir not olarak kaydetme (CO₂ ölçümü değildir)
- Ortam, seans değerlendirmesi ve not geçmişi
- Kuru ortam güvenlik hatırlatmaları ve freediving eğitim bilgileri
- Kayıtlar tarayıcının `localStorage` alanında tutulur; sunucuya gönderilmez.
- Önceki kayıtlar korunur; eski kayıtlar kuru ortam olarak sınıflandırılmaz.

## Güvenlik

Kuru ortamda nefes tutma da hipoksik bayılma, düşme ve yaralanma riski taşır. Uyurken, uykuya dalarken, yatakta uyku sırasında, ayakta, araç kullanırken, banyoda veya suda tek başına nefes tutma denemesi yapılmamalıdır. Maksimum süre denemeleri, süre hedefleri, CO₂ tabloları veya hiperventilasyon kullanılmamalıdır. Baş dönmesi, görme değişikliği, uyuşma veya sersemlikte hemen bırakıp yardım isteyin. Kuru ortam çalışmaları için de nitelikli freediving eğitmeninden kişisel güvenlik değerlendirmesi alın. Su içi çalışmalar uygun eğitim ve yetkin buddy gözetimi gerektirir.

Uygulama bir nefes tutma zamanlayıcısı, antrenman reçetesi, CO₂ ölçüm cihazı veya tıbbi cihaz değildir. Nefes alma dürtüsü alanı yalnızca sonradan girilen öznel bir nottur.

## Yayın

GitHub Pages için statik HTML olarak hazırlanmıştır. `main` dalındaki `index.html` yayınlanır. Özel alan adı `CNAME` dosyasında tanımlıdır.
