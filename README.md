# macros-and-maxes

Keep track of your macros and max lifts. KISS — one file, no installs, no accounts.

**Live app: https://built4m3-dev.github.io/macros-and-maxes/**

Open it on your phone and add it to your home screen (Share → Add to Home Screen) to use it like an app. Your data saves automatically in the browser (localStorage), so it stays on whichever device you log it on — phone and laptop each keep their own history.

You can also just open `index.html` in any browser; it works fully offline apart from the online food search.

## Macros tab

- Set your daily calorie, protein, carb, and fat goals (saved automatically).
- Log foods with calories and macros — totals and progress bars update as you go.
- Type 2+ letters in the Food field to search the food database: ~90 common foods are built in with per-serving macros, and 3+ letters also searches [Open Food Facts](https://world.openfoodfacts.org/) for branded items (shown per 100 g). Tap a result to auto-fill the macros, then adjust for your portion.
- Bars glow green when you hit a goal and amber if you go over.
- Use the arrows or date picker to view or edit past days.

## Max Lifts tab

- Enter an exercise, the weight you lifted, and how many reps.
- The app estimates your 1-rep max (Epley formula) and shows a table of estimated weights for 1–12 reps, rounded to the nearest 5 lbs.
- Personal Records shows your best estimated 1RM per exercise; full history is listed below it.

## Deploying

`.github/workflows/pages.yml` publishes the site to GitHub Pages on every push to `main` — merge a PR and the change is live about a minute later. The repo's Pages source is set to **GitHub Actions** (Settings → Pages); don't switch it to "Deploy from a branch" or the workflow's deployment will stop taking effect.
