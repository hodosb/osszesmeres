**VIZSGA JEGYZŐKÖNYV**

**Vizsgázó neve:** Hódos Balázs
**Dátum:** 2025.02.03.
**Helyszín:** Miskolc  

---

### **1. A vizsga folyamata és szükséges eszközök**


**Antenna Beltéri** Iskra P2845 Logper

**Fejállomás:** LEMCO SCL-824CT

**Set-top box:** MAG IPTV

**Hálózati eszközök:** Switch - HP 2312 procurve

**Mérőműszer:** METEK HDD 240003 digitális TV jelmérő

**Kábelezés:** Koaxiális és UTP kábelek

-A miskolc városi tvre hangoljuk az adást mert ez adja a leggyengébb jelet és ha ez jó az összestöbbi is jó lesz.

![adók](https://github.com/user-attachments/assets/4de2f415-0892-42e4-8459-0c8d7cad6fae)

- Mérési pontok kialakítása
  
- 1,2,7,8 portokra kötöttük a multiplexereket
  
- Az UTP vezetéket a control portba csatlakoztatjuk

- A set top box konfigurálása m3u fájlból történik pendriveon keresztül.

---

### **2. Mérések és eredmények**
### ** Fejállomás konfiguráció**
- Input1 - Multiplex B, ch35
- Input2 - Miskolci Városi TV, ch41
- Input3 - Multiplex A, ch45
- Input4 - Multiplex E, ch48

- **Jelerősség:** 52 dBµV  (Horizontális Dél-Nyugat 233fok Miskolci TV )
- **Modulation Error Ratio (MER):** 13 dB  
- **IPTV stream állapota:** Megfelelő
- **lemco ip** 192.168.1.200

### **Router eleres:** 192.168.50.1-->192.168.1.1

- **VLC elérési cím:** http://192.168.1.1:8888/udp/239.1.1.1:1234
- **Multicast IP tartomány** 239.50.50.1-239.50.50.39
- **router lan iptv proxy:** 8888
- **Multicast port**1234
- **SSID:** iptv
- **wifi pw:** 12345678
- **admin username**admin
- **admin pw:** admin12345678
- **letöltési fel/sebesség:** 93.46
- **Portok felosztása**
  - Lan1:lemco control 1Gbps
  - Lan2:ures
  - Lan3:lemco ip stream 1Gbps
  - Lan4:set top box 100Mbps
    
---

### **4.6 IPTV stream ellenőrzése**

#### **Képek:**
<details>
    <summary>adás</summary>
  
![adás](https://github.com/user-attachments/assets/e1eb954f-d8cf-435b-b4c9-b731cc2ef43c)

</details>
<details>
    <summary>Vlc adatok</summary>
  
![sdfsdfsdf](https://github.com/user-attachments/assets/51338600-5748-484d-81a5-366c112bd244)
  
![fsdsdf](https://github.com/user-attachments/assets/3673a3b8-715b-47d4-aa7a-2fca1a3ae858)

</details>

### **3. Összegzés és értékelés**
- **A vizsga eredménye:** Sikeres 

**Vizsgáztató neve:** SP 
**Dátum:** 2025.02.03.
**Aláírás:** [Aláírás]  

---


