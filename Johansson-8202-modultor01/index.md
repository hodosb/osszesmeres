# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Kónya Zsombor,Hódos Balázs <br>
**A mérés tárgya:** Frekvencia vs. moduláció mérés <br>
**A mérés száma:**  - <br>
**A mérés dátuma:**  2024.12.04 <br>
**A mérést vezette:** Sándor Péter <br>

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3-Labor

---
## Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| Metek HDD                           | 240003     |211110001346          |
| Antenna                             | Iskra P-20  | ...            |
| DVB-T modulátor                     |  Johansson 8202  | ...            |

---
### **Mérési helyszín és környezet**
- **Antenna magassága**: 2 méter.
- **Adó távolsága**: kb 5 méter.

---

## Mért értékek különböző modulációkon és frekvenciákon

706 MHz
| Mérési paraméter    | Moduláció típusa   | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|-------------------- |--------------------|----------------|---------------|----------------|----------------|
| Mérési eredmény 1   |       QPSK         |        8       |     -55,8     |      4.72      |                |
| Mérési eredmény 2   |       16-QAM       |        8       |     -54,9     |      8,8       |                |
| Mérési eredmény 3   |       64-QAM       |        8       |     -54,3     |      14.8      |                |

---

746 MHz
| Mérési paraméter   | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|--------------------|---------------------|------------------|--------------------|----------------|--------------------|
| Mérési eredmény 1  |          QPSK       |        8         |      -52           |       3,9      |                    |
| Mérési eredmény 2  |          16-QAM     |        8         |      -52,5         |       8,8      |                    |
| Mérési eredmény 3  |          64-QAM     |        8         |      -53,4         |       14.1     |                    |

---

858 MHz
| Mérési paraméter   | Moduláció típusa | Sávszélesség (MHz) | Jelszint (dBm) | Bitsebesség (Mbps) | MER érték (dB) |
|--------------------|------------------|-----------------|--------------------|----------------|--------------------|
| Mérési eredmény 1  |         QPSK     |        8        |       -52,0        |    3,4         |                    |
| Mérési eredmény 2  |         16-QAM   |        8        |       -52,7        |        9,5     |                    |
| Mérési eredmény 3  |         64-QAM   |        8        |       -54,1        |         12,8   |                    |

---

## Grafikus ábrázolás
<p>A jelszint, a bitsebesség és MER értékek vizuális ábrázolását az alábbi diagram mutatják be:</p>



https://github.com/hodosb/osszesmeres/blob/main/Johansson-8202-modultor01/m%C3%A9rt%20jelszint%20t%C3%A1bl%C3%A1zat.png

https://github.com/hodosb/osszesmeres/blob/main/Johansson-8202-modultor01/m%C3%A9rt%20bitsebess%C3%A9g%20t%C3%A1bl%C3%A1zat.png

---

## Mérési eredmények elemzése
Az adatok alapján az alábbi következtetéseket lehet levonni:

-A jel erőssége a modulációtól függetlenül hasonló, de a PSK moduláció esetén a legjobb

-A 64QAM rendelkezik a legjobb bitsebességgel, frekvenciától függetlenül

-A modulációs hibaarány általánosan a PSK-nál a legnagyobb

-Minél nagyobb a frekvencia, annál kisebb a bitsebesség

---


