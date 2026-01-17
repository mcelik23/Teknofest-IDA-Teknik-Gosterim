# Teknofest Autonomous Marine Vehicle (IDA) - Technical Showcase

Bu depo, Teknofest İnsansız Deniz Aracı (İDA) yarışması kapsamında geliştirilen otonom seyrüsefer sisteminin teknik kanıtlarını, simülasyon çıktılarını ve saha testlerini içermektedir.

Not: Yarışma kuralları ve stratejik gizlilik gereği, yazılım mimarisi detayları ve kaynak kodlar bu alanda paylaşılmamaktadır. Sistem performansına dair teknik ispatlar aşağıda sunulmuştur.

---

## Teknik Gösterimler ve Test Kayıtları

Aşağıdaki bağlantılar, sistemin farklı senaryolardaki otonom kabiliyetlerini doğrudan oynatılabilir formatta sunmaktadır:

### Simülasyon Çalışmaları

Hibrit yazılım mimarisi test amaçlı ardışıl şekilde kare rota ve slalom görevi : https://github.com/mcelik23/Teknofest_IDA_Media/issues/3#issue-3823981460
Engelli ortamda şerit takip görevi :https://github.com/mcelik23/Teknofest_IDA_Media/issues/11#issue-3824326221

### Saha Testleri (Real Time)

İşlenmiş kamera görüntüsü ve dış çekimle birlikte engelli ortamda şerit takip testi : https://github.com/mcelik23/Teknofest_IDA_Media/issues/7#issue-3824038112
Engelli ortamda şerit takibi dış çekim 1 : https://github.com/mcelik23/Teknofest_IDA_Media/issues/8#issue-3824093923
Engelli ortamda şerit takibi dış çekim 2 : https://github.com/mcelik23/Teknofest_IDA_Media/issues/9#issue-3824099173
Engelli ortamda şerit takibi dış çekim 3 : https://github.com/mcelik23/Teknofest_IDA_Media/issues/10#issue-3824105874
İşlenmiş kamera görüntüsü : https://github.com/mcelik23/Teknofest_IDA_Media/issues/12#issue-3824328227

---

## Sistem Yetkinlikleri

Geliştirilen yazılım aşağıdaki temel otonom görevleri icra etmektedir:

* **Otonom Seyrüsefer:** GNSS ve IMU verileriyle gerçek zamanlı dinamik rota planlama.
* **Nesne Tespiti ve Sınıflandırma:** Saha koşullarında şamandıra ve engellerin tespiti.
* **Engel Sakınma:** Statik ve dinamik engellere karşı geliştirilen karar mekanizmaları.

---
