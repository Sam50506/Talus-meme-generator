# Talus Meme Maker

A professional web-based meme generator featuring Talus/Tally templates with customizable text, fonts, and styling options.

## Features

- **12 Unique Templates** - Curated collection of Talus/Tally meme templates
- **Professional Text Editor** - Multi-layer text management with real-time editing
- **Font Variety** - 11 different font families including Impact, Anton, Arial Black, and more
- **Custom Styling** - Adjustable font size, colors, outlines, and text alignment
- **Mobile Responsive** - Optimized for both desktop and mobile devices
- **High-Quality Export** - Download memes as high-resolution PNG files
- **Layer Management** - Easy text layer selection and organization

## Templates Included

1. Buff Tally vs Cheems
2. Lonely Tally
3. Tally Epic Handshake
4. Clown Tally Evolution
5. Surprised Tally
6. Mood Shifting
7. It's a Secret
8. Confused Tally
9. Distracted Tally
10. Disaster Tally
11. Tally No/Yes
12. 0 Days Without

## Usage

1. **Select Template** - Choose from the available Talus meme templates
2. **Edit Text** - Click on text boxes to edit content
3. **Customize Style** - Adjust fonts, colors, sizes, and alignment
4. **Manage Layers** - Add, delete, or reorder text layers
5. **Download** - Export your finished meme as a PNG file

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Canvas Library**: Fabric.js for advanced text manipulation
- **Fonts**: Google Fonts integration
- **Responsive Design**: CSS Flexbox and Grid

## Installation

### Option 1: Direct Download
1. Download the HTML file
2. Open in any modern web browser
3. Start creating memes immediately

### Option 2: Web Server
1. Clone this repository
2. Serve the files using any web server
3. Access via browser

```bash
git clone https://github.com/yourusername/talus-meme-maker.git
cd talus-meme-maker
# Serve using your preferred method (Python, Node.js, etc.)
python -m http.server 8000
```

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features in Detail

### Text Editing
- **Drag & Drop**: Move text boxes anywhere on the template
- **Resize**: Adjust text box dimensions with corner handles
- **Multi-line Support**: Automatic text wrapping
- **Real-time Preview**: See changes instantly

### Styling Options
- **Font Family**: Impact, Anton, Arial, Arial Black, Comic Sans MS, Courier New, Georgia, Helvetica, Times New Roman, Trebuchet MS, Verdana
- **Font Size**: 10px to 120px range
- **Colors**: Full color picker for text and outlines
- **Stroke Width**: Adjustable outline thickness (0-10px)
- **Alignment**: Left, center, right text alignment

### Export Quality
- **High Resolution**: 2x multiplier for crisp images
- **PNG Format**: Lossless compression with transparency support
- **Filename**: Automatically named "talus-meme.png"

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-template`)
3. Commit your changes (`git commit -am 'Add new template'`)
4. Push to the branch (`git push origin feature/new-template`)
5. Create a Pull Request

## Adding New Templates

To add new meme templates:

1. Upload your image to a reliable hosting service
2. Add template object to the `templates` array in the JavaScript:

```javascript
{
    id: "t13",
    name: "Your Template Name",
    image: "https://your-image-url.com/image.jpg",
    textBoxes: 2
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Fabric.js for powerful canvas manipulation
- Google Fonts for typography
- Talus community for template inspiration

## Support

For issues, questions, or feature requests, please open an issue on GitHub.

---

**Note**: This meme maker is designed for the Talus community. All template images should comply with appropriate usage rights and community guidelines.
```

The key fixes:
- Proper code block formatting with triple backticks
- Separated the bash commands into their own code block
- Removed the mixed template code from the installation section
- Clean, consistent formatting throughout.
