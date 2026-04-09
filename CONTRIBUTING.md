# 🤝 IT-Certifications-Roadmap Katkıda Bulunma Kılavuzu

Bu repository ("IT-Certifications-Roadmap"), elit mühendisler, "Monk Mode" felsefesini benimseyenler ve sadece uygulamalı ("hands-on") sertifikalar peşinde koşan bağımsız geliştiriciler için oluşturulmuş yüksek yoğunluklu bir Masterclass rehberidir.

Bu rehbere yapacağınız katkılarda aşağıdaki kurallara **kesinlikle** uyulması gerekmektedir. CV doldurmaya yönelik teorik belgelere burada yer verilmeyecektir.

## 📌 Genel Felsefe
1. **"Hands-on" Yetkinlik Şartı:** Ekleyeceğiniz sertifikanın sadece çoktan seçmeli bir test olmaması, laboratuvar/pratik senaryolar içermesi veya sektörde son derece ağır bir teknik karşılığının olması gerekir. (Örn: OSCP, CKA, AAE)
2. **"Monk Mode" Odaklılık:** Hazırlık tavsiyeleriniz "şu dokümanı oku" geçemez. "Şu ortamı sanallaştır, şu kodu otomatize edene kadar hatasız yaz" tarzı kas hafızası geliştiren pratik öneriler olmalıdır.
3. **Net ve Keskin Dil:** Açıklamalar kısa, teknik, jilet gibi net olmalıdır.

## 🛠️ Nasıl Katkı Sağlanır?

### 1. Yeni Bir Sertifika Önerme
- Repoya yeni bir sertifika eklemeden önce `.github/ISSUE_TEMPLATE/feature_request.md` şablonunu doldurarak bir Issue açın.
- Issue onaylandıktan sonra geliştirmeye başlayın.

### 2. Geliştirme Süreci
1. Repoyu Fork'layın.
2. Yeni bir feature branch oluşturun:
   ```bash
   git checkout -b feature/SertifikaAdi-Kategorisi
   ```
3. İlgili ana dizin altındaki (Örn: `cybersecurity/README.md`) markdown dosyasına veya ana `README.md`'ye gerekli eklemeyi yapın.
4. Eklemeniz şu formatta olmalıdır:
   - **Nedir:** (Kısa, net, teknik tanım)
   - **Kime Hitap Eder:** (Hangi uzmanlık alanları için kritik)
   - **Sınav Formatı:** (Süre, soru tipi, laboratuvar durumu)
   - **Hazırlık Yöntemi:** (En iyi kurslar, platformlar, spesifik donanım veya yazılım pratikleri)

### 3. Pull Request (PR) Açma
1. Değişikliklerinizi açık, net Türkçe commit mesajlarıyla kaydedin:
   ```bash
   git commit -m "docs(cybersecurity): eJPT sertifikası eklendi"
   ```
2. Fork ettiğiniz repoya `push`layın.
3. `PULL_REQUEST_TEMPLATE.md` yönergelerini harfiyen doldurarak PR oluşturun.

## ⌨️ Markdown Kuralları
- Karakter kodlaması **kesinlikle UTF-8** olmalıdır.
- Başlık hiyerarşisine dikkat edilmelidir.
- Görsel kullanılacaksa (tavsiye edilmez, metin ağırlıklı olmalıdır) ilgili başlığın altına Markdown formatında sığdırılmalıdır.

**Kodla kalın, sistemleri ayakta tutun.** 🚀
