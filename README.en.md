# Small University Assignments

[Русская версия](README.md)

Small labs and practice tasks from 2024–2025 collected in one place.

## Robot modeling (`robot-modeling/`, October 2025)

A two-link manipulator with 30 cm links follows a U-shaped trajectory at 5 cm/s:
- trajectory points second by second;
- inverse kinematics with two solutions (elbow up and elbow down) and a reachability check;
- results in CSV and interactive joint-angle plots (`P_trajectory_plots.html`).

## Artificial intelligence methods (`ai-methods/`, February–March 2025)

- `game_of_life_fsm.ipynb`: the Game of Life on a 250 × 250 grid. Every cell is a finite-state machine, animated in Matplotlib.
- `finite_automaton/`: a finite-state machine for an agent's behavior. The states come from sensor readings (wall, enemy and goal on different sides) in `automaton.json`, with a diagram next to it.
- `log_regex.ipynb`: parsing server log lines with regular expressions. The log itself is not included.

## Databases (`databases/`)

- `design/` (May–June 2024): designing an information system for a company that builds rockets to order.
  - Use case, class, sequence and activity diagrams.
  - An ER diagram in Chen notation.
  - Sources in draw.io and images in PNG.
- `sql/` (October 2025): a MySQL schema for a home rental service (users, listings, bookings, reviews) and a query for the bookings of a chosen week.

Diagram labels and comments are in Russian.

## Tech stack

Python, NumPy, pandas, Matplotlib, Plotly, MySQL, draw.io, Visual Paradigm.

## License

[MIT](LICENSE)
