# Learning Notes: AMICI & Spatial Transcriptomics

A personal knowledge map built while studying the AMICI paper and the CRC tumor-immune project in preparation for joining Azizi Lab at Columbia BME.

**[→ Open the knowledge map](https://[your-username].github.io/amici-notes/)**

---

## What this is

An interconnected set of notes organized around the question:  
*How does the spatial organization of the tumor microenvironment shape immune cell behavior — and how can we measure it computationally?*

The notes cover four layers of knowledge, each a prerequisite for the next:

| Layer | Topics |
|---|---|
| **Cancer Biology** | Colorectal cancer, MSS/MSI/EMAST subtypes, tumor heterogeneity, antagonistic pleiotropy |
| **Immune System** | Tumor microenvironment, T cell effector vs. exhausted states, immune checkpoints, cell differentiation |
| **Technology & Methods** | Spatial transcriptomics, CosMx 6k panel, scRNA-seq, cell annotation pipeline |
| **ML & AMICI** | Gene expression vectors, attention mechanism, AMICI algorithm, CellChat comparison, causality vs. correlation |

---

## The central paper

Goyal et al. (2025). *AMICI: Attention-based Model for Interpretable Cell–Cell Interactions.*  
bioRxiv preprint: [https://www.biorxiv.org/content/10.1101/2025.09.22.677860v1](https://www.biorxiv.org/content/10.1101/2025.09.22.677860v1)

---

## Structure

```
index.html          ← Interactive knowledge graph (D3.js)
pages/              ← One HTML page per concept node
assets/css/         ← Shared stylesheet
README.md
```

---

## Deploy locally

```bash
# Any static server works. Simplest:
python3 -m http.server 8000
# Then open http://localhost:8000
```

---

*Built June 2026. Notes are a record of learning, not a finished reference — expect personal interpretations, open questions, and evolving understanding.*
