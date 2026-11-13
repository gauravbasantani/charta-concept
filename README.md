# Charta Health concept: count only the minutes on the visit day

An unofficial design concept by Gaurav Basantani ([gauravbasantani.com](https://gauravbasantani.com)). Not affiliated with Charta Health.

A coder reviews one clinic day's pre-bill code changes in a screen shaped like Charta's autocorrect card. One autocorrect raises a visit from 99213 to 99214 on 32 documented minutes, but 12 of those minutes are dated the day before the visit. Only time on the date of service counts, so the card flags it before Approve, shows each minute's date, and makes Keep 99213 the main button. Approve it anyway to see the wrong answer caught; Undo and Start over work on every step.

The clinic, provider, patients and notes are made up. Time rules are simplified from public CPT guidance. Not billing advice.

Live page: https://gauravbasantani.github.io/charta-concept/

One static file (`index.html`), no build step.
