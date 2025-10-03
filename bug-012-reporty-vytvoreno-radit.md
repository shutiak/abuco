# BUG-012: Řazení podle sloupce „Vytvořeno“ na stránce Reporty nefunguje (vzestupně/sestupně)

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  

**Předpodmínky:**
- Uživatel otevřel stránku „Reporty“ (`https://ut.a12.abuco.cz/admin/requisition/`) s tabulkou plateb.  

**Kroky k reprodukci:**
1. V tabulce kliknout na záhlaví sloupce **Vytvořeno** pro řazení vzestupně.  
2. Znovu kliknout na záhlaví sloupce **Vytvořeno** pro řazení sestupně.  
3. Porovnat pořadí záznamů (datum/čas) po každém kliknutí.  

**Skutečný výsledek:**
- Po kliknutí se pořadí záznamů nezmění, nebo je řazení nesprávné (neodpovídá chronologii).  

**Očekávaný výsledek:**
- Při prvním kliknutí se záznamy správně seřadí **vzestupně** podle data a času ve sloupci **Vytvořeno**.  
- Při druhém kliknutí se záznamy správně seřadí **sestupně**.  
- Řazení musí respektovat skutečné datum a čas, nikoliv lexikografický řetězec.  

**Závažnost:** Medium  
**Priorita:** Medium  

**Přílohy:**  
<img width="944" height="464" alt="image" src="https://github.com/user-attachments/assets/d94b7b91-ceb1-4397-a95b-863bb0491e8b" />

