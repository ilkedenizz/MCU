# 🎬 MCU & Multiverse Watchlist — 105 Yapımlık Tam Marvel İzleme Listesi

Marvel Sinematik Evreni (Earth-616) ile birlikte **Spider-Man (Raimi & Webb)**, **Sony Örümcek Evreni (SSU & Spider-Verse)**, **Fox X-Men / Wolverine / Deadpool** ve **Klasik Marvel** yapımlarını kapsayan toplam **105 film, dizi, animasyon ve özel bölümü** hem **Çıkış (Vizyon)** hem de **Hikaye (Kronolojik)** sırasına göre takip etmeni sağlayan minimalist, karanlık mod (dark-mode) arayüzlü interaktif izleme listesi.

---

## ✨ Öne Çıkan Özellikler

* **🌐 105 Yapımlık Tam Evren Arşivi:** Ana MCU Faz 1–6 (77 yapım) + Çoklu Evren genişletme paketi (28 yapım) tek listede birleştirildi.
* **📅 Çift İzleme Modu (Çıkış & Hikaye Sırası):**
  * **Çıkış Sırası:** Yapımları vizyon ve yayın tarihlerine göre fazlara ayrılmış şekilde listeler.
  * **Hikaye Sırası:** Paralel evren yapımlarını (*Tobey & Andrew Spider-Man*, *Venom*, *X-Men*, *Logan*, *Deadpool*) doğrudan bağlandıkları ana MCU filmlerinin (*No Way Home* ve *Deadpool & Wolverine*) öncesine kronolojik olarak yerleştirir.
* **🔗 Sihirli URL Senkronizasyonu (`#w=`):** Attığın her tik otomatik olarak sıkıştırılmış aralık formatında (ör. `#w=1-12,78-82`) adres çubuğuna işlenir. Üyelik veya sunucu gerektirmeden **İlerleme Linkini Kopyala** butonuyla mevcut durumunu telefonuna aktarabilir ya da arkadaşlarınla paylaşabilirsin.
* **💾 Çift Katmanlı Otomatik Kayıt:** İşaretlerin hem URL hash parametresinde hem de tarayıcı hafızasında (`localStorage`) eşzamanlı saklanır; geçmiş `#w=` linkleriyle geriye dönük uyumludur.
* **📊 Canlı İlerleme & Kategori Sayaçları:** Genel tamamlanma yüzdesinin yanı sıra **MCU Filmleri (38)**, **Diziler (31)**, **Multiverse (28)**, **Animasyon/Kısa (6)** ve **Özel Bölümler (2)** için ayrı ilerleme sayaçları sunar.
* **🔍 Akıllı Filtreleme & JSON Yedekleme:** Evren, tür, izlenme durumu, yıl veya sıra numarasına göre anlık arama yapabilir; ilerlemeni `.json` dosyası olarak dışa/içe aktarabilirsin.

---

## 📋 Kapsam Özeti (105 Yapım)

| Kategori | Adet | Kapsam |
| :--- | :---: | :--- |
| **Ana MCU Filmleri** | 38 | *Iron Man (2008)* → *Spider-Man: Brand New Day (2026)* |
| **Diziler** | 31 | Disney+ Orijinal Yapımları & Defenders Evreni (*Daredevil, Punisher* vb.) |
| **Multiverse Filmleri** | 28 | Raimi & Webb *Spider-Man*, *Venom*, *Spider-Verse*, Fox *X-Men*, *Logan*, *Deadpool*, *Blade* |
| **Animasyon / Kısa** | 6 | *What If...?*, *I Am Groot*, *Your Friendly Neighborhood Spider-Man*, *Eyes of Wakanda*, *Marvel Zombies* |
| **Özel Bölümler** | 2 | *Werewolf by Night*, *The Guardians of the Galaxy Holiday Special* |

---

## 🛠️ Nasıl Çalışır?

Uygulama harici veritabanı veya sunucu gerektirmeden tamamen istemci tarafında (client-side) çalışır:

1. İzlediğin yapımların ID numaraları ardışık aralıklar halinde sıkıştırılır (`[1, 2, 3, 78, 79]` → `1-3,78-79`).
2. Bu kod tarayıcı geçmişini kirletmeden (`history.replaceState`) sayfa adresindeki `#w=...` parametresine yazılır.
3. Linki favorilerine eklediğinde veya başka bir cihazda açtığında tüm işaretlerin otomatik olarak geri yüklenir.

---

## 🚀 Kurulum ve Kullanım

Proje tek dosyalık (`index.html`) saf HTML, CSS ve Vanilla JavaScript ile geliştirilmiştir:

1. Repoyu klonlayın veya `index.html` dosyasını indirin.
2. Dosyayı tarayıcınızda açın ya da **GitHub Pages** üzerinden doğrudan yayınlayın.
