# 🏋️ Antrenman Pro (Workout Tracker)

Sadece HTML, CSS ve Vanilla JavaScript kullanılarak geliştirilmiş; mobil uyumlu, hızlı ve tamamen cihazınızda (lokal) çalışan profesyonel bir antrenman takip uygulamasıdır. Popüler fitness uygulamalarının (Strong, Hevy vb.) en sevilen özelliklerini barındırır ve gereksiz karmaşadan uzak, "kullanıcı dostu" bir deneyim sunar.

🚀 **Canlı Demo:** [Uygulamayı Dene](https://batuhanhamza.github.io/workout-tracker)

## ✨ Öne Çıkan Özellikler

* **📱 Canlı Antrenman Modu:** Geçmiş antrenmandaki ağırlık ve tekrarlarınız otomatik olarak karşınıza gelir. Gelişimi takip etmek ve setleri işaretlemek saniyeler sürer.
* **⏱️ Akıllı Dinlenme Sayacı:** Seti tamamladığınızda otomatik başlar. Uygulamayı arka plana atsanız bile gerçek zamanlı çalışmaya devam eder ve süre dolduğunda titreşimle uyarır (Ayarlardan varsayılan süre değiştirilebilir).
* **🏆 PR (Kişisel Rekor) Sistemi:** Bir harekette geçmişteki maksimum ağırlığınızı veya sürenizi geçtiğiniz an sistem bunu algılar ve altın kupa (🏆) ile sizi motive eder.
* **⏸️ Antrenman Kurtarma (Pause/Resume):** Antrenman esnasında tarayıcıyı yanlışlıkla kapatsanız bile veriniz kaybolmaz. Geri döndüğünüzde kaldığınız yerden devam edebilirsiniz. İsterseniz antrenmanı "Beklet" butonuna basarak duraklatıp eve geçince sürdürebilirsiniz.
* **💬 Geçmişi Hatırlatan Not Sistemi:** Hareketlere o güne özel notlar (örn: "Sol omzum ağrıdı, hafif girdim") ekleyebilirsiniz. Bir sonraki hafta aynı hareketi yaparken sistem size geçen haftaki notunuzu hatırlatır.
* **📊 Akıllı İstatistikler & Grafikler:** Chart.js altyapısı ile toplam hacim (volume), kas grubu dağılımı ve hareket bazlı gelişim grafikleri. (Buçuklu kiloları destekler, grafikte karmaşa yaratmaz).
* **⚙️ Tamamen Özelleştirilebilir:** Kendi programınızı yazabilir, günleri ve hareketleri satır içi (inline) düzenleyebilirsiniz. Hareketleri `Ağırlık`, `Vücut Ağırlığı` veya `Süre` bazlı olarak kategorize edebilirsiniz.
* **🔒 %100 Gizlilik (Local Storage):** Verileriniz hiçbir sunucuya gönderilmez, sadece telefonunuzun/tarayıcınızın hafızasında tutulur. İstediğiniz zaman `.json` formatında yedeğini indirebilir ve başka bir cihaza yükleyebilirsiniz.

## 🛠️ Kurulum & Kullanım

Bu uygulama bir **PWA (Progressive Web App)** mantığıyla tasarlanmıştır. Herhangi bir indirme veya kurulum gerektirmez.

1. Telefonunuzun tarayıcısından (Safari veya Chrome)[uygulama linkine](https://batuhanhamza.github.io/workout-tracker) gidin.
2. **iOS/Safari:** Ekranın altındaki `Paylaş` butonuna basıp **"Ana Ekrana Ekle"** seçeneğini seçin.
3. **Android/Chrome:** Sağ üstteki üç noktaya basıp **"Ana Ekrana Ekle"** seçeneğini seçin.

Artık ana ekranınızdaki ikonuna tıklayarak uygulamayı tam ekran (URL çubuğu olmadan) gerçek bir mobil uygulama gibi kullanabilirsiniz!

## 💻 Teknoloji Yığını

* **HTML5:** Temel iskelet ve erişilebilirlik.
* **CSS3:** Modern, karanlık mod (Dark Mode) destekli, tamamen responsive (mobil odaklı) UI tasarımı. (Klavye açıldığında ekran kayması sorunları fixlenmiştir).
* **Vanilla JavaScript:** Hiçbir dış framework (React, Vue vb.) kullanılmadan yazılmış saf, hızlı ve optimize edilmiş DOM manipülasyonu.
* **Chart.js:** Veri görselleştirme ve istatistik grafikleri.
* **Local Storage API:** Veri tabanı gerektirmeyen cihaz içi depolama çözümü.

## 📄 Lisans ve Katkı

Bu proje açık kaynaklıdır ve kişisel kullanım/geliştirme amaçlıdır. Geliştirmek, çatallamak (fork) veya ilham almak serbesttir. Hata (bug) bulursanız veya özellik önermek isterseniz "Issues" kısmından belirtebilirsiniz.

---
*Geliştirici: [Batuhan Hamza]*
