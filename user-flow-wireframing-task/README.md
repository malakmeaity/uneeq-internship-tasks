# Task 2: User Flow and Wireframing

**Student Career App** | By Malak Meaity | UneeQ Interns, UI/UX Track

## The task
Users struggle to complete a key action in a digital product because the flow is unclear. The task is to create a clear user flow and low-fidelity wireframes for the core journey.

**Core journey:** a student finds their next career step and adds it as a goal.

## Deliverables

| Deliverable | Where to find it |
|---|---|
| Information architecture (sitemap) | [`diagrams/sitemap.png`](diagrams/sitemap.png) |
| User flow diagram | [`diagrams/user_flow.png`](diagrams/user_flow.png) |
| Mobile wireframes (10 screens, including empty, loading, error and success states) | [`wireframes/mobile/`](wireframes/mobile/) |
| Desktop wireframes (Home, Explore) | [`wireframes/desktop/`](wireframes/desktop/) |
| Key design decisions document | [`Task_2_Key_Design_Decisions.docx`](Task_2_Key_Design_Decisions.docx) |
| Flow explanation video | [Watch on Google Drive](https://drive.google.com/file/d/17tQhF3k5VhxLFcsMFdgFieXGDSpz4gfi/view?usp=drive_link) |

## Links
- Figma wireframes: https://www.figma.com/design/k0pGUihKp1KGKpQlTqdxGQ/Task-2---Wireframes
- FigJam sitemap and user flow: https://www.figma.com/board/sl6EP8PnFqY9l0Ya7WaP7q/Task-2---User-Flow
- Explanation video: https://drive.google.com/file/d/17tQhF3k5VhxLFcsMFdgFieXGDSpz4gfi/view?usp=drive_link
- LinkedIn post: [PASTE LINKEDIN POST LINK]

## Screens in the flow

| # | Screen | Purpose |
|---|---|---|
| 01 | Home | "Your next step" is the largest element |
| 02 | Goals (empty state) | New users get a clear "Find your first step" button |
| 03 | Goals overview | Existing goals, with "Add goal" as the main action |
| 04 / 04b | Explore / Explore (loading) | Suggested next steps and a search field; skeleton cards while loading |
| 05 | Step details | What the step is, its type and time needed, and an "Add as goal" button |
| 06 | Set goal | Only a due date and optional notes, to remove friction |
| 07 | Error | A missing date is flagged and a failed save offers "Try again" |
| 08 | Success | Confirms the goal was added |
| 09 | Home (updated) | The new goal appears under Upcoming goals |

## Key decisions (short version)
- Five main sections (Home, Progress, Goals, Explore, Profile) fit a mobile bottom bar and keep every page one or two taps away.
- One clear main action on every screen.
- The goal form has only a due date and optional notes.
- Empty, loading and error states are designed, not left blank.
- On desktop the bottom bar becomes a left sidebar and the cards sit side by side. The hierarchy stays the same.

Assumptions and what I would test next are listed in the full document.
