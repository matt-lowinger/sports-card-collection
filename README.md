# Sports Card Collection

An interactive showcase for a personal sports card collection — 529 cards across
baseball, basketball, football, and hockey — built as a single self-contained
HTML file with no build step and no external fonts or assets.

**Live demo:** https://mql-cards.tiiny.site/

## What it does

- **Binder** — browse the collection page by page, with 3D card flips (front/back)
- **Slab Case** — graded cards shown with real slab labels
- **Timeline Shelf** — cards arranged along a timeline
- **Table View** — an Excel-style grid showing exactly the same 17 fields as a
  card's detail view, mobile responsive
- **Collection Stats** — totals and breakdowns by sport, set, team, and player,
  plus attribute reports (Rookie Card, Short Numbered, Memorabilia, Autographed)
  and a grading report (grader, certification number, grade name, grade number)
- **Search & filters** — filter by year, brand, set, team, player, attributes,
  and graded status in every view
- **Fun facts** — a researched fact for every card

Prices appear only in a card's detail view and in Stats — never on the card
previews. Grading fields appear in a card's detail view only when that card is
graded.

## Tech

- One file: `sports-card-collection.html` (open it directly, or serve it — no
  build, no dependencies). Card photos load from the URLs stored in the
  collection data itself.
- Data is embedded in the file, sourced from the collection spreadsheet linked
  in the page footer ("Source Data").

## Run it

```sh
# Option 1 — just open the file in a browser
open sports-card-collection.html

# Option 2 — serve it locally
python3 -m http.server 8000
# then visit http://localhost:8000/sports-card-collection.html
```

## Collection at a glance

- 529 cards, 302 players, 96 teams, 244 sets
- 14 graded cards (BCCG, PSA, Beckett, SGC), $1,900 combined graded value
- Most valuable card: 2008-09 Upper Deck Alex Ovechkin Frozen Artifacts, $1,000
