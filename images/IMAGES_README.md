# Game Images

This folder should contain the PNG image files used by the CSE215 Car Racing Game.

## Required Image Files

The following image files are required to run the game:

### Player Car
- **car.png** - The player's car sprite

### Enemy Cars
- **car1.png** - Enemy car sprite 1
- **car2.png** - Enemy car sprite 2
- **car3.png** - Enemy car sprite 3

### Obstacles/Decorations
- **tree.png** - Tree/obstacle sprite for road sides

## Getting Images

If you don't have suitable image files, you can:

1. **Download from reference repository:**
   - Visit: https://github.com/return007/car-racing-game/tree/master/images
      - This repository contains multiple car and road sprites
         - You can use similar sprites like `car_self.png` as the player car
            - Use `car_left_1.png`, `car_left_2.png`, `car_left_3.png` or similar for enemy cars
               - Create or find a simple tree/obstacle image

               2. **Create your own:**
                  - Use any image editor (GIMP, Photoshop, Paint.NET, etc.)
                     - Create simple 32x32 or 64x64 pixel PNG images
                        - One car sprite for the player
                           - Three different car sprites for enemies
                              - One tree/obstacle sprite

                              3. **Find free assets:**
                                 - OpenGameArt.org - Free game graphics
                                    - Itch.io - Free game assets
                                       - pixabay.com - Free images
                                          - pexels.com - Free stock photos

                                          ## How to Add Images

                                          1. Download or create the required PNG files
                                          2. Name them exactly as specified above (car.png, car1.png, etc.)
                                          3. Upload them to this `images/` folder
                                          4. Commit the changes

                                          ## Image Specifications

                                          - **Format:** PNG (required by ImageIO)
                                          - **Recommended Size:** 32x32 to 64x64 pixels per sprite
                                          - **Transparency:** PNG supports alpha channel for transparent backgrounds
                                          - **Quality:** 8-bit or 32-bit PNG

                                          ## Note

                                          The game code expects these files to be in the `images/` folder relative to the compiled Java classes. Make sure the paths in CarGame.java match the filenames you create.
