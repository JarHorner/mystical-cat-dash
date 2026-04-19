# Mystical Cat Dash

A small arcade runner built in Unity, playable now on [Itch.io](https://jarhorner.itch.io/mystical-cat-dash).

## About the game

Mystical Cat Dash is a mash-up of two classic arcade formulas: the **three-lane auto-runner** and **Flappy Bird**.

Your cat sprints forward on its own and never stops. You don't control the speed — you control the cat. At any moment you're juggling two inputs at once:

- **Lanes (left / right).** The world is split into three parallel tracks. Swap between them to line up with pickups or dodge whatever the course throws at you.
- **Hops (tap to flap).** On top of the lane choice, the cat obeys Flappy Bird physics. Tap to give it a little lift, let gravity pull it back down, and thread the gap between low and high obstacles.

The twist is that neither mechanic alone is enough. A clean lane can still have a pipe at head height; a perfectly timed hop can still land you in the wrong track. Survival means reading both axes of the course at the same time and reacting before the next obstacle scrolls in.

As the run goes on, things speed up, gaps tighten, and the course gets meaner — classic endless-runner escalation. The goal is simple: go as far as you can before the cat clips something.

## Requirements

- **Unity 6000.4.1f1** (Unity 6). Other versions may work but aren't guaranteed — Unity Hub will offer to upgrade the project if you open it on a newer editor.
- **Git** to clone the repo.
- Roughly **2–3 GB** of free disk space once the `Library/` folder is generated on first open.
- Any platform the Unity 6 editor supports (Windows, macOS, Linux).

## Installation

1. Install [Unity Hub](https://unity.com/download) and use it to install editor version **6000.4.1f1**.
2. Clone the repo:
   ```
   git clone https://github.com/JarHorner/mystical-cat-dash.git
   ```
3. In Unity Hub, click **Add → Add project from disk** and point it at the cloned folder.
4. Open the project. The first import will take a few minutes while Unity rebuilds the `Library/` cache.
5. Load the main scene from `Assets/Scenes/` and press **Play**.

## Status

hobby project from University. Play on the Itch page! No more updates
