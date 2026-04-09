# ⚡ Gömülü Sistemler, IoT ve Edge-AI Masterclass Roadmap

Yazılımın fiziksel dünyayla bütünleştiği uç noktada (Edge), donanıma hükmeden, RTOS kurgulayan ve otonom yapay zeka tasarlayan mühendislerin yol haritası.

## 📌 Sertifikasyon Haritası

### 1. Arm Accredited Engineer (AAE) ve Bağlı Mimari Eğitimleri
Donanımın en alt seviyesine inip, memory (MMU) yapılarına hükmetmek isteyen mimarlar için.
* **Detay:** Cortex-A/R/M mimarilerinde Assembly ve C ile yüksek performanslı RTOS kodlama yetkinliğini kanıtlar.

### 2. NVIDIA DLI Certifications (Deep Learning Institute)
Görüntü işleme modellerini uç cihazlarda cayır cayır çalıştıran Edge-AI mühendislerine.
* **Detay:** Jetson cihazlar üzerinde TensorRT optimizasyonları ve YOLO modellerini sıfır gecikme ile ayağa kaldırma ustalığını ölçer.

---

## ⚙️ Teknik Derinlik: Framework'ler ve Donanım

Edge-AI ve Gömülü Sistemler dünyası, cihazlara komut satırından hükmetmekle başlar.

### Gerekli Framework ve Araçlar
- **ROS 2 (Robot Operating System):** Otonom sistemler ve robotik projeleri için endüstri standardı middleware. Node'lar arası haberleşmeyi DDS (Data Distribution Service) ile yapar.
- **TensorRT (NVIDIA):** PyTorch veya TensorFlow modellerinizi alıp donanıma en uygun şekle (FP16 veya INT8) çeviren motor.
- **FreeRTOS / Zephyr:** Gömülü sistemlerde CPU zamanını mikro saniye seviyesinde hassas yöneten gerçek zamanlı işletim sistemleri.

### "Hands-on" Donanım Pratikleri
Sanal ortamlarda geliştirme bitmez. Ellerin donanıma değmesi şarttır:
- **NVIDIA Jetson (Nano / Orin serileri):** Sınır bilişim ve AI testleri (Özellikle V4L2 ve GStreamer pipeline denemeleri).
- **STM32 (ARM Cortex-M Serisi):** Kesmeler (Interrupts), DMA, I2C/SPI haberleşme protokollerini "Bare-metal" (işletim sistemsiz saf C/C++) yazarak pratik yapmak.
- **Espressif (ESP32):** Edge-IoT güvenliği, FreeRTOS uygulamaları ve MQTT / TLS entegrasyonu testleri için.
