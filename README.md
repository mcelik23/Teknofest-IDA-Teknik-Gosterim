# Teknofest Autonomous Marine Vehicle (IDA) - Technical Showcase

Bu depo, **Teknofest İnsansız Deniz Aracı (İDA)** yarışması kapsamında geliştirilen otonom seyrüsefer sisteminin teknik kanıtlarını, simülasyon çıktılarını ve saha testlerini içermektedir.

> **Not:** Yarışma kuralları ve stratejik gizlilik gereği, yazılım mimarisi detayları ve kaynak kodlar bu alanda paylaşılmamaktadır. Sistem performansına dair teknik ispatlar aşağıda sunulmuştur.

---

## Teknik Gösterimler ve Test Kayıtları

Aşağıdaki bağlantılar, sistemin farklı senaryolardaki otonom kabiliyetlerini doğrudan oynatılabilir formatta sunmaktadır:

### 1. Simülasyon Çalışmaları
* **Hibrit Yazılım Mimarisi Testi:** (Ardışıl kare rota ve slalom görevi)  
  [Görüntüle](https://github.com/mcelik23/Teknofest_IDA_Media/issues/3#issue-3823981460)
* **Engelli Ortamda Şerit Takip Görevi:** [Görüntüle](https://github.com/mcelik23/Teknofest_IDA_Media/issues/11#issue-3824326221)

### 2. Saha Testleri (Real-Time)
* **Entegre Şerit Takip Testi:** İşlenmiş kamera görüntüsü ve dış çekim analizi.  
  [Görüntüle](https://github.com/mcelik23/Teknofest_IDA_Media/issues/7#issue-3824038112)
* **Dış Çekim Kayıtları:**
  * [Şerit Takibi - Senaryo 1](https://github.com/mcelik23/Teknofest_IDA_Media/issues/8#issue-3824093923)
  * [Şerit Takibi - Senaryo 2](https://github.com/mcelik23/Teknofest_IDA_Media/issues/9#issue-3824099173)
  * [Şerit Takibi - Senaryo 3](https://github.com/mcelik23/Teknofest_IDA_Media/issues/10#issue-3824105874)
* **Görüntü İşleme Çıktısı:**
  * [İşlenmiş Kamera Görüntüsü](https://github.com/mcelik23/Teknofest_IDA_Media/issues/12#issue-3824328227)

---

## Sistem Yetkinlikleri

Geliştirilen yazılım mimarisi, aşağıdaki temel otonom görevleri icra etmektedir:

* **Otonom Seyrüsefer:** GNSS ve IMU verileriyle gerçek zamanlı dinamik rota planlama süreçleri.
* **Nesne Tespiti ve Sınıflandırma:** Saha koşullarında şamandıra ve engellerin yapay zeka tabanlı tespiti.
* **Engel Sakınma:** Statik ve dinamik engellere karşı geliştirilen otonom karar mekanizmaları.

---
