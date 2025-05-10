# ⏰ Alarm Clock – Java konzolová aplikace

Tento jednoduchý Java projekt slouží jako konzolový budík. Uživatel zadá čas ve formátu `HH:mm:ss` a aplikace odpočítává aktuální čas. Po dosažení nastaveného času se spustí zvukový alarm (formát `.wav`), který lze vypnout stiskem klávesy Enter.

---

## 🧠 Funkce

- Uživatelský vstup času ve formátu `HH:mm:ss`
- Kontrola formátu a chyb
- Odpočítávání času s živým výpisem
- Automatické přehrání zvuku při dosažení času
- Možnost manuálního vypnutí alarmu

---

## ▶️ Spuštění

1. Nahraj projekt do IDE (např. IntelliJ, Eclipse)
2. Ujisti se, že máš `.wav` soubor ve složce projektu  
   (nebo uprav cestu ve třídě `Main.java` u proměnné `filePath`)
3. Spusť `Main.java`
4. Zadej čas ve formátu `HH:mm:ss` (např. `14:30:00`)
5. Aplikace spustí alarm ve zvolený čas

---

## 🛠️ Požadavky

- Java SE 8+
- Zvukový soubor ve formátu `.wav`
- Konzolové prostředí

---

## 📁 Struktura projektu

```
Alarm-Clock/
│
├── AlarmClock71/
│   ├── AlarmClock.java    // logika alarmu, přehrávání zvuku
│   └── Main.java          // hlavní třída s uživatelským vstupem
└── README.md
```

---

## 🧰 Použité technologie

- Java SE (`LocalTime`, `Scanner`, `Runnable`, `Thread`, `AudioSystem`)
- OOP – objektově orientované programování
- Základní práce se soubory a vlákny

---

## 📸 Ukázka výstupu

```
Enter alarm time (HH:mm:ss): 14:00:00
Alarm set for: 14:00
13:59:58
13:59:59
14:00:00
Alarm ringing! Time to wake up!
Press Enter to stop the alarm.
```

---

## 📜 Licence

MIT

---

## 🧑‍💻 Autor

Martin Joee  
[GitHub – MartinJoee](https://github.com/MartinJoee)