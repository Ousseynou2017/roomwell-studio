# "Before" photos for the projects slider

One file per project, named `project-<name>-before.webp`, same framing as the "after" photo (3:2 or 4:3; 960 px wide is enough: a card is never wider than 420 px).
The page tries to load each file when the projects come into view: if it loads, that card shows the drag slider; if it is missing, the card shows the "after" photo alone. Nothing else to change.

Names in use: `project-lewis-kitchen-before.webp`, `project-mills-house-before.webp`, `project-patel-bathroom-before.webp`, `project-chen-kitchen-before.webp`.
These files sit outside `assets/` on purpose: `assets/` is cached for a year and fingerprinted, which would break the drop-in.
