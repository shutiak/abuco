# BUG-005: Na stránce „Reporty“ chybí ve výsledkové tabulce sloupec „Datum zaplacení“, přestože existuje filtrování podle tohoto údaje

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  
- URL: https://ut.a12.abuco.cz/admin/requisition/  

**Předpodmínky:**
- Uživatel otevřel stránku „Reporty“ (`https://ut.a12.abuco.cz/admin/requisition/`).  

**Kroky k reprodukci:**
1. Ve vyhledávacím formuláři zvolit v poli **Datum zaplacení od** datum `08/01/2025`.  
2. Ve vyhledávacím formuláři zvolit v poli **Datum zaplacení do** datum `10/03/2025`.  
3. Kliknout na tlačítko **Hledat**.  
4. Zkontrolovat výsledky filtrování objednávek.  

**Skutečný výsledek:**
- Konkrétní data zaplacení nelze ve výsledcích vyhledávání zobrazit.  
- Údaj **Datum zaplacení** chybí také v modálním okně **Detaily objednávky**.  

**Očekávaný výsledek:**
- Datum zaplacení by mělo být možné zobrazit buď ve zvláštním sloupci výsledkové tabulky, nebo v modálním okně **Detaily objednávky**.  

**Závažnost:** Medium  
**Priorita:** Low  

**Přílohy:**  
<img width="953" height="469" alt="image" src="https://github.com/user-attachments/assets/7a28ba1f-f72d-481d-9d2a-2db69e45459e" />

