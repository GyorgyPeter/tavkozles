# *MÉRÉSI JEGYZŐKÖNYV*

***A mérést végző neve:** György Péter*  ((szija)Hivatalosan Vad Leventétől)  
***A mérés tárgya:** Ampitudómoduláció vizsgálata GRF-1300A trénerrel*  
***A mérés száma:** 3B*  
***A mérés dátuma:** 2025.02.10*  
***A mérést vezette:** Sándor Péter*  

***Évfolyam:** 13. E*  
***Csoport:** GYAK 2*  
***Helyszín:** V3 Lab*  

---

## 1. *Mérés célja*

*Ez a mérés az amplitúdómoduláció (AM) alapjainak megértését szolgálja a GRF-1300A tréner használatával. A modulációs paraméterek vizsgálata és a spektrumanalizátor alkalmazása révén lehetőség nyílik a jelszint, sávszélesség és modulációs mélység mérésére.*

---

## 2. *Eszközök*

|  *Eszköz*  |  *Név/Tipus*  | Sorozat szám|
|----------|-------------|-----------|
|RF komunikációs Tréner|GRF-1300A|GEX913036|
|Spektrum Analizátor|Gw INSTEK GSP-730 |GEX120304|
|Oszciloszkóp|Rohde&Schwarz HMO 1002 Series|3593.1764K02-102609-WG|
|RF kábel|100mm Mikrokoaksz 1db|
||200mm Mikrokoaksz 1db|
||800mm Mikrokoaksz 1db|
|AC Powercord|100-240V ~ 50-60Hz|
|Adapter|N-SMA Adapter|
|Student Textbook|RF & Communication Trainer|

<details>

***<summary>Képek és leírások:</summary>***

**GRF-1300A**  
<details>

<summary>Kép és leírás:</summary>
 
*Leírás: https://www.gwinstek.com/en-global/products/detail/GRF-1300A*
 ![GRF-1300A](https://github.com/user-attachments/assets/fcc581d3-ce2f-4d83-90f4-6f88582c2590) 
 
</details>

**Rohde&Schwarz HMO 1002 Series**  
<details>
 
<summary>Kép és leírás:</summary>
 
*Leírás: https://www.rohde-schwarz.com/manual/hmo1002/*
 ![Képernyőkép 2025-02-10 125359](https://github.com/user-attachments/assets/84bfcd79-59d9-41f8-8049-a2df205e6c98)

</details>

**GSP-730**
<details>
 
<summary>Kép és leírás:</summary>
 
*Leírás: https://www.gwinstek.com/en-global/products/detail/GSP-730*
![Képernyőkép 2025-02-10 120314](https://github.com/user-attachments/assets/a581b7a4-3416-4364-97c1-c13bb695633a)

</details>

**RF kábel**
<details>
 
<summary>Kép:</summary>
 
![Képernyőkép 2025-02-10 120913](https://github.com/user-attachments/assets/d256b722-1a14-4a2a-a3e3-eda4be041d5c)

</details>

</details>

---

## 3. *Mérés menete*

**1. Lépés:**
A GRF-1300A, a GSP-730-at az alábbi módon vezetékekkel csatlakoztattuk:  

![Képernyőkép 2025-02-10 124124](https://github.com/user-attachments/assets/7f27b2f2-4c10-496c-bdd9-0459caa582b0)

A Rohde & Schwarz HMO 1002 Series Oszciloszkóp Ch1 csatornályát a GRF-1300A BaseBand részéhez csatlakoztattuk.  
**2 Lépés:**  
A GRF-1300A trénert RF syntesizer/FM részén beálítottuk a 880MHz vivőfrekvenciát. A BaseBand-nél pedig a 100kHz-s sinuszos moduláló jelet 100%-os modulációs mélységgel.  
**3. Lépés:**  
Ac HMO 1002-es Oszcilloszkópot finomhangoljuk hogy megfigyelhessük a 100kHz-s moduláló jelet, A GSP-730 Spektrumanalizátort pedig beállítjuk a fentebb említet modulált jel megfigyeléséhez, és lejegyezzük a mért eredményeket.  
**4. Lépés:**  
A GRF-1300A trénert RF syntesizer/FM részén beálítottuk a 900MHz vivőfrekvenciát. A BaseBand-nél pedig a 500kHz-s sinuszos moduláló jelet 63%-os modulációs mélységgel. Az eredményeket ismét lejegyezzük.

---

## 4 *Mérési eredmények*

### 880 MHz-s mérési eredmények:
**Vpp:** *1.09V*  
**Carrier power:** *30.9 dBm*  
**Modulációs mélység:** *6 dB*  
**Sávszélesség/Bandwidth:** *5 MHz*  

**Vélemény az eredményről:**  
Az 880 MHz vivőfrekvencián az AM jel jellemzői közé tartozik az 1.09V Vpp, 30.9 dBm carrier power, 6 dB modulációs mélység és 5 MHz sávszélesség. Ez az alacsonyabb modulációs mélység kevésbé intenzív modulációt jelent, ami kisebb oldalsávokat eredményez.

<details>

***<summary>Képek a mérési eredményekről:</summary>***

GSP-730:  
![SCR00](https://github.com/user-attachments/assets/c4a8f286-168e-4b6e-8d1c-cc62a674c242)  
HMO 1002:  
![TA01](https://github.com/user-attachments/assets/8c53204a-903f-40b2-afab-c482f516b973)  

</details>

### 900 MHz-s mérési eredmények:
**Vpp:** *1.20*  
**Carrier power:** *32.1 dBm*  
**Modulációs mélység:** *10 dB*  
**Sávszélesség/Bandwidth:** *5 MHz*  

**Vélemény az eredményről:**  
A 900 MHz vivőfrekvencián az AM jel jellemzői közé tartozik az 1.20V Vpp, 32.1 dBm carrier power, 10 dB modulációs mélység és 5 MHz sávszélesség. A nagyobb modulációs mélység intenzívebb modulációt eredményez, ami szélesebb oldalsávokat jelent.

<details>

***<summary>Képek a mérési eredményekről:</summary>***
 
GSP-730:  
![SCR01](https://github.com/user-attachments/assets/77ecc778-82b5-41f6-ab6a-e947a33614ba)  
HMO 1002:  
![TA02](https://github.com/user-attachments/assets/c0c42b46-03e4-4809-b854-3a6c8a17eb63)  

</details>

---

## 5. Konklúzió:
**900 MHz mérés hátrányai:** A 900 MHz-es mérés nagyobb modulációs mélysége (10 dB) intenzívebb modulációt és szélesebb spektrális eloszlást eredményez, ami potenciálisan több zavaró jelenséget okozhat, és nagyobb energiafogyasztást igényelhet a jeltovábbítás során. A 880 MHz-hez képest a 900 MHz-es mérés rosszabb, mert intenzívebb modulációt és szélesebb sávszélességet eredményez, ami kevésbé hatékony spektrumhasználatot jelenthet.

---
