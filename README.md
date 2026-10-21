# 🍅 Simple Pomodoro Timer

A tiny, open-source Pomodoro timer in **one HTML file**. Easy setup, no dependencies, no tracking.

Work in focused sessions, then rest with short and long breaks.

## Features

- **Three modes:** Focus (25 min), Short break (5 min), Long break (15 min)
- **Automatic cycle:** a long break after every 4th focus session
- **Session counters** and a 4-dot cycle indicator
- **Progress ring** that changes color per mode
- **Remembers your state** across reloads (localStorage, expires after 7 days)
- **Accurate in background tabs:** based on timestamps, not tick counting
- **Live countdown in the tab title**

## Quick start

```bash
git clone https://github.com/<your-username>/pomodoro-focus-timer.git
cd pomodoro-focus-timer
open index.html   # or just double-click it
```

Or host it anywhere static: GitHub Pages, Netlify, Cloudflare Pages, or any web server.

## Customize

Everything lives in `index.html`. Edit the constants at the top of the `<script>`:

```js
const DURATIONS = { focus: 25 * 60, short: 5 * 60, long: 15 * 60 }
const LONG_BREAK_EVERY = 4
```

Mode colors are the `--ring-color` values in the CSS (`#ec5e39`, `#2f9e6e`, `#2f6fe5`).

## 📱 Want a Pomodoro timer on your phone? Try PomPom

A browser tab is great at your desk, but a mobile app can keep you on track anywhere. Try **PomPom**, a free, simple Pomodoro app that also tracks your focus trends over time:

| Platform | Link |
| --- | --- |
| 🍎 App Store | [Download PomPom for iPhone & iPad](https://apps.apple.com/us/app/pompom-pomodoro-focus-timer/id6761312217) |
| 🤖 Google Play | [Find PomPom on Google Play](https://play.google.com/store/apps/details?id=com.leadstepp.alldone) |

## Contributing

Issues and pull requests are welcome. Please keep it simple: the goal is to stay a single, dependency-free HTML file.

## License

[MIT](LICENSE)
