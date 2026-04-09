# ⚡ Gömülü Sistemler, IoT ve Edge-AI Roadmap

Donanım programlama, gerçek zamanlı işletim sistemleri (RTOS) ve sınır bilişim (Edge) üzerinde çalışan yapay zeka sistemlerine odaklanan mühendisler için oluşturulmuş rotadır.

## 📌 Sertifikasyon Haritası

### 1. Arm Accredited Engineer (AAE) ve Bağlı Mimari Eğitimleri
Donanım mimarileri ve işlemci yapılarına dair bilgi düzeyini test eden sertifika programı.
* **Detay:** Cortex-A/R/M mimarilerinde Assembly ve C dillerinde yazılım geliştirme yetkinliğini belgelemeyi amaçlar.

### 2. NVIDIA DLI Certifications (Deep Learning Institute)
Görüntü işleme ve derin öğrenme modellerinin donanım üzerinde çalıştırılması ile ilgilenen yapay zeka geliştiricileri içindir.
* **Detay:** Jetson cihazları üzerinde TensorRT optimizasyonları ve AI model kurulum (deployment) tecrübesini ölçer.

---

## ⚙️ Teknik Derinlik: Framework'ler ve Donanım

Edge-AI ve Gömülü Sistemler çalışma alanında bilinmesi beklenen araç ve donanım konseptleri şunlardır:

### Gerekli Framework ve Araçlar
- **ROS 2 (Robot Operating System):** Otonom sistemler ve robotik projeleri için kullanılan "middleware". Node haberleşmeleri DDS (Data Distribution Service) tabanlıdır.
- **TensorRT (NVIDIA):** Mevcut modelleri (PyTorch, TensorFlow) donanım üzerinde yüksek performanslı çalışacak şekilde derleyen optimizasyon kütüphanesi.
- **FreeRTOS / Zephyr:** Mikrodenetleyiciler için tasarlanmış gerçek zamanlı işletim sistemleri (RTOS).

### Donanım Deneyimi
- **NVIDIA Jetson Serisi:** Edge AI, görüntü işleme hatları (pipeline) ve model performans testleri geliştirmek için sıklıkla kullanılan donanımlar.
- **STM32 Serisi:** ARM Cortex-M temelli mikrodenetleyicilerde "Bare-metal" (işletim sistemsiz ortam) geliştirmeler ve donanım birimi (I2C, SPI, DMA) programlama.
- **Espressif (ESP32):** Edge-IoT güvenliği ve MQTT / TLS entegrasyonu testleri için kullanılan Wi-Fi & Bluetooth modülleri.
