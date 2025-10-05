# Impossible Demon List - TOP 75

A modern, responsive website showcasing the top 75 most impossible levels in Geometry Dash. This website is inspired by the Geometry Dash community's Demon List but focuses specifically on levels that are theoretically impossible to complete.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Search**: Search for demons by name or creator
- **Filtering**: Filter demons by categories (All, Top 10, Legacy, Recent)
- **Pagination**: Navigate through the list with smooth pagination
- **Detailed Modals**: Click on any demon to see detailed information
- **Modern UI**: Beautiful gradient backgrounds, animations, and Geometry Dash-inspired design
- **Copy Functionality**: Copy demon IDs directly to clipboard
- **Video Links**: Quick access to YouTube searches for each demon

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Advanced styling with gradients, animations, and responsive design
- **Vanilla JavaScript**: Interactive functionality without frameworks
- **Google Fonts**: Orbitron and Roboto fonts for enhanced typography

## File Structure

```
DerpyIDL-TOP75/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript functionality
├── favicon.svg         # Website icon
└── README.md          # This file
```

## Setup Instructions

1. Clone or download the project files
2. Open `index.html` in a modern web browser
3. No additional setup or dependencies required!

## Features Overview

### Navigation
- **All Demons**: Shows all 75 impossible demons
- **Top 10**: Displays only the top 10 most impossible demons
- **Legacy**: Shows older impossible demons
- **Recent**: Displays recently added impossible demons

### Search Functionality
- Real-time search as you type
- Search by demon name or creator
- Debounced for optimal performance

### Demon Cards
- Ranking display with special styling for top demons
- Creator information
- Level ID and length
- Truncated descriptions with full details in modal

### Modal Details
- Complete demon information
- Copy level ID to clipboard
- Direct YouTube search links
- Responsive design

## Customization

### Adding New Demons
Edit the `impossibleDemons` array in `script.js`:

```javascript
{
    rank: 76,
    name: "New Impossible Demon",
    creator: "CreatorName",
    id: "12345678",
    length: "Long",
    song: "Artist - Song Name",
    description: "Description of the demon...",
    category: "recent"
}
```

### Styling Changes
Modify `styles.css` to customize:
- Colors and gradients
- Animations and transitions
- Layout and spacing
- Responsive breakpoints

### Color Scheme
- Primary: #4ecdc4 (Teal)
- Secondary: #ff6b6b (Red)
- Accent: #45b7d1 (Blue)
- Background: Dark gradient (#0a0a0a to #16213e)

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance Features

- Debounced search for smooth typing
- Pagination for fast loading
- CSS animations with GPU acceleration
- Optimized image loading
- Minimal JavaScript framework overhead

## Contributing

Feel free to contribute by:
1. Adding new impossible demons to the list
2. Improving the UI/UX design
3. Adding new features
4. Fixing bugs or improving performance

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Inspired by the Geometry Dash community
- Special thanks to all the creators of impossible demons
- Font families provided by Google Fonts

---

**Note**: This is a fan-made website inspired by Geometry Dash. Level IDs and some information may be fictional for demonstration purposes.
