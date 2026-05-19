# PITTSBURGH REVITALIZATION PROJECT **→ [Live Site](#)** &nbsp;|&nbsp; Urban Data & Design

> *Mapping where Pittsburgh's vacant properties are, what each neighborhood needs most, and how abandoned houses can become the community assets those neighborhoods are missing.*

---

<img width="1242" height="796" alt="prpthumbnail" src="https://github.com/user-attachments/assets/860ab244-423a-419e-825a-481c10329750" />

---

## Overview

**Pittsburgh Revitalization Project** is an interactive data platform built around a single core question: what should rise in place of Pittsburgh's nearly 24,000 vacant properties?

The site maps vacancy against neighborhood need indicators including food access, green space, and housing density, cross-referenced with open datasets from the Pittsburgh GIS Hub and peer-reviewed reporting. Rather than treating blight as a monolithic problem, it asks what each specific neighborhood is missing, and surfaces the revitalization model that fits.

> **Data Note:** Vacancy and poverty figures are sourced from the Center for Community Progress, Pittsburgh GIS Hub, USDA, the Trust for Public Land, and NeighborhoodScout. All statistics are as current as available public datasets allow.

---

## Key Statistics

| Figure | What It Represents |
|---|---|
| **23,757** | Vacant properties across Pittsburgh, a number that doubled in the past decade |
| **50%** | Pittsburgh residents living in food deserts, one of the highest rates among comparable US cities |
| **93** | Homes reclaimed in Homewood by Rising Tide Partners under community-driven block-by-block redevelopment |
| **$5.2M** | Awarded through Allegheny County's Act 152 Blight Removal Program since 2021, demolishing 181 structures |

---

## Sections

The site is organized across two pages, each approaching the crisis from a different angle.

| Page | What It Does |
|---|---|
| 🏚️ **Main Site** | Problem overview, adaptive reuse strategies, neighborhood profiles, revitalization pipeline, and partner organizations |
| 📊 **Neighborhood Data Dashboard** | Deep dives into 8 priority neighborhoods with vacancy rates, food access scores, green space data, and GIS links |

---

## Adaptive Reuse Strategies

I use the site to argue that the best use for a vacant property depends on what the surrounding neighborhood is already missing. Six core revitalization models are profiled:

- 🌽 **Urban Farm and Community Garden** — For neighborhoods more than a mile from any grocery store, vacant lots become sites for growing food. Priority areas include Homewood, Larimer, East Hills, and Sheraden.
- 🌳 **Pocket Park and Green Space** — Dense neighborhoods without accessible parks can convert vacant lots into rain gardens, playgrounds, or gathering greens. Priority areas include Knoxville, Allentown, and the South Side Slopes.
- 🏘 **Affordable Housing Rehab** — Structurally sound but neglected homes renovated for affordable ownership or rental through the Pittsburgh Land Bank. Priority areas include Homewood, Wilkinsburg, and Garfield.
- 🏛 **Community Hub and Services** — Larger buildings converted to clinics, childcare centers, workforce training spaces, or gathering halls, especially near transit lines.
- 🏬 **Mixed-Use with Corner Market** — Commercial ground floors with housing above, using small-format grocery stores or food co-ops to simultaneously address food access and housing supply.
- 🎨 **Creative and Cultural Space** — Inspired by Lawrenceville and the Strip District's transformation, artist studios, maker spaces, and performance venues that anchor neighborhood economies.

---

## Neighborhood Profiles

<img width="800" height="504" alt="prp1-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/1588c493-ca2c-48e2-b19b-154848603592" />

Eight Pittsburgh neighborhoods profiled with vacancy data, food access distance, green space scores, and location-matched revitalization recommendations.

| Neighborhood | Primary Need | Key Stat |
|---|---|---|
| 🔴 **Homewood** | Food Desert | 93+ properties under active Rising Tide Partners revitalization |
| 🔴 **East Hills** | Food Desert | 19% vacancy rate, 75.2% of children below the federal poverty line |
| 🔴 **Larimer** | Food Desert | Food desert directly adjacent to Bakery Square's prosperity |
| 🟡 **Knoxville** | Green Space Gap | Multiple actionable vacant lots suitable for rain gardens |
| 🔴 **Wilkinsburg** | Housing Crisis | ~1,066 vacant properties, nearly 15% of all property stock |
| 🔴 **Arlington** | Food Desert | Among Pittsburgh's 14 most food-insecure neighborhoods per Just Harvest |
| 🟡 **Spring Garden** | Green Space Gap | Limited flat land, few parks, rare opportunity for urban greenspace |
| 🔴 **Oakland** | Food Desert | 50%+ of residents lack walkable access to an affordable grocery store |

---

## The Revitalization Pipeline

How a vacant, tax-delinquent property moves from blight to community infrastructure, and where this project fits in that process.

1. **Identify and Map** — Pittsburgh GIS Hub open data layers vacancy locations alongside neighborhood need indicators: food access, green space, housing density, and transit.
2. **Assess Fit** — Each property is evaluated against neighborhood gaps. A location in a food desert scores high for urban farm or market potential. A green-space-deficient block scores high for pocket park conversion.
3. **Acquire Title** — The Pittsburgh Land Bank, Allegheny County Vacant Property Recovery Program, or conservatorship legal tools are used to clear title, historically the biggest bottleneck in revitalization.
4. **Build with Community** — Development is modeled on community plans like Homewood's Comprehensive Plan, with direct resident governance built into the process.

---

## Data Sources and Partners

| Organization | Role |
|---|---|
| **Pittsburgh GIS Hub** | Primary open dataset for vacancy mapping and parcel data |
| **Center for Community Progress** | Vacancy statistics and code violation data |
| **WPRDC** | Vacant parcel dataset cross-referenced by neighborhood |
| **Rising Tide Partners** | Community-led redevelopment model in Homewood |
| **Pittsburgh Land Bank** | Title acquisition and blight clearance |
| **Allegheny County Econ. Development** | Act 152 Blight Removal Program funding |
| **Just Harvest** | Food insecurity classification and neighborhood mapping |
| **Trust for Public Land** | Green space equity data, 2025 |

---

## Structure

```
revitalizationpittsburgh/
├── pittsburgh-revitalization.html    # Main site: problem overview, strategies, pipeline, resources
├── neighborhood-data.html            # Neighborhood dashboard: 8 deep-dive profiles with GIS links
└── image.png                         # Hero and section imagery
```

---

## Built With

- **HTML5** — Semantic, accessible markup
- **CSS3** — Custom properties, grid layout, responsive design
- **Vanilla JavaScript** — Neighborhood filter system, interactive pipeline, modal components
- **Google Fonts** — Playfair Display and DM Sans
- **Pittsburgh GIS Hub** — Embedded live map via iframe, open data links per neighborhood

---
