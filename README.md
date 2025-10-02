du hast recht – mein Fehler war, dass ich die komplette README in einen großen Code-Block gepackt habe und darin nochmal … verwendet habe. Das bricht Markdown.
Hier ist eine finale, korrekt formatierte README.md ohne verschachtelte Codeblöcke. Kopier sie genau so in deine README.md.

📈 Stock Price Tracker (Python)

Ein Python-Projekt, das historische Börsendaten über yfinance lädt, Moving Averages berechnet und die Kursentwicklung mit Matplotlib visualisiert.
Ziel: kompakt zeigen, wie man Daten lädt, verarbeitet (pandas) und visualisiert.

⚡ Features
	•	Beliebige Ticker (z. B. AAPL, TSLA, MSFT)
	•	CSV-Export der Daten (<TICKER>_stock.csv)
	•	Gleitende Durchschnitte (MA20 & MA50)
	•	Robustes Laden & Spalten-Normalisierung (funktioniert auch, wenn Adj Close o. ä. geliefert wird)

📦 Installation

1) Repository klonen

git clone https://github.com/<dein-username>/stock-tracker.git
cd stock-tracker

2) (Optional) Virtuelle Umgebung

python3 -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate

3) Abhängigkeiten installieren

pip install yfinance pandas matplotlib

▶️ Nutzung

python tracker.py

Beim Start wirst du interaktiv gefragt:

Enter stock ticker (default: AAPL): TSLA
Enter number of past days (default: 180): 365

	•	Ticker: Kürzel angeben (z. B. AAPL, TSLA, MSFT)
	•	Zeitraum: Anzahl vergangener Tage (z. B. 180, 365)

Ergebnis
	•	CSV: TSLA_stock.csv im Projektordner
	•	Ein Chartfenster mit Kursverlauf + MA20/MA50

🖼️ Screenshot einbinden
	1.	Während der Plot geöffnet ist, mach einen Screenshot (macOS: ⌘ + ⇧ + 4).
	2.	Speichere ihn als screenshot.png im Projektordner (oder in docs/).
	3.	Commit & Push:

git add screenshot.png
git commit -m "Add screenshot"
git push

	4.	In der README einfügen:

![Stock Chart Example](./screenshot.png)

(Falls du docs/screenshot.png nutzt, dann Pfad: ![Stock Chart Example](docs/screenshot.png).)

🛠️ Troubleshooting
	•	ModuleNotFoundError: yfinance in IntelliJ
Deine Run-Config nutzt evtl. ein venv ohne Pakete. Entweder:
	•	Pakete ins venv installieren:
/Pfad/zu/deinem/.venv/bin/python -m pip install yfinance pandas matplotlib
	•	Oder in der Run-Config als Interpreter dein System-Python wählen (/usr/bin/python3 bzw. Homebrew-Pfad).

🧱 Tech Stack
	•	Python 3 · pandas · yfinance · matplotlib

📝 Lizenz

MIT – frei nutzbar & erweiterbar.

⸻

Wenn du willst, formatiere ich dir noch eine englische README-Variante oder füge Badges (Python-Version, License) hinzu.
