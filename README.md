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

### 1. CompTIA Security+ (SY0-701)
Siber güvenliğe giriş seviyesindeki endüstri standardı ve marka bağımsız temel belgedir.
* **Nedir:** Risk yönetimi, bilgi güvenliği temelleri, olay müdahalesi (incident response) ve farklı kriptografi formasyonlarının çerçevesini çizer.
* **Kime Hitap Eder:** Güvenlik alanına ilk adım atanlar, sistem ve ağ yöneticileri ile devlet teşkilatları (DoD gereksinimleri).
* **Sınav Formatı:** 90 dakikalık, en fazla 90 soruluk uygulamalı performans temelli sorular (PBQ) ve çoktan seçmeli test.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Professor Messer'in YouTube eğitim serisi sektör standardı olarak kabul edilir ve yeterlidir.
  - **Pratik Ekosistemi:** Udemy üzerinden Jason Dion deneme sınavları alınarak PBQ (Performance Based Questions) tarzı interaktif sorulara alışılması gerekir.

### 2. OSCP (Offensive Security Certified Professional)
Sektörün en saygı duyulan, uygulamalı sızma testi (penetration testing) sertifikası.
* **Nedir:** Laboratuvar ortamı vererek hedef makineler üzerinde sızma testleri gerçekleştirilmesini bekler.
* **Kime Hitap Eder:** Güvenlik uzmanları ve Red Team üyeleri.
* **Sınav Formatı:** **24 saatlik pratik sınav.** Belirtilen makineler hacklenip 24 saat içinde raporlanmalıdır.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Offensive Security'nin sağladığı PEN-200 kursu ve laboratuvarları zorunlu ve ana kaynaktır.
  - **Pratik Ekosistemi:** TJ_Null'un hazırladığı "OSCP benzeri HTB Makineleri" listesi çözülmelidir. 
  - **Kritik Konular:** Windows/Linux Privilege Escalation (The Cyber Mentor) ile Active Directory sömürüsü sınavın kilit noktalarıdır.

### 3. OSEP (Offensive Security Experienced Penetration Tester)
İleri seviye, gelişmiş güvenlik önlemlerini (AV/EDR atlatma) aşmaya odaklanır.
* **Nedir:** Antivirüs atlatma, gelişmiş Active Directory saldırıları konularında uzmanlığı belgeler.
* **Kime Hitap Eder:** Kıdemli Red Team üyeleri.
* **Sınav Formatı:** **48 saatlik pratik sınav.**
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** PEN-300 kursu titizlikle çalışılmalıdır.
  - **Pratik Ekosistemi:** Hypervisor üzerinde kendi AV ve EDR sisteminizin (Örn. Windows Defender) bulunduğu Active Directory labı oluşturulmalıdır.
  - **Kritik Konular:** C# ve PowerShell kullanarak özel payload (zararlı yazılım) geliştirmek ve bellek içi (in-memory) çalıştırma teknikleri (API Hooking vb.) esastır.

### 4. CISSP (Certified Information Systems Security Professional)
Yönetim ve bilgi güvenliği liderliği alanında altın standart belgedir.
* **Nedir:** Siber güvenliğin teknik detaylarından ziyade büyük resmini, mimari tasarımını ve risk yönetimini masaya yatırır.
* **Kime Hitap Eder:** CISO adayları, güvenlik liderleri ve kıdemli danışmanlar.
* **Sınav Formatı:** 4 saat, adaptif (CAT) sistemde 125-175 arası senaryo sorusu.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** *Sybex CISSP Official Study Guide* kitabı ana referanstır.
  - **Pratik Ekosistemi:** Boson Test Motoru aracılığıyla senaryo odaklı analiz yapılmalıdır. Soruların ezberlenmesi değil "Yönetici Perspektifiyle" analiz edilmesi öğretilmelidir.

