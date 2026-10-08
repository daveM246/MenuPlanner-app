# Menu Planner - COMING SOON

A Windows desktop app for building a 7-day menu plan against nutrient
targets. Ingredients carry nutrient values (calories, protein, sodium,
fibre, and anything else you choose to track), recipes are built from
ingredients, and the Planner tab totals up whichever recipes you've picked
for each day -- colour-coded against the minimums and maximums you set.

This repo exists only to publish the installer. The app's source code is
maintained privately elsewhere.

## Download

Grab the latest `MenuPlanner-Setup.exe` from the
[Releases page](https://github.com/daveM246/MenuPlanner-app/releases/latest).

- No admin rights needed -- it installs just for your own user account.
- Windows SmartScreen will likely show an "unrecognized app" warning the
  first time you run it, since the installer isn't code-signed. Click
  **More info → Run anyway** to continue.
- The app comes with a small sample database (a few ingredients, recipes,
  and a sample week's menu) so there's something to look at right away --
  replace it with your own data whenever you're ready.

## Features

- Ingredients tab: a personal nutrient database, with **Compare Online**
  to look values up against USDA FoodData Central, Open Food Facts, the
  NZ Food Composition Database, AUSNUT, or CoFID.
- Recipes tab: build recipes from batch and per-serving ingredients, with
  live nutrient totals per serving.
- Planner tab: a 7-day plan, colour-coded against minimum/maximum targets
  you set per nutrient category.
- Multiple diet types, each with its own targets, sharing the same
  ingredients and recipes.
- Print a day's plan or a single recipe through the standard Windows
  print dialog.
- Archive and restore named snapshots of the whole database.

See **Help → How to Use...** inside the app for the full walkthrough.

## Updates

The app checks this repo for a newer release automatically (no more than
once a week) and shows a notice with a link here if one's available -- it
never downloads or installs anything on its own. You can also check
manually any time via **Help → Check for Updates...** inside the app.


