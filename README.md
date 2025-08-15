# PLC Proje – Kutu Ayrıştırma ve Konveyör Kontrol Sistemi

Bu proje, **Sakarya Uygulamalı Bilimler Üniversitesi Mekatronik Mühendisliği**  
**MEK-305 Programlanabilir Mantık Denetleyicileri** dersi kapsamında geliştirilmiştir.  
Amaç, **Factory I/O** ortamında oluşturulan konveyör hattında kutuları **ağırlıklarına göre ayırmak**,  
**HMI paneli** üzerinden sistemi kontrol etmek ve Siemens **S7-1500 PLC** ile gerçekçi bir senaryo geliştirmektir.  

---

## 🎯 Proje Amaçları
- Start/Stop ve Acil butonları ile sistemi kontrol etmek  
- Ağırlık sensörü ile kutu boylarını (küçük–orta–büyük) algılayıp ayrıştırmak  
- Konveyörlerin hızını analog giriş/çıkış üzerinden kontrol etmek  
- Ayrıştırılan kutuların adetlerini sayaçlarla tutmak ve göstermek  
- HMI panelinde hem sayaç hem de hız bilgisini görselleştirmek  
- Hedef kutu sayısına ulaşıldığında sistemi otomatik durdurmak  

---

## 🖥️ Kullanılan Yazılımlar
- Siemens TIA Portal vXX  
- Siemens S7-PLCSIM  
- Factory I/O (v2.4.3)  
- WinCC (HMI tasarımı için)  

---

## 📂 Klasör Yapısı

├─ plc/ # Ladder diyagram ve TIA Portal proje dosyaları

├─ hmi/ # HMI ekran tasarımları (WinCC)

├─ factoryio/ # Factory I/O sahne dosyası (.scene)

├─ docs/ # Rapor, PDF dokümanı, ekran görüntüleri



---

## ⚙️ Sistem Bileşenleri
- **Girişler (Sensors)**: Start, Stop, Acil, Reset, Düşük/Orta/Yüksek sensör, Ağırlık sensörü, Potansiyometre  
- **Çıkışlar (Actuators)**: Küçük/Orta/Büyük konveyör motorları, Display göstergeler, Remover üniteleri  
- **Analog I/O**: Konveyör hız referansı (input), hız göstergesi & anlık ağırlık (output)  

---

## 📊 Proje Görselleri
- Ladder diyagram blokları (CTU, TON, Scale)  
- HMI ekranı – Ana Menü ve Ayarlar  
- Factory I/O sahnesi – kutu ayırma hattı  
- I/O etiketleri – giriş/çıkış eşlemeleri  

---

## 📚 Kazanımlar
- Siemens TIA Portal ile Ladder programlama  
- Factory I/O sanal ortamında otomasyon senaryosu kurgulama  
- HMI (WinCC) tasarımı ile kullanıcı etkileşimi geliştirme  
- Analog/dijital I/O kullanarak **gerçekçi endüstriyel kontrol** uygulaması  
- Sayıcılar, zamanlayıcılar, analog işleme fonksiyon bloklarının etkin kullanımı  

---



## 👤 İletişim
- Proje Sahibi: Yusuf Efe Koçhan
- Üniversite: Sakarya Uygulamalı Bilimler Üniversitesi
- E-posta : yusufefekochan@hotmail.com
- Linkedin : https://www.linkedin.com/in/yusufefekochan

