<p align="center">
  <img src="assets/banner.png" alt="IT Certifications Roadmap Banner" width="100%">
</p>

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
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Offensive Security'nin sağladığı PEN-200 kursu ve laboratuvarları (Proving Grounds) zorunlu ve ana kaynaktır.
  - **Pratik Ekosistemi:** TJ_Null'un hazırladığı "OSCP benzeri HTB (HackTheBox) Makineleri" listesi baştan sona çözülmelidir. VulnHub üzerinden yerel sanal makineler indirilip exploit testleri yapılmalıdır.
  - **Kritik Konular:** Windows/Linux Privilege Escalation (Hak Yükseltme) konusunda Tib3rius veya The Cyber Mentor dokümanları/kursları incelenmelidir. Buffer Overflow ve Active Directory sömürüsü sınavın kilit noktalarıdır.
  - **Zaman Çizelgesi:** Günde en az 3-4 saat laboratuvar pratiğiyle 3 ile 6 ay arasında bir hazırlık süreci öngörülür.

### 2. OSEP (Offensive Security Experienced Penetration Tester)
OSCP'nin ileri seviyesidir; gelişmiş güvenlik önlemlerini (AV/EDR atlatma) aşmaya odaklanır.

* **Nedir:** Antivirüs atlatma, gelişmiş Active Directory saldırıları konularında uzmanlığı belgeler.
* **Kime Hitap Eder:** Kıdemli Red Team üyeleri.
* **Sınav Formatı:** **48 saatlik pratik sınav.**
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** PEN-300 kursu titizlikle çalışılmalıdır.
  - **Pratik Ekosistemi:** Kendi yerel hypervisor'ünüz (ESXi veya Proxmox) üzerinde bir Active Directory ve Windows Defender kurulu test ortamı inşa edin.
  - **Kritik Konular:** C# ve PowerShell kullanarak özel payload (zararlı yazılım) taşıyıcıları geliştirmek zorunludur. Bellek içi (in-memory) çalışma, API Hooking ve lateral movement (yatay hareket) konularında ciddi bir kod yazma deneyimi gerektirir.
  - **Zaman Çizelgesi:** Üst düzey bir güvenlik altyapısı bilgisi varsayıldığında dahi 6 aydan fazla kod pratiği gerektirir.

### 3. CISSP (Certified Information Systems Security Professional)
Yönetim ve mimari seviyesindeki standart güvenlik belgelerinden biridir.

* **Nedir:** Siber güvenliğin teknik detaylarından ziyade büyük resmini, mimari tasarımını ve risk yönetimini masaya yatırır.
* **Kime Hitap Eder:** CISO adayları, güvenlik liderleri ve kıdemli danışmanlar.
* **Sınav Formatı:** 4 saat, adaptif (CAT) sistemde 125-175 arası senaryo sorusu.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** *Sybex CISSP Official Study Guide* kitabı "başucu eseri" olmalıdır ve satır satır okunmalıdır.
  - **Pratik Ekosistemi:** Boson Test Motoru veya Sybex'in resmi test bankası üzerinden her gün senaryo sorusu çözülmelidir. Yanlış yapılan soruların açıklamaları ezberlenmek yerine analiz edilmelidir.
  - **Kritik Konular:** CISSP sınavı teknik yetenek değil, vizyon ölçer. Kelly Handerhan'ın ünlü *“Why You Will Pass the CISSP”* videosu sınav felsefesini anlamak için şarttır ("Fix the process, not the problem" zihniyeti).
  - **Zaman Çizelgesi:** Her domene ayrılacak süreler planlanarak düzenli okuma ile 3-4 ay sürer.

### 4. eJPT (eLearnSecurity Junior Penetration Tester)
Sektöre giriş yapmak isteyenler için uygulamalı pratik yetkinliğini kanıtlayan başlangıç sertifikası.

