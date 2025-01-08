
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** Szabó Kristóf

**A mérés tárgya:** Tranzisztor működésének vizsgálata

**A mérés száma:** 08

**A mérés dátuma:** 2025. 01. 08.

**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3 Labor 

---

## 1. Mérés célja

Tranzisztor működésének vizsgálata a bemeneti feszültség változtatásával

### Kapcsolási rajz

![circuit-20250108-1302](https://github.com/user-attachments/assets/ca2c6a63-7281-4e96-9e3a-a007e45bdbfa)


---

## 2. Alkalmazott mérőeszközök és készülékek

| Műszer neve          | Típus | Gyártási szám |
| ---------------------| ------| ------------- |
| National Instruments | myDAQ |  |
| Metec                | M3800 |  |

---

## 3. Alkatrész adatok
  R1 = 220 $\Omega$
  
  R2 = 1.489k $\Omega$
  
  $\beta$ = 87

---

## 4. Mért vs Szimulált eredmények

| Ube [V] | Urc [V] | Ic [A]  | | Ube [V] | Urc [V]| Ic [A]|
| ------- | ------- | ------- |-| ------- | ------ | ------ |
|    0    |   0,0   |    0    | |    0    |   0    |   0    |
|   0,4   |   0,1m  |   450n  | |   0,4   | 114,45u|  520n  |
|   0,5   |   3,3m  |   15u   | |   0,5   |  5,38m |  24,5u |
|   0,6   |  118,7m |   539u  | |   0,6   | 160,94m| 731,6u |
|   0,7   |   906m  |   4,1m  | |   0,7   | 881,1m |   4m   |
|   0,8   |   2,06  |   9,36m | |   0,8   |  1,9   |  8,7m  |
|   0,9   |   2,38  |  10,81m | |   0,9   |  2,97  |  13,5m |
|    1    |   2,4   |  10,91m | |    1    |  3,05  |  13,8m |
|   1,2   |   2,3   |  10,45m | |   1,2   |  3,07  |   14m  |
|   1,4   |   2,29  |  10,41m | |   1,4   |  3,08  |   14m  |
|   1,6   |   2,26  |  10,27m | |   1,6   |  3,09  |  14,1m |
|   1,8   |   2,28  |  10,36m | |   1,8   |  3,098 |  14,1m |
|    2    |   2,29  |  10,41m | |    2    |   3,1  |  14,1m |

<details>
<summary>Szimuláció link</summary>

  https://www.falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBsBmALAJhQdgWgJwAcYKCFIGaIWICk9ApgLRhgBQA7lLQirzSQM4DgHNBwwVkayOAFxAsMxWhllqNEGAmIpCCfCjC40KFeyjQUNhCcJ5sWIVlXFcIACZMAZgEMAVwAbeQ4AJyUVTSUHaMYwFUIOMjp4lA0sLBE6b39g+RYgpk9wXllYTgA3JXY6IRE2MDosjUZ1WjKrBG4appB6yRFIHrStV1EI+PHGYgyZDgAlXlneKI12pFboboAHKjc21SbVGi14c56olZm5Hijj3gfhnhZYlt7m9qwOIA
  
</details>

---

## 5. Mérési eredmények elemzése

Az adatok alapján az alábbi következtetéseket lehet levonni:

- 1V feszültség felett minimális változások vehetők észre az Rc ellenállást mérve
- A mért és a szimulált áramkör között jelentős eltérések vannak

---
## 6. Grafikon
  <details>
    <summary>Mért eredmények grafikon:</summary>
    
![Névtelen terv](https://github.com/user-attachments/assets/c1d97db0-96c2-4d86-a29e-64e72a13c595)
  </details>

  <details>
    <summary>Szimulált eredmények grafikon:</summary>
    
![Névtelen terv (1)](https://github.com/user-attachments/assets/6f1d00e0-ce2a-467f-97b3-5efd7d8e7570)
  </details>
