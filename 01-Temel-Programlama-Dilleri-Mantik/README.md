[🏠 Ana Sayfa](../README.md) / **🏗️ Temel Programlama Dilleri & Mantık**

# 🏗️ Temel Programlama Dilleri & Mantık

## 🎭 Zanaatkarın Bakış Açısı
Programlama dilleri düşüncenin alfabesidir. Bir zanaatkar için dil, sadece sözdizimi (syntax) değil, problem çözme paradigmasıdır.

## 🧠 Kritik Konseptler
- **Bellek Yönetimi (Memory Management):** Stack vs. Heap farkı, manuel (C) vs. otomatik (Java/Python) vs. sahiplik (Rust) modelleri.
- **Eşzamanlılık (Concurrency & Parallelism):** Race condition'lardan kaçınma, Thread'ler, Coroutine'ler ve Actor modeli.
- **Tip Sistemleri (Type Systems):** Statik vs. Dinamik, Güçlü vs. Zayıf tipleme ve bunların hata önlemedeki rolleri.
- **Derleme Süreçleri:** JIT (Just-In-Time) vs. AOT (Ahead-Of-Time) derleme.

## 🏁 Sektör Standartları & Pratikler
- **Clean Code:** Anlamlı isimlendirmeler, küçük fonksiyonlar ve kendini dökümante eden kod.
- **SOLID Prensipleri:** Nesne yönelimli dillerde esnek ve sürdürülebilir mimari.
- **Linting & Formatting:** Proje genelinde standart kod stili (ESLint, Prettier, Black, Clang-Format).

## ⚠️ Sık Yapılan Hatalar
- **Global Değişken Kullanımı:** Kodun test edilebilirliğini ve güvenliğini bozar.
- **Hata Yönetimi İhmali:** Try-catch bloklarını boş bırakmak veya error check yapmamak.
- **Optimizasyon Takıntısı:** Henüz çalışmayan kodu optimize etmeye çalışmak (Premature Optimization).

## 🛠️ Araç Seçim Mantığı
- **Hız mı, Güvenlik mi?** Eğer mikro saniye seviyesinde performans gerekliyse **C/Rust**; hızlı prototipleme gerekiyorsa **Python**.
- **Ekosistem Gücü:** Büyük bir kurumsal proje ise **Java/C#**; modern web dünyası ise **TS/Go**.

## 🚀 Zanaatkarlık Görevleri
- **Çırak:** Terminal üzerinden çalışan basit bir hesap makinesi yap.
- **Kalfa:** Bir sıralama algoritmasını kütüphane kullanmadan görselleştir.
- **Usta:** Kendi betik dilini tasarla veya bir derleyici yaz.

## 🚀 Teknolojiler
- Python, C++, C, C#, JavaScript, TypeScript, Go, Rust, Java, Solidity, Haskell, Elixir, Clojure, Erlang, Julia, PHP, Ruby, Perl, Zig, R, Fortran, Swift, Kotlin, Dart, Lua, Forth, Nim, OCaml, Pkl, Scala, V, Vala, WASM, Haxe.

---
[⬆️ Başa Dön](../README.md)

## ❓ Zanaatkar Mülakat Soruları
1. **Garbage Collection (GC) nasıl çalışır?** Performans üzerindeki etkileri nelerdir?
2. **Statik ve Dinamik tipleme arasındaki fark nedir?** Projenin ölçeklenebilirliğini nasıl etkiler?
3. **Closure nedir?** Hangi durumlarda bellek sızıntısına (memory leak) neden olabilir?
4. **Compiled vs Interpreted diller arasındaki farklar nelerdir?**
5. **Thread-safety nedir?** Bir kodu nasıl thread-safe hale getiririz?

## ✅ Üretim Hazırlık Kontrol Listesi (Production Checklist)
- [ ] Kod standartlarına (Linting/Formatting) uygunluk sağlandı mı?
- [ ] Birim testler (Unit Tests) %80 kapsama ulaştı mı?
- [ ] Bellek sızıntısı (Memory Leak) analizi yapıldı mı?
- [ ] Hata yönetimi (Error Handling) tüm uç durumları kapsıyor mu?
- [ ] Loglama mekanizması (Structured Logging) kuruldu mu?
