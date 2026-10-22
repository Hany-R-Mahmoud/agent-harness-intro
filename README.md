# Agent Harness Presentation

A four-slide interactive HTML presentation explaining the layers around an AI model that help an agent do useful work: its loop, tools, memory, context management, instructions, and supporting capabilities.

## View the presentation

1. Download this repository using **Code → Download ZIP**, then extract it, or clone it:

   ```sh
   git clone https://github.com/Hany-R-Mahmoud/agent-harness-presentation.git
   cd agent-harness-presentation
   ```

2. Open `harness-deck-presentation.html` in a modern web browser.

The presentation includes its styles, scripts, and artwork in one HTML file. No installation, build step, or local server is required. External project links require an internet connection. GitHub's file viewer displays the HTML source; download the file to view the slides.

## Slides

| Slide | Topic |
| --- | --- |
| What makes an AI agent work? | An overview of the agent-harness layers. |
| The core of the harness | Loop, tools, memory, context management, and instructions. |
| Guide and support the work | Supporting capabilities and candidate tools. |
| Observe, recover, and adapt | Capabilities for observing and improving agent work. |

## Controls

| Control | Action |
| --- | --- |
| Previous / Next buttons | Move between slides. |
| Right arrow / Page Down | Next slide. |
| Left arrow / Page Up | Previous slide. |
| Home / End | First / last slide. |
| Escape | Close an open tool detail dialog. |

Slide fragments such as `#slide-2` open a specific slide. Tool cards provide additional details and, where included, links to the relevant projects.

## Files

- [`harness-deck-presentation.html`](harness-deck-presentation.html): the original presentation, preserved without modification.
- [`README.md`](README.md): overview and viewing instructions.

## Editing

Edit the HTML file directly. Slide content is stored in the `slide-data` JSON script block; the same file contains the presentation styles and navigation logic. Reopen or refresh the file in your browser to review changes.

## Attribution and scope

The presentation credits George Fahmy's agent-harness map as its starting point. Third-party names, logos, and artwork belong to their respective owners.

Tool listings describe options and candidates, including exploratory choices. They are not benchmarks or guarantees of availability, effectiveness, or compatibility. Refer to each project's own documentation and license before adopting it.

No repository-wide license is included. Public availability does not grant a separate license to reuse the presentation or third-party artwork.
