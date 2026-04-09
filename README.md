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
* **Nedir:** Risk yönetimi, bilgi güvenliği temelleri, olay müdahalesi (incident response) ve şifreleme formasyonlarının çerçevesini çizer.
* **Kime Hitap Eder:** Güvenlik alanına ilk adım atanlar, sistem ve ağ yöneticileri (Örn: DoD gereksinimleri).
* **Sınav Formatı:** 90 dakikalık, en fazla 90 soruluk interaktif (PBQ) ve çoktan seçmeli test.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Professor Messer'in video seti ana kaynak olarak kabul edilir.
  - **Pratik Ekosistemi:** Jason Dion deneme sınavlarıyla interaktif laboratuvar sorularına aşinalık kazanmak gereklidir.

### 2. OSCP (Offensive Security Certified Professional)
Sektörün en saygı duyulan, laboratuvar temelli sızma testi (penetration testing) sertifikasıdır.
* **Nedir:** Hedef makineler üzerinde sızma testleri gerçekleştirilmesini bekler.
* **Kime Hitap Eder:** Güvenlik uzmanları ve Red Team üyeleri.
* **Sınav Formatı:** **24 saatlik pratik sınav.** Belirtilen makineler ele geçirilip 24 saat içinde raporlanmalıdır.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** PEN-200 kursu ve laboratuvarları birincil kaynaktır.
  - **Pratik Ekosistemi:** TJ_Null "OSCP benzeri makineler" listesi çözülmeli; Privilege Escalation (Hak Yükseltme) ve Active Directory konularına yoğunlaşılmalıdır.

### 3. OSEP (Offensive Security Experienced Penetration Tester)
İleri seviye penetrasyon testi standartlarını belirler. (AV/EDR atlatma odaklıdır).
* **Nedir:** Antivirüs atlatma, gelişmiş AD saldırıları ve sistem güvenlik açıklarını sömürme uzmanlığını belgeler.
* **Kime Hitap Eder:** Kıdemli Red Team uzmanları.
* **Sınav Formatı:** **48 saatlik pratik sınav.**
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** PEN-300 kurs dokümanları üzerinde çalışılmalıdır.
  - **Pratik Ekosistemi:** Kendi ortamınızda bir Active Directory labı kurup, C# / PowerShell üzerinden in-memory zararlı kod enjeksiyonları (API Hooking vd.) test edilmelidir.

### 4. CISSP (Certified Information Systems Security Professional)
Bilgi güvenliği yöneticiliği ve mimarisi alanında altın standart sertifikadır.
* **Nedir:** Siber güvenliğin teknik işleyişi kadar mimari denetimini, güvenli yazılım geliştirme döngüsünü ve risk yönetimini test eder.
* **Kime Hitap Eder:** CISO adayları, kıdemli danışmanlar.
* **Sınav Formatı:** 4 saatlik adaptif uzlaşma (CAT) sisteminde maksimum 175 soru.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Eğitim Materyali:** Sybex CISSP Official Study Guide tam anlamıyla ezberlenmeli ve süreç odaklı ("Yönetici Zihniyeti") analiz becerisi geliştirilmelidir.

### 5. CISM (Certified Information Security Manager)
ISACA tarafından verilen ve tamamen kurumsal güvenlik yönetimine odaklanan C-Level sertifikadır.
* **Nedir:** Olay yönetimi (incident management) ve güvenlik programının iş haritasıyla uyumlanmasını ölçer. CISSP'in daha yönetim odaklı varyasyonudur.
* **Kime Hitap Eder:** Güvenlik yöneticileri, uyumluluk (compliance) uzmanları.
* **Sınav Formatı:** 4 saat, 150 çoktan seçmeli senaryo sorusu.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Resmi ISACA "QAE (Questions, Answers & Explanations)" veri tabanı üzerinden şirket kültürüne uyumlu (Governance odaklı) kararlar alabilme mantığı oturtulmalıdır.

### 6. BSCP (Burp Suite Certified Practitioner)
Web uygulama güvenliğine odaklı %100 uygulamalı bir laboratuvar sınavıdır.
* **Nedir:** OWASP zafiyetlerini (SQLi, XSS, SSRF vb.) gelişmiş senaryolarda tespit yeteneğini ölçer.
* **Kime Hitap Eder:** Web Uygulama Güvenlik Uzmanları ve Bug Bounty avcıları.
* **Sınav Formatı:** 4 saatlik uygulamalı sınav; iki web uygulamasının yetkilerini kırmak hedeflenir.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** PortSwigger Web Security Academy ana çalışma dizinidir. "Practitioner" seviyesindeki araçlar ve OAST (Out-of-band) bypass taktikleri çalışılmalıdır.

