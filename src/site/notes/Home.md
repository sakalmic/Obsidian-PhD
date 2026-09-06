---
{"dg-publish":true,"permalink":"/home/","title":"Home","contentClasses":"phd-home","tags":["gardenEntry","topic/ltsg/breakdown"],"type":"moc","status":"active","context":"phd","topics":["topic/ltsg/breakdown","topic/ltsg/channel","topic/ltsg/model"],"dgHomeLink":true,"dgShowFileTree":true,"noteIcon":"","created":"2026-09-01","updated":"2026-09-03","dg-note-properties":{"title":"Home","aliases":["Home","Research Dashboard"],"tags":["gardenEntry","topic/ltsg/breakdown"],"date":"2026-09-01","last_updated":"2026-09-03","dgHome":true,"dgShowFileTree":true}}
---


# Laser-Controlled High-Voltage Breakdown

> [!abstract] **Doctoral research profile**
> - **Researcher:** Ing. Michal Sakala
> - **Supervisor:** doc. Ing. Jan Mikeš, Ph.D.
> - **Affiliation:** Department of Economics, Management and Humanities, Faculty of Electrical Engineering, Czech Technical University in Prague
> - **Proposed dissertation:** *Laser-Controlled Breakdown in Atmospheric-Pressure High-Voltage Gaps: Plasma-Channel Diagnostics, Stochastic Switching Dynamics, and Predictive Modelling*
> - **Programme:** Economics of Energy and Electrical Engineering · 2024–2028

This garden documents a reproducible investigation of how measured laser-channel state controls the probability, delay and jitter of atmospheric-pressure high-voltage breakdown, together with held-out validation of a reduced predictive model. Power-system applications and economics remain conditional extensions.

---

## Research map

| Area | Focus | Access |
| :--- | :--- | :---: |
| **01 · Research** | Plasma physics, laser-triggered spark gaps, COMSOL modelling and diagnostics | [[II Areas/01_Research/01_MOC\|Explore research]] |
| **02 · Publications** | Manuscript pipeline, target journals, conferences and research outputs | [[II Areas/02_Publications/02_MOC\|View publications]] |
| **03 · Thesis** | Thesis architecture, claim ledger, evidence mapping and LaTeX integration | [[II Areas/03_Thesis/03_MOC\|Open dissertation hub]] |
| **04 · Teaching** | Courses, laboratory teaching and supervised theses | Private workspace |
| **05 · Grants** | Research grants, mobility and conference funding | Private workspace |
| **06 · Administration** | Study plan, doctoral examination, regulations and supervision | Private workspace |

---

## 📋 Task & Administration Kanban Board

```dataviewjs
const adminTasks = dv.pages('"II Areas/06_Administration"').file.tasks;
const milestoneTasks = dv.pages('"I Projects/03_Milestones"').file.tasks;
const dailyTasks = dv.pages('"_Daily"').file.tasks;

const allTasks = [...adminTasks, ...milestoneTasks, ...dailyTasks];

const columns = [
    {
        id: "immediate",
        title: "⚡ Bezprostřední úkoly",
        color: "#e06c75",
        tasks: allTasks.filter(t => !t.completed && (
            t.path.includes("Meeting") || 
            t.text.includes("September 2026") || 
            t.text.includes("professional discussion") ||
            t.text.includes("COMSOL") ||
            t.text.includes("discussion")
        ))
    },
    {
        id: "isp",
        title: "🏛️ ISP & Administrativa",
        color: "#61afef",
        tasks: allTasks.filter(t => !t.completed && (
            t.path.includes("Individual Study Plan") || 
            t.path.includes("Tracking")
        ) && !(
            t.text.includes("September 2026") || 
            t.text.includes("professional discussion")
        ))
    },
    {
        id: "milestones",
        title: "🎯 Milníky & SDZ",
        color: "#d19a66",
        tasks: allTasks.filter(t => !t.completed && (
            t.path.includes("Milestones") || 
            t.path.includes("State Doctoral Exam")
        ) && !t.path.includes("Tracking"))
    },
    {
        id: "done",
        title: "✅ Hotovo",
        color: "#98c379",
        tasks: allTasks.filter(t => t.completed)
    }
];

let html = `<div style="display: flex; gap: 14px; overflow-x: auto; padding: 10px 0 16px 0; font-family: var(--font-interface, sans-serif);">`;

for (let col of columns) {
    html += `
    <div style="flex: 1; min-width: 250px; max-width: 320px; background: var(--background-secondary, #1e2227); border: 1px solid var(--background-modifier-border, #333); border-radius: 8px; display: flex; flex-direction: column; max-height: 480px; box-shadow: 0 4px 6px rgba(0,0,0,0.06);">
        <div style="padding: 10px 12px; border-bottom: 2px solid ${col.color}; display: flex; justify-content: space-between; align-items: center; background: rgba(255,255,255,0.02); border-top-left-radius: 8px; border-top-right-radius: 8px;">
            <span style="font-weight: 600; font-size: 0.9em; color: var(--text-normal, #ddd);">${col.title}</span>
            <span style="background: rgba(255,255,255,0.1); color: var(--text-muted, #aaa); font-size: 0.75em; padding: 2px 7px; border-radius: 10px; font-weight: bold;">${col.tasks.length}</span>
        </div>
        <div style="padding: 10px; display: flex; flex-direction: column; gap: 8px; overflow-y: auto; flex-grow: 1;">`;
    
    if (col.tasks.length === 0) {
        html += `<div style="font-size: 0.8em; color: var(--text-muted, #888); font-style: italic; text-align: center; padding: 20px 0;">Žádné úkoly</div>`;
    } else {
        for (let task of col.tasks) {
            const cleanText = task.text.replace(/\\[\\[.*?\\|(.*?)\\]\\]/g, '$1').replace(/\\[\\[(.*?)\\]\\]/g, '$1');
            const sourceName = task.link ? task.link.fileName.replace(/\\.md$/, '') : 'Úkol';
            
            html += `
            <div style="background: var(--background-primary, #282c34); border: 1px solid var(--background-modifier-border, #3e4451); border-left: 3px solid ${col.color}; border-radius: 6px; padding: 9px 10px; font-size: 0.84em; line-height: 1.4; box-shadow: 0 2px 4px rgba(0,0,0,0.15);">
                <div style="color: var(--text-normal, #abb2bf); margin-bottom: 6px;">${cleanText}</div>
                <div style="display: flex; justify-content: space-between; align-items: center; font-size: 0.75em; color: var(--text-muted, #7f848e);">
                    <span style="background: rgba(255,255,255,0.05); padding: 1px 5px; border-radius: 3px; max-width: 170px; overflow: hidden; text-overflow: ellipsis; white-space: nowrap;" title="${sourceName}">📁 ${sourceName}</span>
                    ${task.completed ? '<span style="color: #98c379;">✓ Splněno</span>' : ''}
                </div>
            </div>`;
        }
    }
    
    html += `</div></div>`;
}

html += `</div>`;
dv.paragraph(html);
```

