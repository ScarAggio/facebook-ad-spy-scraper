# Facebook Ad Spy Tool
This project automates the collection, aggregation, and organization of ad data from Facebook’s mobile interface. The Facebook Ad Spy Tool helps researchers, marketers, and analysts quickly gather competitor insights without manual browsing. It streamlines repetitive tasks and outputs clean, structured intelligence for decision-making.


<p align="center">
  <a href="https://Appilot.app" target="_blank"><img src="https://github.com/Instagram-Automations/Footer-test/blob/main/appilot-baner.png" alt="Appilot Banner" width="100%"></a>
</p>

<p align="center">
  <a href="https://t.me/devpilot1" target="_blank"><img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:support@appilot.app" target="_blank"><img src="https://img.shields.io/badge/Email-support@appilot.app-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://Appilot.app" target="_blank"><img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/xvPWXJXCw7" target="_blank"><img src="https://img.shields.io/badge/Join-Appilot_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Appilot Discord"></a>
</p>



## Introduction
This automation tool navigates Facebook’s ad library UI, extracts ad metadata, and compiles it into exportable formats. It removes the need for endless scrolling, filtering, and copy-pasting—turning hours of manual work into minutes. Businesses benefit from faster research cycles, consistent data, and scalable competitive monitoring.

### Automated Competitive Ad Intelligence
- Reduces manual collection time by more than 80%.
- Ensures consistent extraction across devices using stable UI selectors.
- Handles dynamic content loading, scrolling, and pagination automatically.
- Supports proxy rotation for safer high-volume ad research.
- Generates both raw and summarized datasets for further analytics.

## Core Features
| Feature | Description |
|----------|-------------|
| Automated Ad Collection | Captures ad creatives, text, metadata, and advertiser details through UI automation. |
| Infinite Scroll Handling | Automatically scrolls through long ad feeds and loads additional items. |
| Search & Filter Automation | Applies keywords, regions, and ad categories programmatically. |
| Screenshot & Asset Capture | Saves screenshots of each ad for visual analysis workflows. |
| Data Normalization | Converts raw UI data into structured JSON and CSV formats. |
| Proxy & Session Manager | Handles IP rotation and session freshness for safer operations. |
| Retry & Backoff Logic | Automatically retries failed actions with smart backoff. |
| Queue-Based Scheduler | Spreads tasks across workers and devices for higher throughput. |
| Device Farm Compatibility | Works across hundreds of Android instances simultaneously. |
| Structured Logging | Outputs detailed logs for debugging, auditing, and analytics. |

---
## How It Works
**Input or Trigger** — User provides keywords, filters, and automation parameters.
**Core Logic** — Android automation navigates the app, extracts fields, scrolls, and stores results.
**Output or Action** — JSON, CSV, and screenshot bundles are generated in the output folder.
**Other Functionalities** — Proxy rotation, dynamic wait handling, and environment-based config loading.
**Safety Controls** — Rate limits, cooldowns, session resets, and workflow-level timeouts.

---
## Tech Stack
**Language:** Python
**Frameworks:** Appium, UI Automator
**Tools:** Appilot, scheduler/queue workers, rotating proxies
**Infrastructure:** Local devices, emulators, and distributed Android device farms

---
## Directory Structure
    automation-bot/
    ├── src/
    │   ├── main.py
    │   ├── automation/
    │   │   ├── tasks.py
    │   │   ├── scheduler.py
    │   │   └── utils/
    │   │       ├── logger.py
    │   │       ├── proxy_manager.py
    │   │       └── config_loader.py
    ├── config/
    │   ├── settings.yaml
    │   ├── credentials.env
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── results.json
    │   └── report.csv
    ├── requirements.txt
    └── README.md

---
## Use Cases
- **Marketing teams** use it to collect competitor ads so they can optimize their own campaigns.
- **Agencies** use it to generate ad intelligence reports for clients faster.
- **Researchers** use it to study trends and messaging patterns for industry insights.
- **Analysts** use it to automate large-scale ad sampling for datasets and modeling.
- **Growth teams** use it to track creative changes over time to improve performance strategies.

---
## FAQs
**Does this automate a real device or emulator?**
It works with both and scales effectively across device farms.

**Can it run continuously?**
Yes—task scheduling and queues allow long-running automated collection.

**Does it store screenshots?**
Yes, screenshots and metadata are captured per ad.

**How do I manage proxies?**
The proxy manager handles automatic rotation and assignment.

**Can results be exported into analytics tools?**
Data is saved in JSON/CSV and can be imported anywhere.

---
## Performance & Reliability Benchmarks
**Execution Speed:** 40–55 automated UI actions per minute on mid-range Android device farms.
**Success Rate:** ~93–94% completion across long-running multi-hour jobs with retry logic.
**Scalability:** Supports 300–1,000 Android devices through sharded queues and distributed workers.
**Resource Efficiency:** ~12–18% CPU and 350–500MB RAM per worker under standard load.
**Error Handling:** Automatic retries, exponential backoff, structured logs, alert hooks, and graceful recovery workflows.


<p align="center">
<a href="https://cal.com/app-pilot-m8i8oo/30min" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
 
  <a href="https://www.youtube.com/@Appilot-app/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
