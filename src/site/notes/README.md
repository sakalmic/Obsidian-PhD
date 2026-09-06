# Obsidian PhD Vault

A research, writing, and administration workspace for doctoral study at the **Faculty of Electrical Engineering, Czech Technical University in Prague (CTU FEE)**, in the *Economics of Power Engineering and Electrical Engineering* programme.

- **Author:** Ing. Michal Sakala
- **Supervisor:** doc. Ing. Jan Mikeš, Ph.D.
- **Proposed fixed dissertation title:** *Laser-Controlled Breakdown in Atmospheric-Pressure High-Voltage Gaps: Plasma-Channel Diagnostics, Stochastic Switching Dynamics, and Predictive Modelling*
- **Immediate priority:** [[Minimum Dissertation Study & Research Discussion 2026]]
- **Digital Garden:** [Michal Sakala · Doctoral Research](https://sakalmic-phd.vercel.app/)

---

## Vault architecture

- **`Home.md`:** Central dashboard for active projects, publication work, milestones, and research navigation.
- **`_Daily/`:** Daily research records, decisions, and deep-work logs.
- **`I Projects/`:** Active time-bounded outcomes (`01_Manuscripts/`, `02_Campaigns/`, `03_Milestones/`, `04_Grants/`).
- **`II Areas/`:** Author's primary scientific work and long-term responsibilities:
  - `01_Research/`: Core research work (`Concepts/` for atomic permanent notes, `Experiments/` for HiLASE data, `Simulations/` for COMSOL models).
  - `02_Publications/`: Publication strategy, target journals, and review activities.
  - `03_Thesis/`: Dissertation structure, hypotheses, claim ledger (`Claims/`), and LaTeX manuscript in `II Areas/03_Thesis/LaTeX_Thesis`.
  - `04_Teaching/`: Teaching duties, laboratory exercises, and supervised student theses.
  - `05_Grants/`: CTU student grants (SGS), external funding, and budgets.
  - `06_Administration/`: ISP, KOS, doctoral study regulations, and faculty directives.
- **`III Resources/`:** External inputs, reference materials, and literature:
  - `01_Books/`: Electronic books and reference monographs.
  - `02_Lectures/`: Doctoral courses and lecture materials.
  - `03_Literature/`: Literature notes (`LN - ...`) and external scientific papers (PDFs).
  - `04_Methods/`: Protocols, statistical methods, SOPs, and datasheets.
  - `05_External_Data/`: External reference databases (e.g. LXCat cross-sections).
  - `06_Conferences/`: Conference proceedings and academic event directory.
- **`IV Archives/`:** Inactive and historical records (`01_DP_Master_Thesis/`, `02_Closed_Projects/`, `03_Superseded_Data/`).
- **`_System/`:** Research methodology, property/tag rules, architecture, and publishing guidance.
- **`TEMPLATES/`:** Preconfigured templates for Templater.

---

## Publishing with Digital Garden and Vercel

This vault is configured for the **Digital Garden** plugin ([oleeskild/digitalgarden](https://github.com/oleeskild/digitalgarden)):

1. Notes intended for the public website use `dg-publish: true` in their frontmatter.
2. Private notes—including meeting records, financial information, and daily logs—use `dg-publish: false` and remain local.
3. To publish, open `Digital Garden: Publication Center` from Obsidian's command palette and select `Publish Changed Notes`.

See [[Digital Garden & Vercel Deployment Guide]] for the complete workflow.
