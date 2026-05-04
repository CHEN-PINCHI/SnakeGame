# Snake

A one-page Snake game served from a tiny local Python HTTP server.

## Requirements

- Python 3.7+ (uses only the standard library — no `pip install` needed)

## Run

From the project directory:

```bash
python server.py
```

Then open <http://localhost:8000/> in your browser.

To use a different port, pass it as an argument:

```bash
python server.py 9000
```

Stop the server with `Ctrl+C`.

### Alternative: built-in module

You can also run the bundled Python file server directly without `server.py`:

```bash
python -m http.server 8000
```

## Controls

| Action  | Keys                                   |
| ------- | -------------------------------------- |
| Move    | Arrow keys, or `W` / `A` / `S` / `D`   |
| Pause   | `Space`                                |
| Restart | `R`                                    |

The best score is saved in your browser's local storage.

## Files

- `index.html` — the game (HTML, CSS, and JS in a single file)
- `server.py` — minimal localhost HTTP server
- `README.md` — this file
