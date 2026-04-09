# 🚀 IT-Certifications-Roadmap

Bilgi Teknolojileri (IT) sektöründe yetkinliği global çapta kanıtlamanın en prestijli yollarından biri doğru sertifikalara sahip olmaktır. 

Bu repo, IT endüstrisinde pratik uygulaması olan, teknik kapasiteyi gerçekten ölçen ve sektörel ağırlığı bulunan sertifikaların tarafsız bir haritasıdır. Teorik ezberle geçilen sınavlar yerine uygulamalı (hands-on) yetkinlik gerektiren sertifikalara odaklanılmıştır.

---

## 📑 İçindekiler
- [🛡️ Siber Güvenlik (Cybersecurity)](#-siber-güvenlik-cybersecurity)
- [⚡ Gömülü Sistemler, IoT ve Edge-AI (Embedded & AI)](#-gömülü-sistemler-iot-ve-edge-ai-embedded--ai)
- [📊 Veri Mühendisliği ve Büyük Veri (Data Engineering)](#-veri-mühendisliği-ve-büyük-veri-data-engineering)
- [🌐 Ağ (Network) ve Telekomünikasyon](#-ağ-network-ve-telekomünikasyon)
- [🏗️ Yazılım Mimarisi ve Geliştirme (Software Architecture)](#-yazılım-mimarisi-ve-geliştirme-software-architecture)
- [☁️ Bulut Bilişim ve DevOps (Cloud & DevOps)](#-bulut-bilişim-ve-devops-cloud--devops)
- [🤝 Nasıl Katkıda Bulunurum?](#-nasıl-katkıda-bulunurum)

---

## 🛡️ Siber Güvenlik (Cybersecurity)

*👉 Detaylı Harita: [cybersecurity/](cybersecurity/README.md)*

### 1. OSCP (Offensive Security Certified Professional)
Sektörün en saygı duyulan, uygulamalı sızma testi (penetration testing) sertifikası. 

* **Nedir:** Laboratuvar ortamı vererek hedef makineler üzerinde sızma testleri gerçekleştirilmesini bekler.
* **Kime Hitap Eder:** Güvenlik uzmanları ve Red Team üyeleri.
* **Sınav Formatı:** **24 saatlik pratik sınav.** Belirtilen makineler hacklenip 24 saat içinde raporlanmalıdır.
* **Hazırlık Yöntemi:** PEN-200 eğitimi, HackTheBox, TryHackMe pratikleri.

### 2. OSEP (Offensive Security Experienced Penetration Tester)
OSCP'nin ileri seviyesidir; gelişmiş güvenlik önlemlerini (AV/EDR atlatma) aşmaya odaklanır.

* **Nedir:** Antivirüs atlatma, gelişmiş Active Directory saldırıları konularında uzmanlığı belgeler.
* **Kime Hitap Eder:** Kıdemli Red Team üyeleri.
* **Sınav Formatı:** **48 saatlik pratik sınav.**
* **Hazırlık Yöntemi:** PEN-300 kursu; C# ve PowerShell kullanarak özel payload geliştirme pratikleri.

### 3. CISSP (Certified Information Systems Security Professional)
Yönetim ve mimari seviyesindeki standart güvenlik belgelerinden biridir.

* **Nedir:** Siber güvenliğin teknik detaylarından ziyade büyük resmini, mimari tasarımını ve risk yönetimini masaya yatırır.
* **Kime Hitap Eder:** CISO adayları, güvenlik liderleri ve kıdemli danışmanlar.
* **Sınav Formatı:** 4 saat, adaptif (CAT) sistemde 125-175 arası senaryo sorusu.
* **Hazırlık Yöntemi:** Sybex CISSP Study Guide kitapları ile yöneticinin perspektifinden olayları analiz etmeyi kavramak.

### 4. eJPT (eLearnSecurity Junior Penetration Tester)
Sektöre giriş yapmak isteyenler için uygulamalı pratik yetkinliğini kanıtlayan başlangıç sertifikası.

* **Nedir:** Penetrasyon testlerinin temellerini (bilgi toplama, zafiyet tarama, exploitleme) gerçekçi ağ senaryolarında ölçer.
* **Kime Hitap Eder:** Siber güvenlik kariyerine yeni başlayanlar.
* **Sınav Formatı:** 48 saat süren uygulamalı pratik sınav.
* **Hazırlık Yöntemi:** INE üzerinden PTS (Penetration Testing Student) rotasının bitirilmesi ve ilgili laboratuvarların çözülmesi.

---

## ⚡ Gömülü Sistemler, IoT ve Edge-AI (Embedded & AI)

*👉 Detaylı Harita: [embedded_and_ai/](embedded_and_ai/README.md)*

### 1. NVIDIA DLI Certifications (Deep Learning Institute)
Görüntü işleme ve yapay zeka alanında donanım odaklı geliştirme yapanlar içindir.

* **Nedir:** Bilgisayarlı görü (Computer Vision), derin öğrenme modellerini NVIDIA GPU'ları veya Edge cihazları üzerinde optimize etme yeteneğini ölçer.
* **Kime Hitap Eder:** Yapay zeka mühendisleri, robotik geliştiricileri.
* **Sınav Formatı:** Proje tabanlı uygulamalı değerlendirmeler.
* **Hazırlık Yöntemi:** NVIDIA DLI laboratuvarları ve Jetson cihazları üzerinde gerçek model dağıtımı (deployment) çalışmaları.

### 2. Arm Accredited Engineer (AAE) / Arm Architecture Certifications
Donanım mimarisi ve düşük seviyeli (low-level) sistem programlama yetkinliği sertifikaları.

* **Nedir:** Cortex mimarilerini anlama, bellek yönetimi (MMU), kesme (interrupt) işleme ve Assembly/C bilgisini mühürler.
* **Kime Hitap Eder:** RTOS geliştiricileri, sürücü (driver) geliştiriciler.
* **Sınav Formatı:** Kapsamlı ve donanım mimarisi senaryolarını test eden çoktan seçmeli sınav.
* **Hazırlık Yöntemi:** Arm dokümantasyonları ve geliştirme kartları (STM32, vs.) üzerinde işletim sistemsiz ortamda (bare-metal) uygulamalar geliştirmek.

---

## 📊 Veri Mühendisliği ve Büyük Veri (Data Engineering)

*👉 Detaylı Harita: [data_engineering/](data_engineering/README.md)*

### 1. Google Cloud Professional Data Engineer
Veri mühendisliği için bulut üzerinde tasarım ve operasyon yetkinliğini belgeler.

* **Nedir:** BigQuery, Dataflow, Dataproc ve Pub/Sub gibi platformlarda veri işleme, pipeline kurma ve model dağıtımı becerilerini ölçer.
* **Kime Hitap Eder:** Veri mühendisleri ve veri mimarları.
* **Sınav Formatı:** 2 saatlik vaka analizleri ve mimari senaryoları içeren sınav.
* **Hazırlık Yöntemi:** Google Cloud Skills Boost laboratuvarları, kaynak yönetimi optimizasyonu pratikleri.

### 2. Databricks Certified Data Engineer Professional
Apache Spark ekosistemi üzerinde uzmanlık sertifikası.

* **Nedir:** Databricks üzerinde ETL pipeline'ları kurma, Delta Lake optimizasyonu, veri kalitesi yönetimi ve performans tuning testi.
* **Kime Hitap Eder:** İleri seviye veri mühendisleri.
* **Sınav Formatı:** 120 dakika süren 60 senaryo tabanlı performans veya troubleshooting sorusu.
* **Hazırlık Yöntemi:** Databricks Academy eğitimleri, Spark web arayüzü ölçümleri ve mimari kurgu çalışmaları.

---

## 🌐 Ağ (Network) ve Telekomünikasyon

*👉 Detaylı Harita: [network_telecom/](network_telecom/README.md)*

### 1. Cisco CCNA (Cisco Certified Network Associate)
Ağ mühendisliğinin global temel standartlarından biri.

* **Nedir:** Yönlendirme (routing), anahtarlama (switching), IP adresleme ve ağ otomasyonu temellerini kapsar.
* **Kime Hitap Eder:** Network mühendisleri, sistem yöneticileri.
* **Sınav Formatı:** 120 dakikalık, ağırlıklı olarak CLI tabanlı simülasyon ve senaryo temelli çoktan seçmeli sorulardan oluşur.
* **Hazırlık Yöntemi:** Cisco Packet Tracer veya GNS3 kullanılarak topoloji yapılandırma laboratuvarları.

### 2. Cisco CCNP Enterprise (Cisco Certified Network Professional)
Altyapı mimarisi ve ileri seviye ağ konfigürasyonu sertifikası.

* **Nedir:** Gelişmiş routing, SD-WAN, kablosuz ağlar ve hata ayıklama (troubleshooting) senaryolarını içerir.
* **Kime Hitap Eder:** Kıdemli network uzmanları ve ağ mimarları.
* **Sınav Formatı:** Her biri 120 dakika süren, Core ve Concentration olarak iki sınav aşaması vardır. Çoklu laboratuvar simülasyonları bulunur.
* **Hazırlık Yöntemi:** EVE-NG veya GNS3 sanal ağ laboratuvarları kurgulayarak ağ hatalarını giderme (troubleshooting) pratikleri yapmak.

---

## 🏗️ Yazılım Mimarisi ve Geliştirme (Software Architecture)

*👉 Detaylı Harita: [software_architecture/](software_architecture/README.md)*

### 1. Oracle Certified Professional: Java SE 17 / 21 Developer
Java dilinin mimari ve nesne yönelimli standartlarını derinlemesine ölçen sertifika.

* **Nedir:** Java'nın bellek yönetimi (Garbage Collection), concurrency/multithreading özelliklerini uygulamalı senaryolarda doğru kodlamayı test eder.
* **Kime Hitap Eder:** Backend geliştiricileri, yazılım mühendisleri.
* **Sınav Formatı:** 90 dakikalık karmaşık kod analizi soruları barındırır.
* **Hazırlık Yöntemi:** Java'nın detaylı derleme (compile) kurallarına aşinalık gerektirir.

---

## ☁️ Bulut Bilişim ve DevOps (Cloud & DevOps)

*👉 Detaylı Harita: [cloud_devops/](cloud_devops/README.md)*

### 1. AWS Certified Solutions Architect - Professional
AWS üzerinde karmaşık ve büyük ölçekli mimariler tasarlama yeterliliği belgesi.

* **Nedir:** Hibrit bulut ortamları tasarlama; uygun servisleri seçip güvenlik ve maliyet kıstasına göre kurgulama becerisidir.
* **Kime Hitap Eder:** Kıdemli bulut mimarları.
* **Sınav Formatı:** 180 dakikalık çok paydaşlı entegrasyon soruları.
* **Hazırlık Yöntemi:** AWS servislerinin birbirleri ile çalışma koşulları ve limitlemelerini dökümantasyonlar üzerinden pratik senaryolar eşliğinde analiz etmek.

### 2. CKA (Certified Kubernetes Administrator)
Sistem yönetimi ve mikroservis dağıtımı konusunda yaygın bir endüstri standardı sertifikadır.

* **Nedir:** Konteyner orkestrasyonunda sorun giderme (troubleshooting), cluster kurulumu, bakımı ve pod yönetimi becerilerini kanıtlar.
* **Kime Hitap Eder:** DevOps mühendisleri, sistem yöneticileri, SRE'ler.
* **Sınav Formatı:** 2 saatlik, **%100 uygulamalı** terminal sınavıdır.
* **Hazırlık Yöntemi:** Gerçek cluster'ları bozarak ve onararak sorunları giderme (troubleshoot) laboratuvar pratikleri.

---

## 🤝 Nasıl Katkıda Bulunurum?
Bu repo açık kaynaklı bir referans listesi projesidir. Siz de yeni bir sertifika başlığı veya güncel bir bilgi eklemek isterseniz lütfen:

1. Repoyu Fork'layın
2. Yeni bir branch oluşturun
3. Değişikliklerinizi Commit'leyin
4. Repoya Push'layın
5. Belirlenen şablona (`PULL_REQUEST_TEMPLATE`) uyarak bir PR açın.