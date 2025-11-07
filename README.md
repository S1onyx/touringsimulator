# 🧠 Turing Machine Simulator – Kurzbeschreibung

Ein Online-Tool zum Erstellen, Testen und Visualisieren von **Turingmaschinen** im Browser:  
👉 [https://turingmachinesimulator.com/](https://turingmachinesimulator.com/)

---

## ⚙️ Syntax

### Konfiguration
```text
name: [Name der Maschine]
init: [Startzustand]
accept: [Akzeptierzustand 1], [Akzeptierzustand 2], ...
```

### Übergangsfunktion (Delta-Funktion)
```text
[current_state],[read_symbol]
[new_state],[write_symbol],[>|<|-]
```

| Symbol | Bedeutung          |
|---------|--------------------|
| `>`     | Kopf nach rechts   |
| `<`     | Kopf nach links    |
| `-`     | Kopf bleibt stehen |
| `_`     | Leeres Feld (Blank) |

---

Lade dein Programm hoch, klicke **Compile**, gib eine Eingabe ein und starte die Simulation mit **Play** oder **Step**.
