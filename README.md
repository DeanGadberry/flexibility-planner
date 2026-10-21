# Flexibility Planner

Pick a flexibility skill, take a quick self-test, and get the 3–5 stretches
you need, in order, with doses, a weekly schedule, a target date and a
reassessment date.

Covers the eight positions from Matt Smith's *The Blueprint to Get Flexible
Once, Forever*: Pike & Head to Toe, Pancake, Side Split, Front Split, Bridge,
Shoulder Flexion, Shoulder Extension and Squat. The library has 87 stretches
across 13 methods; every one has written instructions and a demo video.

## Use

Live at https://www.deangadberry.com/flexibility-planner/, or open
`index.html` in a browser, or host the folder anywhere static. No build step,
no dependencies. Pushes to `main` deploy to GitHub Pages through
`.github/workflows/pages.yml`.

1. **Assess** – a 5-minute warm-up for the skill, your level, and a
   radio-button self-test that finds your limiters.
2. **Plan** – focus areas, your stretches with "Show me how" videos, and a
   week built around your lifting days. Reassess every 4 weeks.
3. **Library** – every stretch for the skill (or all of them), with filters
   and a skill-by-method grid.

Answers are saved in the browser on that device only.

## Take it with you

- **Phone image:** a 1080 x 1920 card with the stack, the week and the next
  reassessment date.
- **Print:** a one-page plan with a reassessment sheet for the next three
  dates.

## Files

- `index.html` – the page
- `data.js` – skills, self-tests, warm-ups, methods and the stretch library
- `app.js` – plan builder, scheduler, figures, phone image and print view
- `style.css` – styles (gruvbox-inspired)
- `fonts/` – EB Garamond (SIL Open Font License, see `OFL-EBGaramond.txt`)

## License

CC BY-NC 4.0: free to use, share and adapt for non-commercial purposes with
credit. See `LICENSE` for details and for what isn't covered (fonts and the
embedded videos).

## Credits

Method: Matt Smith (independent project, not affiliated). Dosing and timing
draw on the research listed on the page. Exercise descriptions are original;
every video belongs to its creator and is embedded from YouTube.
