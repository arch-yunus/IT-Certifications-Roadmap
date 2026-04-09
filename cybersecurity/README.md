# 🛡️ Siber Güvenlik (Cybersecurity) Masterclass Roadmap

Bu dizin, teorik "çoktan seçmeli" sınavları geride bırakıp, siber güvenlikte kan dondurucu **"hands-on"** yetkinliği arayan güvenlik uzmanlarına adanmıştır.

## 📌 Sertifikasyon Haritası

### 1. eJPT (eLearnSecurity Junior Penetration Tester)
Sektöre giriş yapmak isteyenler için "hands-on" pratik yetkinliğini kanıtlayan başlangıç noktası.
* **Detay:** Teoriyi değil, nmap, metasploit, burp suite ile ağ üzerinde temel sızma pratiklerini test eder. 48 saatlik VPN lab deneyimidir.

### 2. OSCP (Offensive Security Certified Professional)
Sektörün altın standardı. "Try harder" felsefesiyle Red Team için kutsal kasedir.
* **Detay:** 24 saat içinde Active Directory ve bağımsız makineleri hacklemen, ardından profesyonel rapor yazman beklenir. Privilege Escalation şarttır.

### 3. OSEP (Offensive Security Experienced Penetration Tester)
Kurumsal ortamların kabusu; AV/EDR bypass ve Active Directory katili olmak isteyen senior profesyonellerin sertifikası.
* **Detay:** 48 saatlik sınav. Özel payload'lar (C#/PowerShell) ile evasion (atlatma) tekniklerinin dibine inilir.

### 4. CISSP (Certified Information Systems Security Professional)
Yönetici zihniyeti. Teknik detaylardan sıyrılıp, güvenlik organizasyonunun beyni (CISO) olmanın yolunu çizen mimari sertifika.
* **Detay:** Güvenliğin büyük resmini ve risk yönetimini yöneten "altın standart" belgedir.

---

## 🛠️ Monk Mode Eğitim & Lab Ekosistemi

Sadece sertifika almak yeterli değildir. Aşağıdaki platformlarda kas hafızası oluşturulmalıdır:

- **HackTheBox (HTB):** "Pro Labs" ortamları (Dante, RastaLabs) kurumsal sızma testi pratiği için birebirdir.
- **TryHackMe (THM):** Özellikle "Red Team" path'i, mimari ve konseptleri temelden alıp AD sömürüsüne kadar götürür.
- **PortSwigger Web Security Academy:** Web uygulamaları hacking mekaniklerini kağıt üzerinde değil, gerçek senaryolarda kavramak için ücretsiz "Burp Suite" okuludur.
- **Kişisel Homelab:** Proxmox veya VMware ESXi üzerine kendi Active Directory ortamınızı (Windows Server, Win 10/11 Client) kurun ve kendiniz vurun. Bilinen zafiyetleri (Zerologon vb.) kendi lab'ınızda istismar edin.