### 5. BSCP (Burp Suite Certified Practitioner)
Web uygulama güvenliği ve açıkları konusunda %100 uygulamalı bir laboratuvar sınavıdır.
* **Nedir:** SQL Enjeksiyonu, XSS, CSRF, SSRF gibi standart oWASP zafiyetlerini ileri seviyede tespit etme yeteneğini test eder.
* **Kime Hitap Eder:** Web Uygulama Güvenlik Uzmanları ve Bug Bounty avcıları.
* **Sınav Formatı:** 4 saatlik zorlu uygulamalı sınav. 2 farklı web uygulamasını sadece Burp Suite kullanarak "Root" aşamasına getirmelisiniz.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali & Pratik Ekosistemi:** PortSwigger Web Security Academy ana eğitim rotasıdır. "Apprentice" ve "Practitioner" seviyesindeki tüm laboratuvarlar Burp Suite Professional kurularak bitirilmelidir.
  - **Kritik Konular:** Out-of-band (OAST) saldırıları ve karmaşık kimlik doğrulama bypass yöntemleri saniyeler içinde çalıştırılamıyorsa başarı güçtür.

---

## ⚡ Gömülü Sistemler, IoT ve Edge-AI (Embedded & AI)

*👉 Detaylı Harita: [embedded_and_ai/](embedded_and_ai/README.md)*

### 1. NVIDIA DLI Certifications (Deep Learning Institute)
Görüntü işleme ve yapay zeka alanında donanım odaklı geliştirme yapanlar içindir.
* **Nedir:** Bilgisayarlı görü modellerini NVIDIA GPU'ları veya Edge cihazları üzerinde optimize etme yeteneğini ölçer.
* **Kime Hitap Eder:** Yapay zeka mühendisleri, robotik geliştiricileri.
* **Sınav Formatı:** Proje tabanlı uygulamalı değerlendirmeler.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Resmi NVIDIA DLI çevrimiçi laboratuvarları izlenmelidir.
  - **Pratik Ekosistemi:** Fiziksel bir NVIDIA Jetson cihazı (veya GPU destekli Cloud sunucu) kullanılarak "Deployment" testleri yapılmalıdır.
  - **Kritik Konular:** Modelleri TensorRT kullanarak FP16/INT8 standartlarına küçültmek ve GStreamer üzerinde ardışık işlem yolları (pipeline) kurmak ana odaktır.

### 2. Arm Accredited Engineer (AAE)
Donanım mimarisi ve düşük seviyeli (low-level) sistem programlama yetkinliği sertifikaları.
* **Nedir:** Cortex mimarilerini anlama, bellek yönetimi (MMU) ve kesme (interrupt) işleme bilgisini kanıtlar.
* **Kime Hitap Eder:** RTOS geliştiricileri, aygıt sürücüsü geliştiriciler.
* **Sınav Formatı:** Donanım senaryolarını test eden çoktan seçmeli standart sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Arm *Architecture Reference Manual* bültenleri temel akademik kaynaktır.
  - **Pratik Ekosistemi:** Kiel IDE/GCC Toolchain kurularak, STM32 veya NXP geliştirme kartları üzerinde işletim sistemi olmadan (Bare-metal) C veya Assembly pratikleri yapılmalıdır.

---

## 📊 Veri Mühendisliği ve Büyük Veri (Data Engineering)

*👉 Detaylı Harita: [data_engineering/](data_engineering/README.md)*

### 1. Google Cloud Professional Data Engineer
Veri mühendisliği için bulut üzerinde tasarım ve operasyon yetkinliğini belgeler.
* **Nedir:** BigQuery, Dataflow, Dataproc ve Pub/Sub bileşenlerinde entegrasyon kurma yetisini sınar.
* **Kime Hitap Eder:** Veri mühendisleri ve veri mimarları.
* **Sınav Formatı:** 2 saatlik vaka analizleri ve mimari senaryoları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Google Cloud Skills Boost "Data Engineer Learning Path".
  - **Pratik Ekosistemi:** Qwiklabs üzerinde sunulan pratik laboratuvarların tamamlanması ve BigQuery üzerinde şema dağılımlarının test edilmesi.

### 2. Databricks Certified Data Engineer Professional
Apache Spark ekosistemi üzerinde uzmanlık sertifikası.
* **Nedir:** Databricks üzerinde ETL pipeline'ları kurma, Delta Lake optimizasyonu yetkinliğini test eder.
* **Kime Hitap Eder:** İleri seviye veri mühendisleri.
* **Sınav Formatı:** 120 dakika süren, performans veya troubleshooting temalı test sınavı.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Databricks Academy kursları eşzamanlı izlenmelidir.
  - **Kritik Konular:** Spark UI analizi ve "Execution Plan" optimizasyonu yapabilme kabiliyeti geliştirmek temel gereksinimdir.

