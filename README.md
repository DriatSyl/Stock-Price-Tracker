# 📈 Stock Price Tracker (Python)

Ein kleines Python-Projekt, das aktuelle Börsendaten (über [yfinance](https://pypi.org/project/yfinance/)) lädt, Moving Averages berechnet und die Kursentwicklung grafisch darstellt.  
Erstellt als Lernprojekt, um Python, Datenanalyse und Visualisierung zu üben.

---

## ⚡ Features
- Lade historische Kursdaten für beliebige Ticker (z. B. `AAPL`, `TSLA`, `MSFT`)
- Speichert die Daten automatisch als CSV (`<TICKER>_stock.csv`)
- Berechnet Moving Averages (20 Tage & 50 Tage)
- Visualisierung mit Matplotlib (inkl. MAs im Chart)

---

## ▶️ Nutzung

### 1. Abhängigkeiten installieren
```bash
pip install yfinance pandas matplotlib
