# 🧮 Taschenrechner (Java)

## 📖 Beschreibung
Ein einfacher Taschenrechner, entwickelt in Java.  
Er kann Addition ➕, Subtraktion ➖, Multiplikation ✖️ und Division ➗ durchführen.  
Der Code basiert auf einem Tutorial und wurde von mir zum Lernen verwendet.

## ⚙️ Funktionen
- ➕ Addition
- ➖ Subtraktion
- ✖️ Multiplikation
- ➗ Division

## 🎯 Lernziel
- 💻 Java installieren (bzw. alle nötigen Programme, die man braucht)  
- 🌐 Einen GitHub-Account erstellen und erstes GitHub-Projekt anlegen  
- 📝 Erste Einblicke in die Programmierung bekommen, indem ich ein Tutorial 1:! nachgemacht habe
- 🎨 Den Taschenrechner optisch anpassen, indem ich Farben und Buttons geändert habe

## 🎨 Änderungen am Design
Ich habe den Taschenrechner modernisiert, indem ich **Farben und Button-Darstellung** angepasst habe.

**1. Farben:**  
| Farbe         | Vorher                 | Nachher                                   |
| ------------- | ---------------------- | ----------------------------------------- |
| Light Gray    | ⬜ `Color(212,212,210)` | ⬜ `Color(210,210,210)` (leicht heller)    |
| Dark Gray     | ◼️ `Color(80,80,80)`   | ◼️ `Color(50,50,60)` (dunkler/bläulich)   |
| Black         | ⬛ `Color(28,28,28)`    | ⬛ `Color(20,20,30)` (dunkler)             |
| Orange zu Blau | 🟧 `Color(255,149,0)`  | 🟦 `Color(0,122,255)` (Blau statt Orange) |

**2. Buttons:**
| Eigenschaft | Vorher                | Nachher  |
| ----------- | --------------------- | -------- |
| Button-Rand | sichtbar              | entfernt |
| Fokusrahmen | sichtbar beim Klicken | entfernt | 

| Eigenschaft | Vorher                                          | Nachher                                               |
| ----------- | ----------------------------------------------- | ----------------------------------------------------- |
| Button-Rand | `button.setBorder(new LineBorder(customBlack))` | `button.setBorder(BorderFactory.createEmptyBorder())` |
| Fokusrahmen | `Standard sichtbar beim Klicken`                | `button.setFocusPainted(false)`                       |
