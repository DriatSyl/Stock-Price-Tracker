Sehr gut 👌 – hier hast du die finale, saubere README.md in Markdown.
Die kannst du 1:1 in deine README.md Datei kopieren und ins GitHub-Repo pushen.

⸻


# 📈 Stock Price Tracker (Python)

Ein Python-Projekt, das historische Börsendaten über [yfinance](https://pypi.org/project/yfinance/) lädt, Moving Averages berechnet und die Kursentwicklung grafisch darstellt.  
Entwickelt als Lernprojekt, um Python, Datenanalyse und Visualisierung zu üben.

---

## ⚡ Features
- Lade historische Kursdaten für beliebige Ticker (z. B. `AAPL`, `TSLA`, `MSFT`)
- Speichert die Daten automatisch als CSV (`<TICKER>_stock.csv`)
- Berechnet Moving Averages (20 Tage & 50 Tage)
- Visualisierung mit Matplotlib (inkl. gleitender Durchschnitte im Chart)
- Einfache interaktive Eingabe über Konsole

---

## ▶️ Nutzung

### 1. Repository klonen
```bash
git clone https://github.com/dein-github-username/stock-tracker.git
cd stock-tracker

2. Abhängigkeiten installieren

pip install yfinance pandas matplotlib

3. Script starten

python tracker.py

4. Interaktive Eingabe

Beim Start wirst du gefragt:

Enter stock ticker (default: AAPL): TSLA
Enter number of past days (default: 180): 365

	•	Ticker → z. B. AAPL (Apple), TSLA (Tesla), MSFT (Microsoft)
	•	Zeitraum → Anzahl Tage (z. B. 180 oder 365)

➡️ Ergebnis: CSV-Datei TSLA_stock.csv und ein Chart mit Kursverlauf & Moving Averages.

⸻

🖼️ Screenshot

Beispiel-Ausgabe für Tesla (TSLA, 1 Jahr):

👉 Um einen Screenshot hinzuzufügen:
	1.	Mach einen Screenshot vom Matplotlib-Chart (cmd + shift + 4 auf Mac).
	2.	Speichere ihn als screenshot.png im Projektordner.
	3.	Commit & Push:

git add screenshot.png
git commit -m "Add example screenshot"
git push



⸻

💡 Tech Stack
	•	Python 3
	•	yfinance – Börsendaten
	•	pandas – Datenanalyse
	•	matplotlib – Visualisierung

⸻

🚀 Motivation

Dieses Projekt zeigt, wie man externe APIs (Yahoo Finance) in Python nutzt, Daten verarbeitet und visualisiert.
Es dient als praktisches Lernprojekt im Bereich Data Science, Python-Programmierung und Finanzanalyse.

⸻

📜 Lizenz

Dieses Projekt ist frei zu nutzen und darf gerne erweitert werden.

---

✅ Damit hast du eine richtig starke README:  
- Sauber formatiert  
- Klarer Ablauf zur Nutzung  
- Screenshot eingebaut  
- Motivation/Tech Stack beschrieben  

---

👉 Soll ich dir gleich ein Beispiel-Screenshot-Chart (Tesla 1 Jahr) generieren, den du ins Repo packen kannst, damit deine README sofort professionell aussieht?
