**MÉRÉSI JEGYZŐKÖNYV**

**Mérés tárgya:** Tranzisztor működésének vizsgálata


**Mérés időpontja:** 2025.01.08.

**Mérési eszköz:** NImyDAQ

**Eszköz gyáriszáma:** 305E1ED

---
### **Mérésben használt ellenállások valós értékei**

**Rc=212 Ohm**
**Rbe=1482 Ohm**

### **Mérés folyamata**

1. Az áramkör megépítése a megadott kapcsolási rajz alapján.
2. A mérőeszközök (árammérő- és feszültségmérő)  bekötése.
3. A bemeneti paraméterek (pl. feszültség) lépcsőzetes változtatása, és az összes mérési adat rögzítése táblázatba foglalása.
4. A kapott adatok összehasonlítása az előzetes elvárásokkal.

---

### **Mérési adatok**

Valóságban mért eredmények:

| [V] Ube | [V] URC | [mA] IC |
|-------|----------|----------|
|0,1  |0   |  0,00|
|0,2  |0,0001| 0,00|
|0,3  |0,0005 |0,01|
|0,4  | 0,002 |  0,01|
|0,5 | 0,0048| 0,03|
|0,6  |0,129|  0,65|
|0,7  |1,02   | 5,10|
|0,8  |2,45   | 11,73|
|0,9  |2,80  |  13,32|
|1,0  |2,84  |  13,68|
|1,1  |2,87 |   13,83|
|1,2  |2,89 |   13,88|
|1,3  |2,91  |  13,94|
|1,4  |2,91  |  13,94|
|1,5 | 2,91  |  13,94|





Szimulátorban mért eredmények:
| [V] Ube | [V] URC | [mA] IC |
|-------|----------|----------|
|0,1	|3,12n	|1,55E-08|
|0,2	|45,21n|	2,52E-07|
|0,3|	2,15µ|	0,000|
|0,4	|110,45µ|	0,001|
|0,5|	4,98m|	0,022|
|0,6	|153,22m	|0,725|
|0,7	|875,38m	|4,05|
|0,8	|1,93|	8,5|
|0,9	|2,90|	13,6|
|1	|3,06	|14,3|
|1,1	|3,08|	14,4|
|1,2	|3,09	|14,5|
|1,3	|3,10|	14,5|
|1,4	|3,12	|14,6|
|1,5	|3,13|	14,6|

---

## **Megjegyzés**
Mérési tapasztalatok: A transzisztor bázis-emitter feszültségének növelésével a kollektoráram kezdetben exponenciálisan emelkedett, majd elérte a telítési tartományt, ahol gyakorlatilag állandósult. A kollektor-ellenálláson mért feszültség a bázis-emitter feszültséggel együtt nőtt, de a telítési fázisban az arányosság megszűnt.

Grafikus megjelenítés: A mért adatokat célszerű grafikonok segítségével ábrázolni, hogy jobban áttekinthető legyen az Ube-Lc és Ube-Urc közötti kapcsolat. (Ez a grafikai ábrázolás nem szerepel a feltöltött anyagok között.)

Következtetések: A transzisztor megfelelően működött az aktív tartományban, majd átment a telítési állapotba. Az elvégzett mérés eredményei megerősítik a mérési pontosságot.


---
## **Mérés során készült képek**
 <details>
            <summary>Az összeépített áramkör</summary>
             <img src="https://github.com/hodosb/osszesmeres/blob/main/tranzisztor/IMG_3688%20(1).png"
          </details>
          <details>
            <summary>Az összeépített áramkör Falstadban</summary>
             <img src="https://github.com/hodosb/osszesmeres/blob/main/tranzisztor/falstadt.PNG"
          </details>
         <details>
            <summary> Real Grafikon</summary>
            <img src="https://github.com/hodosb/osszesmeres/blob/main/tranzisztor/igazi.PNG">
          </details>
          <details>
            <summary>Szimulátor Grafikon</summary>
            <img src="https://github.com/hodosb/osszesmeres/blob/main/tranzisztor/sim.PNG">
</details>

---

**Mérőcsoport neve:** MCbukok

**Mérőcsoport tagja:**
Hódos Balázs

**Kelt 2025.01.08**
