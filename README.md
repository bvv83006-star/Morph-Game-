Bro, here is the complete **Game Design Document (GDD)** for your team. 

Copy this entire block and paste it into your team's WhatsApp group, Discord, or a notes file. This is your single source of truth for the 7-day sprint. Keep everyone on the same page.

***

# 🎮 MORPH: Portal Shift — Game Design Document
**Category:** Game Design (Design Championship 2026)
**Engine:** Three.js (JavaScript) 
**Platform:** Web Browser (PC & Mobile)
**Team Size:** 2-5 Members

## 🧠 1. The Game Idea
**Genre:** 3D First-Person Puzzle Platformer
**Theme:** Sci-fi Test Chamber
**Overview:** You are a test subject trapped in a digital simulation. You don't have a single body; you have the ability to **Shapeshift** into six different geometric forms. Each form has unique physics, sizes, and abilities. You must use these forms, combined with a portal gun, to solve environmental puzzles and escape each room.

## 🧬 2. The 6 Shapeshifter Forms
Players can switch between these forms at any time. Every shape changes how the player moves and interacts with the world.

1. **Cube** 🟦 
   - *Physics:* Heavy, slow, low jump.
   - *Ability:* Can press down heavy pressure plates. Breaks weak walls by running into them.
2. **Sphere** 🔵
   - *Physics:* Very fast, rolls easily, bouncy.
   - *Ability:* Fits through narrow pipes/vents. Can bounce off jump pads to reach high areas.
3. **Pyramid** 🔺
   - *Physics:* Medium speed, high friction.
   - *Ability:* Can climb up specific "rough" walls. Reaches high switches.
4. **Slime** 🟢
   - *Physics:* Low gravity, sticky.
   - *Ability:* Can squeeze through tiny cracks (collision box shrinks). Sticks to ceilings.
5. **Ghost** ⚪
   - *Physics:* Floats, ignores gravity.
   - *Ability:* Passes through green laser grids and certain grates. Cannot touch pressure plates.
6. **Magnet** 🟣
   - *Physics:* Heavy, slow.
   - *Ability:* Pulls metal bridges and objects towards it. Can redirect lasers.

## 📱 3. Full Mobile Controls (Touch)
Since this is a mobile web game, the controls are designed for thumbs.

*   **Left Thumb (Virtual Joystick):** Move Forward, Backward, Left, Right.
*   **Right Thumb (Action Buttons):**
    *   🔘 **JUMP:** Tap to jump (only works on solid ground).
    *   🔄 **MORPH:** Tap to cycle through the 6 shapes. HUD shows current shape.
    *   🔵 **BLUE PORTAL:** Tap to place blue portal (only on special white walls).
    *   🟠 **ORANGE PORTAL:** Tap to place orange portal.
*   **Camera:** Automatically follows the player from behind. (Optional: Swipe right side of screen to rotate camera).

## 🧩 4. Puzzle Elements (The Room)
*   **Pressure Plates:** Only the heavy Cube can hold these down.
*   **Narrow Vents:** Only the tiny Slime or Sphere can fit through.
*   **Laser Grids:** Only the Ghost can walk through.
*   **Metal Bridges:** Only the Magnet can pull them into place.
*   **Climbable Walls:** Only the Pyramid can scale them.
*   **Portals:** Used to teleport across gaps or bypass obstacles.

## 🎯 5. Game Modes & Progression
*   **Single Player Campaign:** 3 Rooms (Tutorial, Main Puzzle, The Finale).
