# TMT: Volleyball Hub — team data (private)

Team-specific data for https://kagazzie.github.io/TMT-VolleyballHub/. Keep this repo **private**.
The public site repo pulls these files in at deploy time; every push here triggers a redeploy.

- `team.json`: team name and roster (used by the hub and Clip Marker)
- `rotations.json`: rotation guide positions (Edit positions → Export JSON)
- `clips/`: one JSON per game, exported from Clip Marker

Requires the `TEAM_DATA_TOKEN` Actions secret (see the site repo's README).
