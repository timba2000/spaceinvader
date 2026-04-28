# Space Invaders

A web-based clone of the classic 1978 arcade game Space Invaders.

## Tech Stack

- **Frontend:** Pure HTML5, CSS3, and vanilla JavaScript (no frameworks or dependencies)
- **Rendering:** HTML5 Canvas API at 224x256 logical resolution (scaled 2x)
- **Audio:** Web Audio API for synthesized sound effects
- **Server (dev):** Python's built-in HTTP server

## Project Structure

```
index.html          # Main game file (complete game engine in one file)
space_invaders.html # Alternate/duplicate game file
README.md           # Short project description
LICENSE             # License information
```

## Running the Project

The workflow `Start application` serves the project using:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

Open `index.html` in a browser or visit port 5000.

## Controls

- **Arrow keys / A & D** — Move left/right
- **Space / Z** — Fire
- **Enter or Click** — Start game

## Deployment

Configured as a **static** deployment. The root directory (`.`) serves as the public directory.
