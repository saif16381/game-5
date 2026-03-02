# Geometric Survivor - Improvement Roadmap

## 1. MARKET DIFFERENTIATION
- **Neon Pulse Mechanic**: Energy orbs don't just give points; they power a "Pulse" that pushes enemies back. This creates a risk/reward loop: get close to collect, but stay away to survive.
- **Dynamic Grid Warp**: The background grid reacts to player movement and explosions, creating a high-fidelity visual experience usually reserved for desktop bullet-hells.
- **Boss Evolution**: Every 3000 points, a boss spawns with a unique movement pattern (Chaser, Spinner, Wall-Maker), breaking the monotony of simple chaser enemies.

## 2. FIRST 30 SECONDS (DOPAMINE HIT)
- **Instant Action**: The "Play" button immediately transitions with a neon "Shatter" effect.
- **Particle Feedback**: Every collected orb now triggers a subtle screen shake and a high-pitched "chime" sound.
- **Level 2 Rush**: The first level-up happens within 10 seconds, granting a temporary "Blast" to clear the screen, teaching the player the power-up mechanic early.

## 3. MONETIZATION & RETENTION
- **Revive System**: Implemented a "Core Shield" revive via rewarded ads. Only available once per run if score > 500, preserving the challenge while boosting ad revenue.
- **Bonus Chests**: Post-game "Energy Cache" that offers a 2x orb multiplier in exchange for a short ad.
- **Permanent Meta**: Shop upgrades (Shield, Speed, Magnet) ensure players have a reason to come back for "one more run" to afford the next upgrade.

## 4. VISUAL JUICE
- **Screen Shake**: Added to all collisions and explosions.
- **Chromatic Aberration**: Brief flash on death to emphasize the "Core Breach."
- **Trail Persistence**: Player trail length is tied to current speed, making high-speed play feel faster.

## 5. REJECTION RISK MITIGATION
- **Input Friction**: Optimized touch-drag for mobile (preventing accidental scrolling).
- **Loading Speed**: Kept entire game in a single optimized HTML file (<1MB) for instant loading on CrazyGames.
- **Ad Frequency**: Logic ensures ads are never forced; they are always optional rewards.