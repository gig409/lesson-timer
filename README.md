# Lesson Timer

Classroom countdown with Start / Pause / Reset, for embedding in slides.com or reveal.js via an iframe.

URL options: `m` (minutes), `s` (seconds), `label`, `theme=dark|clear`, `end=0` (end alarm off), `ticks=0` (final-seconds countdown beeps off), `tickfrom=15` (when the countdown beeps start), `auto=1`, `compact=1` (always icon-only buttons; otherwise they switch automatically when the timer is small), `id=q1` (unique name per timer so two slides with the same settings keep separate state), `update=1m` or `update=30s` (the clock moves in steps instead of every second: with `m=5&update=1m` it shows 5:00, 4:00, 3:00, 2:00, 1:00, then counts down every second from 0:30).

The timer remembers its state for the browser tab, so it keeps running when slides.com reloads it as you move between slides.

On-screen switches toggle the end alarm and the final-seconds countdown beeps during a lesson.

Example: `https://gig409.github.io/lesson-timer/?m=4&label=Do%20Now`
