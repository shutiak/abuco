# BUG-001: Nepracuje vyhledávání partnerů podle názvu na stránce „Přehled partnerů“

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  
- URL: https://ut.a12.abuco.cz/operator/prehled-partneru  

**Předpodmínky:**
- Uživatel otevřel stránku „Přehled partnerů“ (`https://ut.a12.abuco.cz/operator/prehled-partneru`).  

**Kroky k reprodukci:**
1. Vybrat v seznamu existujícího partnera, např. *Springfield High School*.  
2. Zkopírovat název *Springfield High School*.  
3. Vložit tento název do pole **Partner/Organizace**.  
4. Zrušit zaškrtnutí u filtrů **Ověřený SMS**, **Schválený operátorem**, **Aktivní**.  
5. Kliknout na tlačítko **Hledat**.  

**Skutečný výsledek:**
- Nezobrazí se žádní partneři, kteří mají v názvu *Springfield High School*.  
- Nezobrazí se ani žádné chybové hlášení.  

**Očekávaný výsledek:**
- Zobrazí se partneři, jejichž název obsahuje *Springfield High School*.  
- Pokud vyhledávání selže, mělo by se zobrazit odpovídající chybové hlášení.  

**Závažnost:** High  
**Priorita:** High  

**Přílohy:**  
*(neposkytnuto)*
