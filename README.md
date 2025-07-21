
## ⚙️ Project Goals

- 🗺️ Map military activity & reported strikes from OSINT data
- 📊 Detect narrative shifts and sentiment changes in Telegram/Twitter channels
- 📰 Auto-generate daily situational reports in markdown/HTML
- ✅ Publish summaries with confidence levels and geolocation
- 🔁 Automate everything with scheduled tasks

---

## 📦 Key Features

| Feature | Description |
|--------|-------------|
| 🔄 **Data Collection** | Scrapes Telegram, Twitter (via `snscrape`), ISW RSS feeds, and optionally ACLED/Oryx |
| 🧠 **NLP Analysis** | Uses spaCy + multilingual BERT to extract entities, locations, events |
| 📌 **Geo-tagging** | Uses OpenStreetMap + `geopy` to map extracted place names |
| 📊 **Sentiment/Narrative Monitoring** | Tracks key military terms, mobilisation claims, morale narratives |
| 🗺️ **Map Visualisation** | Renders Folium-based heatmaps or overlays (e.g., front-line shifts, strike clusters) |
| 🧾 **Daily Report Generator** | Publishes a structured markdown or HTML report with event counts, maps, and summaries |

