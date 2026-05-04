[🏠 Ana Sayfa](../README.md) / **🗄️ Veritabanları & Depolama**

# 🗄️ Veritabanları & Depolama

## 🎭 Zanaatkarın Bakış Açısı
Veritabanı sistemin kalıcı hafızasıdır. Bir zanaatkar burada veriyi sadece saklamaz, onu en hızlı ve güvenli şekilde sorgular.

## 🧠 Kritik Konseptler
- **Normalization vs. Denormalization:** Veriyi bölerek tutarlılığı sağlamak vs. birleştirerek hızı artırmak.
- **Indexing:** Milyarlarca veri arasından aradığını milisaniyeler içinde bulma sanatı.
- **Transactions (ACID):** İşlemlerin ya tamamen gerçekleşmesi ya da hiç gerçekleşmemesi garantisi.
- **Sharding & Replication:** Veriyi farklı sunuculara yayarak ölçekleme ve yedekleme.

## 🏁 Sektör Standartları & Pratikler
- **Schema Migrations:** Veritabanı yapısındaki değişiklikleri kod gibi versiyonlayarak yönetme.
- **ORM (Object-Relational Mapping):** Veritabanı tablolarını kod tarafında nesne gibi kullanma.
- **Pooling:** Veritabanı bağlantılarını verimli yönetmek için "Connection Pool" kullanımı.

## ⚠️ Sık Yapılan Hatalar
- **N+1 Sorgu Problemi:** Döngü içinde veritabanına yüzlerce gereksiz sorgu göndermek.
- **İndeks Eksikliği:** Sorguların büyümesiyle sistemin aşırı yavaşlaması.
- **Hatalı Seçim:** İlişkisel veri için NoSQL, veya döküman tipi veri için katı SQL şemaları kullanmak.

## 🛠️ Araç Seçim Mantığı
- **Karmaşık İlişkiler:** Kesinlikle **PostgreSQL**.
- **Hız & Önbellek:** Key-Value saklama için **Redis**.
- **Esnek Şema:** Hızlı değişen döküman verileri için **MongoDB**.

## 🚀 Zanaatkarlık Görevleri
- **Çırak:** SQL ile birbirine bağlı 3 tablo kur ve verileri sorgula.
- **Kalfa:** Bir projende Redis kullanarak API yanıtlarını önbellekle (Caching).
- **Usta:** Veritabanında "Sharding" veya karmaşık bir "Query Optimization" çalışması yap.

## 🚀 Teknolojiler
- PostgreSQL, MongoDB, MySQL, SQLite, Redis, Cassandra, DynamoDB, Neo4j, PlanetScale, Supabase, Appwrite, Firebase.

---
[⬆️ Başa Dön](../README.md)

## ❓ Zanaatkar Mülakat Soruları
1. **Veritabanı indeksi sorgu performansını nasıl artırır? Dezavantajları nelerdir?**
2. **ACID prensipleri nelerdir?**
3. **Optimistic vs Pessimistic Locking farkı nedir?**
4. **Database Sharding ve Partitioning arasındaki fark nedir?**
5. **NoSQL veritabanlarında 'Eventual Consistency' ne anlama gelir?**

## ✅ Üretim Hazırlık Kontrol Listesi (Production Checklist)
- [ ] Slow query logları aktif edildi mi?
- [ ] Veritabanı yedekleme (Backup) ve geri yükleme (Restore) test edildi mi?
- [ ] Bağlantı havuzu (Connection Pooling) ayarları optimize edildi mi?
- [ ] Hassas veriler (Sensitive Data) şifrelendi mi?
- [ ] İndeksleme stratejisi gözden geçirildi mi?

## 🏆 Onur Listesi (Hall of Fame)
- **Edgar F. Codd:** İlişkisel veritabanı modelinin (RDBMS) mucidi.
- **Michael Stonebraker:** Ingres ve PostgreSQL'in yaratıcısı.
- **Salvatore Sanfilippo (antirez):** Redis'in yaratıcısı.
- **Martin Kleppmann:** Modern veri mimarileri ve dağıtık sistemler üzerine "Designing Data-Intensive Applications" kitabının yazarı.
