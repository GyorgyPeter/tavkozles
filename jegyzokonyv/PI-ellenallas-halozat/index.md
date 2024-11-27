
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** György Péter

**A mérés tárgya:** $\displaystyle \pi$  ellenállás hálózat

**A mérés száma:**  02

**A mérés dátuma:**  2024.11.13 

**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:**   V3 labor

---

## 1. Mérés célja
A PI ellenállás-hálózat jellemzőinek meghatározása a megadott ellenállásértékek alapján.

---

## 2. Eszközök 
- **NI myDAQ** 
- **Ellenállások:**
  - **számolás alapján:**
    - Rg/out =Ω
    - R1/2 =Ω
    - R3 =Ω
  - **méréskor használt:**
    - Rg =Ω
    - R1/2 =Ω
    - R3 =Ω
    - Rout =Ω
---

## 3. Elmélet

<details>

</details>

![Pi](https://github.com/user-attachments/assets/95e4a821-77a8-4a7e-a232-541bf97f85b0)


---

## 4. Szimuláció
A Pi-tagú csillapítás szimulációjából láthatjuk, hogy a bemeneti szinuszos jel csillapodik, mivel a kimeneti feszültség jelentősen kisebb, mint a bemeneti feszültség. A hálózat két ellenállásból és egy kapacitív elemből álló kombinációja széles frekvenciatartományban hatékonyan csökkenti a rezgési amplitúdót. A kimeneti feszültség csökkenése mutatja, hogy a rendszer hatékonyan elnyeli a rezgési energiát. A szimuláció grafikonokon ábrázolva pontos képet ad a Pi-tag csillapító teljesítményéről és hatékonyságáról.
<a href="https://tinyurl.com/27zr42a8" target="_blank">
![circuit-20241127-1204](https://github.com/user-attachments/assets/aede68db-8bc8-4f6e-b271-54708c6c6334)
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

Képletek forrása: https://www.electronics-tutorials.ws/attenuators/pi-pad-attenuator.html

**Aláírás:** ...

**Dátum:** ...
