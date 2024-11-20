
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** György Péter
**A mérés tárgya:** T ellenállás hálózat
**A mérés száma:**  01
**A mérés dátuma:**  2024.11.13 
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:**   V3 labor

---

## 1. Mérés célja
A T ellenállás-hálózat jellemzőinek meghatározása a megadott ellenállásértékek alapján.

---

## 2. Eszközök 
- **NI myDAQ** 
- **Ellenállások:**
  - **számolás alapján:**
    - Rg/out = 680
    - R1/2 = 220 Ω
    - R3 = 900 Ω
  - **méréskor használt:**
    - Rg = 681 Ω
    - R1/2 = 219,193 Ω
    - R3 = 193+676 Ω
    - Rout = 681 Ω
---

## 3. Elmélet
A T pad egy speciális csillapító áramkör az elektronikában, ahol az áramkör topológiája a "T" betű alakjában van kialakítva.

Az elektronikában a csillapítókat a jel szintjének csökkentésére használják. Párnáknak is nevezik őket, mivel az akusztikával analóg módon lepárolják a jelet. A csillapítók lapos frekvenciamenettel rendelkeznek , amely minden frekvenciát egyformán csillapít abban a sávban, amelyen működni kívánnak. A csillapítónak az erősítővel ellentétes feladata van . A csillapító áramkör topológiája általában az egyszerű szűrőszakaszok egyikét követi . A szükséges frekvenciaválasz egyszerűsége miatt azonban nincs szükség bonyolultabb áramkörre, mint a szűrők esetében.
<details>
  <img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-13%20133202.png" width="300" height="200">
  <img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-13%20140110.png" width="800" height="375">
</details>
<img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-13%20133415.png" width="800" height="375">

---

## 4. Szimuláció
A T-tagú csillapítás szimulációja megmutatja, hogy a T-tag milyen hatékonyan csökkenti a rezgés amplitúdóját. A harmonikus torzítás elemzésével megérthetjük, hogy a csillapító mennyire hatékonyan csökkenti a nem kívánt rezgéseket. Ezek az eredmények segítenek optimalizálni a csillapító rendszer paramétereit a kívánt teljesítmény elérése érdekében.
<a href="https://tinyurl.com/22fpw5ch" target="_blank">
<img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/circuit-20241120-1216.png" width="800" height="350">
</a>

## 5. Gyakorlatban/Számítások

- ***Breadboardon összerakva***
  
  CH0 a bemeneti feszülstég CH1 pedig a kimeneti fesz. Szépen látszódik hogy a CH1 feszültsége nagyyábol a fele a CH0-nak.
  A jelgenerátoron 100Hz-s 5V váltakozó feszültséget állítottunk be.
<details>
  <img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/IMG_20241120_131014.jpg">

  <img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-20%20131409.png">

  <img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-20%20131428.png">
</details>

- ***Ellenállások számítása***
<details>
  
  **R1/2**
  
  <img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/IMG_20241120_123158.jpg">
  
  **R3**
  
  <img src="https://github.com/GyorgyPeter/tavkozles/blob/main/jegyzokonyv/T-ellenallas-halozat/kepek/K%C3%A9perny%C5%91k%C3%A9p%202024-11-20%20123956.png">
</details>

**Aláírás:** ...

**Dátum:** ...
