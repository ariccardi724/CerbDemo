# Cerebella Demo

A standalone demo of Cerebella. It shows seven exercises on six background themes, using the same exercise and background engine as the full app, so every scene and level looks and moves exactly the same.

## Exercises
H-pattern tracking, Random saccades, VOR x1 with letter, Optokinetic stripes (left), Peripheral colored dot tracking, VOR cancellation, VOR x2 horizontal.

## Backgrounds
Patterns, Grocery aisle, Neural matrix, Driving, Boat deck, Screen scroll — each at levels 1 to 6.

## Controls
Target speed, background theme, background level, and forward speed (Neural matrix and Driving only).

## Hosting on GitHub Pages
1. Create a new repository and upload `index.html`, `.nojekyll` and this README to the root.
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The demo will be live at `https://<username>.github.io/<repo>/`.

The demo stores its settings under its own browser keys (`vtdemo_…`), so it never reads or changes data from the full app. It is a demo only, not a treatment plan.