---

## ⚡ Gömülü Sistemler, IoT ve Edge-AI (Embedded & AI)

*👉 Detaylı Harita: [embedded_and_ai/](embedded_and_ai/README.md)*

### 1. NVIDIA DLI Certifications (Deep Learning Institute)
Derin öğrenme modellerinin donanım düzeyinde çalıştırılması standartlarını tanımlar.
* **Nedir:** Bilgisayarlı görü (CV) modellerini Edge cihazlarda optimize etme yeteneğini ölçer.
* **Kime Hitap Eder:** Yapay zeka mühendisleri, robotik sistem mimarları.
* **Sınav Formatı:** Proje tabanlı model dağıtım senaryoları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Modelleri "TensorRT" ile kuantize etmek (FP16/INT8) ve NVIDIA Jetson/Cloud GPU'ları üzerinde çıkarım (Inference) yapmak ana hazırlık evresidir.

### 2. Arm Accredited Engineer (AAE)
Düşük seviyeli (low-level) sistem ve işlemci programlama sertifikasıdır.
* **Nedir:** Cortex mimarilerinde bellek yönetimi (MMU), kesme işlemleri (interrupt) fonksiyonlarını test eder.
* **Kime Hitap Eder:** RTOS geliştiricileri, SoC yazılımcıları.
* **Sınav Formatı:** Çoktan seçmeli sistem analizi ve donanım senaryosu soruları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Kiel IDE/GCC ile mikrodenetleyiciler üzerinde (Örn: STM32) işletim sistemsiz ortamda "Bare-metal" programlama pratikleri yapılmalıdır.

### 3. AWS Certified Machine Learning – Specialty
Algoritmaların bulut bilişim ekosistemleriyle ve donanımlarla buluşma noktasıdır.
* **Nedir:** Veri mühendisliği (Data Engineering), keşifsel analiz (EDA), modelleme ve Amazon SageMaker entegrasyonlarını ölçer.
* **Kime Hitap Eder:** MLOps mimarları, kurumsal AI uzmanları.
* **Sınav Formatı:** Makine öğrenimi algoritmaları optimizasyonlarına dayalı 180 dakikalık senaryo sınavı.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Sagemaker üzerinde model dağıtımı ve VPC yapısıyla güvenli API "Endpoint" açma gibi pratik AWS senaryoları tasarlanmalıdır.

### 4. CompTIA Linux+ / LPIC-1
Embedded (gömülü) dağıtımların ve işletim sistemlerinin can damarı Linux altyapısıdır.
* **Nedir:** Linux sistem mimarisi, ağ ayarları, güvenlik (SELinux) ve shell scripting yeteneğini kanıtlar.
* **Kime Hitap Eder:** Gömülü Linux (Yocto/Buildroot) geliştirenler, Sistem Yöneticileri.
* **Sınav Formatı:** Komut sonuçlarını veya parametrelerini ölçen uygulamalı yapılandırma soruları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Fiziksel bir Debian ya da Red Hat cihazda (ya da Raspberry Pi üzerinde) bash betikleri hazırlayıp, LVM ve Systemd dosya yapılandırmalarını dökümantasyon kurcalayarak çözümlemek şarttır.

---

## 📊 Veri Mühendisliği ve Büyük Veri (Data Engineering)

*👉 Detaylı Harita: [data_engineering/](data_engineering/README.md)*

### 1. Google Cloud Professional Data Engineer
Veri mimarilerini Google Cloud araç seti etrafında kurgulayan ve bu mimarileri tasarlayan uzmanlar içindir.
* **Nedir:** Dataproc, Dataflow ve BigQuery ile esnek pipeline kurgularını sınar.
* **Kime Hitap Eder:** Veri mühendisleri ve mimarları.
* **Sınav Formatı:** 2 saatlik vaka analizleri ve senaryo mimarisi.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Qwiklabs görevleri ve BigQuery üzerinde şema dağılımlarının (Partitioning ve Clustering) test edilmesi.

### 2. Databricks Certified Data Engineer Professional
Apache Spark ekosistemi spesifikasyonunda büyük veri uzmanlık sertifikasıdır.
* **Nedir:** Databricks üzerinde ETL ardışık düzenleri (pipelines) tasarlama, Delta Lake konfigürasyonunu test eder.
* **Kime Hitap Eder:** İleri seviye big data mühendisleri.
* **Sınav Formatı:** 120 dakika, performans ve "troubleshooting" temalı 60 analiz sorusu.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Spark Web UI arayüzünden "Execution Plan" optimizasyonunu analiz etmek zorunlu bir beceridir.

