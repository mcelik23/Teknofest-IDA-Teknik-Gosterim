# Teknofest Autonomous Marine Vehicle (IDA) - Technical Showcase

Bu depo, Teknofest İnsansız Deniz Aracı (İDA) yarışması kapsamında geliştirilen otonom seyrüsefer sisteminin saha testlerini ve operasyonel performans kayıtlarını içermektedir.

Not: Yarışma kuralları ve stratejik gizlilik prensipleri gereği, yazılım mimarisi detayları ve kaynak kodlar bu alanda paylaşılmamaktadır. Sistemin görev icra yetkinliği, aşağıdaki test kayıtları ve depo içerisindeki media/ dizini ile belgelenmiştir.

---

## Saha Testleri (Real Time)

Trabzon sahil şeridinde gerçekleştirilen gerçek zamanlı testler; akıntı ve dalga direncine karşı sistemin otonom stabilizasyon ve hedef takibi yeteneklerini doğrulamaktadır.

<div align="center">
  <video src="media/simulation/2026_Hibrit.mp4" width="800" controls>
    Tarayıcınız video etiketini desteklemiyor.
  </video>
  <p><i>Saha Testi: Otonom Rota Takibi ve Manevra Kabiliyeti</i></p>
</div>

---

## Sistem Yetkinlikleri

Geliştirilen yazılım stack'i, aşağıdaki temel otonom görevleri icra etmektedir:

* **Otonom Seyrüsefer:** GNSS ve IMU verileriyle gerçek zamanlı dinamik rota planlama.
* **Nesne Tespiti ve Sınıflandırma:** Saha koşullarında şamandıra ve engellerin gerçek zamanlı tespiti.
* **Engel Sakınma:** Statik ve dinamik engellere karşı geliştirilen karar mekanizmaları.

---
