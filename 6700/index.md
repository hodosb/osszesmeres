
# Miskolci Szakképzési Centrum  
**Kandó Kálmán Informatikai Technikum**  
**Miskolc Palóczy u. 3.**

# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Kónya Zsombor,Hódos Balázs,Gáspár Máté  
**A mérés tárgya:** Programozható Antennaerősítő-szűrő használata 
**A mérés száma:** 2. mérés  
**A mérés dátuma:** 2024. 11. 13  
**A mérést vezette:** Sándor Péter  
**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3 Labor 

---

## 1. Mérés Célja

A Johansson 6700 Profiler egy antennajelerősítő és szűrő, amely rádiófrekvenciás jelek erősítésére és szűrésére szolgál.
 Az Avasi adótorony jeleit egy antenna fogja, majd a Johansson eszköz a csatornákat megfelelő sorrendben és frekvencián továbbítja
 , így a régi UTP-kábeles rendszeren is zavartalanul nézhető a TV.
 
---

## 2. Helyszín

- **Koordináták:** 48°06’20”N 20°46’48”E  
- **Antenna Típus:** Iskra P-20  
- **Antenna magassága:** 1.5m  
- **Környezet:** V3 labor, Városi körülmények között  
- **Adó Távolsága:** 780m  
<details>   
  <summary> ADÓTORONY - VÉTELI HELY távolság </summary>
  
  <img src="https://github.com/hodosb/6700-as-meres/blob/main/map.png" alt="adotorony" />
  
</details>

<br>


---

## 3. Alkalmazott Mérőeszközök és Készülékek

| Műszer neve                         | Típus           | Gyártási szám         |
| ----------------------------------- | ---------       | -------------------   |
| Programozható antennaerősítő-szűrő  | Johansson 6700  |                       |
| Antenna                             | Iskra P-20      | 38331002931507        |
| Spektrum Analizátor                 | Metek  HDD      |                       |

---
## 4. Blokkvázlat

<img src="https://github.com/hodosb/6700-as-meres/blob/main/blokk.png" alt="blokkvázlat" />

- **Iskra P-20 Antenna**: az RF jelek vételére
- **Johansson 6700 Profiler**: az RF jelek erősítésére és szűrésére
- **Metek HDD Spektrum Analizátor**: az erősített és szűrt jelek vizsgálatára

---
## 5. Mérési Adatok és Eredmények

### Mért adatok

Az alábbi táblázat a különböző frekvenciasávokhoz tartozó mért jelerősségeket mutatja a Johansson 6700 Profiler használata nélkül és használatával.

| Beérkező Csatornák (CH) | Frekvencia (MHz) | Jelszint (dBu) | Átrendezett Csatornák (CH) |  Frekvencia (MHz) | Jelszint (dBuV) |
|---------------|------------------|----------------|--------------------------|----------------------------|----------------------------|
| 28            | 530              | 64             | 40                       | 626                        | 100.8                      |
| 31            | 554              | 60             | 41                       | 634                        | 100.9                      |
| 35            | 586              | 60             | 42                       | 642                        | 100.8                      |
| 41            | 634              | 59             | 45                       | 650                        | 100.8                      |
| 45            | 666              | 59             | 48                       | 658                        | 100.6                      |
| 48            | 690              | 56             | 45                       | 666                        | 100.4                      |
### Eredmények értelmezése
A mérések szerint a Johansson 6700 Profiler a kiválasztott frekvenciasávokban stabilan 30 dB erősítést nyújtott. Az eszköz sikeresen növelte a bemeneti jelerősséget, így a gyengébb jelek is stabilan vehetők és feldolgozhatók. Az eredmények megfeleltek az elvárásoknak, az erősítés minimális eltérésekkel stabil volt.

---
## 7. Hibák és Korlátozások
A mérés során az alábbi problémák merültek fel:
Környezeti tényezők: Az épületek közelsége és a laborban lévő egyéb elektromos eszközök különösen az alacsonyabb frekvenciákon interferenciát okozhatnak.
Antenna elhelyezése: A vétel nem volt ideális az alacsony, 1,5 méteres antennamagasság miatt; a jelerősség növelése és a zavarok csökkentése érdekében magasabbra kellene telepíteni az antennát.
Interferencia: A spektrumanalizátor időnként külső zajokat észlelt, amelyek más rádiófrekvenciás forrásokból, például WiFi-ből vagy mobiltelefonokból származhattak.
## 8. Következtetések és Javaslatok
A mérés sikeresen bemutatta a Johansson 6700 Profiler teljesítményét, igazolva, hogy a készülék megbízhatóan végzi az erősítési feladatokat.

