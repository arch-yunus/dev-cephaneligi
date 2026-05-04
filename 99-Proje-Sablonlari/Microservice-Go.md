# 🐹 Go Mikroservis Şablonu

## 📁 Klasör Yapısı (Standard Go Layout)
`	ext
/
├── cmd/                # Uygulama Giriş Noktası (main.go)
├── internal/           # Dışarıya Kapalı İş Mantığı
│   ├── api/            # HTTP/gRPC Handlerlar
│   ├── service/        # Business Logic
│   └── repository/     # Veritabanı İşlemleri
├── pkg/                # Diğer Projelerin Kullanabileceği Kodlar
├── api/                # API Tanımları (Protobuf, OpenAPI)
├── deployments/        # Docker, K8s Konfigürasyonları
└── configs/            # Yapılandırma Dosyaları (YAML, Env)
`

## 🛠️ Temel Araç Seti
- **Router:** Gin / Echo / Fiber
- **DB:** GORM / SQLx
- **Config:** Viper
- **Logging:** Zap / Zerolog
