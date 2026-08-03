<div align="center">

<img width="50%" src="https://raw.githubusercontent.com/AmMoPy/164/main/assets/ppme.svg">

<details>
<summary><h3>DEMO</h3></summary>

https://github.com/user-attachments/assets/9d5e15c9-876d-4c58-ab7a-9ef0e13d7f00

</details>

# PinPointMe - Spatial Inference Engine

</div>

> **Built By An Auditor Who Got Tired of Landlords Winning**
>
> *"Transforming complex regulatory data into robust compliance framework"*

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![No Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen)](#)
[![Offline](https://img.shields.io/badge/Offline-Yes-success)](#)
[![Court Ready](https://img.shields.io/badge/Court%20Ready-Debatable-orange)](#)
[![Powered by Spite](https://img.shields.io/badge/Powered%20by-Administrative%20Injustice-red)](#)

---

## .....?

[PP-ME](https://ammopy.github.io/164/) is a spatial analytics and regulatory compliance engine designed to ensure compliance with zone classification following **Cairo Governorate Decree No. 978 of 2026.** Basically, it's a mathematical middle finger to landlords who try to squeeze you out using blurry maps.

**In English:** Takes your building's GPS/DMS coordinates, compares them to the official DMS anchors published in the decree's text tables, and test if your landlord is just gaslighting you with pixelated PDFs.

**In Technical:** A single `index.html` file that computes geodesic distance (Vincenty/Haversine) between your target and the decree's tier coordinates, test for tier exclusion, illustrate tier proximity, works offline and fits on a floppy disk.

**In Therapy Speak:** A coping mechanism for rent control anxiety.

**Perfect for:** Tenants who want to fight back.

**Silence that Landlord [164](https://suno.com/s/cHzm2H0msPVBpGo1)**

**Promote your trash code [FIZX](https://github.com/AmMoPy/FIZX)**

---

## The Core Legal Thesis (I Read It So You Don't Have To)

Under established Egyptian Administrative Law (*القضاء الإداري بمجلس الدولة*), **explicit written text in legislative tables takes absolute precedence over accompanying visual maps or drawings** in the event of a contradiction. 

I just made this up!

### The Problem™
Cairo's zoning committees classified neighborhoods into zones, supporting the classification by both colored maps and text tables (zone labels and DMS coordinates). Each zone is given a category and color (Premium/Medium/Economic) that dictates rent calculation; "Premium" is the highest and "Economic" lowest.

Map colors bleed and contradicts zone classification referenced in text tables causing identity crises to everyone reading these maps including the local district divisions! This led to issuing conflicting "Premium Zone" certificates to landlords and "Medium Zone" certificates to tenants for THE EXACT SAME BUILDING AND ZONE, relying only on blurry maps while completely ignoring text tables and zone/building coordinates.

This sparked heated debates between Landlords and tenants, so here I am pretending to solve an issue that shouldn't even exist because WHY DO WE NEED CERTIFICATES WHEN ZONES ARE CLEARLY LABELED AND CATEGORIZED IN THE OFFICIAL GAZETTE TABLES!

### How PP-ME works (The Spatial Defense Algorithm)

#### Distance From Centroids (Anchor Based Analysis):
PP-ME uses a pure **Point‑to‑Anchor Proximity Matrix**. If a building physically resides tightly within a 200‑meter cluster of a text‑verified **Medium Zone** anchor but sits over 400 meters away from the closest **Premium Zone** anchor, it is mathematically and legally impossible for that building to "overlap" or sit inside a "Premium" boundary. The straight‑line geodesic distance acts as an ironclad defense, revealing that the visual map discrepancies are clerical typos, not intentional zoning.

#### Axis-dominance (Boundary Based Analysis):
If every reference point of a tier lies on one side of a building (all-north / all-south / all-east / all-west), then NO polygon connecting those points — whatever its true, unknown shape — could contain that building. This is a proof, not an estimate: a straight edge between two points that are both, say, south of a line stays south of that line everywhere along it, so a polygon whose every vertex is south of the line can never cross it. **You win....YAAY!**

#### Illustration (Boundary Estimate):
when axis-dominance fails and there are multiple points of the same tier clustered together, PP-ME draws a best-effort shape (simple polygon) purely to build the "here's my whereabouts" mental picture; this shape is **NOT** a proof of the true boundary, rather a visual representation of your location and tier clusters.

**In other words:** Landlords can't just draw a line on a map and call it "Premium". The law says numbers win, and we have numbers.

---

## Getting Started
- Input your location coordinates (latitude/longitude) or use the "Locate Me" button (coarse fix, but it's a start).
- Paste the DMS anchors from the decree.
- Run Analysis.
- Claim the verdict.

<div align="center">
<sub>© 20XX - No rights reserved, honestly do whatever. Just don't drag my name into it</sub>

</div>