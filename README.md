# From Flat Diagrams to Living Models

A design thinking project on bringing interactive 3D models into everyday engineering teaching — so that concepts like fields, waveforms and circuits can be entered and manipulated instead of only being drawn on a board.

This repository holds both halves of the project: the **proposal presentation** and a **working prototype** with 70 built-in visualisations.

## The idea in one paragraph

Engineering is taught largely through static 2D diagrams, while the things being taught are dynamic and three-dimensional. Students are asked to build a mental 3D model from a flat picture, and many never get there — which shows up later as weak practical readiness. This project proposes a low-cost, browser-based layer of interactive 3D models that sits **alongside** the teacher, not in place of them: the lecture stays, but the diagram becomes something you can rotate, slice and change in real time.

## The prototype

`prototype-3d.html` is a working demonstration. Type a topic into the search bar, press Visualize, and the model appears.

- 70 built-in topics across calculus, differential equations, engineering physics, optics, semiconductor physics, basic electrical and electronics, network analysis, engineering chemistry, programming and basic civil and mechanical engineering
- Any equation can be typed straight in, for example `z = sin(x)*cos(y)`, and it is plotted directly
- The search tolerates spelling mistakes
- Controls: drag to orbit, scroll or pinch to zoom, `Space` pauses, `R` resets the view

The complete list of what to type for each of the 70 topics is in `prototype-topic-list.pdf`.

## What's inside the presentation

- Overview and context — the shift from flat diagrams to spatial models
- Research grounding — published work on visualisation and learning outcomes
- Evidence — the numbers behind the problem
- Equity and access — why a browser-based approach matters
- Institutional fit — why this amplifies faculty rather than replacing them
- Design thinking process — Empathize, Define, Ideate, Prototype, Test
- Prototype — interface concept and a worked example
- Evaluation — feasibility, viability, scalability
- Implementation — phases, timeline, cost drivers
- Roadmap — AR, digital twins, personalised learning paths
- Honest self-assessment — known risks and how they would be handled

## Files

- `presentation.html` — the full animated deck, 22 slides. One file, nothing to install.
- `presentation.pdf` — the same 22 slides as pages, for printing or quick reading.
- `prototype-3d.html` — the working visualisation tool.
- `prototype-topic-list.pdf` — every topic the prototype knows, and what to type for each.

## How to run it

Download the file and open it in any browser — Chrome, Edge, Firefox or Safari. Nothing to install and no setup.

- **The deck:** move with the arrow keys, the space bar, or by swiping on a phone. Press `F11` for full screen before presenting.
- **The prototype:** needs an internet connection, because it loads its 3D engine from the web. The deck works completely offline.

## Built with

Plain HTML, CSS and JavaScript, with three.js for the 3D rendering. No frameworks, no build step, no installation, no API keys and no accounts. Each piece is a single file that opens straight in a browser.

## Author

**Rishitha Chapati** — Student in the Department of Electronics & Communication Engineering and B.S. in Electronic Systems.

## Note

This is an independent student project. It is a proposal and a prototype, not a released product, and it is not affiliated with or endorsed by any institution. Research figures cited inside the deck belong to their original authors and are credited on the relevant slides.