* **Nedir:** Penetrasyon testlerinin temellerini (bilgi toplama, zafiyet tarama, exploitleme) gerçekçi ağ senaryolarında ölçer.
* **Kime Hitap Eder:** Siber güvenlik kariyerine yeni başlayanlar.
* **Sınav Formatı:** 48 saat süren uygulamalı pratik sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** INE (eLearnSecurity) platformunda sunulan PTS (Penetration Testing Student) eğitim rotası ana kaynaktır.
  - **Pratik Ekosistemi:** PortSwigger Web Security Academy üzerinde Burp Suite ile request manuplasyonları yapmak; TryHackMe (THM) üzerinde "Jr Penetration Tester" odalarını çözmek.
  - **Kritik Konular:** Nmap kullanımı, Metasploit bileşenlerine hakimiyet ve ağ üzerinde (Pivoting) temel ilerleme prensipleri bol bol pratik edilmelidir.

---

## ⚡ Gömülü Sistemler, IoT ve Edge-AI (Embedded & AI)

*👉 Detaylı Harita: [embedded_and_ai/](embedded_and_ai/README.md)*

### 1. NVIDIA DLI Certifications (Deep Learning Institute)
Görüntü işleme ve yapay zeka alanında donanım odaklı geliştirme yapanlar içindir.

* **Nedir:** Bilgisayarlı görü, derin öğrenme modellerini NVIDIA GPU'ları veya Edge cihazları üzerinde optimize etme yeteneğini ölçer.
* **Kime Hitap Eder:** Yapay zeka mühendisleri, robotik geliştiricileri.
* **Sınav Formatı:** Proje tabanlı uygulamalı değerlendirmeler.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Resmi NVIDIA DLI çevrimiçi laboratuvarları takip edilmeli, verilen notebook'lar dikkatle analiz edilmelidir.
  - **Pratik Ekosistemi:** AWS üzerinde GPU barındıran EC2 sunucuları veya fiziksel bir NVIDIA Jetson Nano/Orin cihazı kullanılarak "Deployment" testleri gerçekleştirilmelidir.
  - **Kritik Konular:** Modele TensorRT kullanarak FP16/INT8 düzeyinde "Qunatization" (sıkıştırma) yapmak ve GStreamer üzerinde ardışık veri işleme hatları (pipelines) tasarlamak temel hazırlık odağıdır.

### 2. Arm Accredited Engineer (AAE) / Arm Architecture Certifications
Donanım mimarisi ve düşük seviyeli (low-level) sistem programlama yetkinliği sertifikaları.

* **Nedir:** Cortex mimarilerini anlama, bellek yönetimi (MMU) ve kesme (interrupt) işleme bilgisini mühürler.
* **Kime Hitap Eder:** RTOS geliştiricileri, sürücü (driver) geliştiriciler.
* **Sınav Formatı:** Kapsamlı ve donanım mimarisi senaryolarını test eden çoktan seçmeli sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Arm *Architecture Reference Manual* serileri ve *Joseph Yiu*'nun Cortex-M kılavuz kitapları temel akademik referanstır.
  - **Pratik Ekosistemi:** Kiel IDE veya GCC Toolchain kurulu ortamlarda, STM32 veya NXP geliştirme kartları kullanarak fiziksel kodlama. İşletim sistemi olmadan (Bare-metal) C veya Assembly ile donanım register konfigürasyonları yapmak şarttır.

---

## 📊 Veri Mühendisliği ve Büyük Veri (Data Engineering)

*👉 Detaylı Harita: [data_engineering/](data_engineering/README.md)*

### 1. Google Cloud Professional Data Engineer
Veri mühendisliği için bulut üzerinde tasarım ve operasyon yetkinliğini belgeler.

* **Nedir:** BigQuery, Dataflow, Dataproc ve Pub/Sub platformlarında pipeline kurma becerilerini ölçer.
* **Kime Hitap Eder:** Veri mühendisleri ve veri mimarları.
* **Sınav Formatı:** 2 saatlik vaka analizleri ve mimari senaryoları içeren sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Google Cloud Skills Boost'daki "Data Engineer Learning Path" ve Coursera eğitimleri izlenmelidir.
  - **Pratik Ekosistemi:** Qwiklabs üzerinde sunulan pratik görevlerinin zaman sınırları içerisinde tamamlanması rutin hale getirilmelidir.
  - **Kritik Konular:** Geleneksel veritabanından veri aktarımı (Migration), Pub/Sub ile asenkron Stream oluşturma ve BigQuery üzerinde veri ambarı (Data Warehouse) şema tasarımı, sınav senaryolarının temelini oluşturur.

