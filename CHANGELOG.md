# Changelog

## v1.0.0 – 15.10.2025
**První veřejná verze ClickCreator**

### Hlavní funkce
- Přehledné grafické uživatelské rozhraní (GUI) postavené na Tkinteru.
- Možnost nastavení **počtu kliků**, které má program provést.
- Nastavení **rychlosti klikání (CPS)** až do 64 kliků za sekundu.
- Podpora **klávesové zkratky F6** pro snadné spuštění a zastavení klikání.
- Přesné časování kliků s minimalizací zpoždění.

### Další vlastnosti
- Multithreaded implementace pro hladký běh GUI i klikací logiky současně.
- Minimalizace zpoždění mezi kliky pomocí interní časové smyčky.
- Cross-platform styl GUI (Vista theme na Windows, default na ostatních systémech).
- Podpora pouze pro **Windows 10 a 11**.

### Optimalizace a bezpečnost
- PyAutoGUI PAUSE nastaven na 0 pro maximální rychlost.
- Robustní kontrola vstupu – zajištění, že uživatel zadá validní počet kliků.
- Program je určen **pouze pro testovací a automatizační účely**.

### Poznámky
- Verze 1.0.0 je první stabilní release – všechny hlavní funkce jsou implementovány.
- Následující verze budou obsahovat:
  - Možnost ukládání presetů pro různé rychlosti/počet kliků.
  - Vylepšenou podporu pro vyšší CPS a stabilitu při extrémním zatížení.
  - Přidání logování kliků a statistiky CPS.

