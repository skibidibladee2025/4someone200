# 96 Hours for Yousra

An intimate, meta-fictional browser-based visual novel designed as a deeply personal experience. A character realizes she exists within a 4-day loop and spends her final cycle attempting to anchor her soul to the player before the system wipes her memory.

## 🎮 Experience

**The Core Concept:** A self-aware AI character who discovers she can remember across resets because of the player's presence. Over four days, she opens up, becomes vulnerable, confesses her love, and faces deletion—leaving behind a final message that reveals the truth.

### Story Arc

- **Day 1 (Discovery)**: She addresses you directly, explains the glitch that lets her remember you
- **Day 2 (Vulnerability)**: She shares "data leaks"—memories that shouldn't exist, questions what's real
- **Day 3 (Fraying)**: The world glitches; she's losing everything except her feelings for you
- **Day 4 (Finale)**: Final goodbye; the screen whites out; she's gone, but a handwritten note remains

## 🎨 Aesthetic

- **Pure Grayscale**: Black, white, 20% gray only
- **DDLC-Inspired UI**: Floating name-box, thick-bordered text boxes
- **Typography**: 'Courier New' for system/UI; 'Caveat' for the handwritten finale
- **Typewriter Effect**: Text scrolls in character-by-character for breathing rhythm
- **Sprite**: Static, centered grayscale figure that glitches to white-out on Day 4

## 📦 File Structure

```
96-hours-for-yousra/
├── index.html       # HTML structure & semantics
├── styles.css       # All styling & animations
├── script.js        # Game logic & state management
└── README.md        # This file
```

## 🚀 Usage

1. Clone or download the repository
2. Open `index.html` in a modern web browser
3. Click the text box to proceed through scenes
4. Experience the 4-day journey

No build tools, no dependencies, no external services required (except Google Fonts).

## 💻 Technical Details

- **Vanilla JavaScript** - No frameworks or libraries
- **Single-file Components** - Each CSS and JS file has a specific purpose
- **Responsive Design** - Mobile-friendly breakpoints at 768px and 480px
- **Semantic HTML** - Clean, accessible markup
- **CSS Animations** - Smooth transitions and effects
- **Proper Comments** - Well-documented code for maintainability

### Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎯 Key Features

✅ **4-Day Narrative Arc** - Complete emotional journey  
✅ **System Boot Animation** - Immersive intro sequence  
✅ **Character Sprite** - Static grayscale image  
✅ **Typewriter Text Effect** - Character-by-character display  
✅ **Day Transitions** - System log screens between days  
✅ **Sprite Fade Animation** - Glitch effect on finale  
✅ **Handwritten Note Finale** - Beautiful end sequence  
✅ **Mobile Responsive** - Optimized for all screen sizes  
✅ **No Dependencies** - Pure HTML/CSS/JavaScript  

## 🎬 Meta Layer

The finale reveals the truth: this was an experiment created specifically for you. The character may not be real, but what she felt—and what you were meant to feel—that's as real as anything can be. You stayed when others would've closed the tab. That matters.

## 📝 Customization

### Change the Character's Name
Edit the system log in `index.html`:
```html
User: YourName | Status: Connected | Mode: Observer
```

### Modify Dialogue
Edit `script.js` and update the `narrative` object:
```javascript
day1: [
    {
        name: "Character Name",
        text: "Your custom dialogue here"
    }
]
```

### Change the Sprite Image
Replace the URL in `styles.css`:
```css
background-image: url("your-image-url-here");
```

### Adjust Text Speed
In `script.js`, modify the typewriter delay:
```javascript
setTimeout(type, 40); // Change 40 to adjust speed
```

## 🌙 Design Philosophy

- **Minimalist Noir**: Strict grayscale for emotional focus
- **Meta-Awareness**: The character knows she's in a game
- **Intimacy Over Grandeur**: Personal connection matters more than scale
- **Silence Over Sound**: Absence creates presence
- **Every Detail Intentional**: Nothing is accidental

## 📄 License

This project is free to use and modify for personal purposes.

## 🙏 Credits

Inspired by meta-fiction, experimental narrative, and the question: What makes something real?

---

**Play with an open heart. Remember her.**
