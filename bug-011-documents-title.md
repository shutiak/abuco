# BUG-011: Nesprávný název v menu – místo „Dokuments“ má být „Dokumenty“

**Prostředí:**
- Zařízení: Windows 11  
- Prohlížeč: Chrome 138.0  

**Předpodmínky:**
- Uživatel otevřel stránku „Dokuments“ (`https://ut.a12.abuco.cz/admin/dokumenty/`).  

**Kroky k reprodukci:**
1. Zkontrolovat název v postranním menu, v záložce prohlížeče (HTML `<title>`) a případně v dalších prvcích rozhraní.  

**Skutečný výsledek:**
- V postranním menu se zobrazuje text **„Dokuments“**.  

**Očekávaný výsledek:**
- Na všech místech se má zobrazovat správný český název **„Dokumenty“**.  

**Závažnost:** Low  
**Priorita:** Low  

**Přílohy:**  
<img width="956" height="470" alt="image" src="https://github.com/user-attachments/assets/675040c9-3e63-4cd8-810e-69c25305b787" />

