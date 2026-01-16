# Teknofest Autonomous Marine Vehicle (IDA) - Technical Showcase

Bu depo, Teknofest İnsansız Deniz Aracı (İDA) yarışması kapsamında geliştirilen otonom seyrüsefer sisteminin teknik kanıtlarını, simülasyon çıktılarını ve saha testlerini içermektedir.

Not: Yarışma kuralları ve stratejik gizlilik gereği, yazılım mimarisi detayları ve kaynak kodlar bu alanda paylaşılmamaktadır. Sistem performansına dair teknik ispatlar aşağıda sunulmuştur.

---

## Teknik Gösterimler ve Test Kayıtları

Aşağıdaki bağlantılar, sistemin farklı senaryolardaki otonom kabiliyetlerini doğrudan oynatılabilir formatta sunmaktadır:

### Simülasyon Çalışmaları

Hibrit yazılım mimarisi test amaçlı ardışıl şekilde kare rota ve slalom görevi : https://github.com/user-attachments/assets/link-buraya
Engelli ortamda şerit takip görevi (Yarışmanın ikinci parkuru birebir simüle edilmiştir) : https://github.com/user-attachments/assets/link-buraya

### Saha Testleri (Real Time)

Engelli ortamda şerit takibi gerçek saha testi dış çekim: https://github.com/user-attachments/assets/link-buraya
İşlenmiş kamera görüntüsü ve dış çekimle birlikte engelli ortamda şerit takip testi

---

## Sistem Yetkinlikleri

Geliştirilen yazılım aşağıdaki temel otonom görevleri icra etmektedir:

* **Otonom Seyrüsefer:** GNSS ve IMU verileriyle gerçek zamanlı dinamik rota planlama.
* **Nesne Tespiti ve Sınıflandırma:** Saha koşullarında şamandıra ve engellerin tespiti.
* **Engel Sakınma:** Statik ve dinamik engellere karşı geliştirilen karar mekanizmaları.

---
