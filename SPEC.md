# Grid spec

The repo is a 3x3 gif grid rendered in README.md.

- Cell size: 200x200 px, animated GIF.
- File naming: `<subject>_column#<row>#<column>.gif` — subject in lowercase snake_case, row and column are 1-based grid coordinates.
- Wide sources are center-cropped to square, then resized to 200x200 (no aspect distortion).
- File names contain `#`, so image URLs in README.md must be percent-encoded (`%23`).

## Current grid

| Position | File |
|----------|------|
| 1#1 | linus_torvalds_column#1#1.gif |
| 1#2 | al_pachino_column#1#2.gif |
| 1#3 | marilyn_monroe_column#1#3.gif |
| 2#1 | jet_fighter_column#2#1.gif |
| 2#2 | jensen_laptop_column#2#2.gif |
| 2#3 | mesmerizing_china_column#2#3.gif |
| 3#1 | to_the_moon_column#3#1.gif |
| 3#2 | navi_column#3#2.gif |
| 3#3 | n3charrtt2_column#3#3.gif |
