Open the timeline in Mac Safari and hit record, then press toggle to open
the flexbox grid. Stop the recording and look at "Layout and rendering", sort
by duration.

Recalculate styles takes around 5 times longer on Tailwind 2 than on
Tailwind 1 (on my Macbook Pro). The same happens in Chrome but is less
noticeable.

Try here: https://tailwind-perf.netlify.app

The code that renders the slow grid is inside `renderGrid()`.
