# Zeyneb & Veysel Düğün Davetiyesi

Zeyneb ve Veysel'in düğünü için hazırlanmış, mobil öncelikli dijital davetiye
sitesidir.

Canlı adres: https://davetiye.veyselbayramoglu.com.tr/

## Etkinlik

- Düğün: 30 Ağustos 2026 Pazar, 12.00
- Düğün için canlı geri sayım
- Google Maps yol tarifi
- Davetlilerin fotoğraf yükleyebileceği anı paylaşım ekranı

30 Ağustos 2026 saat 12.14'ten itibaren düğün programı sayfasının yerini
teşekkür sayfası alır. Fotoğraf paylaşım bölümü kullanılmaya devam eder.

## Özellikler

- Mühür dokunuşuyla açılan çift kanatlı kapak animasyonu
- Davetiye açıldıktan sonra başlayan arka plan müziği
- Kullanıcının müzik tercihini tarayıcıda saklama
- Sayfaya geri dönüldüğünde, kullanıcı kapatmadıysa müziği sürdürme
- Ekran ekran ilerleyen mobil uyumlu içerik
- İlk ziyarette kaydırma ipuçları
- Sosyal medya paylaşım önizlemesi
- Hareket azaltma tercihi için erişilebilirlik desteği

## Dosya yapısı

- `index.html`: Sayfa içeriği, düğün bilgileri ve dış bağlantılar
- `style.css`: Görsel tasarım, mobil uyumluluk ve animasyonlar
- `script.js`: Açılış, müzik, geri sayım, tarih sonrası görünüm ve geçişler
- `assets/`: Kapak, arka plan, mühür, önizleme görselleri ve müzik
- `CNAME`: GitHub Pages özel alan adı

## Yerel çalıştırma

Proje bağımlılık veya derleme adımı gerektirmeyen statik bir sitedir. Yerel bir
HTTP sunucusuyla proje dizinini yayınlayıp tarayıcıdan açmak yeterlidir.

Değişikliklerden sonra özellikle şu akışlar kontrol edilmelidir:

- Kapak ve mühür animasyonu
- Mobil kaydırma ve sayfa hizalama
- Müzik başlatma, durdurma ve sayfaya dönüş davranışı
- Düğün geri sayımı
- Konum ve fotoğraf yükleme bağlantıları
- Küçük ekranlarda program, teşekkür ve fotoğraf sayfaları

## Güncelleme noktaları

- Düğün tarihi ve geri sayım: `index.html` ve `script.js`
- Etkinlik sonrası geçiş zamanı: `script.js` içindeki `postEventDate`
- Konum ve fotoğraf yükleme bağlantıları: `index.html`
- Sosyal medya önizleme görseli: `index.html` ve `assets/preview.jpg`
- Arka plan müziği: `assets/zv.mp3`

## Yayınlama

Site `main` dalından GitHub Pages ile yayınlanır. `CNAME` dosyası özel alan adı
ayarını korur. Yayına gönderilmeden önce çalışma ağacının ve değişikliklerin
kontrol edilmesi önerilir.
