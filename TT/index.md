
## &#928; Csillapító Áramkör Jegyzőkönyv.

**Mérés helye**: Miskolci SZC Kandó Kálmán Informatikai Technikum  
**Mérő személyek**: Hódos Balázs, Kónya Zsombor

**Mérés időpontja**: 2024.12.18.  
**Mérő műszerek**: HMO1002 Oscilloscope - 1764K02-102609-WG  
**Felelős személy**: Sándor Péter  
**Cél**: A pi csillapító áramkör elemzése.

---

### 1. **Bevezetés**

A projekt célja egy PI csillapító áramkör megépítése, amelynek központjában a csillapítás mérése áll. Az áramkört breadboardon állítottuk össze a könnyebb megvalósítás érdekében.

## Elmélet:

Az értékeket a következő képletekkel számoljuk ki:

![1 (3)](https://github.com/user-attachments/assets/f678db84-c319-4f38-966f-072e41745d0c)



6 dB-es csillapításra kiszámolt ellenállás értékek:

![2 (1)](https://github.com/user-attachments/assets/8f23f380-4fd0-48f8-bb7a-c8559c103b36)


<br>

A kapcsolási rajz a jelgenerátort a belső ellenállásával, valamint a Pi csillapítót a kiszámított ellenállás értékekkel ábrázolja.
![3 (1)](https://github.com/user-attachments/assets/d2339106-b518-4fbf-99dc-042e2f212ad6)

</a>


### 3. **Mérési paraméterek**

| Paraméter           | Érték |
|---------------------|-------|
| Generátor jel       | 5.00 Vp2p|
| Kimeneti Jel        | 2.06 Vp2p |
| Generátor Frekvencia| 1000 Hz |
| Csillapítás         | -7.702 dB |
| Átviteli Arány      | 7.702 dB |

<br>

Az oszcilloszkópon a sárga 1-es csatornán látható a csillapított kimeneti jel, míg a kék 2-es csatornán a generátor jel figyelhető meg.

![4 (1)](https://github.com/user-attachments/assets/99d67865-22dc-48b8-9250-1fe33cb08b26)



### 4. **Mérési eredmények**

- **Kimeneti Jel**: A kimeneti jel mindössze 41.4%-a a generátor jelének.
  
- **Csillapítás/Átviteli arány**:  7.708 dB csillapítást tapasztalunk az áramkör jóvoltából.

### 5. **Elemzés**
A Pi csillapító ellenállás áramkörének elemzése során megfigyelhető, hogy a tervezett áramkör hatékonyan csökkenti a jel amplitúdóját, miközben megőrzi annak formáját. Az áramkör négy fő komponensből áll: három ellenállásból és egy terhelő ellenállásból. Kisebb eltérések figyelhetők meg a kiszámolt és a valós értékek között.

### 6. **Következtetések**
A Pi csillapító áramkör sikeresen elkészült, és a tesztelési eredmények azt mutatják, hogy a csillapítás megfelel a tervezett elvárásoknak. A mérések alapján a csillapító hatás a kívánt frekvenciatartományban optimális, és a jelminőség is jól megmarad. A projekt során szerzett tapasztalatok alapján fontos figyelembe venni a komponensek toleranciáját és a környezeti hatásokat, mivel ezek befolyásolhatják az áramkör működését.


---

**Aláírás**:  
Felelős mérő személy(ek): Hódos Balázs, Kónya Zsombor

Dátum: 2024.12.18

