# BUG-003: Ve výběrovém seznamu „Metoda“ na stránce Reporty neprobíhá validace podle zvoleného platebního způsobu

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  
- URL: https://ut.a12.abuco.cz/admin/requisition/  

**Předpodmínky:**
- Uživatel otevřel stránku „Reporty“ (`https://ut.a12.abuco.cz/admin/requisition/`).  

**Kroky k reprodukci:**
1. Ve formuláři pro filtrování a vyhledávání transakcí najít rozbalovací seznam **Metoda**.  
2. Vybrat možnost **Pays / Bankovní převod**.  
3. Kliknout na tlačítko **Hledat**.  

**Skutečný výsledek:**
- Filtrování dat podle platební metody se neprovede.  

**Očekávaný výsledek:**
- Po zvolení konkrétní platební metody se zobrazí pouze platby, které odpovídají podmínce filtrování a byly uhrazeny metodou **Pays** nebo **Bankovní převod**.  

**Závažnost:** Medium  
**Priorita:** Low  

**Přílohy:**  
<img width="941" height="469" alt="image" src="https://github.com/user-attachments/assets/afd3f83f-faf3-4535-a51f-1fafef0602cf" />

