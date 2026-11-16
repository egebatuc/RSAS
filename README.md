# RSAS — Rhizosphere-Spray Agrivoltaic System

> Climate-resilient agriculture powered by NASA Earth observation data.

**NASA Space Apps Challenge 2026** · Challenge: *Field Shift: Adapting Farms with NASA Data*

[![Status](https://img.shields.io/badge/status-proof--of--concept-yellow)]()
[![License](https://img.shields.io/badge/license-MIT-blue)]()
[![NASA](https://img.shields.io/badge/data-NASA%20POWER%20%7C%20SMAP%20%7C%20MODIS-0B3D91)]()

![RSAS Hero](assets/screenshots/hero.png)

## The Problem

Climate change no longer delivers stresses one at a time. The same field faces **drought, heatwaves, and frost** within a single growing cycle. Conventional agriculture responds to each stress separately — and usually too late. A single frost night during flowering can destroy up to **35%** of a fruit orchard's flowers.

## Our Solution

RSAS is a **closed-loop, data-driven agricultural system** that unifies three independently validated technologies under one NASA-data-powered decision layer:

| Pillar | What it does | Key metric |
|---|---|---|
| **RE 2.0** (Rhizosphere Engineering) | Predicts stress 3–7 days ahead, deploys pre-designed synthetic microbial communities (SynComs) to the root zone | -20 °C survival (P. putida GR12-2) |
| **SMART SPRAY** | Biodegradable polymer spray that fixes SynComs, preserves moisture, and insulates plants against frost | Up to 35% soil moisture retention |
| **Dynamic Agrivoltaics** | Autonomous panel tilt: shades crops in heat, rotates horizontal on frost nights | 3–4 °C cooling · 41–42% water savings |

Frost defense is **four-layered**: prediction + biological (antifreeze proteins) + physical (polymer film) + structural (panel blanket).

## How NASA Data Drives the System
NASA POWER (weather) ─┐
SMAP (soil moisture) ─┼──► AI prediction ──► SynCom + Spray + Panel angle
MODIS (vegetation) ─┘ ▲ │
│ ▼
IoT sensor feedback ◄──────────┘

text

- **NASA POWER** — meteorological data
- **SMAP** — soil moisture
- **MODIS** — vegetation health, land surface temperature

## Quick Start

1. Clone or download this repository
2. Open `index.html` in any modern browser (no build step, no dependencies)
3. Switch between **TR / EN** using the toggle in the top-right corner

The site includes an **interactive data loop animation** and a **live cost calculator** — click any pillar in the architecture diagram, or adjust the hectare slider in the cost section.

## Cost Estimate (1 hectare pilot)

| Component | Estimated cost |
|---|---|
| Dynamic agrivoltaic structure | ~€1,000,000 / ha |
| SMART SPRAY polymer | $650 – $4,500 / ha |
| SynComs | $20 – $50 / ha |
| IoT sensors | $500 – $2,000 / ha |
| **Total** | **$1.1M – $1.5M USD / ha** |
| Annual energy revenue | €100,000 – €200,000 / ha |

*USD and EUR reported separately; no currency conversion performed.*

## Status & Honesty Note

**RSAS is at the proof-of-concept and simulation level.** Each component is grounded in peer-reviewed literature (see the site's References section), but the full closed loop has **not yet been field-tested at commercial scale**.

## Team — RSAS Team

| Name | Role |
|---|---|
| Ege Batu Caymaz | Team Leader / Presenter |
| Doga Cerci | Team Member |
| Ece Ozcanlar | Team Member |
| Yusa Ozturk | Team Member |
| Etka Yagiz Bekci | Team Member |
| Simya Tekoglu | Team Member |

## License

MIT — see [LICENSE](LICENSE).