---

## Current public work

| Project                                                                          | Priority | Status      | Updated    |
| -------------------------------------------------------------------------------- | -------- | ----------- | ---------- |
| [[I Projects/01_Manuscripts/Dissertation Manuscript\|Dissertation Manuscript]]               | high     | active | 2026-09-03 |
| [[I Projects/01_Manuscripts/Paper - IEEE Transactions 2026\|Paper 1 - Channel-State-Dependent Laser Triggering]] | high | active | 2026-09-03 |

{ .block-language-dataview}

---

## Publication pipeline

| Manuscript                                                                       | Target venue                                         | Status      | Deadline          |
| -------------------------------------------------------------------------------- | ---------------------------------------------------- | ----------- | ----------------- |
| [[I Projects/01_Manuscripts/Paper - IEEE Transactions 2026\|Paper 1 - Channel-State-Dependent Laser Triggering]] | Venue selected after WP3 | active | November 30, 2027 |

{ .block-language-dataview}

---

## Latest research notes

| Note                                                                                                                                                                           | Updated    | Status |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ------ |
| [[II Areas/01_Research/Concepts/202609011030 - Techno-Economic Valuation of Ultrafast Grid Protection\|202609011030 - Techno-Economic Valuation of Ultrafast Grid Protection]] | 2026-09-01 | \-     |
| [[II Areas/01_Research/Concepts/202609011015 - Arc Quenching Dynamics in Hybrid Breakers\|202609011015 - Arc Quenching Dynamics in Hybrid Breakers]]                           | 2026-09-01 | \-     |
| [[II Areas/01_Research/Concepts/202609011000 - Optical Breakdown Mechanism in Air\|202609011000 - Optical Breakdown Mechanism in Air]]                                         | 2026-09-01 | \-     |
| [[II Areas/01_Research/Concepts/Zettelkasten Index\|Zettelkasten Index]]                                                                                                       | 2026-09-01 | \-     |
| [[III Resources/03_Literature/LN - Sakala2025 - APL Lightning Protection\|LN - Sakala2025 - APL Lightning Protection]]                                                         | 2026-09-01 | \-     |
| [[III Resources/03_Literature/LN - Mikes2024 - Laser Spark Gaps\|LN - Mikes2024 - Laser Spark Gaps]]                                                                           | 2026-09-01 | \-     |
| [[III Resources/03_Literature/Literature Index\|Literature Index]]                                                                                                             | 2026-09-01 | \-     |
| [[III Resources/06_Conferences/Academic Conferences Directory\|Academic Conferences Directory]]                                                                                 | 2026-09-01 | \-     |

{ .block-language-dataview}

---

## Essential links

- **Dissertation keystones:** [[Keystones/Keystones\|Core Claims & Findings]]
- **Experimental archive:** [[II Areas/01_Research/Experiments/Experiments Index\|Experiments & Diagnostics]]
- **Numerical simulations:** [[II Areas/01_Research/Simulations/Simulations Index\|COMSOL & Multiphysics Models]]
- **Evidence and traceability:** [[II Areas/03_Thesis/Claim Ledger & Evidence Matrix\|Claim Ledger & Evidence Matrix]]
- **Dissertation structure:** [[II Areas/03_Thesis/Thesis Structure & Chapter Outline\|Thesis Structure & Chapter Outline]]
- **Publication strategy:** [[II Areas/02_Publications/Publication Strategy & Targets\|Publication Strategy & Targets]]
- **Research methodology:** [[_System/Research Methodology & Workflows\|Research Methodology & Workflows]]
