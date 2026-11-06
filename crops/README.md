# Crops

Research and game-ready data for crops, organized into the following
subdirectories. This same layout is used by every data category in this
project (animals, ecology, equipment).

- `raw-data/` — Source research for each crop, in Markdown. Thorough,
  sourced, human-readable, and not meant to be parsed by game code directly.
- `game-data/` — Game-ready data derived from `raw-data/`, in JSON. This is
  what a game or simulation actually consumes.
- `metadata/` — Schema descriptions (field names, types, constraints) for
  the files in `game-data/`.
- `help/` — Player-facing reference articles drawn from `raw-data/` and
  `game-data/`. Not meant to be parsed by game code.
- `code/` — Reference reader code that loads `game-data/` files into simple
  objects, with unit tests. No dependencies beyond the language's standard
  library and general-purpose public libraries.
