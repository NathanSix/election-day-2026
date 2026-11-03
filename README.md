# Election Day 2026

Live dashboard for the Nov. 3, 2026 U.S. midterms: Georgia's statewide races and constitutional amendments, control of Congress, and the 12 Senate races CBS News named as most likely to decide the majority.

**Live page:** https://nathansix.github.io/election-day-2026/

## How it updates

Claude, an AI assistant, refreshes the files in `data/` on a schedule: every two hours from 8 AM to 6 PM ET, hourly from 7:20 PM to 2:20 AM ET on election night, and every two hours on Wednesday. Race calls come from the Associated Press; Georgia vote counts come from the Georgia Secretary of State. A race is shown as called only after AP calls it. The page checks for new data every minute while it is open.

All results are unofficial until certified. For real-time counts, use [AP](https://apnews.com/projects/elections-2026/) and the [Georgia Secretary of State](https://sos.ga.gov/november-3-2026-general-election).
