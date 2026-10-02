# Healthy Me — Onboarding Redesign

A clickable concept of a shorter, friendlier onboarding for a wellness app. Built as a single HTML file, no dependencies. Available in English and Ukrainian.

## What changed

1. **Cut the number of taps.** Single-choice answers open the next screen on tap, with no separate Next button.
2. **Lowered the barrier to entry.** No login form or Terms checkbox on the first screen. People start the quiz right away and create an account after they see their plan.
3. **Cut the quiz from ~25 to 10 screens.** Sex, age, height and weight live on one screen; detailed questions move into the app.
4. **Replaced 5 consent screens with one line** under the Next button on the health screen.
5. **Moved pickers under the field they change**, following iOS inline-picker behaviour.

## Expected product impact

Hypotheses to validate with an A/B test against the current flow:

| Change | Metric |
|---|---|
| Lower barrier to entry | Onboarding completion rate |
| Faster time to value | Sign-up rate after the plan |
| More trust in the plan | Share who tap “Start Day 1” |
| Higher day-1 activation | Day-1 workout completion, D1/D7 retention |
| More notification opt-ins | Push opt-in rate |

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 5173
```

Then go to http://localhost:5173.
