# ☁️ Bulut Bilişim ve DevOps Roadmap

Esneklik, maliyet optimizasyonu, otomatik ölçeklendirme platformları ve sürekli entegrasyon (CI/CD) mekanizmalarında uzmanlık geliştirmeyi hedefleyen standartlar bütünüdür.

## 📌 Sertifikasyon Haritası

### 1. AWS Certified Solutions Architect - Professional
AWS ortamında esnek, erişilebilir ve optimal maliyetli kurumsal teknoloji mimarileri kurgulanmasını belgeler.
* **Detay:** Mimarı süreçte Route53, Transit Gateway gibi servislerin geniş alan senaryoları tasarımlarını ve iş gereksinimlerine göre en uygun servis dağılımını (deployment) test eder.

### 2. CKA (Certified Kubernetes Administrator)
Konteynerli yapıların (container orch.) yönetim merkezi olan Kubernetes ortamında uzmanlığı belgeler.
* **Detay:** Tamamen performansa (hands-on) dayalı terminal tabanlı bir sınav olup, sunulan senaryolara göre bir cluster kurulumunu/tamirini talep eder.

### 3. HashiCorp Certified: Terraform Associate
Infrastructure-as-Code (IaC) pratiklerinin önemli aracı Terraform üzerinde işlevsel yetkinlik değerlendirmesi yapar.
* **Detay:** Terraform işleyiş mekanizması, syntax (HCL) beklentileri, durum dosyası (state file) ve modüller üzerinden değerlendirmeler sunar.

---

## 🔥 Uygulamalı Pratik (CI/CD & IaC)

Sistem yönetiminin standart süreçleri otomasyon ile optimize edilir:

### 1. Kod Temelli Altyapı (Infrastructure as Code - IaC)
- **Terraform:** Manuel yapılandırma gereksinimlerini kod üzerinden modüler olarak devreye alan altyapı otomasyon aracı.
- **Ansible:** Sunucular üzerinde uygulanan yapılandırmaların ve uygulama yüklemelerinin durum (state-based) ve YAML formatlarına bağlanması.

### 2. Sürekli Entegrasyon & Dağıtım (CI/CD)
- **GitHub Actions / GitLab CI:** Kod versiyonlama platformlarına tanımlanan kurallar serisiyle sürüm kontrol testleri (Unit tests vb.) ve yayın otomasyonu yürütmek.
- **ArgoCD:** Kubernetes kaynaklarının versiyon saklanan uzak bir reponun durumu ile otomatik senkronizasyonunu sağlayan GitOps felsefeli platform.
