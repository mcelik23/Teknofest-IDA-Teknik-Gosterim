# Teknofest İnsansız Deniz Aracı (İDA)

Bu depo; Teknofest İDA yarışması kapsamında kaptanlığını üstlendiğim ekibimizce geliştirilen otonom deniz aracının teknik ispatlarını sunar. İçerik; nesne tespiti tabanlı seyrüsefer algoritmalarımızın simülasyon ve saha ortamlarındaki performans çıktılarını kapsamaktadır.

> **Not:** Yarışma kuralları ve stratejik gizlilik gereği, yazılım mimarisi detayları ve kaynak kodlar bu alanda paylaşılmamaktadır. Sistem performansına dair teknik ispatlar aşağıda sunulmuştur.

---

## Teknik Gösterimler ve Test Kayıtları

Aşağıdaki bağlantılar, sistemin farklı senaryolardaki otonom kabiliyetlerini doğrudan oynatılabilir formatta sunmaktadır:

### 1. Simülasyon Çalışmaları
* **Temel Hareket Komutları Testi:** (Ardışıl kare rota ve slalom görevi)  [Görüntüle](https://github.com/mcelik23/Teknofest_IDA_Media/issues/3#issue-3823981460)
* **Engelli Ortamda Şerit Takip Görevi:** [Görüntüle](https://github.com/mcelik23/Teknofest_IDA_Media/issues/11#issue-3824326221)

### 2. Saha Testleri (Real-Time)
* **Entegre Şerit Takip Testi:** İşlenmiş kamera görüntüsü ve dış çekim analizi.  
  * [Görüntüle](https://github.com/mcelik23/Teknofest_IDA_Media/issues/7#issue-3824038112)
* **Dış Çekim Kayıtları:**
  * [Teknofest 2026 Kamikaze ve Engelli Ortamda Şerit Takibi Görevleri](https://github.com/mcelik23/Teknofest-IDA-Teknik-Gosterim/issues/13)
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
