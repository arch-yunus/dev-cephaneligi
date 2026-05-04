[🏠 Ana Sayfa](../README.md) / **🛡️ Altyapı, Bulut & DevOps**

# 🛡️ Altyapı, Bulut & DevOps

## 🎭 Zanaatkarın Bakış Açısı
DevOps, sistemlerin sürdürülebilirliğini sağlayan görünmez güçtür. Bir zanaatkar burada altyapıyı kod gibi yönetir.

## 🧠 Kritik Konseptler
- **Infrastructure as Code (IaC):** Sunucuları manuel kurmak yerine kodla tanımlama (Terraform, Ansible).
- **CI/CD Pipelines:** Kodun her adımda otomatik test edilmesi ve yayına alınması.
- **Observability (İzlenebilirlik):** Logging, Metrics ve Tracing ile sistemin nabzını tutma.
- **GitOps:** Tüm altyapı ve uygulama değişikliklerini Git üzerinden yönetme felsefesi.

## 🏁 Sektör Standartları & Pratikler
- **Twelve-Factor App:** Bulut tabanlı uygulamalar geliştirmek için 12 altın kural.
- **Sıfır Güven (Zero Trust):** Ağ içindeki hiçbir cihazın varsayılan olarak güvenli kabul edilmemesi.
- **Immutable Infrastructure:** Değiştirilemez altyapı; güncelleme yapmak yerine yenisini kurma prensibi.

## ⚠️ Sık Yapılan Hatalar
- **Hardcoded Secrets:** Şifreleri ve API anahtarlarını kodun içine yazmak (Asla yapma!).
- **Manuel Müdahale:** SSH ile canlı sunucuya girip konfigürasyon değiştirmek.
- **Yedekleme İhmali:** Çalışan sistemin yedeğinin alındığını ve geri yüklenebildiğini doğrulamamak.

## 🛠️ Araç Seçim Mantığı
- **Hangi Bulut?** Global ölçek için **AWS/Azure**; başlangıç ve kolaylık için **DigitalOcean/Vercel**.
- **Orkestrasyon:** Basit işler için **Docker Compose**; kompleks mikroservisler için **Kubernetes**.

## 🚀 Zanaatkarlık Görevleri
- **Çırak:** Bir web uygulamasını Dockerize et ve local'de çalıştır.
- **Kalfa:** GitHub Actions ile otomatik build ve test süreci oluştur.
- **Usta:** Terraform ile multi-region bir AWS altyapısı kur ve ayağa kaldır.

## 🚀 Teknolojiler
- Docker, Kubernetes, Git, GitHub, GitLab, GitHub Actions, Jenkins, AWS, GCP, Azure, Nginx, Cloudflare, Terraform, Ansible, Vagrant, OpenShift, OpenStack, Vercel, Netlify, Heroku.

---
[⬆️ Başa Dön](../README.md)

## ❓ Zanaatkar Mülakat Soruları
1. **Kubernetes'te Pod ve Deployment arasındaki fark nedir?**
2. **CI/CD sürecinde 'Blue-Green Deployment' ve 'Canary Release' farkları nelerdir?**
3. **Infrastructure as Code (IaC) kullanmanın avantajları ve riskleri nelerdir?**
4. **Docker Layer Caching nedir ve build süresini nasıl etkiler?**
5. **SRE (Site Reliability Engineering) prensipleri nelerdir?**

## ✅ Üretim Hazırlık Kontrol Listesi (Production Checklist)
- [ ] Load Balancer konfigürasyonu yapıldı mı?
- [ ] Otomatik ölçekleme (Auto-scaling) kuralları tanımlandı mı?
- [ ] Backup ve Disaster Recovery planı hazır mı?
- [ ] SSL/TLS sertifikaları güncel mi?
- [ ] Alarm ve izleme (Alerting/Monitoring) sistemleri aktif mi?
