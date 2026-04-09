# 📊 Veri Mühendisliği ve Büyük Veri Roadmap

Büyük veri işleme (Big Data), ETL (Extract, Transform, Load) hatları kurma ve veri ambarı yönetimine odaklanan mühendisler için sertifikasyon haritasıdır.

## 📌 Sertifikasyon Haritası

### 1. Google Cloud Professional Data Engineer
Veri mimarilerini Google Cloud araç seti etrafında kurgulayan ve bu mimarileri tasarlayan uzmanlar içindir.
* **Detay:** Dataproc, Dataflow, BigQuery gibi çözümleri kullanarak sürdürülebilir ve performanslı veri ürünleri geliştirmeyi amaçlar.

### 2. Databricks Certified Data Engineer Professional
Apache Spark ekosistemi ve Databricks altyapısı konusunda uzmanlığı bulunan mühendislerin tercih ettiği sertifikadır.
* **Detay:** Delta Lake yönetimi, pipeline oluşturma aşamalarındaki performans darboğazlarını (bottleneck) tespit etme becerisini ölçer.

### 3. AWS Certified Data Engineer - Associate/Professional
AWS araçlarını kullanarak veri akış (stream) ve yığın (batch) işlemleri yürüten mimarlar içindir.
* **Detay:** AWS Glue, Amazon EMR, Amazon Kinesis ve Redshift bileşenlerini kullanarak mimari yapı inşa etme kurgularını sınar.

---

## 🛠️ Temel Teknoloji Yığını

Bir veri mühendisinin operasyonel tecrübeye sahip olması beklenen güncel endüstri araçları:

- **Apache Kafka / Redpanda:** Log-bazlı asenkron "event streaming" mimarileri kurmak ve gerçek zamanlı sensör/kullanıcı verisi aktarımı görevleri için kullanılır.
- **Apache Airflow / Dagster:** Karmaşık Python tabanlı ETL görevlerini belli bir takvime göre (Scheduling) ve bağımlılıklara göre orkestre eder.
- **dbt (data build tool):** Veri dönüşüm (Transform) işlemlerinin, yazılım mühendisliği pratikleri uygulanarak (versiyon kontrolü, testler) veritabanı içerisinde yapılmasını sağlayan altyapı.
