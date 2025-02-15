## ❓ Fixes and changes:

- Fixed wisp cages not being deleted when out of range.
- Fixed clear button not deleting wisp cages.
- Automatically open the links in the browser at startup.
- Changed the player detected sound.
- Horizontal layout by default.
- Added volume slider for Player Detected sound.
- Added Sonar.
- Added Sonar volume slider.
- Added Player Direction Announcer (great for people with only one screen)
- Added Player Direction Announcer volume slider
- Added Min HP to show monsters

## 🔰 How to Run (Windows)
1. Download and install [Node.js v18.18.2 (64-bit)](https://nodejs.org/dist/v18.18.2/node-v18.18.2-x64.msi).
2. Download and install [Npcap 1.79](https://npcap.com/dist/npcap-1.79.exe).
3. Download and install [Python 3.12.3](https://www.python.org/downloads/). Ensure you check all installation options like "Use admin privileges" and "Add python.exe to PATH."
4. Download and install [Windows Build Tools](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools).
   - Select `Desktop development with C++` and proceed with the installation.
5. Download the project ZIP file.

   ![download](https://github.com/T0T0W/AOR-Extended/assets/161255413/72cce3c1-47fc-4cbe-bb1f-fa5a95c3dd84)

6. Run `INSTALL.bat` to install dependencies.
7. Once finished, use `RUN.bat` to start the radar and wait for the prompt:
   ```
   Please select one of the adapters that you use to connect to the internet:
     1. ******
     2. ******
     3. ******
   
   input the number here:
   ```
8. Choose the appropriate adapter and enter the corresponding number (do not choose 127.0.0.1).
9. Enjoy!

## ✨ Items Pack to View Player Inventories
[Download](https://github.com/T0T0W/AOR-Extended/releases/tag/Items)

Place the items folder into the images folder.

## ✨ Layout to Position Player Inventories Under the Map
[Download](https://github.com/T0T0W/AOR-Extended/releases/tag/Layout)

Replace this file: `AOR-Extended-main\views\main\drawing.ejs`
