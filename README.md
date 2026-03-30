# rocnikovy-projekt

# ☕ Webová aplikace pro správu kavárny a objednávek

## 👥 Uživatelé a oprávnění
Aplikace umožňuje práci s uživatelskými účty a rozdělením rolí:
- uživatel se může registrovat a přihlásit do systému
- každý uživatel má přiřazenou roli:
  - zákazník
  - barista
  - administrátor
- podle role má uživatel přístup k různým funkcím aplikace

---

## 🖥️ Hlavní rozhraní (dashboard)
Po přihlášení se uživateli zobrazí přehledové rozhraní, které se mění podle jeho role:
- zákazník vidí nabídku a své objednávky
- barista má přehled o aktuálních objednávkách
- administrátor spravuje obsah a sleduje statistiky

---

## 🍰 Správa menu
Administrátor má možnost spravovat nabídku produktů:
- přidávání nových položek (např. nápoje, dezerty)
- úprava existujících položek
- odstranění položek z nabídky
- nastavení dostupnosti produktu

Každá položka obsahuje základní informace:
- název
- cenu
- kategorii

---

## 🧾 Objednávkový systém
Zákazník může vytvářet objednávky výběrem z nabídky:
- přidávání produktů do objednávky
- odeslání objednávky do systému

Barista následně objednávky zpracovává:
- zobrazení všech aktivních objednávek
- změna stavu objednávky:
  - přijatá
  - připravuje se
  - dokončená

---

## 🔄 Aktualizace stavu
Aplikace reaguje na změny v objednávkách:
- změna stavu objednávky se projeví v systému
- uživatel má přehled o aktuálním stavu své objednávky

---

## 📈 Přehledy a statistiky
Administrátor má k dispozici základní analytické funkce:
- počet vytvořených objednávek
- nejčastěji objednávané produkty
- přehled tržeb

Data mohou být zobrazena pomocí jednoduchých grafů.

---

## 📚 Historie
Systém uchovává záznamy o:
- minulých objednávkách
- aktivitě uživatelů

Uživatel si může zobrazit historii svých objednávek.

---

## 🧠 Shrnutí
Aplikace slouží jako komplexní nástroj pro správu kavárny a zpracování objednávek.  
Uživatelé pracují se systémem na základě své role, která určuje jejich oprávnění.  

Součástí aplikace je správa menu, objednávkový systém a přehledy o provozu.  
Důraz je kladen na jednoduchost ovládání, přehlednost a efektivní práci s daty.