### 3. Microsoft Certified: Azure Data Engineer Associate (DP-203)
Microsoft kurumsal bulut ağlarında veri hatları (pipeline) tasarlayan mimarlar için birincil sertifikadır.
* **Nedir:** Azure Synapse Analytics, Azure Data Lake Storage Gen2, Azure Databricks ve Azure Data Factory üzerinden hibrit veri dönüşümleri yapılabilmesini test eder.
* **Kime Hitap Eder:** Data Mühendisleri, .NET/Azure ekosistemine entegre çalışan analistler.
* **Sınav Formatı:** Performans senaryoları içeren (laboratuvar simülatörü içerebilir) 120 dakikalık teknik sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Azure Portal üzerinden bir ücretsiz hesap açılarak Azure Data Factory arayüzünde çok yapılı (JSON, CSV, Parquet) verilerin blob ortamları arasında dönüşümleri pratik edilmelidir. Data Factory içindeki kopyalama etkinlikleri ile Data Flow senaryoları simüle edilmelidir.

---

## 🌐 Ağ (Network) ve Telekomünikasyon

*👉 Detaylı Harita: [network_telecom/](network_telecom/README.md)*

### 1. Cisco CCNA (Cisco Certified Network Associate)
Ağ mühendisliğinin global temel standartlarından biri.
* **Nedir:** Yönlendirme, anahtarlama, IP adresleme ve temel otomasyonu kapsar.
* **Kime Hitap Eder:** Network mühendisleri, sistem yöneticileri.
* **Sınav Formatı:** 120 dakikalık CLI laboratuvar simülasyonları ve çoktan seçmeli sorular.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Jeremy's IT Lab kursları veya CCNA Official Cert Guide.
  - **Pratik Ekosistemi:** Cisco Packet Tracer ile VLAN, OSPF topolojileri kurulmalı; IPv4 subnet hesaplaması otomatik hale getirilmelidir.

### 2. Cisco CCNP Enterprise (Cisco Certified Network Professional)
Altyapı mimarisi ve ileri seviye ağ konfigürasyonu sertifikası.
* **Nedir:** BGP, OSPF, SD-WAN, kablosuz ağlar ve hata ayıklama (troubleshooting) senaryolarını içerir.
* **Kime Hitap Eder:** Kıdemli network uzmanları ve ağ mimarları.
* **Sınav Formatı:** Core (ENCOR) ve Concentration olmak üzere çift aşamalı sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** EVE-NG veya GNS3 laboratuvarında Cisco IOS imajları yüklenerek büyük donanım topolojileri kurgulanmalıdır.

### 3. PCNSA (Palo Alto Networks Certified Network Security Administrator)
Yeni nesil güvenlik duvarları (Next-Generation Firewalls) ve güvenlik ilkeleri (Policy) alanında aranan bir akreditasyondur.
* **Nedir:** Kullanıcı bazlı ve uygulama bazlı profil kuralları (App-ID, User-ID) yönetimi yetilerini sınar.
* **Kime Hitap Eder:** Ağ Güvenlik Yöneticileri, SOC seviyesi ağ analistleri.
* **Sınav Formatı:** 80 dakikalık tasarım ve bileşen kurgulama sınavı.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Palo Alto Beacon platformu üzerindeki EDU-210 kursları ana dökümandır.
  - **Pratik Ekosistemi:** Palo Alto Networks VM-Series NGFW imajlarını bir EVG-NG platformuna yükleyerek gerçek bir web filtreleme ve loglama (Traffic Logs) işlemi simüle edilmelidir.

---

## 🏗️ Yazılım Mimarisi ve Geliştirme (Software Architecture)

*👉 Detaylı Harita: [software_architecture/](software_architecture/README.md)*

### 1. Oracle Certified Professional: Java SE 17 / 21 Developer
Java dilinin mimari ve nesne yönelimli standartlarını ölçen sertifika.
* **Nedir:** Java'nın bellek yönetimi, concurrency/multithreading özelliklerini yetkin düzeyde ölçer.
* **Kime Hitap Eder:** Backend geliştiricileri, yazılım mühendisleri.
* **Sınav Formatı:** 90 dakikalık karmaşık kod analizi soruları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** IDE hata ayıklama ve otomatik tamamlamaları kapatılmalı. Kod metin editöründe izlenip derlenmelidir.
  - **Kritik Konular:** Enthuware deneme sınavlarındaki JVM analizleri dikkatle okunmalıdır.

