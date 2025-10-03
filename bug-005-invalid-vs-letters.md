# BUG-005: Variabilní symbol (VS) obsahuje neplatné znaky – písmena

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  

**Předpodmínky:**
- Uživatel otevřel stránku s přehledem reportů (https://ut.a12.abuco.cz/admin/requisition/)  

**Kroky k reprodukci:**
1. Otevřít seznam plateb.  
2. Zkontrolovat sloupec **VS (Variabilní symbol)**.  
3. Najít platby, kde variabilní symbol obsahuje písmena.  

**Skutečný výsledek:**
- V některých platbách se u variabilního symbolu zobrazují písmena (např. „Premium“).  

**Očekávaný výsledek:**
- Variabilní symbol může obsahovat pouze číslice (0–9), max. 10 znaků.  
- Platby s neplatným VS by neměly být přijaty nebo by měly být jasně označeny jako chybné.  

**Závažnost:** High  
**Priorita:** High  

**Přílohy:**  
<img width="941" height="470" alt="image" src="https://github.com/user-attachments/assets/adf6fa35-956b-41e1-adc3-c2425ee13360" />

