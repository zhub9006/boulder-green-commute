# 🤝 Contributing to the Boulder Green Commute Guide

**This guide is for Boulder residents, by Boulder residents. Help us make it better!**

---

## How to Add Your Own Commute Route

### Step 1: Gather Your Route Data
- **From:** Your home address (or nearest cross-street)
- **To:** Your office address (or nearest cross-street)

### Step 2: Create Your Route File
1. Name it `routes/[your_initials]_commute.md` (e.g., `routes/jsmith_commute.md`)
2. Follow the template in the walking and biking route files
3. Include: turn-by-turn, segment distances, times, CO₂, calories, landmarks
4. Add your personal experience

### Step 3: Update Summary
1. Add your route to the `route_data.json` file
2. Update the README comparison table

---

## Formatting Guidelines

- **Headers:** Use `#` (H1), `##` (H2), `###` (H3)
- **Tables:** Use pipes for mode comparisons
- **Coordinates:** Decimal degrees (WGS84) — e.g., `40.0163281, -105.2789726`
- **Distances:** Prefer meters and kilometers (convert to miles in parentheses)
- **Times:** Minutes with context (e.g., "~48 min at 5 km/h")
- **Emoji:** Use the mode emojis: 🚶 Walking, 🚴 Biking, 🚗 Driving, 🚌 Bus

---

## Data Sources
- **OpenStreetMap** — primary source for geocoding, routing, and POI data
- **RTD (Regional Transportation District)** — for bus/transit info
- **B-Cycle** — for bike-share data
- **City of Boulder / Boulder County** — for infrastructure updates
- **EPA** — for emissions factors
- **CDC / WHO** — for health/calorie estimates

---

## Pull Request Process
1. Fork the repo
2. Create a branch: `git checkout -b add-your-route-name`
3. Commit your changes: `git add routes/your_route.md && git commit -m "Add [Name] route"`
4. Push to your fork: `git push origin add-your-route-name`
5. Open a Pull Request against `zhub9006/boulder-green-commute`

---

## Reporting Issues
If you find:
- Discontinued businesses or transit lines
- New bike infrastructure or closures
- Inaccurate route advice
- Weather/corridor changes

Open an issue on GitHub so we can update the guide.

---

*Thank you for helping Boulder become a greener, more walkable, and more bikeable city. Let us go! 🌿🚴🚶*