# ☁️ Bulut Bilişim ve DevOps Masterclass Roadmap

Bulut bilişim, bir sunucuyu internete açmak değil; esnek, otomatik ve maliyet/performans ekseninde hatasız mimariler tasarlamaktır. DevOps ise bu mimariyi sürekli çalışır ve entegre (CI/CD) tutma sanatıdır.

## 📌 Sertifikasyon Haritası

### 1. AWS Certified Solutions Architect - Professional
Bulut dünyasında milyar dolarlık akışların yönetildiği, AWS üzerinde birden fazla ekosistemin birbiriyle nasıl konuştuğunu tasarlayan mimarların zirvesi.
* **Detay:** Meta-Engineering çapında geniş düşünme; Route53, Transit Gateway, Direct Connect kullanım senaryoları.

### 2. CKA (Certified Kubernetes Administrator)
Otomasyonun ve mikromimarinin kalbi kubernetes'in efendilerine.
* **Detay:** %100 uygulamalı. Çökmüş bir pod ekosistemini uzak bir terminalden düzeltmeniz istenir.

### 3. HashiCorp Certified: Terraform Associate
Infrastructure-as-Code (Kod olarak altyapı) konseptinin tartışmasız lideri olan Terraform üzerine yetkinlik.
* **Detay:** State yönetimi, modüler altyapı mimarisi ve deklaratif syntax hakimiyeti.

---

## 🔥 Gerçek Dünyada DevOps (CI/CD & IaC)

Sınavlar vizyon katar, ancak pratik şirketleri ayakta tutar.

### 1. Kodlanmış Altyapı (Infrastructure as Code - IaC)
Mühendis AWS paneline tıklayarak makine açmaz; kodu tetikler:
- **Terraform:** Hangi bulut sağlayıcısı (AWS, GCP, Azure) olursa olsun mimariyi `HCL` koduyla ayağa kaldırma.
- **Ansible:** Ayağa kalkan makinelerin içine gerekli araçları `yaml` kodları ile kurarak otomasyonu mühürleme.

### 2. Sürekli Entegrasyon & Dağıtım (CI/CD)
"Benim bilgisayarımda çalışıyordu, sunucuda çalışmıyor" sözü tarihe karıştı:
- **GitHub Actions / GitLab CI:** Koda yazılan her `push` işlemi sonrası otomatik Unit Testlerin ve Build adımlarının çalıştırılması.
- **ArgoCD:** GitOps felsefesiyle, Kubernetes cluster'ının GitHub reposuyla otomatik olarak senkronize edilip kendini tamir etmesi.
