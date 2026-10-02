# pomodoro-timer-v1

A React **Pomodoro Timer** component — focus/break cycle timer with start/pause/reset controls, built with shadcn/ui and lucide-react.

## What it does

- **25-minute focus sessions** with automatic break cycles
- Play / pause / reset controls
- Session progress display (focus vs. short/long break)
- Clean card-based UI via shadcn/ui `Card`, `Button`, and lucide icons

## The file

- `pomodoro-timer v1` — single self-contained React component (`PomodoroTimer`)

## Usage

The component expects a project with:

- React 18+
- shadcn/ui (`components/ui/button`, `components/ui/card`)
- lucide-react

```tsx
import PomodoroTimer from "./pomodoro-timer v1";

export default function App() {
  return <PomodoroTimer />;
}
```

## License

CC0 1.0 Universal (see `LICENSE`).

## Author

Built by [Girish Lade](https://ladestack.in).
