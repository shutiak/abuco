# BUG-001: Odkaz v navigaci „Alcohol Sets“ přesměrovává na českou verzi místo anglické

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  
- URL: https://simply33food.com/en/  
- Jazyk: EN  

**Předpodmínky:**
- Uživatel je na úvodní stránce v anglické verzi (`/en/`).  

**Kroky k reprodukci:**
1. Najet na horní navigační menu a kliknout na odkaz „Menu“.  
2. Sjet dolů k sekci „Alcohol Sets“ nebo kliknout na přímý odkaz na tuto sekci v menu.  
3. Sledovat chování URL.  

**Skutečný výsledek:**
- Odkaz přesměruje na českou stránku: `https://simply33food.com/cz/menu/#alcohol-sets`.  

**Očekávaný výsledek:**
- Odkaz by měl přesměrovat na anglickou stránku: `https://simply33food.com/en/menu/#alcohol-sets`.  

**Závažnost:** Minor  
**Priorita:** Low  

**Přílohy:**  
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/0496f86e-d9ae-4f4e-bcfa-00bccbf3e2a8" />  
<img width="955" height="535" alt="image" src="https://github.com/user-attachments/assets/ed0b7024-8f5c-4eb6-acd3-e43b9d66e498" />  
