
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
    - Rg/out = 1,5 Ω
    - R1/3 = 4514.16 Ω
    - R1 = 1120.59 Ω
  - **méréskor használt:**
    - Rg =Ω
    - R1 = párhuzamosan  Ω
    - R2 = párhuzamosan  Ω
    - R3 = párhuzamosan  Ω
    - Rout =  Ω
 
---

## 3. Elmélet

A Pi-pad csillapítót azért nevezik így, mert alapvető elrendezése és felépítése hasonlít a görög pi (π) betűre. Ebben a konfigurációban az ellenállások energiaveszteséget okoznak, ami csökkenti a rezgés amplitúdóját és stabilizálja a rendszert. Az ellenállások értékétől függően különböző mértékű csillapítást érhetünk el, ami közvetlenül befolyásolja a kimeneti feszültség nagyságát. Bár ez a rendszer kevésbé hatékony széles frekvenciatartományban, mégis képes csökkenteni a nem kívánt rezgéseket, és javítja a rendszer stabilitását egyszerűbb alkalmazásokban.

![attenuators-attn39](https://github.com/user-attachments/assets/b8cbdfca-ee9c-4d19-97e2-3ee155769aba)


![Pi](https://github.com/user-attachments/assets/95e4a821-77a8-4a7e-a232-541bf97f85b0)


---

## 4. Szimuláció
A szimulációban megfigyelhető, hogy az ellenállások hatására a bemeneti feszültség jelentősen csökken, ami a rezgési energia elnyelésére utal. A kizárólag ellenállásokkal működő rendszer hatékonyan csökkenti a rezgés amplitúdóját, bár nem olyan széles frekvenciatartományban, mint kapacitív elemekkel kiegészítve. Az energiaveszteség révén a rendszer stabilabbá válik, mivel csökkenti a nem kívánt rezgések amplitúdóját. Összességében a rendszer hatékonyan javítja a mechanikai rendszer működését és élettartamát, bizonyítva, hogy az ellenállások önmagukban is hasznosak a rezgéscsillapításban.

<a href="https://tinyurl.com/27zr42a8" target="_blank">
  
![circuit-20241127-1204](https://github.com/user-attachments/assets/aede68db-8bc8-4f6e-b271-54708c6c6334)

</a>

## 5. Gyakorlatban/Számítások

- ***Breadboardon összerakva***
  
  CH0 a bemeneti feszülstég CH1 pedig a kimeneti fesz. Szépen látszódik hogy a CH1 feszültsége nagyyábol a fele a CH0-nak.
  A jelgenerátoron 1KHz-s 5V váltakozó feszültséget állítottunk be.
<details>

</details>

- ***Ellenállások számítása***

**R1/3=** $Z \times (\frac {K+1}{K-1}) = 1,5k \times (\frac {1,9953+1}{1,9953-1} = 4,51k)$

**R2=** $Z \times (\frac {K^2-1}{2K}) = 1,5k \times (\frac {1,9953^2-1}{2 \times 1,9953}) = 1,12k$

**Aláírás:** ...

**Dátum:** ...

Forrás: https://www.electronics-tutorials.ws/attenuators/pi-pad-attenuator.html
