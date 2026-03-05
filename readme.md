# 🎰 Cheat The House
### _Versla het systeem. Word het systeem._

Cheat The House is een casino progression simulator ontwikkeld in **Unity (C#)**.

De speler start als straatgokker en werkt zich op tot eigenaar van een casino-imperium.  
De focus ligt op risico, economie, schaalbare systemen en uitbreidbare gameplay.

---

# 🧠 Technische Stack

- Engine: Unity (LTS)
- Programmeertaal: C#
- Architectuur: Component-based + Modulaire systeemopbouw
- Data Configuratie: ScriptableObjects
- Persistency: JSON Save System (gepland)
- Platform: PC (Steam)

---

# 🏗 Architectuur Overzicht

Het project volgt een gescheiden lagenstructuur:

Presentation Layer (UI)
↓
Game Logic Layer (Systems)
↓
Data Layer (ScriptableObjects / SaveData)


Belangrijk principe:

✔ UI kent Systems  
❌ Systems kennen geen UI  

Dit voorkomt spaghetti-code en maakt testen eenvoudiger.

---

# 🎮 Kernsystemen

## 💰 Economy System

Verantwoordelijk voor:
- Spelerbalans
- Inzetcontrole
- Uitbetalingen
- House edge berekening

