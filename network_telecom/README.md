# 🌐 Ağ (Network) ve Telekomünikasyon Roadmap

Altyapı otomasyonu, yönlendirme (routing), anahtarlama (switching) ve yazılım tanımlı ağ yapıları (SDN) konularına profesyonelleşmek isteyen uzmanlar için derlenmiştir.

## 📌 Sertifikasyon Haritası

### 1. Cisco CCNA (Cisco Certified Network Associate)
Ağ mühendisliğinde global temel kabul edilen başlangıç seviyesi sertifikasıdır.
* **Detay:** Teorik bilgiyi ve temel CLI (Komut Satırı Arayüzü) kullanımını router ve switch konfigürasyon senaryolarında sınar. OSPF, VLAN yapısı gibi konuları ele alır.

### 2. Cisco CCNP Enterprise (Cisco Certified Network Professional)
Gelişmiş yönlendirme senaryoları ve entegrasyonlar sağlayan ileri seviye ağ uzmanlığı sertifikasıdır.
* **Detay:** İki ayrı sınav birleşiminden oluşur. BGP, SD-WAN, Wireless tasarım ve ağ cihazlarında hata tespiti (troubleshooting) üzerine yoğunlaşır.

### 3. JNCIS / JNCIP (Juniper Networks Certified Specialist/Professional)
İnternet servis sağlayıcıları (ISP) ve veri merkezlerinde ağ yöneticiliği yapan mühendisler için Juniper tarafındaki yetkinlik sertifikalarıdır.
* **Detay:** Junos OS üzerinde BGP ve yoğun yapılandırma gerektiren altyapı yetkinliklerini değerlendirir.

---

## 🌩️ Laboratuvar Simülasyonu ve Ağ Otomasyonu

Mevcut ağ mimarisinde manuel donanım kurulumlarının haricinde simülasyon araçları ve otomasyon teknikleri öne çıkmaktadır.

### Sanallaştırma Ortamları
- **EVE-NG:** Sektörde çoklu platform (Cisco, Juniper, Fortinet vb.) sanallaştırması yapabilen gelişmiş bir sanal ağ laboratuvarı yazılımı.
- **GNS3:** Kurulum esnekliği ve çeşitli cihaz emülasyonlarını sağlayan diğer yaygın geliştirme ortamıdır.

### Network Automation (NetDevOps)
Modern ağ yönetiminde geliştirilen pratikler:
- **Ansible & Netmiko:** Açık kaynaklı otomasyon modülleriyle birçok ağ cihazının konfigürasyonunun merkezileştirilmesi.
- **YANG & NETCONF/RESTCONF:** Ağ cihazlarını geleneksel CLI erişimi yerine programlanabilir (API tabanlı) bir model olan JSON/XML şemaları ile kontrol etmek.
