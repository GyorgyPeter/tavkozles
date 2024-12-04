
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:** György Péter
**A mérés tárgya:** Johansson 6700 Profiler
**A mérés száma:**  07
**A mérés dátuma:**  2024.12.04
**A mérést vezette:** Sándor Péter  

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:**   V3 labor

---

## 1. Mérés célja

A gyakorlat célja, hogy a diákok elsajátítsák a Johansson 6700 Profiler antennaerősítő-szűrő beállításainak gyakorlati használatát különböző antennák jeleinek kezelésére. A feladat során a diákok beállítják a csatornákat, optimalizálják a jelszinteket és vizsgálják a bejövő és kimenő jeleket spektrum analizátor segítségével.

---

## 2. Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| Profiler  |                Johansson 6700              | 28806          |
| Spektrum Analizátor                 | Metek HDD          | 211112002390|
| DVB-T Szoba Antenna                       | Smart HD 550     | ...    |
| FM Antenna                       | Hurok-Dipolus     | ...    |

---

## 3. Mérési helyszín és környezet
**Antenna magassága:** 1,65 Méter
**Időjárás:** 5°C, Sűrű köd
**Adó távolsága:**  ~780 Méter

---

## 4.  Mérés
| Antenna típusa    | Eredeti csatorna  | Áthelyezett csatorna | Eredeti frekvencia | Áthelyezett frekvencia | Bemeneti jelszint (dBu) | Kimeneti jelszint (dBu) |
|--------------------------|-------------------|----------------------|--------------------|------------------------|------------------------|------------------------|
| DVB-T Szoba Antenna | 28         | 41            | 530 Mhz            | 634 MHz                |             61          | ~100           |
| DVB-T Szoba Antenna | 31         | 42            | 554 MHz            | 642 MHz                |             64          | ~100           |
| DVB-T Szoba Antenna | 35         | 43            | 586 MHz            | 650 MHz                |             62          | ~100           |
| DVB-T Szoba Antenna | 41         | 44            | 634 MHz            | 658 MHz                |             48          | ~100           |
| DVB-T Szoba Antenna | 45         | 45            | 666 MHz            | 666 MHz                |             63          | ~100           |
| DVB-T Szoba Antenna | 48         | 46            | 690 MHz            | 674 MHz                |             58          | ~100           |

---

## 5. Mérési eredmények elemzése
Az adatok alapján az alábbi következtetéseket lehet levonni:

- Az avasi adótoronyról érkező csatornákat sikeresen befogtuk és rendeztük.
- Az rendendezés után egymás követték a csatornák és a spektrum analizátor ábrázolta is ezt.
- A johansson eszközben állítottunk egy 100 dBu-s erősítést is beállítottunk a kimenő csatornákra. 
  <details open>
  <summary>Spektrum analizátor előtte utánna</summary>
    
  ![its_snapshot_0004](https://github.com/user-attachments/assets/2f111542-4d61-4703-ab87-aa67ebedad50)
  ![its_snapshot_0003](https://github.com/user-attachments/assets/d9c9e5ed-3fe1-4a06-98a5-6dd57d3704b3)

  </details>
 
---

## 6. Konklúzió
A mérési folyamat során sikeresen végrehajtottuk a beérkező csatornák áthelyezését a Johansson 6700 Profiler antennaerősítő-szűrő segítségével. Az eszközt megfelelően konfiguráltuk, így a különböző antennák jeleit optimálisan kezeltük. Az áthelyezett csatornák közötti átmenet hibamentesen zajlott, és a spektrum analizátor segítségével nyomon tudtuk követni az eredményeket, melyek jól illeszkedtek az elvárásokhoz.

Az eszköz beállításainak finomhangolása során a kimeneti jelszintek stabilizálódtak, és sikeresen elértük a kívánt 100 dBu-s erősítést, amely lehetővé tette a csatornák megfelelő teljesítményének biztosítását. A mérések során tapasztalt zökkenőmentes működés és az eredmények megerősítették a beállítások hatékonyságát. A mérés során alkalmazott műszerek pontosan rögzítették a jelek viselkedését, és az adatok egyértelműen visszaigazolták a csatornák áthelyezésének sikerét.
