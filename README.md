# ynera-legal (arşiv · yönlendirme)

Ynera'nın gizlilik politikası, kullanım koşulları ve tanıtım sayfası **13 Ağustos 2026'da
taşındı**:

| Eski | Yeni |
| --- | --- |
| `harundogdu.github.io/ynera-legal/` | <https://harundogdu.dev/ynera> |
| `harundogdu.github.io/ynera-legal/privacy.html` | <https://harundogdu.dev/ynera/privacy> |
| `harundogdu.github.io/ynera-legal/terms.html` | <https://harundogdu.dev/ynera/terms> |

Yeni sayfalar dört dilde (Türkçe, İngilizce, Almanca, İspanyolca) ve kaynağı
`harundogdu/modern-portfolio` deposunda: `src/lib/ynera/legal.ts`.

## Bu depo neden duruyor

**Silinmemeli.** Mağazadaki eski Ynera sürümlerinin Ayarlar ekranı buradaki adreslere
gidiyor ve o sürümler güncellemeyen kullanıcıların telefonunda kalmaya devam ediyor.
Depoyu kaldırmak, güncellemeyen herkes için gizlilik politikasını erişilemez yapar.

Üç sayfa artık yalnız yönlendirme: `canonical` + `meta refresh`, artı yenilemeyi
izlemeyen bir denetçinin ya da tarayıcının okuyabilmesi için görünür bir bağlantı
(GitHub Pages 301 döndüremiyor).

## Metin neden taşınırken değişti

Kopyalanmadı, düzeltildi:

- Eski koşullar madde 2 "küre ... satın alınamaz" diyordu, oysa mağazada üç ayrı küre
  paketi satılıyor. Koşullar kataloğun tersini söylüyordu.
- Politika iOS-only dönemde yazılmıştı ("Apple'ın UserDefaults mekanizması", "yaş
  derecelendirmesi App Store üzerinden belirlenecektir"). Ynera Google Play'de de yayında.
- Uygulama içi satın alma politikada hiç geçmiyordu, oysa beş ürün satılıyor.
- Eski açılış sayfası "Yakında App Store'da" diyordu (oyun 30 Temmuz 2026'dan beri
  yayında) ve "Sonsuz, Zen, Zor, Günlük" diye dört mod sayıyordu (Zen kaldırıldı, altı
  serbest mod var).

## Kalan iş

App Store Connect ve Play Console'daki Privacy Policy / Support URL alanları hâlâ eski
adresi gösteriyor. Yönlendirme çalıştığı için acil değil, ama sıradaki sürümde yeni
adrese çevrilmeli.

---

© 2026 Ynera · Harun Doğdu
