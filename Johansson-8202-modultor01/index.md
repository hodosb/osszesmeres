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




![mért jelszint táblázat](https://github.com/user-attachments/assets/478446b1-a32b-47b9-bc0e-0c8ba5570bb2)

---
![mért bitsebesség táblázat](https://github.com/user-attachments/assets/33094e76-9a9b-40c1-aa49-3df946013fed)

## 11. Mért Képek

<details>
<summary>Kattins a részletekért</summary>
  
![its_snapshot_0001](https://github.com/user-attachments/assets/ff37db14-e48f-45cb-b650-6ebf3bd1d2e6)

![its_snapshot_0002](https://github.com/user-attachments/assets/6b005d1a-259d-49d8-9815-444693ea52e6)

![its_snapshot_0003](https://github.com/user-attachments/assets/a587c139-d819-41d3-aeaa-c4df69025fdd)

![its_snapshot_0004](https://github.com/user-attachments/assets/065e6ca4-96f2-4ce1-9875-74c9b5b4caef)

![its_snapshot_0005](https://github.com/user-attachments/assets/2c5b3291-f383-495f-a7d0-e4c5df84edaf)

![its_snapshot_0006](https://github.com/user-attachments/assets/05fcfeef-3d0e-40fa-b80b-4de99f327ec0)

![its_snapshot_0007](https://github.com/user-attachments/assets/a7c5b644-d574-4351-8694-acefd55f32b0)

![its_snapshot_0008](https://github.com/user-attachments/assets/918857f7-9eb1-4869-a80b-b1eea1e4f900)

![its_snapshot_0009](https://github.com/user-attachments/assets/7f3d8e10-1652-4b7a-aea0-50df29db80cf)





## Mérési eredmények elemzése
Az adatok alapján az alábbi következtetéseket lehet levonni:

-A jel erőssége a modulációtól függetlenül hasonló, de a PSK moduláció esetén a legjobb

-A 64QAM rendelkezik a legjobb bitsebességgel, frekvenciától függetlenül

-A modulációs hibaarány általánosan a PSK-nál a legnagyobb

-Minél nagyobb a frekvencia, annál kisebb a bitsebesség

---


