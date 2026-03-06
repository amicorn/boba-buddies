
# 🍓 boba besties 🥤
by Amy Ouyang 2/25/26

A cozy, physics-based game where you can pop the boba (designed as Line friends) created as a special birthday surprise for my friend <3
Tilt your phone to slosh the characters around, tap to pop them (like popping boba!).
If you pop all the boba, you get a sweet surprise at the end :) (a birthday card pop up that i wrote) 

This game is 100% hand-drawn and has completely custom assets.

🐻🐸🐰🐥🎀

**Play at https://amicorn.github.io/boba-besties/**

## 🎨 Screenshots
![Alt text for the image](image_url_or_path "Optional title")


## ✨ Inspiration
This game was inspired by my friend, who likes the korean Line friends characters and boba.

**Characters:** 
- The cast includes:
   -  🐻 Brown (bear)
   -  🐰 Cony (rabbit)
   -  🐥 Sally (chick)
   -  🎀 Choco (bear with pink bow)
   -  🐸 Leonard (frog)
-  yes i turned them all into cute face bubbles you can pop lol
  
**References:**
- https://linefriendssquare.us/collections/b-f?&sort_by=created-descending
- https://www.pinterest.com/suannsworld/minini-line-friends/

**Alternate names considered:**

- Boba Baddies (bc my friend's a baddie 💅 I do still like this name, maybe I'll code/draw something different for this)
- Boba Buddies (similar to boba besties, in line with the "line friends" character name)

## 🫧 Features 
- physics: boba bubbles bounce and roll using the Matter.js physics engine. also supports collision detection & responds to gravity

- move phone: tilt your phone to "slosh" the tea and move the characters around! on desktop: bobas follow your mouse

- interactive: tap or click the buddies to pop them with a satisfying sound effect.

- surprise ending: pop all the bobas to reveal a custom-designed birthday card.

- responsive design: works smoothly on both Desktop and Mobile (i put in the extra work to make this compatible on both platforms).

## 🎮 How to Play

Go to https://amicorn.github.io/boba-besties/ on your phone or computer. I made sure the game works on both mobile and desktop!

1. **Start:** Tap the big boba button to begin.

2. **Slosh:** If on mobile, tilt your device to watch the bobas tumble. On desktop, move your mouse to influence gravity.

3. **Pop:** Tap on every character until the screen is clear.

4. **Celebrate:** Read the special birthday message once all the bobas are gone!

## 🛠️ Tech Stack
Built with the following open source libraries:
- **p5.js**: Creative coding library for the visuals
  - graphics rendering for the sprites, also plays the popping sfx
  - link: https://p5js.org/

- **Matter.js**: 2D physics engine for realistic movement
  - calculates the gravity, motion, collisions, etc
  - link: https://brm.io/matter-js/

- **Google Fonts**: Retro 'VT323' pixel-art font
  - this is for the "START" button text
  - link: https://fonts.google.com/specimen/VT323

## 🚀 How to Run Locally
To play the game on your own machine:

1. Clone the repository:

```
Bash
git clone https://github.com/your-username/strawberry-boba-gift.git
```

2. Navigate to the folder:

```
Bash
cd strawberry-boba-gift
```

3. Run a local server:
   
Since the game loads assets (images/sounds), you need a local server. You can use the Live Server extension in VS Code (right-click the index.html file and 
Open with Live Server" or Python:

```
Bash
# If you have Python installed
python -m http.server
```

4. Open in Browser:
Go to http://localhost:8000 and enjoy!

## 📂 File Structure
Plaintext
├── index.html          # Main game code & logic
├── assets/
│   ├── background.png  # Main tea background
│   ├── title_sig.png   # Bottom signature/logo
│   ├── pop.mp3         # Popping sound effect
│   └── ...             # Various character sprites (bunny, bear, frog, etc.)
└── README.md

## 💖 Credits
- Designed, drawn, and coded with love by Amy Ouyang.
- Drew all assets by hand in Procreate.
- Special thanks to the open-source communities of p5.js and Matter.js
