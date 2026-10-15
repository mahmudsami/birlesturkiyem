# Birleş Türkiyem

81 ili kutuya doldur, komşu iller birleşsin, bölgeler oluşsun ve sonunda Türkiye tamamlansın.

Oyna: https://mahmudsami.github.io/birlesturkiyem/

## Orijinalden farkları

Fikir ve temel mekanik DopaGameLab'in "都道府県ゲーム" (https://sns.dopagamelab.com/pref-pack/) oyunundan uyarlanmıştır. Bu sürümde değişenler:

- **Harita:** 47 prefektörlük yerine 81 il ve 7 coğrafi bölge. İstanbul ve Çanakkale iki yakasıyla tek şekil.
- **Tamamen rastgele sıra:** İller komşuluğa göre değil, her turda rastgele sırayla gelir.
- **Kutu:** Yatay (400×300). Birleşen parçalar küçülmez, kutuya sığmıyorsa dönerek yerleşir.
- **Denge kuralı:** Bir parça, kendisinin yarısından küçük bir parçayla birleşemez. İstisnalar: küçüğü tamamen saran büyük parça ve tüm komşuları birleşemeyeceği kadar büyük gruplarda kalan iller.
- **Birleşme:** Komşu iki parça, herhangi bir yerinden değince birleşir (sadece komşu illerin değdiği yerde değil).
- **Taşma:** Kırmızı çizgi gerçek sınırdır. Yerleşmiş bir parça çizginin üstünde 1,5 sn kalırsa oyun biter. Yeni birleşen parça 2,5 sn korumalıdır.
- **Süre:** 81 il kutuya girince Türkiye'yi tamamlamak için 30 sn.
- **Diğer:** Türkçe arayüz, paylaşım butonu yok.

## Kaynaklar

- İl sınırları: Natural Earth 1:10m admin-1 (kamu malı).
- Fizik: matter-js (MIT), poly-decomp (MIT) — `index.html` içinde gömülü.
