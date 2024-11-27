

# Miskolci Szakképzési Centrum  
**Kandó Kálmán Informatikai Technikum**  
**Miskolc Palóczy u. 3.**

# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Hódos Balázs ,Kónya Zsombor
**A mérés tárgya:** Programozható Antennaerősítő-szűrő használata 
**A mérés száma:** 07. mérés  
**A mérés dátuma:** 2024. 11. 27.  
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 1
**Helyszín:** V3 Labor 

---

## 1. Mérés Célja

A **Johansson 6700 Profiler** antennaerősítő-szűrő megismerése és beállítása, különböző antennák jeleinek kezelése.
A mérés célja a Johansson 6700 Profiler antennaerősítő-szűrő eszköz beállítása és a különböző antennák jeleinek kezelése. Az eszköz a rádiófrekvenciás jelek szűrésére és erősítésére szolgál, különösen több frekvenciasáv feldolgozására. A mérés során az Avasi adó torony jeleit vesszük, majd a Johansson eszközzel áthelyezzük a csatornákat, biztosítva a zavartalan TV-nézést a meglévő UTP rendszerben.


---

## 2. Helyszín

- **Koordináták:** 48°06’20”N 20°46’48”E  
- **Antenna Típus:** Opticum Smart HD 550  
- **Antenna magassága:** 1.5m  
- **Környezet:** V3 labor 


<br>


---

## 3. Alkalmazott Mérőeszközök és Készülékek

| Műszer neve                         | Típus           | Gyártási szám         |
| ----------------------------------- | ---------       | -------------------   |
| Programozható antennaerősítő-szűrő  | Johansson 6700  |                       |
| DVB-T Antenna                             | Opticum Smart HD 550   |         |
| FM ANTENNA               | -      |                       |
| Spektrum Analizátor                 | METEK HDD      |                       |
---



## 4. Mérési Adatok és Eredmények

### Mért adatok

Az alábbi táblázat a különböző frekvenciasávokhoz tartozó mért jelerősségeket mutatja a Johansson 6700 Profiler használata nélkül és használatával.

|Csatorna (CH)|Frekvencia (MHz)|Jelszint(dBu)|Átírányított Csatorna (CH)|Következő Frekvencia (MHz)|Következő Jelszint(dBuV)|befogadott sugárzási teljesítmény(microwatt)   |
|---------------|------------------|----------------|--------------------------|----------------------------|----------------------------|--------------|
| 28            | 530              | 62             | 41                       | 626                        | 108.4                      |   0.00214    |
| 31            | 554              | 60             | 42                       | 634                        | 108.8                      |  0.00135     |
| 35            | 586              | 58             | 43                       | 642                        | 108.4                      |  0.00085     |
| 41            | 634              | 45             | 44                       | 650                        | 108.8                      |   0.00004    |
| 45            | 666              | 60             | 45                       | 658                        | 108.7                      |  0.00135     |
| 48            | 690              | 57             | 46                       | 666                        | 108.2                      |    0.00068   |

### 5 Eredmények értelmezése


A Johansson 6700 Profiler a kiválasztott frekvenciasávokban stabil, 40 dBuV erősítést biztosított. A készülék sikeresen növelte a bemeneti jelerősséget, javítva a gyengébb jelek stabil vételét és feldolgozását. Az erősítés stabilnak bizonyult, az eltérések minimálisak, és a mérések megfeleltek az elvárásoknak.


---

## 6. Elemzés és Értékelés

A mérések eredményei alapján a Johansson 6700 Profiler megbízhatóan teljesített. Az eszköz sikeresen növelte a jelerősséget a kiválasztott frekvenciasávokban, javítva ezzel a gyenge RF jelek minőségét. A kalibrációs beállítások pontosak voltak, és az eltérések elhanyagolhatók. Bár az eszköz jól működött a városi környezetben, alacsonyabb frekvenciákon kisebb interferenciát tapasztaltunk. A csatornák áthelyezésére és a stabil jel biztosítására az eszköz megfelelően képes volt.

---

## 7. Hibák és Korlátozások

