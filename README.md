# A Tale of Two LLM Startups: Anthropic vs. Cohere
### Digital Economy Final Project — NTU / NTUST 2026

> **Course:** Digital Economy (數位經濟)  
> **Instructor:** Dr. Melody Pei-yu Lo  
> **Team:** Ting-Ying Lai (賴亭穎) · Yuan-Zhen Huang (黃元禎)  
> **Topic:** Application / Impact of LLM — Winner-Take-All vs. Niche Strategy in Enterprise AI

---

## Research Question

> In the enterprise LLM market, does a 58-to-1 revenue gap signal a winner-take-all dynamic, or can capital-efficient niche strategies sustain long-run viability?

We compare Anthropic ($14B ARR, $380B valuation) and Cohere ($240M ARR, $7B valuation) across four analytical lenses: Business Model Canvas, competitive dynamics (Hotelling + signaling), J-curve capital efficiency, and social network analysis of alliance structures.

---

## Repository Structure

```
anthropic-vs-cohere/
│
├── README.md                        ← This file
├── .gitignore
│
├── 00_proposal/                     ← Original proposals (3 versions)
│   ├── proposal_EN.pdf              ← English proposal (submitted)
│   ├── proposal_ZH_v1.pdf           ← Chinese proposal v1
│   ├── proposal_ZH_v2.pdf           ← Chinese proposal v2 (extended)
│   └── 分工表.txt                   ← Task allocation across 6 weeks
│
├── 01_data/
│   ├── raw/
│   │   ├── financials/              ← ARR, valuation, funding rounds (CSV)
│   │   │   ├── anthropic_funding_rounds.csv
│   │   │   └── cohere_funding_rounds.csv
│   │   ├── market_share/            ← Menlo Ventures survey data, market reports
│   │   │   └── enterprise_llm_market_share_2024-2026.csv
│   │   ├── pricing/                 ← Token pricing tables (API, per model)
│   │   │   ├── anthropic_pricing_2026.csv
│   │   │   └── cohere_pricing_2026.csv
│   │   └── sna_edgelist/            ← Partnership network edges (~100 edges, ~40 nodes)
│   │       ├── nodes.csv
│   │       └── edges.csv
│   └── processed/
│       ├── bmc_comparison.csv       ← Business Model Canvas structured data
│       ├── jcurve_inputs.csv        ← J-curve model parameters
│       └── sna_metrics.csv          ← Centrality, clustering outputs
│
├── 02_literature/
│   ├── references.bib               ← Full BibTeX bibliography
│   ├── references_annotated.md      ← Annotated bibliography with notes
│   └── readings/                    ← PDFs of key papers (gitignored if large)
│       ├── burt_1992_structural_holes.pdf
│       ├── edelman_wright_2015_price_coherence.pdf
│       ├── ma_chen_mukhopadhyay_2008.pdf
│       ├── brynjolfsson_2026_ai_jcurve_RAND.pdf
│       └── tesoriere_balletta_2025_opensource.pdf
│
├── 03_analysis/
│   ├── bmc/
│   │   ├── bmc_anthropic.md         ← Business Model Canvas — Anthropic
│   │   ├── bmc_cohere.md            ← Business Model Canvas — Cohere
│   │   └── bmc_comparison_table.md  ← Side-by-side 9-box comparison
│   ├── hotelling/
│   │   ├── hotelling_model.md       ← Text analysis: performance–compliance axis
│   │   └── hotelling_diagram.svg    ← Positioning diagram (editable)
│   ├── signaling/
│   │   └── signaling_model.md       ← Separating equilibrium analysis
│   ├── jcurve/
│   │   ├── jcurve_analysis.md       ← Dual J-curve narrative + 3 scenarios
│   │   └── jcurve_chart.py          ← Python script to generate chart
│   ├── sna/
│   │   ├── sna_analysis.py          ← NetworkX: degree, betweenness, clustering
│   │   ├── sna_gephi_export.gexf    ← Gephi-ready export
│   │   └── sna_results.md           ← Interpretation of SNA metrics
│   └── opensource/
│       └── opensource_vs_closed.md  ← LLaMA impact, Ma et al. framework
│
├── 04_report/
│   ├── draft/
│   │   ├── 01_intro.md
│   │   ├── 02_bmc_comparison.md
│   │   ├── 03_competitive_dynamics.md
│   │   ├── 04_capital_efficiency.md
│   │   ├── 05_opensource.md
│   │   ├── 06_theoretical_synthesis.md
│   │   ├── 07_policy.md
│   │   └── 08_conclusion.md
│   └── final/
│       └── anthropic_vs_cohere_final_report.pdf
│
├── 05_slides/
│   ├── slide_deck.pptx              ← 15–20 slides, 25-min presentation
│   └── speaker_notes.md             ← Per-slide speaking notes + timing
│
└── 06_figures/
    ├── hotelling_positioning.png
    ├── jcurve_dual.png
    ├── sna_network_map.png
    ├── market_share_timeline.png
    └── competitive_positioning_matrix.png
```