### 2. Databricks Certified Data Engineer Professional
Apache Spark ekosistemi üzerinde uzmanlık sertifikası.

* **Nedir:** Databricks üzerinde ETL pipeline'ları kurma, Delta Lake optimizasyonu ve performans tuning testi.
* **Kime Hitap Eder:** İleri seviye veri mühendisleri.
* **Sınav Formatı:** 120 dakika süren 60 senaryo tabanlı performans veya troubleshooting sorusu.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Databricks Academy üzerindeki "Advanced Data Engineering with Databricks" kursu zorunludur.
  - **Kritik Konular:** Spark Web Kullanıcı Arayüzü (UI) üzerinden DAG grafikleri okumak, "Execution Plan" analiz edip yavaş çalışan sorguların altında yatan bellek/şema kaynaklı problemleri teşhis etmek en yoğun çalışılması gereken konudur. Delta Lake mekanizmaları (Time Travel, OPTIMIZE ve Z-ORDER) pratik edilmelidir.

---

## 🌐 Ağ (Network) ve Telekomünikasyon

*👉 Detaylı Harita: [network_telecom/](network_telecom/README.md)*

### 1. Cisco CCNA (Cisco Certified Network Associate)
Ağ mühendisliğinin global temel standartlarından biri.

* **Nedir:** Yönlendirme, anahtarlama, IP adresleme ve ağ otomasyonu temellerini kapsar.
* **Kime Hitap Eder:** Network mühendisleri, sistem yöneticileri.
* **Sınav Formatı:** 120 dakikalık CLI (komut satırı) tabanlı laboratuvar simülasyonları ve çoktan seçmeli sorular.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Wendell Odom'un CCNA Official Cert Guide (OCG) kitap seti ve Jeremy's IT Lab kursları en ideal başlangıçtır.
  - **Pratik Ekosistemi:** Cisco Packet Tracer programını bilgisayara kurarak her gün yeni bir topoloji oluşturulmalı.
  - **Kritik Konular:** Fiziksel bir ağ cihazını yapılandırmak için gereken her terminal komutu kas hafızasına kazınmalıdır. Subnetting hesaplamalarının kağıt üzerinde 10 saniyede yapılabilecek hıza erişmesi kritik önem taşır.

### 2. Cisco CCNP Enterprise (Cisco Certified Network Professional)
Altyapı mimarisi ve ileri seviye ağ konfigürasyonu sertifikası.

* **Nedir:** BGP, OSPF, SD-WAN, kablosuz ağlar ve hata ayıklama (troubleshoot) konularını içerir.
* **Kime Hitap Eder:** Kıdemli network uzmanları ve ağ mimarları.
* **Sınav Formatı:** Core (ENCOR) ve Concentration (ENARSI vb.) olmak üzere iki aşamalı laboratuvar simülasyonlu sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Sistem yöneticisi seviyesindeki bu sertifikada Packet Tracer yetersiz kalır. GNS3 veya EVE-NG üzerinde Cisco IOS imajları yüklenerek çoklu BGP komşulukları ve yönlendirme protokollerinin detayları simüle edilmelidir.
  - **Kritik Konular:** Sorun gidermeyi (Troubleshooting) öğrenmek tek yoldur. Tasarlanmış bir ağı sizin veya çalışma arkadaşınızın bilerek bozarak, sistemin çalışmayan noktasını CLI arayüzlerinden adım adım teşhis etme yeteneği geliştirilmelidir.

---

## 🏗️ Yazılım Mimarisi ve Geliştirme (Software Architecture)

*👉 Detaylı Harita: [software_architecture/](software_architecture/README.md)*

### 1. Oracle Certified Professional: Java SE 17 / 21 Developer
Java dilinin mimari ve nesne yönelimli standartlarını ölçen sertifika.

