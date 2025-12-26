# NeuroTrace Web

Browser-based neural structure annotation tool for neuroscience research.

![NeuroTrace Screenshot](screenshots/main-interface.png)

## Features

- 🎨 **15-Color Coding System** - Track multiple neural structures
- 🔄 **Smart Propagation** - Annotations auto-resize across slices
- 📊 **Data Export** - JSON & CSV formats for analysis
- ⌨️ **Keyboard Shortcuts** - Efficient workflow
- 💾 **Auto-Save** - Browser localStorage persistence
- 🖱️ **Interactive Canvas** - Drag-and-drop annotations

## Live Demo

[Try it live](https://your-portfolio-url.com/neurotrace) 

## Tech Stack

- React 18
- Canvas API
- Lucide React (icons)
- Tailwind CSS
- LocalStorage API

## Installation

\`\`\`bash
# Clone the repository
git clone https://github.com/yourusername/neurotrace-web.git

# Navigate to project
cd neurotrace-web

# Install dependencies
npm install

# Run development server
npm run dev
\`\`\`

Open `http://localhost:5173` in your browser.

## Usage

1. **Upload Images** - Click "Upload MRI Stack" to select multiple images
2. **Add Annotations** - Click "Add Marker" to create circular markers
3. **Adjust Size** - Use slider to change marker size (20-120px)
4. **Select Color** - Choose from 15 distinct colors
5. **Smart Propagation** - Set resize delta (-20 to +20px)
6. **Navigate** - Use arrow keys or buttons to move between slices
7. **Export Data** - Download annotations as CSV or JSON

## Keyboard Shortcuts

- `←` `→` - Navigate between images
- `Ctrl+A` - Add new annotation
- `Delete` - Remove selected annotation

## Data Export Format

**CSV Output:**
\`\`\`csv
image_index,annotation_id,x,y,size,color
0,0,245,312,50,"#FF0000"
\`\`\`

**JSON Output:**
\`\`\`json
{
  "version": "2.0",
  "annotations": [...]
}
\`\`\`

## Screenshots

![15-Color Palette](screenshots/color-palette.png)
![Smart Propagation](screenshots/propagation.png)
![CSV Export](screenshots/export.png)

## License

MIT

## Related Projects

- [NeuroTrace Desktop](https://github.com/yourusername/neurotrace-desktop) - JavaFX desktop version

## Author

Aden - [GitHub](https://github.com/yourusername) - [LinkedIn](https://linkedin.com/in/yourprofile)