Javasolt további méréseket végezni eltérő körülmények között, hogy feltárjuk a potenciális befolyásoló tényezőket.
Érdemes lenne szélesebb frekvenciasávban is vizsgálni az eszközt, hogy felmérjük annak sokoldalúságát.
Az eredmények összességében megfeleltek az elvárásoknak, és a rendszer az UTP kábeles rendszeren keresztül is zavartalanul működött.
A mérés célja megvalósult, de a vétel minőségének javításához további finomításokra van szükség.
## 9. További mérési javaslatok a jobb vétel és minőség érdekében
Antenna elhelyezése: A jobb jelerősség érdekében ajánlott az antennát magasabbra telepíteni, különösen az alacsonyabb frekvenciák esetén.
Környezeti hatások csökkentése: A következő méréseknél érdemes megvizsgálni, hogyan befolyásolják a különböző környezeti tényezők (pl. időjárás, épületek) a vételt.
További tesztelés: Javasolt más antennatípusokat is kipróbálni, és összehasonlítani a jelenlegi Iskra P-20 antennával.
## 10. Felhasznált Források
Johansson 6700 Felhasználói Kézikönyv – A gyártó által biztosított dokumentáció az eszköz beállítási lehetőségeiről.
Iskra P-20 Antenna Műszaki Leírás – Az antenna specifikációi és teljesítménye különböző frekvenciasávokban.
Műholdas és Földi Adóállomások Jellemzői – Általános útmutató a városi adótornyok és az általuk sugárzott frekvenciák jellemzőiről.
## 11. Magyarázatok és tanulmányok
SNR (Jel-zaj viszony): A jel és a zaj aránya decibelben (dB); minél magasabb az érték, annál tisztább a jel. Stabil vételhez általában legalább 30 dB szükséges.
QPSK: Kvadratúra fáziseltolásos moduláció (Quadrature Phase Shift Keying), egy hatékony adatátviteli technika, amelyet gyakran alkalmaznak digitális tévéadásokhoz.
UTP kábel: Árnyékolatlan sodrott érpárú kábel, amely adatátvitelre, például Ethernet hálózatokban, széles körben használt.
## 12. Jelerősség diagramok
<img src="https://github.com/hodosb/6700-as-meres/blob/main/1_freki_dbuv.jfif" alt="frekivaz" />
<img src="https://github.com/hodosb/6700-as-meres/blob/main/2_freki_dbuv.jfif" alt="frekivaz2" />

## 13. Záró Összegzés
A mérés során a Johansson 6700 Profiler programozható antennaerősítő-szűrő sikeresen kezelte és optimalizálta a városi környezetben működő antenna jeleit. A jelerősség és vételi minőség alapján az eszköz rövid UTP-kábelezésű rendszerekben is hatékonyan alkalmazható. Az antennarendszer telepítése megfelelő volt, de a jelerősség javítása érdekében további teszteket ajánlott végezni.

A mérés fő tanulságai:

Az antennák megfelelő elhelyezése alapvető a vétel optimalizálásához.
A környezeti hatások jelentősen befolyásolják a jelerősséget és a vétel minőségét.
A Johansson 6700 egyszerűen beállítható, és a mérések szerint hatékonyan működik.
Összességében a Johansson 6700 Profiler alkalmas városi antennarendszerek kezelésére, bár a vétel további optimalizálása érdekében javasolt kiegészítő mérések elvégzése.

## 14. Mért Képek

<details>
<summary>Kattins a részletekért</summary>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/01.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/02.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/03.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/04.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/05.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/06.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/its_snapshot_0050.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/its_snapshot_0049.bmp"/>

<br>

<img src="https://github.com/hodosb/6700-as-meres/blob/main/its_snapshot_0048.bmp"/>

<br>


</details>

**Aláírás:** Hódos Balázs,Kónya Zsombor,Gáspár Máté

**Dátum:** 2024.11.13







