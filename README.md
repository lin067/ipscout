# 🕵️ IP-Scout – Das vielseitige IP-Analysetool für Windows (Batch)

`IP-Scout.bat` ist ein vollständig lokal laufendes Batch-Toolkit zur schnellen Analyse von IP-Adressen, Netzwerkverbindungen und Geodaten – mit Update-Funktion und integriertem News-Feed.

---

## 🚀 Funktionen

✅ **IP-Abfrage & Geo-Analyse**
- Manuelle IP-Eingabe oder automatische Erkennung der eigenen IP
- Standortdaten über `ip-api.com`
- Anzeige von Land, Region, Stadt, PLZ, ISP
- Google Maps-Link zur Position
- VPN-/Proxy-Erkennung über Hosting-Flag

🛠️ **Netzwerktools**
- Live-Anzeige aktiver Verbindungen (`netstat`)
- Eingehende/verbindende IPs als Livemonitor
- Erweiterter IP-Scanner mit:
  - Hostname-Auflösung (Reverse DNS)
  - Filter für externe IPs (keine lokalen 127.x, 192.x etc.)

📂 **Weitere Features**
- Logging in `lookup_log.txt`
- News Feed über `news.txt` aus dem GitHub-Repo
- Auto-Updater für `IP-Scout.bat` direkt aus GitHub (Branch `main`)

---

## 🧪 So verwendest du das Tool

1. [ ] Repository klonen oder `IP-Scout.bat` herunterladen  
2. [ ] Optional: `news.txt` im gleichen Repo pflegen  
3. [ ] Tool starten mit Doppelklick oder über `cmd`
4. [ ] Gewünschten Menüpunkt (1–5, 9) wählen

---

## 🔄 Update-Funktion

Der Menüpunkt `[9] Update auf neue Version suchen` vergleicht die aktuelle lokale Version mit der Version im GitHub-Repo:

- Wenn eine neue Version erkannt wird, wird sie automatisch heruntergeladen und installiert
- Danach erfolgt ein automatischer Neustart des Tools
- Zusätzlich werden die letzten Änderungen aus `news.txt` angezeigt

---

## 📜 Rechtlicher Hinweis

> Dieses Tool dient ausschließlich zu Bildungs-, Analyse- und Testzwecken.  
> Die Nutzung für böswillige, ausspähende, strafbare oder sicherheitskritische Zwecke – wie das Ermitteln fremder IP-Adressen ohne Zustimmung, Netzwerkangriffe, DoS/DDoS, oder gezielte Nachverfolgung – ist ausdrücklich untersagt.  
> Der Entwickler übernimmt keinerlei Haftung für missbräuchliche oder gesetzeswidrige Verwendung.

---

## 💡 Mitwirken oder Anfragen?

Fragen, Vorschläge oder Erweiterungswünsche?  
Gerne via [Issues](https://github.com/lin067/ipscout/issues) oder Pull Request.

---

**Autor:** [lin067](https://github.com/lin067)  