### 3. Microsoft Certified: Azure Data Engineer Associate (DP-203)
Microsoft ekosisteminde entegre veri dönüştürme sistemleri tasarlamayı doğrular.
* **Nedir:** Azure Data Factory ve Azure Synapse ile çok kaynaklı veri akışlarının kurgulanması.
* **Kime Hitap Eder:** .NET ve Azure kurumsal ekosistemi Data Mühendisleri.
* **Sınav Formatı:** 120 dakikalık interaktif vaka analizi soruları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Azure Portal üzerinden Data Factory arayüzünde "Data Flow" (T Dönüşüm aşaması) işlemleri ve Synapse Analytics pratikleri gerçekleştirilmelidir.

### 4. Snowflake SnowPro Core Certification
Modern bulut tabanlı veri ambarı (Data Warehouse) olan Snowflake konseptinin operasyonel sertifikasıdır.
* **Nedir:** Snowflake veri kopyalama (cloning), "Time Travel", paylaşımlı erişim ve maliyet optimizasyonu standartlarını değerlendirir.
* **Kime Hitap Eder:** Veri Analistleri, Bulut Veri Mimarları.
* **Sınav Formatı:** 115 dakika, 100 soru.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Snowflake'in kendi dokümantasyonu eşliğinde ücretsiz bir instance açarak sanal "Warehouse" küme boyutlarının query (sorgu) performansı üzerindeki farklılıkları saniyeler cinsinden canlı test edilmelidir.

---

## 🌐 Ağ (Network) ve Telekomünikasyon

*👉 Detaylı Harita: [network_telecom/](network_telecom/README.md)*

### 1. CompTIA Network+
Marka bağımsız, giriş-orta seviye ağ topoloji ve protokollerini temellendiren endüstri sertifikası.
* **Nedir:** OSI Modeli katmanları, TCP/IP yönlendirmeleri, Wi-Fi standartları ve subnetting temellerini oluşturur.
* **Kime Hitap Eder:** Yeni başlayan network teknisyenleri, HelpDesk uzmanları.
* **Sınav Formatı:** İnteraktif ve senaryo temelli (PBQ) 90 çoktan seçmeli soru.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Kavramların temel network kitaplarından okunması ve Packet Tracer üzerinde küçük topolojiler kurgulanması kafadaki IP hiyerarşisini netleştirecektir.

### 2. Cisco CCNA (Cisco Certified Network Associate)
Endüstri lideri Cisco ortamının başlangıç anahtarıdır.
* **Nedir:** Yönlendirme ve anahtarlama standartlarını, OSPF, VLAN gibi protokollerle Cisco CLI üstünde yürütmeyi test eder.
* **Kime Hitap Eder:** Orta seviye Network Analistleri.
* **Sınav Formatı:** 120 dakikalık CLI simülasyonları ve çoktan seçmeli sorular.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Cisco Packet Tracer ile laboratuvar ortamları simüle edilmeli ve subnetting işlemleri için refleks kazandırılmalıdır.

### 3. Cisco CCNP Enterprise (Cisco Certified Network Professional)
Altyapı tasarımı ve enterprise düzeyde hata teşhisi ve giderme ustalık sertifikasıdır.
* **Nedir:** BGP komşulukları, SD-WAN entegrasyonu, kablosuz altyapı dağıtımları gibi konuları kapsar.
* **Kime Hitap Eder:** Kıdemli network yöneticileri.
* **Sınav Formatı:** İki aşamalı (Core + Concentration sınavı) ağırlıklı laboratuvar sınavları bütünü.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** EVE-NG ortamında Cisco IOS (Örn: IOL imajları) yüklenerek büyük donanım topolojileri kurgulanmalıdır.

### 4. PCNSA (Palo Alto Networks Certified Network Security Administrator)
Yeni nesil güvenlik duvarları (NGFW) ve sıfır güven (Zero Trust) politikalarının konfigürasyon belgesi.
* **Nedir:** Kullanıcı bazlı ve uygulama bazlı profil kuralları yönetiminin Palo Alto platformunda uygulanması.
* **Kime Hitap Eder:** Güvenlik Duvarı Mühendisleri (Firewall Engineers).
* **Sınav Formatı:** 80 dakikalık altyapı kurgusu sınavı.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** EVE-NG ortamına kurulan VM-Series (Palo Alto Firewall) üzerinden trafik loglamaları, SSL dekripsiyon ve Policy (Kural) yapılandırmaları pratiğe dökülmelidir.

