# 🎬 MCU Watchlist — Marvel Sinematik Evreni İzleme Listesi

Marvel Sinematik Evreni'ndeki (MCU) **Faz 1'den Faz 6'ya (2008 – 2026)** kadar yayınlanan toplam **77 film, dizi, animasyon ve özel bölümü** hem **Çıkış (Vizyon)** hem de **Hikaye (Kronolojik)** sırasına göre takip etmeni sağlayan minimalist, karanlık mod (dark-mode) arayüzlü interaktif izleme listesi.

---

## ✨ Öne Çıkan Özellikler

* **📅 Çift İzleme Modu (Çıkış & Hikaye Sırası):** Tek tıkla *Vizyon/Yayın Sırası* (Faz 1–6) ile *Kronolojik Hikaye Zamanı* (6 Ana Dönem) arasında geçiş yapabilir; seçtiğin moda göre güncellenen **Sıradaki Yapım** önerisini takip edebilirsin.
* **🔗 Sihirli URL Senkronizasyonu (`#w=`):** Attığın her tik otomatik olarak sıkıştırılmış aralık formatında (ör. `#w=1-12,16,34`) sayfa adresine (URL) işlenir. Üyelik veya sunucu gerektirmeden **İlerleme Linkini Kopyala** butonuyla mevcut durumunu telefonuna aktarabilir ya da arkadaşlarınla paylaşabilirsin.
* **💾 Çift Katmanlı Otomatik Kayıt:** İşaretlerin hem URL hash parametresinde hem de tarayıcı hafızasında (`localStorage`) eşzamanlı saklanır.
* **📊 Canlı İlerleme & Kategori Sayaçları:** Genel tamamlanma yüzdesinin yanı sıra **Filmler (38)**, **Diziler (31)**, **Animasyon/Kısa (6)** ve **Özel Bölümler (2)** için ayrı ilerleme göstergeleri sunar.
* **🔍 Akıllı Filtreleme & JSON Yedekleme:** Tür, izlenme durumu, yıl veya sıra numarasına göre anlık arama yapabilir; ilerlemeni `.json` dosyası olarak dışa/içe aktarabilirsin.

---

## 🛠️ Nasıl Çalışır? (Sihirli Link Mantığı)

Uygulama tamamen istemci tarafında (client-side) çalışır ve harici bir veritabanına ihtiyaç duymaz:

1. İzlediğin yapımların ID numaraları ardışık aralıklar halinde sıkıştırılır (`[1, 2, 3, 16]` → `1-3,16`).
2. Bu veri tarayıcı geçmişini kirletmeden (`history.replaceState`) adres çubuğundaki `#w=...` parametresine yazılır.
3. Linki yer imlerine eklediğinde veya başka bir cihazda açtığında tüm işaretlerin otomatik olarak geri yüklenir.

---

## 🚀 Kurulum ve Kullanım

Proje harici bağımlılık içermeyen tek dosyalık (`index.html`) saf HTML, CSS ve Vanilla JavaScript ile geliştirilmiştir:

1. Repoyu klonlayın veya `index.html` dosyasını indirin.
2. Dosyayı tarayıcınızda açın ya da **GitHub Pages** üzerinden doğrudan yayınlayın.

---

## 📋 Kapsam Özeti

| Kategori | Adet | Kapsam |
| :--- | :---: | :--- |
| **Filmler** | 38 | *Iron Man (2008)* → *Spider-Man: Brand New Day (2026)* |
| **Diziler** | 31 | Disney+ Orijinal Yapımları & Defenders Evreni |
| **Animasyon / Kısa** | 6 | *What If...?*, *I Am Groot*, *Eyes of Wakanda*, *Marvel Zombies* |
| **Özel Bölümler** | 2 | *Werewolf by Night*, *The Guardians of the Galaxy Holiday Special* |


Proje tek dosyalık (`index.html`) saf HTML, CSS ve Vanilla JavaScript ile geliştirilmiştir. Herhangi bir kurulum gerektirmez:

1. Repoyu klonlayın veya indirin.
2. `index.html` dosyasını herhangi bir modern tarayıcıda açın.
3. *(İsteğe bağlı)* **GitHub Pages** üzerinden doğrudan canlı web uygulaması olarak yayınlayabilirsiniz.
