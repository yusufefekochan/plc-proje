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

## LADDER DİYAGRAM GÖRÜNTÜLERİ ## 

1 - <img width="1464" height="503" alt="1 2 " src="https://github.com/user-attachments/assets/d4d0263e-c4dc-4473-b9ca-690c49a2ceac" />

2 - <img width="1367" height="740" alt="3" src="https://github.com/user-attachments/assets/6e63f8ef-4146-4b66-a605-2ddaa5729c6f" />

3 - <img width="970" height="736" alt="4" src="https://github.com/user-attachments/assets/4dc4f48c-25d2-4e08-b069-0603478c297e" />

4 - <img width="852" height="299" alt="5" src="https://github.com/user-attachments/assets/6c0e159c-671a-46a8-a41a-0a2cabffec11" />

5 - <img width="1145" height="517" alt="6 1" src="https://github.com/user-attachments/assets/f607831e-affc-43ed-bfc2-b1ec438b2d47" />

6- <img width="1042" height="436" alt="6 2" src="https://github.com/user-attachments/assets/8a01f78c-317a-4673-ac74-fcd354d76be4" />

7- <img width="1390" height="629" alt="7" src="https://github.com/user-attachments/assets/4cf8de80-ffd8-47a0-b10a-7fc7ce9b1f5a" />



## HMİ EKRAN GÖRÜNTÜLERİ ## 

1 - <img width="737" height="563" alt="ekran1" src="https://github.com/user-attachments/assets/5d3dac32-1684-4fa7-ad07-1924fb60ca06" />

2 - <img width="494" height="387" alt="ekran 2" src="https://github.com/user-attachments/assets/7a65e0ee-d44e-4b90-96b3-db2f969d3143" />


## FACTORY İO GÖRÜNTÜLERİ ## 

Sanal ortam görüntüsü - <img width="1920" height="1041" alt="ıo-sanal-ortam" src="https://github.com/user-attachments/assets/46c4aac7-98fa-4a48-9cdb-ab78d75668c0" />

Factory io all tags - <img width="1909" height="831" alt="ıo-tags" src="https://github.com/user-attachments/assets/cb0ff5de-6bbf-456d-8e3e-e0f9c24832a9" />


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

