# llmtrade

**Multi-Agenten-LLM-Handelssystem für WTI Crude Oil**

llmtrade ist ein experimentelles Handelssystem, das mehrere spezialisierte KI-Agenten koordiniert, um Handelsentscheidungen für WTI Crude Oil zu treffen. Das System läuft gegen die eToro Demo-API und dient als Forschungsplattform für Multi-Agent-Architekturen im Finanzbereich.

---

## Architektur

Das System besteht aus mehreren spezialisierten Agenten, die zusammenarbeiten:

| Agent | Aufgabe |
|---|---|
| **Market Agent** | Marktdaten abrufen und aufbereiten |
| **Analysis Agent** | Technische & fundamentale Analyse |
| **Sentiment Agent** | News und Marktsentiment auswerten |
| **Decision Agent** | Finale Handelsentscheidung koordinieren |
| **Risk Agent** | Position Sizing und Risikoüberwachung |

---

## Features

- **Multi-Agent-Koordination** — Agenten kommunizieren und validieren gegenseitig ihre Einschätzungen
- **LLM-basierte Entscheidungslogik** — keine statischen Regeln, sondern kontextbasiertes Reasoning
- **FastAPI Backend** — REST-API für Monitoring und manuelle Eingriffe
- **eToro Demo-Integration** — Trades werden gegen echte Marktdaten aber auf Demo-Konto ausgeführt
- **Logging & Tracing** — vollständige Nachvollziehbarkeit aller Agenten-Entscheidungen

---

## Tech Stack

| Bereich | Technologie |
|---|---|
| Sprache | Python |
| API | FastAPI |
| KI | Multi-Agent LLM (OpenAI / Ollama) |
| Trading | eToro Demo API |
| Deployment | Docker |

---

## Hinweis

Dieses Projekt ist ein Forschungs- und Lernprojekt. Es handelt sich ausschließlich um Demo-Trading ohne echtes Kapital. Keine Finanzberatung.

---

## Status

![Status](https://img.shields.io/badge/Status-Experimentell-orange?style=flat)
![License](https://img.shields.io/badge/Lizenz-Proprietär-red?style=flat)

> Quellcode ist nicht öffentlich. Bei Fragen oder Interesse an der Architektur: [info@peerstelter.de](mailto:info@peerstelter.de)

---

**[peerstelter.de](https://peerstelter.de)** · [LinkedIn](https://www.linkedin.com/in/peer-stelter-88371827b)
