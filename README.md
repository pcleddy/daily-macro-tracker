# Daily Macro Tracker

A single-page macro tracking app with 100 common ingredients, custom quick-add, and personalized daily targets.

**[Launch App](https://pcleddy.github.io/daily-macro-tracker/)**

## Features

- **100 common ingredients** with per-gram macro data across 9 categories
- **Common serving sizes** for each ingredient (cups, oz, slices, etc.)
- **Quick Add** custom macros via pill buttons for unlisted items
- **Daily targets** calculated from your profile using Mifflin-St Jeor BMR, 1g protein/lb body weight, remaining calories split 55/45 carbs/fat
- **Daily tracker** with running totals for calories, protein, carbs, and fat
- **Resizable panels** — drag the left panel border to resize
- **LocalStorage persistence** — profile settings and daily log survive page refreshes

## Tech

Single `index.html` file. No dependencies, no build step. All ingredient data and macro logic lives in inline JSON and vanilla JS.