### 5. F5 Certified BIG-IP Administrator (F5-CA)
Devasa web servislerinin Load Balancer (Yük Dengeleme) ve ADC (Application Delivery Controller) yönetimleri tasdikidir.
* **Nedir:** Gelen trafiğin sunuculara (node/pool) algoritmalara göre dağıtılması ve temel L4/L7 korumasını ölçer.
* **Kime Hitap Eder:** Veri Merkezi ve Telekomünikasyon Yöneticileri.
* **Sınav Formatı:** TMOS (Traffic Management OS) GUI ve CLI bazlı mimari test.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Sanal ağınızda "F5 BIG-IP Virtual Edition" çalıştırarak iki web sunucusu (Örn: Apache) arasında 'Round Robin' (trafik dengeleme) algoritmasını denemek temel prensipleri çözmenizi sağlar.

---

## 🏗️ Yazılım Mimarisi ve Geliştirme (Software Architecture)

*👉 Detaylı Harita: [software_architecture/](software_architecture/README.md)*

### 1. Oracle Certified Professional: Java SE 17 / 21 Developer
Java dilinin standart kütüphaneleri, çalışma mantığı (JVM) üzerinde akademik düzey testidir.
* **Nedir:** Concurrency, Garbage Collection gibi performans metriklerini kod seviyesinde ele alır.
* **Kime Hitap Eder:** Backend yazılım mühendisleri.
* **Sınav Formatı:** 90 dakikalık kod parçası okuma (IDE imkanı olmaksızın derleyici hatası arama) soruları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Enthuware veri tabanındaki uç (trick) sorular incelenip hata ayıklama kod metinlerinde satır satır hesaplanmalıdır.

### 2. AWS Certified Developer – Associate
Uygulama geliştiricileri için doğrudan bulut servisleriyle entegrasyonu (SDK, Lambda) standartlaştıran sertifikadır.
* **Nedir:** Düz bir sunucu kodlamak yerine Serverless (AWS Lambda, API Gateway) ve asenkron veri erişimi (DynamoDB) servisleriyle native uygulamalar tasarlamayı test eder.
* **Kime Hitap Eder:** Bulut tabanlı yazılım geliştiren Backend ekipleri.
* **Sınav Formatı:** 130 dakikalık uygulama mimarisi odaklı API / Kod çoktan seçmeli testi.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** AWS üzerinde Python Boto3 (veya JavaScript/Java AWS SDK) uçları kullanarak S3 ve DynamoDB üzerinde IAM rollerine dayalı operasyonlar yazılmalı ve AWS CLI etkin şekilde kullanılmalıdır.

### 3. TOGAF 9 Certified (The Open Group Architecture Framework)
Kurumsal (Enterprise) düzey organizasyonların "Tüm sistemlerimiz nasıl dönüşecek?" sorusunu yanıtlayan global IT Mimarlık sertifikasıdır.
* **Nedir:** Kod yazmaktan çok, yüzlerce bileşeni olan organizasyonları hizalamaya yarayan bir "mimari döngü (Architecture Development Method - ADM)" metodolojisini sorgular.
* **Kime Hitap Eder:** Kurumsal Mimarlar (Enterprise Architects), CTO adayları.
* **Sınav Formatı:** Vakaları çerçeve içinde yorumlamayı gerektiren Part 1 (Foundation) ve Part 2 (Certified) karma sınavları.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Kod pratiklerinin yerini UML diyagramları, paydaş yönetim senaryoları ve stratejik iş planı analiz şablonları okumaları alır. The Open Group resmi dokümanları referanstır.

---

## ☁️ Bulut Bilişim ve DevOps (Cloud & DevOps)

*👉 Detaylı Harita: [cloud_devops/](cloud_devops/README.md)*

### 1. AWS Certified Solutions Architect - Professional
Bulut mimarilerinde çoklu bileşenlerin (hibrit cloud, security, maliyet) uçucu durumlara göre entegrasyon belgesidir.
* **Nedir:** İş gereksinimine özgü esnek, yüksek erişilebilir dağıtım (deployment) stratejileri testidir.
* **Kime Hitap Eder:** Kıdemli bulut mimarları.
* **Sınav Formatı:** Son derece zorlayıcı, uzun paragraflarla ve senaryolarla dolu 180 dakikalık sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Adrian Cantrill eğitimleri ile TutorialsDojo sınav simülatörü ikilisi üzerinden çalışma temposunu tutturmak önceliklidir.

