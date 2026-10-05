# 🎂 Jorgensen's Birthday Website

A cute, mobile-first birthday website built with HTML, CSS, and vanilla JavaScript for **Jorgensen's 18th Birthday on October 6**.

---

## 🚀 How to View the Website
Simply double-click [`index.html`](./index.html) or right-click it and choose **Open with > Chrome / Edge / Safari / Firefox**.
You can also view it on mobile by transferring the folder or hosting it on GitHub Pages, Netlify, or Vercel.

---

## ✏️ How to Customize (At the Top of `<script>` in `index.html`)

Open [`index.html`](./index.html) in your text editor (VS Code, Notepad, etc.) and look for the `CONFIG` object near line 450:

```javascript
const CONFIG = {
  // Friend's Name
  name: "Jorgensen",

  // Birthday Date Text
  birthdayDate: "October 6",

  // Age to count up to
  age: 18,

  // 6 Memory Cards (Front: emoji + title, Back: personal message)
  memories: [
    { emoji: "🚀", title: "Big Dreams", message: "..." },
    { emoji: "☕", title: "Coffee Runs", message: "..." },
    // ...
  ],

  // 8 Wishes for the Balloon Pop Game
  balloonWishes: [
    "May this year bring you endless happiness & peace! 🌸",
    // ...
  ],

  // Heartfelt letter at the Cake Finale
  personalLetter: {
    title: "To My Dearest Friend Jorgensen,",
    body: `Happy 18th Birthday! 🎉 ...`,
    signoff: "Made with love,\nAndy ♥"
  }
};
```

---

## 🎨 Sections Included:
1. **Landing Page**: Big wrapped gift box with bow that bounces. Tapping triggers a lid pop, multi-colored confetti burst, rising balloons, and smooth scroll to Section 2.
2. **"Level Up" Section**: Animated counter reaching **Level 18** with RPG-style stat bars (Wisdom, Charisma, Luck).
3. **Memory Lane**: 6 interactive 3D flip cards with emojis, titles, and customizable memory notes.
4. **Balloon Pop Mini Game**: 8 floating pastel balloons. Tapping pops them with sound-free particle animations, revealing 8 custom wishes, ending in a victory celebration banner.
5. **Cake Finale**: Handcrafted CSS multi-tier birthday cake with glowing candles. Tapping the candles blows them out with smoke puffs, launches a grand confetti shower, and reveals a personal letter from Andy.
6. **Footer**: *"Made with love by Andy ♥"*
