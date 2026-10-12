# lsiwei68-alt.github.io

Personal robotics portfolio published with GitHub Pages.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Media still needed

The first project card intentionally uses a placeholder. Recommended assets:

1. `assets/multi-robot-overview.webp`
   - RViz overview showing both robots, paths, footprints and the map.
   - Recommended size: 1600 × 1000 px or larger.
2. `assets/narrow-passage-demo.gif`
   - 12–20 second loop showing conflict detection, one robot yielding, release,
     and both robots reaching the goal.
   - Crop around RViz; avoid showing terminal windows or personal paths.
3. `assets/conflict-markers.webp`
   - Close-up showing red conflict markers, the yellow waiting point and the
     green released markers.
4. `assets/final-formation.webp`
   - Both robots stopped side by side at the destination.

After adding an image, replace the `.media-placeholder` element in
`index.html` with an `<img>` using the matching asset path and descriptive alt
text.

## Publishing

The repository name must remain `lsiwei68-alt.github.io`. GitHub Pages serves
the `main` branch at <https://lsiwei68-alt.github.io/>.
