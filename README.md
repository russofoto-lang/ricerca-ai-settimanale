# Ricerca AI settimanale

Rassegna automatica in italiano su agenti AI, automazioni, strumenti social e MCP, realizzata da Gemini CLI con il browser cloud Simular Box.

## Configurazione iniziale
Aggiungere in **Settings → Secrets and variables → Actions** questi repository secrets:

- `GEMINI_API_KEY`: chiave Gemini API.
- `BOX_TOKEN`: personal key Simular Box.

La workflow `.github/workflows/rassegna.yml` può essere avviata manualmente da Actions oppure ogni lunedì alle 07:00 UTC (08:00 in Italia in inverno, 09:00 in estate). I report vengono salvati in `reports/`.

Le chiamate Gemini API e il tempo/crediti di Simular Box possono avere costi o limiti separati. Il repository è privato.
