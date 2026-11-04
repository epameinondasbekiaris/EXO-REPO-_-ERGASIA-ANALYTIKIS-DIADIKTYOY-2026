# Exo Repo

A mobile-first prototype for finding an Attica outing based on your mood, appetite, budget, group size, and the day you are planning for.

## Run locally

Open `index.html` in a browser, or serve this directory with a local static web server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Flow and features

1. Sign up with an email, a strong password, and a region in Attica.
2. Choose a date, mood, appetite, budget, and group size.
3. Browse matching categories by estimated fullness, reverse the sort order, and choose one with **I'm going here**.
4. Use the bottom navigation to explore places and crowd levels in your selected region, search or filter venues, view place details, save places, and manage your daily plan.
5. Open **For You** to see a ranked list of recommendations. It counts category interests from exploring, viewing, saving, planning, and choosing places, and combines those signals with today's mood, appetite, budget, and region.

The app keeps its original categories and includes Escape Rooms, Cinemas (Movie Theaters), Theaters (Live Plays), Mezedopoleia / Koutoukia, Chill Drink Spots, Nightclubs / Nightlife, Bowling & Billiard Halls, and Board Game Cafes. Places can belong to both an original category and a more specific category.

This is a front-end demo only. It does not create accounts, send or store passwords, or connect to live venue/crowd data. Venue and fullness data are examples. Saved places, plans, and recommendation interest counts are held in memory and reset when the page reloads.
