# Firefighter 2D Game Development Runbook

## Project Overview
- **Game Title**: Firefighter
- **Objective**: Develop a 2D game where a firefighter extinguishes flames by shooting water droplets. The game is primarily developed in JavaScript and designed to run smoothly on Android and iOS devices. All graphical elements are generated programmatically.
- **Repository**: [GitHub - firefighter](https://github.com/signoredellarete/firefighter)

## Gameplay Dynamics
1. **Game Area**:
   - Rectangular area with smartphone-like proportions.
   - Contains a small firefighter character at the bottom, who moves left and right.
2. **Player Actions**:
   - Tap anywhere on the screen to start shooting water droplets.
   - Hold to adjust the angle of the droplets (from 0 to 90 degrees, then back to 0 in a looping manner).
   - Release to lock the angle; the droplets continue until the supply runs out.
3. **Objective**:
   - Extinguish flames positioned on platforms or objects.
   - Each droplet can extinguish one flame.
   - Advance to the next level upon extinguishing all flames.
4. **Physics**:
   - Droplets must bounce and slide realistically.
   - The number of droplets per level is predefined and varies with difficulty.

## Tools and Technologies
### Core Framework
- **Phaser 3**: For game development, physics, and rendering.

### Supporting Tools
- **VS Code**: IDE for development.
- **Git**: Version control.
- **Parcel/Vite**: Bundlers for efficient development.
- **Cordova/Capacitor**: To package the game for Android and iOS.

### Documentation
- Format: Markdown.
- Content: Descriptions of game elements, features, and development milestones.

## Development Milestones
### Phase 1: Setup
1. Initialize Phaser 3 project.
2. Configure the repository for development:
   - Clone repository: `git clone https://github.com/signoredellarete/firefighter`
   - Setup project structure.
3. Configure bundler (Parcel/Vite).
4. Create initial assets and test scene.

### Phase 2: Core Mechanics
1. Implement character movement.
2. Add water-droplet shooting mechanics.
3. Develop angle adjustment feature.
4. Integrate basic physics for droplets.
5. Create flame objects and interaction logic.

### Phase 3: Level Design
1. Create platform objects.
2. Define flame positions and behaviors.
3. Add level progression logic.

### Phase 4: Optimization and Packaging
1. Optimize game for mobile devices.
2. Use Cordova/Capacitor to package for Android and iOS.
3. Test on multiple devices for performance and compatibility.

## Next Steps
1. **Repository Confirmation**: Ensure the repository setup is complete.
2. **Initial Setup**: Begin Phase 1 by setting up the Phaser 3 project and bundler.
3. **Documentation**: Continue updating this runbook with progress and detailed specifications.

