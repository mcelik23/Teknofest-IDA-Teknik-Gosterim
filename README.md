# Teknofest Autonomous Marine Vehicle (IDA) - Technical Showcase

Bu depo, Teknofest İnsansız Deniz Aracı (İDA) yarışması kapsamında geliştirilen otonom seyrüsefer sisteminin simülasyon testlerini ve operasyonel performans kayıtlarını içermektedir.

Not: Yarışma kuralları ve stratejik gizlilik prensipleri gereği, yazılım mimarisi detayları ve kaynak kodlar bu alanda paylaşılmamaktadır. Sistemin görev icra yetkinliği, aşağıdaki simülasyon kayıtları ve depo içerisindeki media/ dizini ile belgelenmiştir.

---

## Simülasyon Testleri

Gazebo ve RViz ortamlarında kurgulanan simülasyonlar, gerçek dünya koşullarına geçmeden önce sistemin uç senaryolardaki karar mekanizmalarını ve sensör verisi doğrulama süreçlerini kapsamaktadır.

<div align="center">
  <video src="https://github.com/mcelik23/Teknofest_IDA_Media/raw/main/media/simulation/2026_Hibrit.mp4" width="800" controls>
    Tarayıcınız video etiketini desteklemiyor.
  </video>
  <p><i>Simülasyon Testi: Sensör Füzyonu ve Otonom Seyrüsefer Senaryosu</i></p>
</div>

---

## Sistem Yetkinlikleri

Geliştirilen yazılım stack'i, aşağıdaki temel otonom görevleri icra etmektedir:

* **Otonom Seyrüsefer:** GNSS ve IMU verileriyle gerçek zamanlı dinamik rota planlama.
* **Nesne Tespiti ve Sınıflandırma:** Saha koşullarında şamandıra ve engellerin gerçek zamanlı tespiti.
* **Engel Sakınma:** Statik ve dinamik engellere karşı geliştirilen karar mekanizmaları.

---

## İletişim
Sistem mimarisi veya teknik detaylar hakkında mülakat/bilgi talebi için iletişime geçebilirsiniz.
