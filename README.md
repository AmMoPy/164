<div align="center">

<img width="50%" src="https://raw.githubusercontent.com/AmMoPy/164/main/assets/ppme.svg">

# PinPointMe - GPS/DMS Point Based Proximity Dashboard

</div>

> **Built By An Auditor Who Got Tired of Landlords Winning**
>
> *"It's a feature request from my landlord"*

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![No Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen)](#)
[![Offline](https://img.shields.io/badge/Offline-Yes-success)](#)
[![Court Ready](https://img.shields.io/badge/Court%20Ready-Debatable-orange)](#)
[![Powered by Spite](https://img.shields.io/badge/Powered%20by-Administrative%20Injustice-red)](#)

---

## .....?

A zero‑dependency, client‑side spatial analytics and regulatory compliance dashboard designed to audit zone classifications under **Cairo Governorate Decree No. 978 of 2026** (published in *El-Waqae' El-Mesriya*, Issue No. 21 Follow‑up). Basically, it's a mathematical middle finger to landlords who try to squeeze you out using blurry maps.

**In English:** [PP-ME](https://ammopy.github.io/164/) takes your building's GPS coordinates, compares them to the official DMS anchors published in the law's text tables, and tells you if you're *actually* near a "Premium Zone" or if your landlord is just gaslighting you with a pixelated PDF.

**In Technical:** A single `index.html` file that computes exact geodetic distances (Vincenty/Haversine) between your target point and the decree's anchor points, that works offline and fits on a floppy disk.

**In Therapy Speak:** A coping mechanism for rent control anxiety.

**Perfect for:** Tenants who want to fight back.

**PSST! Want to promote your trash code for free with zero chances of going viral? Check out [FIZX](https://github.com/AmMoPy/FIZX)**

---

## The Core Legal Thesis (I Read It So You Don't Have To)

Under established Egyptian Administrative Law (*القضاء الإداري بمجلس الدولة*), **explicit written text in legislative tables takes absolute precedence over accompanying visual maps or drawings** in the event of a contradiction. 

I just made this up!

### The Problem™
Cairo's zoning committees drew maps and exported single‑point centroids (anchors) for each zone and labeled them precisely in text tables including their DMS co-ordinates. Each zone is given a category (Premium/Medium/Economic) that dictates rent calculation where Premium is the highest and Economic lowest.

Due to extreme compression in the official gazette print, map colors bleed and contradicts text table classifications causing identity crises to everyone reading these gazette even the local district engineering departments! Leading to issuing contradicting "Premium Zone" certificates to landlords and "Medium Zone" certificates to tenants for THE EXACT SAME ZONE, relying on blurry maps only while ignoring text schedules and zone/building co-ordinates.

This sparked heated debates between Landlords and tenants, so here I am pretending to solve an issue that didn't exist because WHY THE F WE NEED CERTIFICATES WHERE ZONES ARE CLEARLY LABELED AND CATEGORIZED IN THE OFFICIAL GAZETTE!!!!!!

### The Spatial Defense (PP-ME Algorithm)
PP-ME uses a pure **Point‑to‑Anchor Proximity Matrix**. If a property physically resides tightly within a 200‑meter cluster of a text‑verified **Medium Zone** anchor but sits over 400 meters away from the closest **Premium Zone** anchors, it is mathematically and legally impossible for that property to "overlap" or sit inside a Premium boundary. The straight‑line geodetic distance acts as an ironclad defense, revealing that the visual map discrepancies are clerical typos, not intentional zoning.

**In other words:** Landlords can't just draw a line on a map and call it "Premium." The law says numbers win. And we have numbers.

---

## Getting Started
- Input your location coordinates (latitude/longitude) or use the "Locate Me" button (coarse fix, but it's a start).
- Paste the DMS anchors from the decree.
- Run Analysis.
- Claim the verdict.

<div align="center">
<sub>© 20XX - No rights reserved, honestly do whatever. Just don't drag my name into it</sub>

</div>