---

## Analytical Framework

| Framework | Application in This Project |
|---|---|
| **Business Model Canvas** | 9-box side-by-side: value prop, revenue streams, cost structure, key partners |
| **Hotelling Model** | Performance–compliance axis; Meta LLaMA compresses Anthropic's space, not Cohere's |
| **Signaling Theory** | Safety certs + data sovereignty as screening devices → separating equilibrium |
| **J-Curve / Capital Efficiency** | Dual curves: Anthropic ($64B raised) vs. Cohere (~$1B); capital efficiency ratio ~0.22 vs. ~0.24 |
| **Social Network Analysis** | Bipartite firm–partner network; degree, betweenness, clustering coefficients via NetworkX |
| **Platform Envelopment** | Anthropic's cloud partners (AWS, Google, Azure) compete with their own models |
| **Open-Source Economics** | Ma, Chen & Mukhopadhyay (2008) complement/substitute framework applied to LLaMA |

---

## Timeline

| Phase | Week | Deliverable |
|---|---|---|
| Data collection | 1–2 | Company profiles, competitor data, literature |
| Analysis & modeling | 3–4 | BMC, Hotelling diagram, SNA metrics, J-curve |
| Report writing | 5 | Full draft, cross-review |
| Slides & rehearsal | 6 | 15–20 slide deck, full run-through |

---

## Key Data Sources

**Financials & Market**
- Menlo Ventures (2025) — Enterprise LLM Spend Report ($8.4B, market share data)
- Crunchbase / Sacra / Contrary Research — Funding round details
- BetaKit, Seeking Alpha, IndexBox — Cohere ARR reports

**Academic**
- Burt (1992) — *Structural Holes*
- Edelman & Wright (2015) — Price coherence and excessive intermediation
- Ma, Chen & Mukhopadhyay (ICIS 2008) — Open source adoption
- Brynjolfsson et al. (2026, RAND) — AI productivity J-curve

**Policy**
- Center for American Progress (2026) — DoD vs. Anthropic
- EU AI Act compliance analysis

See `02_literature/references.bib` for the complete BibTeX file.

---

## Setup (SNA Analysis)

```bash
pip install networkx pandas matplotlib gephi-lite
python 03_analysis/sna/sna_analysis.py
```

Output: centrality metrics in `01_data/processed/sna_metrics.csv` + network visualization.

---

## FAQ (Anticipated Presentation Questions)

**Q: Why Anthropic and Cohere instead of OpenAI?**  
OpenAI dominates consumer AI; this comparison isolates two pure-play enterprise strategies with contrasting capital structures, making the winner-take-all question sharper.

**Q: Is the open-source threat overstated?**  
Closed models retain a 5–10% edge on SWE-bench and Chatbot Arena. For pure cognitive tasks (GPQA, MATH), the gap has closed. The threat is real but asymmetric—it hits Anthropic's commodity layer harder than Cohere's workflow-integration moat.

---

*Last updated: April 2026*
