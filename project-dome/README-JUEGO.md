Create a modern 2D platform game inspired by classic side-scrolling games like Mario Bros, using React, Vite, Phaser.js, JavaScript, and face-api.js for facial control detection through the webcam.

The game must contain ONE playable level with:

- platforms
- coins
- enemies
- gaps
- a finish flag
- score system
- lives system
- smooth side scrolling camera
- background music and sound effects
- pixel-art or modern cartoon style

The player DOES NOT use keyboard controls.
The character is controlled ONLY using facial actions detected from the webcam in real time.

Facial controls:

1. Look Left

- Move character left
- Use face landmarks and head orientation detection

2. Look Right

- Move character right
- Use face landmarks and head orientation detection

3. Open Mouth

- Jump
- Small mouth opening = small jump
- Large mouth opening = high jump
- Detect mouth openness ratio using facial landmarks

4. Smile

- Activate running/sprint mode
- Increase movement speed while smiling

5. Raise Eyebrows

- Shoot projectile/fireball
- Detect eyebrow distance from eyes

Game requirements:

- Webcam feed visible in a small corner overlay
- Draw facial landmarks on top of the webcam
- Show detected emotion/action labels in real time
- Smooth and responsive facial controls
- Calibration screen before starting the level
- Responsive design
- FPS optimized
- Mobile-friendly structure if possible

UI Requirements:

- Modern game HUD
- Health/lives display
- Coins counter
- Facial action status indicator
- Start screen
- Game Over screen
- Victory screen

Technical requirements:

- React + Vite
- Phaser.js for gameplay
- face-api.js for face detection
- Use requestAnimationFrame for tracking loop
- Use MediaDevices API for webcam access
- Organize project with clean folder structure
- Use reusable hooks/components
- Include comments explaining important logic

Suggested structure:
src/
/game
components/
game/
hooks/
faceDetection/
scenes/
assets/
utils/
se crea una carpeta en src que se llame game, y dentro de esta solo ponga dependecias para el juego, no toque nada mas.

Gameplay details:

- Character automatically stays idle if no facial movement detected
- Add small cooldown to prevent accidental jumps/shots
- Add facial sensitivity configuration
- Include gravity and smooth physics
- Add enemy collision system
- Add collectible coins
- Add one boss or final challenge at the end

Visual effects:

- Particle effects
- Smooth animations
- Camera shake when shooting or taking damage
- Facial action feedback animations

The project should feel innovative, futuristic, and fun, demonstrating AI-powered gameplay interaction through real-time facial tracking.

Generate:

- Full project architecture
- Main React app
- Phaser scenes
- face-api.js integration
- Facial gesture detection logic
- Character controller logic
- Example assets placeholders
- Game loop implementation
- Calibration system
- Clean and maintainable code

The final result should look like a professional prototype suitable for:

- portfolio projects
- university presentations
- AI/gameplay demonstrations
- viral social media content

cree una carpeta en src/game donde quiero definir esto, pero no toques nada de las otras carpetas, solo vas a trabajar en esta, dejame un componente como main para poder probar lo que creaste, este es el requerimiento:
