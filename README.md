# FlowState — Mindful Productivity Hub

A personal dashboard that keeps the four things that actually move a day in one
place: what has to get done, what should happen repeatedly, how the day felt,
and one block of undistracted work.

## What is in it

| Panel | What it holds |
| --- | --- |
| Tasks | A checklist with add and complete, persisted locally |
| Habits | Repeatable items with their own add flow |
| Daily Journal | A dated entry with a mood prompt and a list of recent entries |
| Focus Session | A countdown timer at 15, 25 or 45 minutes, start and reset |

A local account gate (sign up, log in, log out, forgot-password stub) keeps the
dashboard on the machine it was created on.

## Run it

Open `index.html` in a browser. State lives in the browser, so the dashboard
survives a reload on the same machine.

## Notes

No backend. There is no sync between devices, and clearing site data clears the
journal.