---

## ☁️ Bulut Bilişim ve DevOps (Cloud & DevOps)

*👉 Detaylı Harita: [cloud_devops/](cloud_devops/README.md)*

### 1. AWS Certified Solutions Architect - Professional
AWS üzerinde karmaşık ve büyük ölçekli mimariler tasarlama yeterliliği belgesi.
* **Nedir:** Hibrit bulut ortamları tasarlama, yüksek erişilebilirlik sağlama mimarisi testidir.
* **Kime Hitap Eder:** Kıdemli bulut mimarları.
* **Sınav Formatı:** 180 dakikalık çok yoğun senaryo analizleri.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Adrian Cantrill veya Stephane Maarek platformları ve resmi çalışma rehberleri incelenmelidir.
  - **Pratik Ekosistemi:** TutorialsDojo üzerinden pratik senaryolar süre bazlı çözülerek analiz edilmelidir.

### 2. CKA (Certified Kubernetes Administrator)
Sistem yönetimi ve mikroservis dağıtımı konusunda yaygın endüstri standardı sertifikadır.
* **Nedir:** Konteyner orkestrasyonunda kümelenme kurulumu, bakım ve sorun giderme standartlarını belgeler.
* **Kime Hitap Eder:** DevOps mühendisleri, SRE'ler.
* **Sınav Formatı:** 2 saatlik, **%100 uygulamalı** terminal tabanlı sınavdır.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** KodeKloud üzerindeki laboratuvarlar eşliğinde çalışılıp, Killer.sh simülatöründe geçiş puanı (passing score) yakalanmalıdır. 
  - **Kritik Konular:** Terminal üzerinde `kubectl dry-run` kullanımı tam anlamıyla ezberden, hızlıca gerçekleştirilebilir olmalıdır.

### 3. Red Hat Certified System Administrator (RHCSA)
DevOps temellerini atan, gerçek dünyadaki sunucu komut satırı yeteneklerinin teyit edildiği sertifikadır.
* **Nedir:** Red Hat Enterprise Linux (RHEL) üzerinde ağ, diskin LVM konfigürasyonları, kullanıcı izinleri ve log analiz gibi operasyonları değerlendirir.
* **Kime Hitap Eder:** Sistem Yöneticileri, Bulut ve DevOps tarafına ilerlemek isteyen herkes.
* **Sınav Formatı:** İnternet erişimsiz, tamamıyla uygulamalı süren ~3 saatlik terminal sınavıdır. (Birden fazla bozuk veya boş makine terminali verirler)
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Sander van Vugt RHCSA kitapları ve eğitim videoları birincil kaynaktır.
  - **Pratik Ekosistemi:** Sanal makine üzerinde bir veya birden fazla CentOS stream ya da RHEL çalıştırıp; komutlara (`nmcli`, `fdisk` / `parted`, `LVM`) hiç dokümantasyon bakmadan anında cevap erecek noktada alıştırma yapılmalıdır.

### 4. AWS Certified DevOps Engineer - Professional
DevOps yaşam döngüsü operasyonlarının AWS spesifik CI/CD araçları ile uygulanmasını hedefler.
* **Nedir:** AWS CloudFormation, CodePipeline, CodeBuild vasıtasıyla "Sıfır Kesintili Yükseltme" (Blue/Green, Canary) taktiklerini ölçer.
* **Kime Hitap Eder:** Site Reliability Engineer (SRE) rolleri, Kıdemli DevOps mimarları.
* **Sınav Formatı:** Kurumsal bulut kurgularında dağıtım problemlerini çözmeyi de içeren 180 dakikalık kavramsal sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** AWS'de CodePipeline kurarak kişisel repo entegrasyonuyla CI/CD çalıştırılmalı ve otomatik ölçeklendirme gruplarının davranışları (Auto Scaling Lifecycle Hooks) mutlaka canlı test edilerek incelenmelidir.

---

## 🤝 Nasıl Katkıda Bulunurum?
Bu repo açık kaynaklı bir referans listesi projesidir. Siz de yeni bir sertifika başlığı veya güncel bir bilgi eklemek isterseniz detaylar için `CONTRIBUTING.md` dosyasına göz atabilirsiniz.