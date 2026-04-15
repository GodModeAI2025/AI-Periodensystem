# 🧠 Periodensystem der Künstlichen Intelligenz

**128 interaktive Elemente · 10 Kategorien · Das gesamte AI-Ökosystem auf einen Blick**

Ein interaktives Periodensystem, das alle wesentlichen Komponenten der modernen KI-Landschaft kartografiert — von Foundation Models über Architekturen und Lernparadigmen bis hin zu Ethik, Agenten und Infrastruktur.

## 🚀 Live Demo

👉 **[Periodensystem ansehen](https://DEIN-USERNAME.github.io/ai-periodic-table/)**

## 📋 Kategorien

| Farbe | Kategorie | Elemente |
|-------|-----------|----------|
| 🔴 | Foundation Models | GPT, Claude, Gemini, LLaMA, BERT, DALL·E, ... |
| 🟠 | Architekturen | Transformer, Attention, CNN, Diffusion, MoE, ... |
| 🟡 | Lernparadigmen | RLHF, Chain-of-Thought, Few-Shot, Distillation, ... |
| 🟢 | Daten & Processing | RAG, Vektordatenbank, GraphRAG, Chunking, ... |
| ⚫ | Tools & Frameworks | PyTorch, LangChain, MCP, Hugging Face, ... |
| 🟣 | Anwendungen | Vibe Coding, Computer Vision, Robotik, ... |
| 🔶 | Ethik & Safety | Alignment, EU AI Act, Red Teaming, Guardrails, ... |
| 🔵 | Infrastruktur | GPU, TPU, CUDA, Cloud ML, Scaling Laws, ... |
| 🩵 | Agenten &Tic | Agentic Workflows, Tool Use, Multi-Agent, ... |
| 🔷 | NLP & Sprache | NER, Translation, Summarization, QA, ... |

## 🛠 Deployment auf GitHub Pages

### Schnellstart (3 Schritte)

1. **Repository erstellen**
   ```bash
   # Neues Repo auf GitHub erstellen, dann:
   git clone https://github.com/DEIN-USERNAME/ai-periodic-table.git
   cd ai-periodic-table
   ```

2. **Datei kopieren**
   ```bash
   # Die index.html in das Repository kopieren
   cp /pfad/zu/index.html .
   git add .
   git commit -m "Initial: Periodensystem der KI"
   git push
   ```

3. **GitHub Pages aktivieren**
   - Gehe zu **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / Ordner: **/ (root)**
   - Speichern → nach 1–2 Minuten ist die Seite live

### Custom Domain (optional)

Eine `CNAME`-Datei anlegen:
```
ki-periodensystem.deine-domain.de
```

## 🔧 Technologie

- **React 18** via CDN (kein Build-Schritt nötig)
- **Babel Standalone** für JSX-Transformation im Browser
- **DM Sans + DM Mono** Typografie
- **Keine Dependencies** — eine einzige HTML-Datei
- **Responsive** — funktioniert auf Desktop, Tablet und Mobile
- **Accessible** — Keyboard-Navigation, ARIA-Labels, Escape zum Schließen

## 📝 Eigene Elemente hinzufügen

Im `elements`-Array in der `index.html` einfach ein neues Objekt ergänzen:

```javascript
{
  sym: "XYZ",       // 2-3 Buchstaben Symbol
  num: 129,         // Fortlaufende Nummer
  name: "Mein Element",
  cat: "FM",        // Kategorie-Kürzel (FM, AR, LP, DA, TF, AP, ES, IN, AG, NL)
  row: 0,           // Zeile im Grid (0-9)
  col: 2,           // Spalte im Grid (0-17)
  desc: "Beschreibung des Elements."
}
```

## 📄 Lizenz

MIT — frei verwendbar, auch kommerziell.

---

*Erstellt mit KI · Inspiriert vom Periodensystem der chemischen Elemente*
