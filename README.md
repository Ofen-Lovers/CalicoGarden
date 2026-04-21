# Calico Garden

**Calico Garden** is a relaxing gardening simulation game built with **Java** and the **LibGDX** framework. Play as you nurture plants through various growth stages, interact with your cat companion **Ming**, and manage a growing garden economy.

<img width="1179" height="658" alt="image" src="https://github.com/user-attachments/assets/a5fd382a-d123-4247-914f-f5ff33c5ee28" />

## Core Features
- **Gardening Simulation**: Purchase seeds, monitor plant growth stages, and keep your garden healthy by watering them (Key: `W`).
- **Dynamic Economy**: Earn and spend coins to buy new plants, accessories, and garden upgrades in the dedicated **Shop Screen**.
- **Pet Interaction**: Features **Ming**, a calico cat with custom animations. Use the **Accessory Menu** to customize Ming and your garden space.
- **Time Cycle System**: Experience an in-game time and day system where plant growth is tied to the progression of days.
- **Atmospheric Experience**: Includes custom background music (BGM) and sound effects (SFX) that change based on your location and activity.

## Key Controls
- **Water Plant**: Stand near a pot and press `W`.
- **Shop Menu**: Press `E` or click the shop icon.
- **Accessory Menu**: Press `M` or click the accessory icon.
- **Reset State**: Press `Enter` to reset the shelf system.

## Technical Details
- **Game Engine**: [LibGDX](https://libgdx.com/) (Java)
- **Resolution**: 1400x800
- **Architectural Highlights**:
    - **Scene Management**: Uses a centralized `GameSceneManager` for smooth transitions between gameplay, shop, and customization screens.
    - **Persistence**: Implements `Gdx.app.getPreferences` for saving game state, day progress, and coin balances.
    - **Animation System**: Custom sprite-based animation logic for character and growth transitions.

## Project Structure
- `core/`: Main game logic and shared source code.
- `desktop/`: Desktop-specific launcher and configuration.
- `assets/`: Game assets including textures, sound effects, and music.

## Contributors
- **Krystal Heart M. Bacalso**
- **Javier M. Raut**
- **Joseph Jose A. Deysolong**
- **Shaira Jane T. Dadios**
- **Cyreh Angelo M. Bayson**


