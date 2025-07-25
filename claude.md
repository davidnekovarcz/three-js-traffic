# Claude.md - Project Context

## Project Overview

- **Name**: Traffic Run Three.js Game
- **Type**: Browser-based 3D racing/dodging game
- **Stack**: Vanilla JavaScript + Three.js + Vite
- **Description**: Figure-8 track racing game where player dodges AI vehicles

## User Preferences

- User prefers concise responses without unnecessary explanations
- User is experienced with git and development workflows
- Always check the workspace's version of node (nvm use) or ruby (rbenv)
- **IMPORTANT**: User will always run `npm run dev` in Warp app on their own - never run it via Bash tool

## Project Structure

```bash
traffic-run-three-js/
   index.html          # Main HTML with UI elements
   src/
      main.js        # Game loop and state management
      scene.js       # Three.js scene setup
      vehicles.js    # Car/Truck models
      track.js       # Track generation
      collision.js   # Collision detection
      audio.js       # Sound management
      ui.js          # UI controls
      style.css      # Styling
   audio/             # Sound files
```

## Key Features

- Orthographic camera view
- Figure-8 track with lane switching
- AI vehicles with random spawn
- Collision detection with explosion effects
- Score based on laps completed
- Pause functionality (SPACE key)
- Arrow key controls

## Recent Work

- User explored migrating to React Three Fiber but decided to keep Vanilla JS implementation
- Project uses Vite as build tool with Three.js v0.178.0

## Notes

- Game uses procedural generation for vehicles and track textures
- Audio system integrated with Three.js positional audio
- Performance optimized for smooth 60fps gameplay
