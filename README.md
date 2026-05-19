# India Holidays JSON (Community Dataset)

This repository provides a free, open JSON dataset of Indian holidays and festivals.  
It is designed to be used by developers without requiring API keys, OAuth, or paid subscriptions.

## 📌 About
- Data originally sourced from Calendarific API.
- Converted into static JSON files for public use.
- Maintained and updated yearly (e.g., `holidays2026.json`, `holidays2027.json`).
- Hosted on GitHub, accessible via raw file links.

## 📂 Structure
Each JSON file contains:
- `name` → Holiday name  
- `description` → Short explanation  
- `date.iso` → Date in `YYYY-MM-DD` format  
- `type` → Holiday type (National, Observance, Religious, etc.)  
- `primary_type` → Gazetted, Restricted, Observance, etc.  

Example:
```json
{
  "name": "Republic Day",
  "description": "India's Republic Day marks the adoption of the constitution.",
  "date": {
    "iso": "2026-01-26"
  },
  "type": ["National holiday"],
  "primary_type": "Gazetted Holiday"
}