* **Nedir:** Java'nın bellek yönetimi (Garbage Collection), concurrency/multithreading özelliklerini uygulamalı senaryolarda doğru kodlamayı test eder.
* **Kime Hitap Eder:** Backend geliştiricileri, yazılım mühendisleri.
* **Sınav Formatı:** 90 dakikalık karmaşık kod analizi soruları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Jeanne Boyarsky & Scott Selikoff tarafından yazılan OCP Java SE çalışma rehberleri.
  - **Pratik Ekosistemi:** IDE (Eclipse, IntelliJ) otomatik tamamlamaları kapatılmalı. Kodun çıktısını ve çalışma davranışını düz metin editöründe inceleyerek derleyici (compiler) mantığı kavranmalıdır.
  - **Kritik Konular:** Enthuware deneme sınavları alınmalıdır. Enthuware'deki her bir yanlış sorunun altındaki JVM analizleri son derece bilgilendiricidir. Streams API ve Concurrency API uç durum analizlerine ağırlık verilmelidir.

---

## ☁️ Bulut Bilişim ve DevOps (Cloud & DevOps)

*👉 Detaylı Harita: [cloud_devops/](cloud_devops/README.md)*

### 1. AWS Certified Solutions Architect - Professional
AWS üzerinde karmaşık ve büyük ölçekli mimariler tasarlama yeterliliği belgesi.

* **Nedir:** Hibrit bulut ortamları tasarlama, çok paydaşlı veri ağları kurgulama.
* **Kime Hitap Eder:** Kıdemli bulut mimarları.
* **Sınav Formatı:** 180 dakikalık çok yoğun entegrasyon senaryo analizleri.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Adrian Cantrill veya Stephane Maarek'in Professional seviye kursları izlenmelidir. Ayrıca AWS Whitepapers doküman kütüphanesi mutlaka okunup analiz edilmelidir.
  - **Pratik Ekosistemi:** TutorialsDojo platformundaki deneme sınavı motoru son derece gerçeğe yakındır ve oradaki sorular analiz edilerek hazırlık sınanmalıdır.
  - **Kritik Konular:** Çok uzun (paragraf bazlı) mimari senaryo sorularını, "Security, Reliability, Cost Optimization" gereksinimleri bağlamında hızlı okuma/filtreleme taktikleri çalışılmalıdır.

### 2. CKA (Certified Kubernetes Administrator)
Sistem yönetimi ve mikroservis dağıtımı konusunda uçtan uca altyapı yönetimi becerisi.

* **Nedir:** Konteyner orkestrasyonunda kümelenme kurulumu, bakım ve sorun giderme (troubleshoot) standartlarını belgeler.
* **Kime Hitap Eder:** DevOps mühendisleri, SRE'ler.
* **Sınav Formatı:** 2 saatlik, **%100 uygulamalı** terminal tabanlı sınavdır.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** KodeKloud üzerindeki CKA eğitim seti ve interaktif laboratuvarlar mükemmel bir eşlikçidir.
  - **Pratik Ekosistemi:** Killer.sh simülatörü sınav kaydı alındığında size iki adet ücretsiz oturum verir. Bu simülatör, gerçek sınavdan kat be kat zor olacak şekilde dizayn edilmiştir; simülatörü başarı ile geçmek sınav için bir garantidir.
  - **Kritik Konular:** Zaman çok kısıtlı olduğundan Kubernetes terminal alias komutları (örn: `k get po`, `k run --dry-run=client -o yaml`) saniyeler içinde ezberden yazılabilir hale gelene kadar pratik tekrarları yapılmalıdır. Sadece Kubernetes belgeleri incelenebildiği için bu belge üzerinde arama yapma yetkinliği geliştirilmelidir.

---

## 🤝 Nasıl Katkıda Bulunurum?
Bu repo açık kaynaklı bir referans listesi projesidir. Siz de yeni bir sertifika başlığı veya güncel bir bilgi eklemek isterseniz detaylar için `CONTRIBUTING.md` dosyasına göz atabilirsiniz.