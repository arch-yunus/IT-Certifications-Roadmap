# 🌐 Ağ (Network) ve Telekomünikasyon Masterclass Roadmap

Bulut, siber güvenlik veya gömülü sistemler... Hiçbiri ağ mimarisi olmadan çalışamaz. Ağ mühendisliği sadece kablo takmak değil, altyapıyı güvenli, ölçeklenebilir ve otomatik hale getirmektir.

## 📌 Sertifikasyon Haritası

### 1. Cisco CCNA (Cisco Certified Network Associate)
Ağ alfabesi. OSPF, VLAN, Subnetting ve otomasyon temel bilgilerini ölçen "olmazsa olmaz" sertifika.
* **Detay:** Router komut satırı (CLI) üzerinden sizi gerçek ağ topolojilerinde test eder.

### 2. Cisco CCNP Enterprise (Cisco Certified Network Professional)
Mimari tasarım seviyesi. Sistemleri entegre etmek ve kurumsal BGP, SD-WAN, Wireless tasarım ile yoğurmak.
* **Detay:** Bozulan bir altyapıyı Cisco IOS/IOS-XE komut satırından arıza kaydıyla (troubleshooting) bulma sanatı.

### 3. JNCIS / JNCIP (Juniper Networks Certified Specialist/Professional)
İnternet servis sağlayıcıları (ISP) ve dev veri merkezlerinde yönlendirme yapan ağ mimarları için Cisco'nun doğrudan ağır sıklet rakibi.
* **Detay:** Junos OS üzerinde mimari yapılanma ve yoğun BGP konfigürasyonu ölçülür.

---

## 🌩️ Laboratuvar Simülasyonu ve Network Otomasyonu

Bir ağ mühendisi fiziksel cihazlarla kısıtlı kalmaz; sistemi kodla test eder.

### Gerekli Sanallaştırma Ortamları
- **EVE-NG:** Sektörün en "Heavy-weight" sanal ağ laboratuvarı. Gerçek Cisco, Juniper ve Fortinet imajlarını içe aktarıp BGP laboratuvarları kurgulayabilirsiniz.
- **GNS3:** Kurulumu daha hafif, ancak mimari testlerde (Python Docker container'larını ağa entegre etme) muazzam esnek.

### Network Automation (NetDevOps)
Modern çağda `ssh` ile cihaz yapılandırmak devri kapanıyor. Otomasyon bilmeyen bir ağ mühendisi elenecektir:
- **Ansible & Netmiko:** Yüzlerce switch ve router konfigürasyonunu bir tek `yaml` dosyası ve Python scriptinden yürütmek.
- **YANG & NETCONF/RESTCONF:** Ağ cihazlarını "API üzerinden" JSON/XML verisi ile nesne tabanlı kontrol etme pratiği.
