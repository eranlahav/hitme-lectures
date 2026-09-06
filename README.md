# hitme-lectures

Course lecture materials for **עיצוב החלטות** (Designing Decisions) at HIT — Holon Institute of Technology.

Published via GitHub Pages. This repository holds **lecture decks only** — it is intentionally separate from the application repository so that student clones of the app stay lean and free of large binary media.

## Layout

```
/                README + this index
index.html       RTL Hebrew landing page linking to each lecture
/lesson-01/      Lesson 1 deck (index.html + assets)
.nojekyll        disables Jekyll so underscore-prefixed paths are served
robots.txt       disallows indexing
```

Lessons 2–14 will be added under `/lesson-NN/` as the semester progresses.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Notes

- The deck loads React/ReactDOM from unpkg.com at runtime. See repository history / owner notes on vendoring if presenting on unreliable networks.
