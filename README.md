# Supply Chain Task Time Calculator v1

Pilot prototype for Matt Rubin and Eric.

## What it is
A low-friction time calculator that tracks *work mode*, not micro-tasks.

### Eight modes
- Planning / analysis
- Supplier / manufacturing coordination
- Logistics / fulfillment execution
- Meetings
- Document updates / notes
- Approvals / handoffs
- Systems / admin / transactional work
- Fire drills / exceptions

### Optional secondary tags
- Plan
- Source
- Make
- Deliver
- Quality
- Systems/Projects

## How to use
1. Open `index.html` in a browser.
2. Click the mode you’re doing.
3. Optionally click a phase tag.
4. Use *Pause / break* when needed.
5. Use *Undo last switch* if you fat-finger a mode.

## Built-in behavior
- localStorage persistence
- idle auto-pause after 3 minutes
- today and last-7-days summaries
- break state
- one-click switching

## Pilot assumption
This is for Matt + Eric only, to see where supply-chain bandwidth actually goes before we overbuild automation. Meetings and document-update overhead are separate buckets on purpose, because they were getting hidden inside "internal coordination".
