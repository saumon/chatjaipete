# ChatJaiPété 💨

A humorous ChatGPT clone with a twist - every message submission triggers a delightful symphony of sound effects and animations!

## 🎯 Overview

ChatJaiPété is a playful web application that mimics the ChatGPT interface but adds a fun twist: when you submit a message, it plays random sound effects while displaying animated emojis and dynamic loading states. The interface features random welcome messages that change on each page load and after every command execution.

🌐 **[Try the live demo here!](https://saumon.github.io/chatjaipete/)**

## ✨ Features

### 🎨 **User Interface**

- **ChatGPT-inspired design** with dark theme
- **Custom SVG logo** with transparent background
- **Dynamic welcome messages** - 12 different random greetings
- **Responsive design** that works on all devices
- **Smooth animations** and transitions

### 🎵 **Sound Effects**

- **22 unique sound files** ranging from gentle puffs to epic thunders
- **Random sound sequences** (2-5 sounds per submission)
- **Variable timing** with random delays between sounds
- **Dynamic volume control** for each sound

### 🎭 **Animations**

- **Emoji animation** with 💨 characters during sound playback
- **Loading dots animation** that replaces the title during execution
- **Bouncing emojis** with staggered timing
- **Smooth send button** that appears/disappears based on input content

### 🎲 **Dynamic Content**

- **Random welcome phrases** that change on:
  - Page reload
  - After each command execution
- **12 different welcome messages** including:
  - "What's the plan for today?"
  - "Ready to learn something new?"
  - "Need help brainstorming?"
  - And 9 more engaging prompts!

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- No server setup required - it's a static HTML file!

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/saumon/chatjaipete.git
   cd chatjaipete
   ```

2. **Open the application**

   ```bash
   # Simply open index.html in your browser
   open index.html
   # or
   double-click index.html
   ```

### Alternative: Direct Download

- Download the repository as a ZIP file
- Extract and open `index.html` in your browser

## 🎮 How to Use

1. **Open the application** in your web browser
2. **Type a message** in the input field
3. **Press Enter** or **click the send button** (appears when typing)
4. **Enjoy** the sound effects and animations!
5. **Refresh** the page to see a different welcome message

## 🛠️ Technical Details

### Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Styling, animations, and responsive design
- **Vanilla JavaScript** - Interactive functionality and audio handling
- **Web Audio API** - Sound playback and control

### Key Features Implementation

- **Responsive Design**: CSS Flexbox and Grid for layout
- **Animation System**: CSS keyframes and transitions
- **Audio Management**: HTML5 Audio API with error handling
- **Random Selection**: Math.random() for dynamic content
- **Event Handling**: DOM manipulation and user interaction

### Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Requires modern browser with Audio API support

## 🎨 Customization

### Adding New Sounds

1. Add your `.mp3` files to the `assets/sounds/` directory
2. Update the `availableSounds` array in `index.html`:

   ```javascript
   const availableSounds = [
       // ... existing sounds
       'your_new_sound.mp3'
   ];
   ```

### Adding New Welcome Messages

Update the `welcomePhrases` array in `index.html`:

```javascript
const welcomePhrases = [
    // ... existing phrases
    "Your new welcome message!"
];
```

### Styling Modifications

- Modify CSS variables in the `<style>` section
- Adjust colors, fonts, and animations to your liking
- Change the dark theme by updating background colors

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Credits

- **Interface Design**: Inspired by ChatGPT's clean and modern UI
- **Sound Effects**: Custom collection of humorous audio files
- **SVG Icons**: Custom designed vector graphics
- **Font**: Apple System Fonts for consistent cross-platform appearance

## 🐛 Known Issues

- Audio playback requires user interaction (browser security policy)
- Some browsers may show audio permission prompts
- Mobile devices might have different audio behavior

## 📧 Support

For support, questions, or feedback:

- Open an issue on GitHub
- Contact the maintainer through the repository

---

**Enjoy the silly sounds and have fun with ChatJaiPété!** 💨🎉
