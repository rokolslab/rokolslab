# Token Stream Experiment

Goal: explore a more LLM-like contribution visualization without shipping unsupported action parameters into the main profile README.

Current stable implementation:

- `Platane/snk/svg-only@v3`
- default light SVG
- `github-dark` dark palette

Why this stays experimental:

- custom token-style palettes are not part of the validated stable setup here
- the main profile should prefer reliable rendering over visual novelty
- any custom stream metaphor should degrade cleanly when images fail

Possible next step:

- prototype a separate SVG generator or post-processing step outside the profile README release path
