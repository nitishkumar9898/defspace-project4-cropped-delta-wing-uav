# Project 4 — Cropped Delta Wing UAV Aerodynamic Analysis Dashboard

**Def Space Summer Internship 2026 | Bharat Space Education Research Centre**

## Student
- **Name:** Nitish Kumar Kannaujiya
- **Roll No.:** 24BECCS33
- **Course:** B.Tech CSE (Cybersecurity), 5th Semester
- **University:** Central University of Jammu

## About This Project
Full aerodynamic analysis dashboard for a **cropped delta wing UAV**, replicating all Excel-based calculations in JavaScript. All 8 charts are computed live from first-principles aerodynamic formulas — no hardcoded data.

## Key Parameters
| Parameter | Value |
|-----------|-------|
| CLα (wing lift slope) | 2.8 /rad |
| CD0 (zero-lift drag) | 0.02 |
| Cm0 (zero-AOA pitching moment) | -0.05 |
| Cmα (static stability derivative) | -0.3 /rad |
| Cmδe (elevator effectiveness) | -1.2 /rad |
| Wing Area | 0.5 m² |
| Aircraft Weight | 10 N |
| Air density (ρ) | 1.225 kg/m³ |

## Key Results
| Performance Metric | Value |
|-------------------|-------|
| Max L/D Ratio | ~14.2 at α = 6° |
| Trim velocity at α = 5° | ~13.2 m/s |
| Min Thrust Required | ~0.70 N at ~12 m/s |
| Min Power Required | ~8.5 W at ~10 m/s |

## Features
- 🗂️ 5-tab interactive dashboard
- 🧮 All formulas computed in real-time JavaScript (δe, CL, CD, V, Tr, Pr, L/D, CL^1.5/CD)
- 📊 8 Chart.js charts: Trim, CL vs α, Drag Polar, Tr vs V, Pr vs V, L/D vs α
- 📋 Full trim analysis table (−5° to +15° AoA)
- 📈 Key performance findings section

## How to Run
Open `index.html` directly in any browser — no server or build step required.

## Live Demo
Deployed via GitHub Pages: https://nitishkumar9898.github.io/defspace-project4-cropped-delta-wing-uav/
