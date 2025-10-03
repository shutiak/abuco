# BUG-001: Vyhledávání partnerů podle názvu nefiltruje výsledky na stránce „Přehled partnerů“

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
- Zobrazí se **všichni partneři**, místo aby byl seznam omezen pouze na ty s názvem *Springfield High School*.  

**Očekávaný výsledek:**
- Zobrazí se pouze partneři, jejichž název obsahuje *Springfield High School*.  

**Závažnost:** High  
**Priorita:** High  

**Přílohy:**  
<img width="950" height="492" alt="image" src="https://github.com/user-attachments/assets/686900e5-d91f-4173-9afa-5053201195b1" />