**Mérési Jegyzőkönyv**  
**Problémák**  
A mérés során az alábbi problémák merültek fel:

- **Környezeti tényezők**: Az épületek közelsége és a laborban lévő egyéb elektromos eszközök interferenciát okoztak, különösen az alacsonyabb frekvenciákon.
- **Antenna elhelyezése**: A viszonylag alacsony antennamagasság (1,5 m) miatt a vétel nem volt optimális. Az antenna magasabb elhelyezése javítaná a jelerősséget és csökkentené a zavarokat.
- **Interferencia**: A spektrumanalizátor néha külső zajokat érzékelt, amelyek valószínűleg más rádiófrekvenciás forrásokból (pl. WiFi, mobiltelefonok) származó zavarok voltak.

## 8. Következtetések és Javaslatok
- Az LTE csatornákát sikeresen kiszűrtük így azok a már átírányított spektrumképen nem látszódik. 
- A mérés sikeresen demonstrálta a Johansson 6700 Profiler képességeit. A kapott eredmények azt mutatják, hogy a készülék megbízhatóan teljesíti a kívánt erősítési feladatokat.
- Javasolt további méréseket végezni eltérő környezeti feltételek mellett, hogy megismerjük az esetleges befolyásoló tényezőket.
- Fontos lenne a méréseket nagyobb spektrális sávban is elvégezni, hogy felmérjük az eszköz széleskörű alkalmazhatóságát.
- A mérések eredményei összességében megfelelnek az elvárásoknak.
- A rendszer zavartalanul működött a rövid UTP kábeles rendszeren keresztül is.
- A mérés célja teljesült, de további finomítások szükségesek a vétel minőségének javítása érdekében.

---

## 9. További mérési javaslatok a jobb vétel és minőség érdekében 

- **Antenna elhelyezése**: Javasolt az antennát magasabb pozícióba telepíteni a jobb jelerősség érdekében, különösen az alacsonyabb frekvenciák esetében.
- **Környezeti hatások minimalizálása**: További mérések során érdemes lenne tesztelni, hogyan befolyásolják a különböző környezeti feltételek (pl. időjárás, építészeti akadályok) a vételt.
- **További tesztek**: Érdemes más antennatípusokat is tesztelni és összehasonlítani a jelenlegi Opticum Smart HD 550 antennával.

---

## 10. Felhasznált Források

1. **Johansson 6700 felhasználói kézikönyv** - A gyártó által biztosított dokumentáció az eszköz beállításairól.
2. **Opticum Smart HD 550 antenna műszaki leírás** - Az antenna specifikációi és teljesítménye különböző frekvenciákon.
3. **Műholdas és földi adóállomások jellemzői** - Általános útmutató a városi adótornyok és sugárzott frekvenciák jellemzőiről.


## 11. Záró Összegzés
A mérés során a Johansson 6700 Profiler programozható antennaerősítő-szűrő sikeresen kezelte és optimalizálta a városi környezetben lévő antenna jeleit. A jelerősség és vételi minőség alapján az eszköz hatékonyan alkalmazható rövid UTP kábelezésű rendszerekben. Az antennarendszer telepítése megfelelően történt, de a jelerősség növelése érdekében további tesztek javasoltak.

Legfontosabb tanulságok:

Az antennák helyes pozicionálása kulcsfontosságú a vétel optimalizálásához.
A környezeti hatások jelentős mértékben befolyásolják a jelerősséget és minőséget.
A Johansson 6700 könnyen konfigurálható és hatékonyan működik.
Összegzésül a Johansson 6700 Profiler megfelelő eszköz a városi antennarendszerek kezelésére, de a vétel további optimalizálása érdekében további mérések szükségesek.




---

## 12. Mért Képek




<img src="https://github.com/hodosb/osszesmeres/blob/main/6700/its_snapshot_0008.png"alt="nyers jelek"/>

<br>

<img src="https://github.com/hodosb/osszesmeres/blob/main/6700/its_snapshot_0009.png"alt="Átírányított jelek"/>

<br>



</details>

**Aláírás:** Kónya Zsombor,Hódos Balázs

**Dátum:** 2024. 11. 27.
