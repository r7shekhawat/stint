# Stint

A small, single-file time tracker. Add tasks, start and stop timers, see a 7-day dashboard, and export your log as CSV.

- Pomodoro mode (15, 25 or 50 minute rounds) and stopwatch mode
- Any number of tasks; starting one stops the previous one and logs it
- Today, last 7 days, per-task breakdown and a stacked bar chart
- Log of every session, with delete
- CSV export: date, task, start, end, duration (h:mm:ss), minutes
- Light and dark themes that follow your system setting
- No build step, no dependencies, no tracking

## Use

Open `index.html` in a browser. Data is stored in your browser's `localStorage`, so it stays on your device.

To host it, serve the file from any static host (GitHub Pages works: Settings, Pages, deploy from the main branch).

## Notes

- Clear site data and you lose the log, so export the CSV now and then.
- If the browser blocks the CSV download, Export CSV shows the text with a Copy button instead.

## License

MIT, see [LICENSE](LICENSE).
