# Ascend Demo

Ascend Demo is a free playable preview of **Ascend**, an atmospheric endless-flight game about guiding a glowing paper aircraft through an increasingly difficult field of drifting asteroids.

## Included

- Complete launch and flight controls for mouse, touch, and keyboard
- Classic aircraft with its white fading trail
- Procedural asteroids, three lives, collision knockback, and invulnerability
- Rechargeable boost ability
- Collectible colored lights
- Dynamic altitude colors, ambient audio, settings, and tutorial
- Local personal-best score
- Responsive layouts for phones, tablets, and desktop browsers

## Full-Game Features

The demo intentionally excludes aircraft and trail progression, the shop, advancements, save codes, player profiles, and cloud leaderboards. Core flights are not time- or altitude-limited.

## Play Locally

The game is a static website. Open `index.html` directly, or serve this directory with any static web server.

## Tests

Run the dependency-free test suite with:

```sh
node game.test.cjs
```

## Deployment

Pushes to `main` deploy automatically to GitHub Pages through the included workflow.

This repository contains the demo edition. The complete game is developed separately in the private/full Ascend project.
