**TÁVKÖZLÉSI HÁLÓZAT ÖSSZEÁLLÍTÁSI FOLYAMAT**

**1. Előkészütetés**

1.1. **Szükséges eszközök ellenőrzése és előkészítése**  
- Mikrotik LHG18 LTE antenna
- Mikrotik nRay 60GHz antennapár
- D-Link, TP-Link vagy ASUS SOHO router
- HP switch (opcionális)
- Laptop vagy PC a konfigurációhoz
- Ethernet kábelek és tápegységek
- Iperf szoftver a sávszélesség méréséhez

1.2. **Eszközök gyári alaphelyzetbe állítása**  
- Mikrotik LHG18 LTE, nRay 60GHz antennák és router gyári beállításainak visszaállítása
- Gyári reset után ellenőrizni az eszközök elérhetőségét alap IP címükön

---

**2. Hálózati topológia megtervezése**

2.1. **Hálózati diagram elkészítése**  
- Az eszközök IP-címeinek kiosztása:
  - Mikrotik LHG18 LTE: `192.168.88.1`
  - Mikrotik nRay Master: `192.168.88.2`
  - Mikrotik nRay Slave: `192.168.88.3`
  - Router (AP mód): `192.168.88.4`
  - Switch (ha szükséges): `192.168.88.254`
  - Kliens laptop: `192.168.88.100-250` (DHCP-ből)

---

**3. Eszközök fizikai telepítése és összekapcsolása**

3.1. **Mikrotik LHG18 LTE antenna beállítása**  
- Laptop csatlakoztatása Ethernet kábellel
- Böngészőben vagy WinBox segítségével bejelentkezés (`192.168.188.1`)
- LTE kapcsolat konfigurálása és hálózati beállítások módosítása

3.2. **Mikrotik nRay 60GHz Master-Slave beállítás**  
- Master antenna konfigurálása (`192.168.88.2`)
- Slave antenna csatlakoztatása és konfigurálása (`192.168.88.3`)
- Kapcsolat tesztelése és jelerősség mérése

3.3. **SOHO router AP módba állítása**  
- Router elérése böngészőn keresztül
- SSID és jelszó beállítása
- IP cím módosítása és AP mód aktiválása

---

**4. Hálózati tesztelés és finomhangolás**

4.1. **Kapcsolatok ellenőrzése**  
- Ping tesztek végrehajtása (`ping 192.168.88.x`)
- IP-címek és hálózati konfiguráció ellenőrzése (`ipconfig` vagy `ifconfig` parancsokkal)

4.2. **Sávszélesség mérése iperf használatával**  
- Szerver indítása az egyik laptopon: `iperf3 -s`
- Kliens csatlakoztatása másik laptopról: `iperf3 -c 192.168.88.xxx`
- Eredmények dokumentálása

4.3. **Hibakeresés**  
- Ha nem működik a kapcsolat:
  - Hálózati kábelek és csatlakozások ellenőrzése
  - IP-címek helyességének ellenőrzése
  - Tűzfal beállítások módosítása (`netsh advfirewall firewall set rule group="Network Discovery" new enable=Yes`)
  - DHCP szerver megfelelő működésének ellenőrzése

---

**5. Dokumentáció és záró lépések**

5.1. **Mérési eredmények rögzítése**  
- Ping teszt eredmények mentése
- Jelerősség paraméterek (RSRP, RSRQ, SINR, RSSI) dokumentálása
- Sávszélesség mérési eredmények rögzítése

5.2. **Képernyőképek készítése és dokumentáció összeállítása**  
- Hálózati topológia
- Konfigurációs beállítások
- Hibakeresési lépések és megoldások

5.3. **Vizsga lezárása**  
- Eszközök megfelelő működésének ellenőrzése
- Dokumentáció és prezentáció elkészítése

**Összegzés:** A hálózat megfelelően telepítve és konfigurálva lett, a mérési eredmények megfelelő teljesítményt mutattak, és az esetleges hibák sikeresen elhárításra kerültek.


