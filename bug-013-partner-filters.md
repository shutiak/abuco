# BUG-013: Filtry „Schválený operátorem“ a „Aktivní“ při vyhledávání partnerů nefungují správně

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  
- URL: 

**Předpodmínky:**
- Uživatel otevřel stránku „Partneři“ (https://ut.a12.abuco.cz/operator/prehled-partneru  ).  

**Kroky k reprodukci:**
1. V hledacím formuláři zapnout přepínač **Schválený operátorem**.  
2. Kliknout na tlačítko **Hledat**.  
3. Prohlédnout seznam výsledků.  

**Skutečný výsledek:**
- Výsledky obsahují i partnery, kteří **nebyli schváleni operátorem** nebo **nejsou aktivní**, přestože filtry byly nastaveny.  

**Očekávaný výsledek:**
- Při zapnutí přepínače **Schválený operátorem** se mají zobrazit pouze partneři, kteří byli skutečně schváleni.  
- Při zapnutí přepínače **Aktivní** se mají zobrazit pouze aktivní partneři.  

**Závažnost:** High  
**Priorita:** High  

**Přílohy:**  
<img width="938" height="481" alt="image" src="https://github.com/user-attachments/assets/fa70cd0b-5f3e-439c-9408-d0992a7898d0" />

