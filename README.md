# 2026 SBC Annual Meeting — Reference Documents

Structured reference documents for the **2026 Southern Baptist Convention Annual Meeting**, held June 7–10, 2026 at the Orange County Convention Center, Orlando, FL.

This repo is intended as a knowledge base that attendees and AI agents can query for schedules, venue navigation, exhibitor locations, resolutions, and reports.

---

## Files

| File | Contents |
|------|----------|
| [01_Annual_Meeting_Program.md](01_Annual_Meeting_Program.md) | Official plenary session schedule, speakers, and SBC officer roster |
| [02_Proposed_Resolutions.md](02_Proposed_Resolutions.md) | All 11 proposed resolutions submitted for convention action |
| [03_Book_of_Reports.md](03_Book_of_Reports.md) | Full Book of Reports — entity summaries, Cooperative Program financials, statistics |
| [04_Venue_Navigation.md](04_Venue_Navigation.md) | Walking times, skybridge access, rideshare zones, and OCCC internal room guide |
| [05_Exhibitors.md](05_Exhibitors.md) | All 277 exhibitors with booth numbers, organized by floor section with walking estimates |
| [2026_SBC_Annual_Meeting_Events.md](2026_SBC_Annual_Meeting_Events.md) | Complete event schedule June 6–10 — meals, breakouts, fellowships, childcare |

---

## Using with AI Agents

Each file is plain Markdown and can be fetched directly from GitHub's raw content URL:

```
https://raw.githubusercontent.com/dsethbrown/2026SBC/main/<filename>
```

**Example — fetch the exhibitor directory:**
```
https://raw.githubusercontent.com/dsethbrown/2026SBC/main/05_Exhibitors.md
```

Point your AI agent at one or more of these files as context. Suggested pairings:

- **"Where is booth X?"** → `05_Exhibitors.md` + `04_Venue_Navigation.md`
- **"What's happening Tuesday morning?"** → `2026_SBC_Annual_Meeting_Events.md` + `01_Annual_Meeting_Program.md`
- **"What did the IMB report?"** → `03_Book_of_Reports.md`
- **"What resolutions are being voted on?"** → `02_Proposed_Resolutions.md`

---

## Data Sources

- Floor plan and exhibitor data: [sbc26.mapyourshow.com](https://sbc26.mapyourshow.com/8_0/floorplan/index.cfm?hallID=campus&level=2&st=exhibitor)
- Official meeting site: [sbcannualmeeting.net](https://sbcannualmeeting.net)
- Pastors' Conference: [sbcpc.net](https://www.sbcpc.net)
