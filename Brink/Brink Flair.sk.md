# Brink Flair 400 — Modbus (RS‑485) zapojenie a aktivácia

Tento návod popisuje **čisto elektrické zapojenie** Modbusu na jednotke Brink Flair 400 a **postup aktivácie v menu**. Konkrétne parametre Modbusu (adresy, baudrate, registre …) zámerne **neuvádzame** – sú súčasťou samostatnej šablóny.

---

## 1) Bezpečnosť

- Pred akoukoľvek prácou **odpojte jednotku od napájania** vytiahnutím sieťovej vidlice. Ide o výrobcom uvádzaný postup pri práci na zariadení.  [oai_citation:0‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)

---

## 2) Konektory pre Modbus na Flair 400

Podľa verzie dosky použite **červený 3‑pinový konektor**:

- **Štandardná doska UWA2‑B (Basic pcb)**: konektor **X15** (Modbus / InternalBus).  [oai_citation:1‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
- **Plus doska UWA2‑E (Plus pcb)**: konektor **X06** (Modbus).  [oai_citation:2‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)

**Vyznačenie pinov (smerovanie je uvedené v elektrickej schéme):**

1. **RS485‑GND**  
2. **RS485‑A**  
3. **RS485‑B**   [oai_citation:3‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)

> Poznámka: V manuáli je tento 3‑pin zobrazený v kruhovom detaile „ModBus“ s číslovaním *1=RS485‑ground, 2=RS485‑A, 3=RS485‑B*.  [oai_citation:4‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)

---

## 3) Jumpre a zakončenie (terminácia)

Na doskách sú výrobcom pripravené prepojky (jumpre) pre voľbu zbernice a zakončenie RS‑485:

- **X12 = 120 Ω Modbus terminácia na UWA2‑B**  
  – **použite len vtedy**, ak je jednotka **na konci** Modbus zbernice; inak **jumper X12 vyberte**.  [oai_citation:5‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)
- **X121 a X122 (UWA2‑B)**  
  – pri **Modbus aplikácii majú byť odstránené** (nezasunuté).  [oai_citation:6‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)
- **X07 (UWA2‑E, Plus pcb)**  
  – pri použití Plus dosky sa má **jumper X07 vybrať** (pozri popis pri schéme).  [oai_citation:7‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)

> Výrobca zároveň uvádza, že funkcia konektora X15/X06 (InternalBus/Modbus) sa volí v menu krokmi 14.1–14.4 – pozri časť *Aktivácia v menu*.  [oai_citation:8‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)

---

## 4) Odporúčaná kabeláž a topológia

- Vedenie: **dvojvodič RS‑485 (twisted pair) + referenčná zem (GND)**, vedené na pin 1 (GND), 2 (A), 3 (B).  [oai_citation:9‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
- **Termináciu 120 Ω** používajte **iba na oboch koncoch** zbernice (vstavaná koncová terminácia je na UWA2‑B pod jumperom X12; pri Plus pcb sa rieši zvlášť podľa schémy).  [oai_citation:10‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)
- Pri kaskáde viacerých Brink zariadení sa Modbus pripája **na „Master“ jednotku s Plus PCB UWA2‑E**.  [oai_citation:11‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/modbus-uwa2-b-uwa2-e-installation-regulations-614882.pdf)

---

## 5) Postup zapojenia (krok za krokom)

1. **Odpojte napájanie** jednotky (vytiahnite sieťovú vidlicu).  [oai_citation:12‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
2. Otvorte kryt nad elektronikou a **nájdite príslušný konektor**:  
   - UWA2‑B: **X15 (červený 3‑pin)**,  
   - UWA2‑E: **X06 (červený 3‑pin)**.  [oai_citation:13‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
3. **Nastavte jumpre** pre Modbus podľa kapitoly *Jumpre a zakončenie* (X12 – terminácia podľa pozície na zbernici; **X121, X122 odstrániť**; pri Plus pcb **X07 odstrániť**).  [oai_citation:14‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
4. **Pripojte vodiče RS‑485** na 3‑pinový konektor:  
   - pin **1 = GND**, pin **2 = A**, pin **3 = B**; dodržte polaritu A↔A, B↔B po celej linke.  [oai_citation:15‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
5. Skontrolujte, že **terminácia 120 Ω** je prítomná **iba** na koncových uzloch (na UWA2‑B je to jumper **X12**).  [oai_citation:16‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
6. Zatvorte kryt a **znovu pripojte napájanie**.

---

## 6) Aktivácia Modbusu v menu jednotky

1. Na dotykovom displeji otvorte **Settings / Nastavenia**.  
2. V časti **14 – Communication (Komunikácia)** nastavte položku **14.1 „Type of Bus connection“ = *Modbus***. (Ostatné položky komunikácie nechajte podľa vašej šablóny.)  [oai_citation:17‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/modbus-uwa2-b-uwa2-e-installation-regulations-614882.pdf)  
3. Poznámka výrobcu: **keď je Modbus aktívny**, režim vetrania **nie je možné meniť** cez displej ani prípadný viacrežimový prepínač; **prípadné RH čidlo nebude funkčné** (riadenie prebieha cez Modbus).  [oai_citation:18‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)

---

## 7) Rýchla kontrola

- Po výbere *Modbus* v kroku 14.1 a po správnom zapojení vodičov by mala nadriadená zbernica (BMS/PLC) nadviazať komunikáciu s jednotkou. **Parametre komunikácie a registre** nastavte podľa vašej šablóny.

---

### Referencie výrobcu
- **Flair 400 – Installation regulations** (kap. 5.5.6–5.5.9, elektrická schéma str. 35–36).  [oai_citation:19‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/flair-400-installation-regulations-614895.pdf)  
- **Modbus UWA2‑B/UWA2‑E – Installation regulations** (popis Modbus, kroky pripojenia, nastavenie krok 14.1).  [oai_citation:20‡Brink Climate Systems](https://www.brinkclimatesystems.nl/documenten/modbus-uwa2-b-uwa2-e-installation-regulations-614882.pdf)