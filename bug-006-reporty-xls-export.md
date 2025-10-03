# BUG-006: Export výsledků vyhledávání do XLS na stránce „Reporty“ generuje prázdný soubor

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  
- URL: https://ut.a12.abuco.cz/admin/requisition/  

**Předpodmínky:**
- Uživatel otevřel stránku „Reporty“ (`https://ut.a12.abuco.cz/admin/requisition/`).  
- Uživatel provedl filtrování dat podle pole **Datum zaplacení od** `08/01/2025` a **Datum zaplacení do** `10/03/2025`.  

**Kroky k reprodukci:**
1. Sjet na konec tabulky.  
2. Kliknout na tlačítko **Export do XLS**.  
3. Počkat na stažení souboru.  
4. Otevřít soubor v aplikaci **MS Excel**.  

**Skutečný výsledek:**
- Soubor je prázdný a obsahuje pouze zprávu: *„Opps, this seems to be broken...“*.  

**Očekávaný výsledek:**
- Stažený soubor obsahuje validní data podle zvoleného filtrování.  

**Závažnost:** Medium  
**Priorita:** Low  

**Přílohy:**  
[seznam-objednavek-20251003-184347.xls](https://github.com/user-attachments/files/22684680/seznam-objednavek-20251003-184347.xls)
<br>
<img width="959" height="538" alt="image" src="https://github.com/user-attachments/assets/700dda0c-3c87-4467-b95b-f81d54b11f63" />





