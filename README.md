# Maize, Blue, and a Fuller Big Ten

Big Ten Academic Alliance Love Data Week 2027 Data Viz Championship entry (University of Michigan, faculty/staff).
Author: Fadhl Alakwaa, University of Michigan.

Live page: `https://<your-github-username>.github.io/b1g-wbb-love-data-2027/`

## Contents
- `index.html` — the full interactive story. It is self-contained: the Vega/Vega-Lite libraries, chart data, and basemap are embedded, so nothing loads from external servers.
- `data/b1g_wbb_home_attendance_clean.csv` — the 2,785 Big Ten home games used for the attendance charts (2013–14 to 2025–26; 2020–21 omitted).
- `data/b1g_wbb_conference_matchups_2024_2026.csv` — the regular-season conference matchup pairs behind the travel map.

## Data
NCAA women's college basketball schedules and team box scores from ESPN, compiled by the SportsDataverse wehoop project
(sportsdataverse-data GitHub releases). Exclusions: neutral-site games, games with no reported attendance, the 2020–21 COVID season,
and one implausible value (111,368 fans at Breslin Center, Feb. 24, 2019). Travel distances are straight-line, one-way, between approximate campus coordinates.

## AI use
This entry was produced with the help of an AI assistant (Claude, Anthropic). The AI proposed candidate story angles, wrote the Python code used to download, clean and analyze the data, generated the charts and draft text, and assembled and published this page. The author chose the competition track and the story, selected the headline and design direction, reviewed the findings and text, and is responsible for the accuracy of the final entry. All figures come directly from the cited public data, and the cleaning steps, including the excluded attendance error, are documented on the page.

## Publish on GitHub Pages
1. Create a public repository named `b1g-wbb-love-data-2027` and upload the contents of this folder (keep `index.html` at the top level).
2. Settings → Pages → Build and deployment → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. After a minute or two the page is live at the URL above. Open it in a private/incognito window to confirm it works with no login.
