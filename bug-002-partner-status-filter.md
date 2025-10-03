# BUG-002: Vyhledávání nerespektuje nastavení stavů partnerů

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  
- URL: https://ut.a12.abuco.cz/operator/prehled-partneru  

**Předpodmínky:**
- Uživatel otevřel stránku „Přehled partnerů“ (`https://ut.a12.abuco.cz/operator/prehled-partneru`).  

**Kroky k reprodukci:**
1. Do pole **ID** zadat existující ID partnera `8`.  
2. Ověřit, že partner s ID `8` má stav **Čeká na schválení operátorem, Neaktivní**.  
3. Ve vyhledávacím formuláři zapnout přepínače **Schválený operátorem** a **Aktivní**.  
4. Kliknout na tlačítko **Hledat**.  

**Skutečný výsledek:**
- Ve výsledcích vyhledávání se zobrazí partner s ID `8`.  

**Očekávaný výsledek:**
- Výsledky vyhledávání by měly být prázdné, protože partner s ID `8` má stav **Čeká na schválení operátorem, Neaktivní**.  

**Závažnost:** High  
**Priorita:** High  

**Přílohy:**  
<img width="947" height="470" alt="image" src="https://github.com/user-attachments/assets/a1a5d006-6a8e-4bf0-a7b5-b1ff6b977581" />

