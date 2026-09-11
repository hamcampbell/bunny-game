# Bunny Winter

A tiny low-res 2D browser game. You are a little white rabbit and winter is
coming. Dig a den, gather carrots from the meadow and stash them deep
underground before the snow arrives. Watch out for the fox.

Play it by opening `index.html` in any modern browser. It is built for a
phone in portrait, with on-screen touch controls, and also works on desktop
with the keyboard.

## How to play

- Dig a den of at least **12 tiles** (walk into dirt to dig, stones can't be dug).
- Walk over carrots on the surface to pick them up (you can carry 3).
- Go underground at least **2 tiles deep** and press **STORE CARROT** to stash one.
- Store **8 carrots** before the 12 days run out and winter arrives.
- The fox patrols the surface and steals whatever you're carrying. It can't follow you underground.

Controls: on-screen d-pad and STORE button on touch devices. Keyboard: arrows or WASD to move and dig, space or enter to store.

## Hosting on a phone

Easiest option is GitHub Pages: in the repository settings, enable Pages from
the `main` branch root and open the resulting URL on your phone. Adding the
page to the home screen gives a full-screen, app-like experience.

Everything is a single `index.html` with no dependencies or build step.
Append `?season=30` to the URL for a shorter 30-second game while testing.
