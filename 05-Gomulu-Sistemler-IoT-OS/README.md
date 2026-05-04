[🏠 Ana Sayfa](../README.md) / **📟 Gömülü Sistemler, IoT & İşletim Sistemleri**

# 📟 Gömülü Sistemler, IoT & İşletim Sistemleri

## 🎭 Zanaatkarın Bakış Açısı
Kodun donanımla el sıkıştığı en saf katman. Bir zanaatkar burada mikro saniyelerle ve baytlarla yarışır.

## 🧠 Kritik Konseptler
- **Interrupts & Polling:** İşlemcinin dış dünyadaki olaylardan nasıl haberdar olduğu.
- **Memory Mapping:** Donanım birimlerine bellek adresleri üzerinden erişme.
- **RTOS (Real-Time Operating System):** Kritik zamanlamalı işleri hatasız yöneten sistemler.
- **Kernel Space vs. User Space:** İşletim sisteminin güvenli ve kısıtlı çalışma alanları.

## 🏁 Sektör Standartları & Pratikler
- **MISRA C:** Güvenlik kritik sistemler için belirlenmiş C yazım kuralları.
- **Low Power Design:** Pil ile çalışan cihazlar için enerji verimliliği odaklı kod yazımı.
- **HAL (Hardware Abstraction Layer):** Kodu donanımdan bağımsız hale getiren katman yapısı.

## ⚠️ Sık Yapılan Hatalar
- **Watchdog Timer İhmali:** Sistemin kilitlendiği durumlarda kendini resetleyememesi.
- **Memory Leaks:** Belleği kısıtlı cihazlarda sızan her bayt sistemin çökmesine yol açar.
- **Blocking Code:** Interrupt veya kritik döngüler içinde bekletici (delay) kod kullanmak.

## 🛠️ Araç Seçim Mantığı
- **Hangi Kart?** Basit hobi işleri için **Arduino**; profesyonel endüstriyel işler için **STM32/ESP32**.
- **Oyun Motoru:** 2D ve hafif işler için **Godot**; yüksek performanslı 3D için **Unreal Engine**.

## 🚀 Zanaatkarlık Görevleri
- **Çırak:** Arduino ile bir butona basıldığında LED yakan ve söndüren bir devre yap.
- **Kalfa:** Raspberry Pi üzerinde Python ile sıcaklık sensöründen veri oku ve ekrana bas.
- **Usta:** Bir RTOS (Örn: FreeRTOS) kullanarak çok görevli (multitasking) bir gömülü sistem projesi geliştir.

## 🚀 Teknolojiler
- Linux, Ubuntu, Debian, Fedora, Kali Linux, Arch Linux, Linux Mint, RedHat, BSD, Nix, Plan9, Apple, Windows, ROS (Robot Operating System), Arduino, Raspberry Pi, Bevy, Godot, Unity, Unreal Engine.

---
[⬆️ Başa Dön](../README.md)
