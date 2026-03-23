# Progetto: Smart School IoT

| Campo | Valore |
|-------|--------|
| **Titolo** | Smart School – Connettere la nostra scuola con IoT |
| **Anno di corso** | 3° |
| **Durata** | Ottobre – Maggio (7 mesi) |
| **Team size** | 4–5 studenti |
| **Stato** | `attivo` |
| **Referente** | Docenti A042 + A040 |

---

## Il Problema

La nostra scuola non sa in tempo reale quante persone sono in un'aula,
che temperatura c'è, se ci sono posti disponibili, o quanto si consuma energeticamente.
**Come possiamo rendere la scuola più smart usando sensori, reti e software?**

---

## Committente / Stakeholder

- **Dirigenza scolastica** – efficienza energetica e sicurezza
- **ATA** – gestione degli spazi
- **Docenti e studenti** – utilizzo pratico del sistema

---

## Output attesi

- [x] Rete di sensori installati (temperatura, presenza, luminosità)
- [x] Backend REST API che raccoglie i dati in tempo reale
- [x] Dashboard web con visualizzazione live dei dati
- [x] Sistema di notifiche (email/telegram) per soglie critiche
- [x] Documentazione architetturale (diagrammi, API docs)
- [x] Report di sicurezza del sistema
- [x] Presentazione all'istituto (open day)

---

## Macro-fasi

| Fase | Descrizione | Durata |
|------|-------------|--------|
| 1. Discovery | Analisi degli spazi, interviste, requisiti | 2 sett. |
| 2. Hardware | Assemblaggio sensori, test Arduino/Raspberry | 3 sett. |
| 3. Backend | API REST, database time-series, MQTT broker | 4 sett. |
| 4. Frontend | Dashboard web, grafici in tempo reale | 3 sett. |
| 5. Integrazione | Hardware + software insieme, test sistema | 2 sett. |
| 6. Sicurezza | Analisi vulnerabilità, HTTPS, autenticazione | 2 sett. |
| 7. Deploy & Docs | Installazione definitiva, documentazione | 2 sett. |

---

## Ruoli nel team

- **Hardware Engineer:** sensori, cablaggio, Arduino/Raspberry
- **Backend Developer:** API, database, logica server
- **Frontend Developer:** dashboard, grafici, UX
- **DevOps:** rete, server, deployment
- **Documenter:** architettura, report sicurezza, presentazione

---

## Cattedre e contributi disciplinari

| Cattedra | Disciplina | Fase | Contenuti attivati |
|----------|-----------|------|-------------------|
| A042 | TPSIT | 3–5 | Node.js/Flask, REST API, WebSocket, DB time-series |
| A042 | Sistemi e Reti | 1–6 | TCP/IP, MQTT, LAN, VLAN, sicurezza, Linux server |
| A040 | Tecnologie | 2 | Arduino, Raspberry Pi, sensori, protocolli I2C/SPI |
| A026 | Matematica | 4–5 | Statistica su serie temporali, anomaly detection base |
| Inglese | Inglese | 3, 7 | Lettura documentazione tecnica, commenti in inglese |

---

## Strumenti e tecnologie

- **Hardware:** Arduino Uno/Nano, Raspberry Pi, sensori DHT22, PIR, BH1750
- **Protocolli:** MQTT (Mosquitto), HTTP/HTTPS, WebSocket
- **Backend:** Node.js (Express) o Python (FastAPI), InfluxDB o SQLite
- **Frontend:** HTML/JS, Chart.js o Grafana
- **AI:** Copilot per codice, anomaly detection con librerie ML base
- **Deployment:** Raspberry Pi come server locale + tunnel ngrok/Cloudflare

---

## Criteri di valutazione

| Criterio | Peso |
|----------|------|
| Sistema funzionante (sensori + dashboard live) | 30% |
| Qualità architettura e codice | 25% |
| Presentazione all'open day | 20% |
| Documentazione tecnica e report sicurezza | 15% |
| Uso AI (anomaly detection, Copilot) | 10% |
