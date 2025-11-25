# Early Internet Simulator

A fully interactive nostalgia experience that recreates the chaotic charm of the late-1990s web — guestbooks, chatrooms, broken polls, web-rings, random popups, hidden cheat codes, and a sprawling Easter-egg hunting system.

This simulator blends humor, retro UI, interactive components, console tricks, and classic internet chaos into a single self-contained HTML page.

---

## 🌐 Features

### **📓 Guestbook**

Write a message, sign the guestbook, and watch your post appear at the top.
You’ll get a popup declaring you visitor #XXXXX (randomly generated for authenticity).

### **💬 Early-Web Chatroom**

Send a message and receive randomized replies from characters like:

* CoolDude69
* xXPrincessXx
* SurfNinja
* Admin
* SpamBot3000
* DeepThoughts2000
* HackerMan

The page scrolls like an old-school IRC or AOL chat.

### **📊 Broken Poll**

A nostalgia-rich broken poll with results like:

* Netscape Navigator — **147%**
* Internet Explorer — **–12%**
* Mosaic — **3.14159%**

Blamed on the "Y2K bug," obviously.

### **🔗 Web-Ring Navigator**

Navigate fictional GeoCities-era websites that no longer exist.
Each attempt ends with a message mourning the death of 2009-era GeoCities.

---

# 🥚 Easter Eggs

This simulator contains **23** hidden Easter eggs, triggered through:

* Click sequences
* Typing secret codes
* Hidden UI elements
* Invisible pixels
* Console commands
* Random timers
* Multi-click triggers
* Retro cheat codes

You can monitor progress with:

```js
tfindEggs();
```

Get a randomized hint with:

```js
giveHint();
```

---

# 🥚 Complete Easter Egg List

### **1. TOOLBAR MASTER**

Click the toolbar icons in this exact order:
`jeeves → yahoo → aol → google → kazaa`

### **2. RANDOM ENCOUNTER**

A rare periodic event that may trigger automatically.

### **3. Console: `findEggs()`**

Shows egg progress, count, and hints.

### **4. Console: `giveHint()`**

Provides clues such as:

* “Click Patrick’s name multiple times.”
* “Type NETSCAPE.”
* “Find the tiny pixel.”
* “The ASCII art box holds a deeper secret…”

### **5. MATRIX MODE**

Triggered by clicking a special ASCII/hacker region.
Enables green raining digits for ~10 seconds.

### **6. GOD MODE — Type `IDDQD`**

Just like *Doom*:

* Gold border applied
* +99 power-ups
* “GOD MODE” popup
* God Mode panel unlocked

### **7. NETSCAPE MODE**

Typing **NETSCAPE** turns the whole page sepia temporarily and displays a retro message.

### **8. Konami Code**

Enter:
`↑ ↑ ↓ ↓ ← → ← → B A`
Triggers a hidden effect.

### **9. Secret God Button**

A nearly invisible **10×10 pixel** square in the upper-right corner that instantly activates God Mode.

### **10. PATRICK MODE**

Click “Patrick” **three times**.

### **11. PERSISTENT CLICKER**

Click Patrick’s name **nine times**.

### **12. HIGHWAY TO THE DANGER ZONE**

Triggered via God Mode panel → “superHighway()”.

### **13. LUCKY NUMBER 7**

Click the visitor counter until the click count hits 7.

### **14. UNLUCKY 13**

Same, but hit 13.

### **15. TIME TRAVELER**

Updates timestamp to “Last Tuesday” and fires a themed popup.

### **16. COME ON AND SLAM**

Triggers a Space Jam–style full-screen animation overlay.

### **17. ASCII TERMINAL SECRET**

Clicking the “ACCESS_MAINFRAME.EXE” ASCII box opens a hidden terminal message sequence.

### **18. Easter Egg Hints Panel**

The hint list contains meta-secrets:

* 23 total eggs
* The blinking cursor is clickable
* A special tiny pixel hides something
* “The AI knows things”

### **19. Guestbook Easter Egg**

Signing the guestbook triggers its own unique popup event.

### **20. Blinking Cursor Egg**

Clicking the blinking `_` reveals another hidden effect.

### **21. Tiny Pixel Egg**

Separate from the God Mode pixel — a 1-pixel Easter egg nearby triggers a different popup.

### **22. Meta-AI Egg**

The hint about “The AI knows things” is itself an Easter egg referencing interaction with ChatGPT.

### **23. Guestbook Hidden Behavior**

Certain names/messages in the guestbook can trigger additional secret events.

---

# 🎮 How to Play

1. Open the HTML file in any modern browser.
2. Click everything — nearly all UI elements are interactive.
3. Try secret codes:

   * `IDDQD`
   * `NETSCAPE`
   * `↑↑↓↓←→←→BA`
4. Open DevTools → Console and type:

   ```js
   findEggs();
   giveHint();
   ```
5. Look for hidden pixels, blinking cursors, rapid-click triggers, and ASCII console surprises.

---

# 📄 License

© 2025 Accelerate Solutions, LLC.
All rights reserved.
