[🏠 Ana Sayfa](../README.md) / **🧠 Yapay Zeka, Veri & Zeka**

# 🧠 Yapay Zeka, Veri & Zeka

## 🎭 Zanaatkarın Bakış Açısı
AI, verinin ham halini zekaya dönüştürme sanatıdır. Bir zanaatkar burada hem bir istatistikçi hem de bir yazılım mimarıdır.

## 🧠 Kritik Konseptler
- **Backpropagation:** Sinir ağlarının hatalardan nasıl ders çıkardığının matematiksel temeli.
- **Overfitting & Underfitting:** Modelin veriyi ezberlemesi veya hiç öğrenememesi sorunsalı.
- **Feature Engineering:** Ham veriden model için anlamlı öznitelikler çıkarma sanatı.
- **Transformers & Attention:** Verideki uzak ilişkileri yakalayan modern AI mimarisi.

## 🏁 Sektör Standartları & Pratikler
- **Veri Temizliği (Cleaning):** Kirli veriyle iyi model kurulamaz (Garbage In, Garbage Out).
- **Model Versiyonlama:** Kod gibi modellerin ve veri setlerinin de versiyonlanması (DVC).
- **Explainable AI (XAI):** Modelin neden bu kararı verdiğini açıklayabilme yeteneği.

## ⚠️ Sık Yapılan Hatalar
- **Test Verisinin Sızması (Data Leakage):** Test verisinin eğitim sürecine dahil edilmesi, yanıltıcı sonuçlar doğurur.
- **Yetersiz Veri:** Çok karmaşık modelleri çok az veriyle eğitmeye çalışmak.
- **Etik & Yanlılık (Bias):** Eğitim verisindeki önyargıların modele aktarılması.

## 🛠️ Araç Seçim Mantığı
- **Akademik vs. Üretim:** Hızlı araştırma ve esneklik için **PyTorch**; kararlılık ve mobil/web dağıtımı için **TensorFlow**.
- **Analitik:** Hızlı tablo işlemleri için **Pandas**; devasa veriler için **Spark**.

## 🚀 Zanaatkarlık Görevleri
- **Çırak:** Pandas ile bir CSV dosyasını temizle ve temel istatistikleri çıkar.
- **Kalfa:** Scikit-learn kullanarak bir ev fiyatı tahminleme modeli kur.
- **Usta:** Transformers kullanarak kendi dökümanların üzerinde çalışan bir soru-cevap botu yap.

## 🚀 Teknolojiler
- TensorFlow, PyTorch, OpenCV, Scikit-learn, NumPy, Pandas, Matlab, Octave, Anaconda, D3, Grafana, Prometheus, Regex, Processing.

---
[⬆️ Başa Dön](../README.md)

## ❓ Zanaatkar Mülakat Soruları
1. **Gradient Descent nedir?** Yerel minimum (local minimum) probleminden nasıl kaçınılır?
2. **Transformer mimarisindeki 'Attention' mekanizması ne işe yarar?**
3. **Overfitting'i önlemek için kullanılan Regularization teknikleri nelerdir?**
4. **Supervised vs Unsupervised learning arasındaki farklar nelerdir?**
5. **Model bias (yanlılık) nedir ve nasıl ölçülür?**

## ✅ Üretim Hazırlık Kontrol Listesi (Production Checklist)
- [ ] Model performansı (Accuracy/F1-Score) hedef seviyede mi?
- [ ] Veri boru hattı (Data Pipeline) hatalara karşı dayanıklı mı?
- [ ] Model çıkarım süresi (Inference Latency) ölçüldü mü?
- [ ] Veri drifti (Data Drift) izleme mekanizması kuruldu mu?
- [ ] Etik ve yanlılık kontrolleri yapıldı mı?
