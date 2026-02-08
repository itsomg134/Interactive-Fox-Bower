# Interactive-Fox-Bower

A beautiful, interactive web application featuring a friendly fox in its cozy forest bower. Built with HTML, CSS, and JavaScript.

![Fox Bower Preview](https://img.shields.io/badge/Fox-Bower-orange?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## Features

### Interactive Fox
- **Pet the Fox**: Click to increase happiness
- **Feed the Fox**: Restore energy with virtual treats
- **Play with Fox**: Engage in playtime (consumes energy)
- **Sleep Mode**: Put the fox to sleep to restore energy
- **Dynamic Status**: Fox responds based on energy and happiness levels

<img width="1876" height="1618" alt="image" src="https://github.com/user-attachments/assets/24ad5c2b-979d-40ba-b353-71c76723fdbc" />

### Bower Environment
- **Day/Night Cycle**: Switch between daytime, nighttime, and dawn
- **Adjustable Lighting**: Slider to control bower brightness
- **Forest Scene**: Animated trees, bushes, moon, and stars
- **Responsive Design**: Works on desktop and mobile devices

### Visual Design
- Beautiful color palette with forest greens and fox oranges
- Smooth animations and transitions
- Custom-drawn fox character with expressive features
- Atmospheric lighting effects

## Live Demo

You can view the live demo [here](https://your-demo-link.com) or simply open the `index.html` file in any modern browser.

##  Project Structure

```
fox-bower/
│
├── index.html          # Main HTML file
├── README.md           # This documentation
└── (No external dependencies!)
```

## Technologies Used

- **HTML5**: Semantic structure and content
- **CSS3**: Advanced styling, animations, and responsive design
- **JavaScript**: Interactive functionality and state management
- **Font Awesome**: Icon library for UI elements

## How to Use

1. **Clone or Download** the repository
2. **Open** `index.html` in your web browser
3. **Interact** with the fox using the control panel:
   - Click "Pet the Fox" to show affection
   - Click "Feed the Fox" to restore energy
   - Click "Play with Fox" for fun activities
   - Click "Put Fox to Sleep" for rest
   - Use the slider to adjust lighting
   - Switch between day, night, and dawn

## Interaction Guide

### Fox States
- **Happy**: When happiness > 80%
- **Content**: When happiness > 60%
- **Bored**: When happiness > 40%
- **Restless**: When happiness < 40%

### Energy System
- Playing consumes energy
- Sleeping restores energy
- Feeding provides moderate energy boost

### Environmental Controls
- **Daytime**: Bright, cheerful atmosphere
- **Nighttime**: Dark with stars and moon
- **Dawn**: Sunrise colors with partial lighting

## Browser Compatibility

Tested and works on:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

Want to customize your fox bower? Here are some easy modifications:

### Change Colors
Edit the CSS variables in the `<style>` section:
```css
:root {
    --fox-color: #d84315;
    --bower-bg: #1a3c27;
    --accent-color: #ff9800;
}
```

### Add New Interactions
Extend the JavaScript by adding new buttons and functions:
```javascript
// Example: Add a new "Groom" button
btnGroom.addEventListener('click', function() {
    showMessage("I love being groomed!");
    foxState.happiness += 8;
    updateStatus();
});
```

### Modify the Scene
Add new elements to the bower scene:
```html
<div class="new-element" id="myElement"></div>
```

## Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Areas for Contribution
- Add more fox animations
- Create seasonal themes (winter, autumn, etc.)
- Implement sound effects
- Add more interactive elements to the bower
- Improve mobile responsiveness
- Create additional animal friends

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Icons by [Font Awesome](https://fontawesome.com)
- Color palette inspired by forest ecosystems
- Inspired by nature sanctuaries and digital pet simulations

## Future Enhanceances

Planned features for future versions:
- [ ] Multiple fox personalities
- [ ] Weather system (rain, snow, fog)
- [ ] Seasonal changes
- [ ] Sound effects and ambient music
- [ ] More detailed fox animations
- [ ] Save/load fox state
- [ ] Achievements system

## Project Stats

![Code Size](https://img.shields.io/github/languages/code-size/username/fox-bower)
![Last Commit](https://img.shields.io/github/last-commit/username/fox-bower)
![Open Issues](https://img.shields.io/github/issues/username/fox-bower)

## 📞 Support

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
