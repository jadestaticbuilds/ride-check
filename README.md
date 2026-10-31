# Ride check

A single-file, browser-based app for deciding if it is actually a good day to ride. Open `index.html` in a browser — no build step, no server needed.

## What it does

- **Weather verdict** — Good to ride, Ride with care, or Hold off, based on the next 6 hours
- **Next 6 hours** — temperature, conditions, rain chance, and gusts
- **Recent weather** — if it rained in the past 3 hours but has stopped, it warns that roads may still be wet and slippery, and bumps a Good to ride verdict to Ride with care
- **Ride timer** — Start ride and Stop ride, with elapsed time in hours, minutes, and seconds. Start new ride also resets the timer to 00:00:00
- **Before you go checklists** — motorcycle checks (tire pressure and tread, oil, chain, brakes, fluids, lights and signals, fuel) and riding gear checks (helmet and visor, gloves, jacket and pants, boots, rain gear)
- **Fuel and directions** — Waze directions and a live Waze map in the page

## Try it

- Open `index.html` directly in your browser, or
- Use the live site: https://jadestaticbuilds.github.io/ride-check/

Allow location on the site, or search a town or city, to get the verdict for that place.

## Make it your own

This repo is public under the MIT License (see `LICENSE`). Fork it, change the checks, restyle it, add new tools — your fork is yours.

## Notes

- Weather comes from Open-Meteo; location is used only to fetch the forecast for that place.
- The app is a single HTML file, so the whole project is just `index.html` plus this README and the license.
