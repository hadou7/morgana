# Morgana:  A Modular ESP-32 Powered Coffee Machine with a custom boiler, steamer and voice-assisted brewing

**Morgana** is a modular, low-voltage-controlled, high-voltage-powered espresso machine boiler. Built from scratch, Morgana features:

- A compact 0.5L stainless steel pressure-rated boiler
- Digital temperature and pressure monitoring
- Fully electronic brew/steam control via 2-way solenoids
- SSR-controlled 230V AC heating with Arduino logic
- No mechanical levers or spring assemblies

---

## 🔧 Project Goals

- Deliver reliable boiler + steam pressure with rapid heat-up
- Enable electronic automation of shots and steaming
- Keep modular for future GUI, PID, or refill system upgrades

---

## 📦 Current System Status

| Subsystem     | Status        |
|---------------|---------------|
| Boiler        | ✅ Installed (SS304, 0.5L) |
| Sensors       | ✅ DS18B20 + 0–16 bar transducer |
| Power         | ✅ 24V PSU + SSR-40DA |
| Solenoids     | 🔄 Sourcing 2x G1/4 24V valves |
| Heater        | 🔄 Selecting 230V 600–800W unit |
| Control       | ✅ Arduino Uno (bang-bang) |
| Display       | ✅ OLED (SSD1306) |

---

## 🛠️ Quick Links

- [Wiring Diagram](docs/wiring.md)
- [Plumbing & Fittings](docs/hydraulics.md)
- [Build Log](logs/build_log.md)
- [Bill of Materials](docs/BOM.md)
