[README.md](https://github.com/user-attachments/files/21858225/README.md)
# Notion Widgets Pack (EN)

Included Widgets:
- **Focus Timer (Pomodoro)** — work/break, long break, auto-next, beep
- **Goal Progress Bar** — % or value/goal, labels, theming
- **Countdown** — until/since/auto, progress window, labels
- **Habit Checklist** — daily reset, goal badge, streak, reset button

## 1) Deploy (Vercel)
1. Create a GitHub repo and add these files.
2. Connect the repo to **Vercel** (no framework preset needed).
3. Deploy. Your widgets will be available under:
   `https://your-domain.vercel.app/widgets/<name>.html`

## 2) Use in Notion
Open Notion → type **/embed** → paste the widget URL with its parameters.

## 3) Quick Params Cheat-Sheet

### Focus Timer
- `work`, `break`, `rounds`, `long`, `every`, `auto=1`, `beep=0`
- Theming: `bg`, `panel`, `fg`, `accent`, `ring`
- Example: `?title=Deep%20Work&work=45&break=10&rounds=3&auto=1`

### Goal Progress
- `progress=67` **or** `value=42&goal=100&unit=pages`
- Labels: `left`, `right`, `showlabels=0`, `showpct=0`, `format=%|number`
- Sizing/Theming: `size=sm|md|lg`, `radius=12px`, `bg/panel/fg/accent/accent2/ring`

### Countdown
- `date=YYYY-MM-DD` or `date=YYYY-MM-DD HH:mm`
- Modes: `mode=until|since|auto`; Progress window: `start=YYYY-MM-DD`
- Labels override: `ld/lh/lm/ls` (days/hours/minutes/seconds)

### Habit Checklist
- `habits=Drink%20Water,Reading,Workout`
- `goal=3` (day validated at 3 checks)
- Theming: `bg/panel/fg/accent/ring`

## 4) License
For your own store: include a **Personal Use** license by default, and sell a **Commercial Use** add-on if needed.
