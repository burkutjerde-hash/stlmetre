# 📐 STLmetre — 3D STL Ölçüm ve Geometrik Analiz Platformu

STLmetre, 3D baskı (3D Print) ve CAD kullanıcıları için geliştirilmiş; kurulum, üyelik veya sunucu gerektirmeyen, tamamen tarayıcı üzerinde çalışan modern bir 3D STL ölçüm aracıdır.

---

## ✨ Özellikler

- **Tablaya Sıfırlama (Bed Alignment):** Yüklenen parçaların en alt tabanını doğrudan 3D baskı tablasına ($Y = 0$) oturtur.
- **A-B Noktası Mesafe Ölçümü:** Model üzerindeki iki nokta arasındaki net mesafeyi milimetre (mm) ve santimetre (cm) cinsinden $\Delta X, \Delta Y, \Delta Z$ kırılımlarıyla hesaplar.
- **3 Noktalı Daire & Çap Tespiti (Circle Fit):** Dairesel kenar veya delik üzerinde seçilen 3 nokta ile Çap (Ø), Yarıçap (R) ve merkez koordinatlarını anında bulur.
- **Yükseklik Kesit Analizörü (Cross-Section):** Modeli tabladan itibaren istenilen yükseklikte yatay dilimleyerek iç çap (ID), dış çap (OD) ve et kalınlığını otomatik analiz eder.
- **Köşe Yakalama (Magnet Snapping):** Üçgen köşelerine (vertex) yapışarak hassas CAD ölçümü sağlar.
- **Rapor Dışa Aktarma:** Yapılan tüm ölçümleri tek tıkla `.txt` raporu olarak bilgisayarınıza kaydeder.
- **Gizlilik Odaklı:** Dosyalarınız hiçbir sunucuya yüklenmez, tüm işlemler bilgisayarınızın tarayıcısında (Three.js WebGL) işlenir.

---

## 🚀 Hızlı Başlangıç

Bu proje tek bir `index.html` dosyasından oluşur.

1. Depoyu klonlayın veya `index.html` dosyasını indirin.
2. `index.html` dosyasını Chrome, Edge, Safari veya Firefox gibi herhangi bir modern web tarayıcısında çift tıklayarak açın.
3. STL dosyanızı ekranın ortasına sürükleyip bırakın veya demo parça ile hemen ölçüm yapmaya başlayın!

---

## 🛠️ Kullanılan Teknolojiler

- [Three.js](https://threejs.org/) (WebGL 3D Render & Geometri Motoru)
- [Tailwind CSS](https://tailwindcss.com/) (Kullanıcı Arayüzü Tasarımı)
- [FontAwesome](https://fontawesome.com/) (İkon Seti)

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) altında açık kaynak olarak paylaşılmıştır.