### 2. CKA (Certified Kubernetes Administrator)
Konteyner orkestrasyon mekanizması Kubernetes üzerinde arıza tespit (troubleshooting) ve kümeye (cluster) bakım sertifikasıdır.
* **Nedir:** Bozulmuş bir sistemin çalışır konuma getirilmesi gibi tamamen pratik yeteneği sınar.
* **Kime Hitap Eder:** Kubernetes yöneticileri, SRE uzmanları.
* **Sınav Formatı:** Terminal üzerinden uygulanan iki saatlik pratik sınav.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Killer.sh simülatör puanı garantisine kadar terminaldeki `kubectl` objelerinin hızlıca tetiklenmesi çalışılmalıdır.

### 3. CKAD (Certified Kubernetes Application Developer)
Ortamı yöneten (Admin) yerine, ortam içine pod ve servis dağıtan (Deploy) geliştirici spesifikasyonudur.
* **Nedir:** Uygulama sağlık kontrollerini (Liveness/Readiness Probes), Secrets / ConfigMaps gibi değişkenlerin Pod'lara empoze edilmesini ölçer.
* **Kime Hitap Eder:** DevOps Ekipleri, Backend Yazılımcılar.
* **Sınav Formatı:** 2 Saatlik komut satırı (terminal) pratiği. Terminalden kopyalama/yapıştırma ve YAML düzeltmeleri (Indentler vs.) ölçülür.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** KodeKloud eğitim ortamları üzerinden Kubernetes dokümantasyonlarından arama yaparak (`yaml` snippetleri kopyalayarak) süreyi optimize etmek ana hedeftir.

### 4. Red Hat Certified System Administrator (RHCSA)
Sektörün tartışmasız en geçerli System Admin sertifikasıdır. DevOps felsefesine atılan güçlü bir pratik Linux temeli.
* **Nedir:** Gerçek makineler (RHEL ortamı) üzerinde depolama (LVM), kullanıcı izni (ACL), ağ yönetimi ve dosya sistemi konfigürasyonu yapabilmeyi ölçer.
* **Kime Hitap Eder:** Sistem yöneticileri ve DevOps ekipleri.
* **Sınav Formatı:** Uygulamalı (İnternetsiz) terminal sınavı. "Sistem parolası kilitlenmiş bir makineye eriş, izinleri düzenle" yaklaşımı barındırır.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Sanal bir makine üzerinde Sander van Vugt RHCSA doküman pratikleri (`nmcli`, `fdisk`, `tar`, `systemctl`) hiçbir kaynağa bakmadan hızla gerçekleştirilmelidir.

### 5. AWS Certified DevOps Engineer - Professional
DevOps sürekli entegrasyon ve otomasyon araç setlerinin (CI/CD) tüm AWS kaynaklarıyla uyumlu yönetilmesini ölçer.
* **Nedir:** CodePipeline entegrasyonu, yüksek trafik ölçekleme grupları (Auto-Scaling Lifecycle) ve CloudFormation betik formatlarını denetler.
* **Kime Hitap Eder:** Kıdemli SRE mimarları, Cloud otomasyon uzmanları.
* **Sınav Formatı:** Mimarının otomatikleşmesine dayalı vaka analizlerin sorulduğu üst düzey bir teori/pratik testidir.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** AWS üzerinde manuel kurulum bırakılarak; örnek bir React uygulamasını S3 ve CloudFront'a GitHub bağlantılı (CodeBuild/CodePipeline devrede) bir otomasyon scripti ile yayınlamak sınav felsefesini özetler.

### 6. Microsoft Certified: DevOps Engineer Expert (AZ-400)
Azure ekosistemi ve GitHub konseptleriyle bütünleşik üst düzey DevOps standardı.
* **Nedir:** Azure DevOps, Boards, Repos, Pipelines ve ArgoCD/GitOps standartlarının yönetimine ve "Sürekli Geri Bildirim" ölçümlerine (telemetry) odaklanır.
* **Kime Hitap Eder:** Azure odaklı ekiplerde kıdemli DevOps mimarları.
* **Sınav Formatı:** Azure portalı simulasyonunu da kapsayabilen karmaşık CI/CD analizleri.
* **Kapsamlı Hazırlık Yöntemi:**
  - **Pratik Ekosistemi:** Azure Pipelines kullanılarak (yaml formatında) ARM şablonları dağıtan Release takvimleri programlamak gereklidir.

---

## 🤝 Nasıl Katkıda Bulunurum?
Bu repo açık kaynaklı bir referans listesi projesidir. Siz de yeni bir sertifika başlığı veya güncel bir bilgi eklemek isterseniz detaylar için `CONTRIBUTING.md` dosyasına göz atabilirsiniz.