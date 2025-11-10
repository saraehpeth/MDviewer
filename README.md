# Markdown Viewer

A clean, professional markdown viewer for comparing and reviewing `.md` files with customizable themes and typography controls.

---

## Features

### View Modes
- **Side-by-Side**: Compare two markdown documents simultaneously
- **Single**: Focus on one document with full-width display

### Input Options
Each document pane supports two input methods:
- **Paste Markdown**: Paste content directly into the textarea for quick testing
- **Upload File**: Load `.md` files from your computer

### Document Actions
- **Load Markdown**: Render pasted content as formatted markdown
- **Save**: Download pasted content as a `.md` file
- **Clear**: Empty the paste area (with confirmation)

### Customization
**Themes**: Choose from 6 color schemes
- Professional (default)
- Dark Mode
- Warm
- Cool
- High Contrast
- Sepia

**Typography Controls**: Adjust reading experience
- Font size (12px - 24px)
- Line height (1.2 - 2.0)
- Paragraph spacing (0.5× - 2.0×)

**Additional Controls**:
- Synchronized scrolling (toggle on/off)
- Collapsible document headers for distraction-free reading

### Document Statistics
Each loaded document displays:
- Word count
- Character count (excluding whitespace)
- Estimated read time (based on 200 words/minute)

### Special Features
- **Frontmatter Support**: YAML frontmatter is automatically detected and displayed as document metadata
- **Sticky Headers**: Document controls remain accessible while scrolling
- **Persistent Preferences**: Your theme and typography settings are saved automatically

---

## How to Use

### Quick Start
1. Open `index.html` in your web browser
2. Choose **Single** or **Side-by-Side** view mode
3. Paste markdown content or upload a `.md` file
4. Click **Load Markdown** to render
5. Adjust theme and typography to your preference

### Comparing Documents
1. Select **Side-by-Side** mode
2. Load content in both left and right panes
3. Use synchronized scrolling to compare sections
4. Collapse headers for more reading space

### Working with Pasted Content
1. Switch to **Paste Markdown** tab
2. Paste your markdown content
3. Click **Load Markdown** to render
4. Use **save** to download as `.md` file
5. Use **clear** to start fresh

### Keyboard-Friendly
- Textareas are resizable (drag bottom-right corner)
- All controls are keyboard accessible
- Toggle buttons use standard tab navigation

---

## Tips & Tricks

- **Collapse headers** (click the ▼ button) when you're done setting up to maximize reading space
- **Sync scroll** is great for comparing similar documents section-by-section
- **Theme switching** is instant - try different themes to find what works best for your content
- **Stats are calculated** excluding frontmatter for accurate content metrics
- All preferences persist between sessions - set it once and you're done!

---

## Technical Details

### Supported Markdown
- GitHub Flavored Markdown (GFM)
- YAML frontmatter
- Tables with styling
- Code blocks with syntax highlighting
- Blockquotes
- Lists (ordered and unordered)
- Links, images, and inline formatting

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for mobile and tablet
- Local storage for preferences

### Files
- `index.html` - Complete standalone application (no external dependencies except marked.js CDN)

---

## Planned Features (TBD)

The following features are under consideration for future releases:

- [ ] Line numbers in markdown viewer
- [ ] Highlight differences between documents (diff view)
- [ ] Export rendered HTML
- [ ] Export to PDF
- [ ] Table of contents generation
- [ ] Word/character count overlay
- [ ] Custom CSS injection
- [ ] Markdown syntax help reference
- [ ] Dark mode auto-detect from system preferences

**Have an idea?** If there's a feature you'd like to see added, please let me know! I'm actively developing this tool and would love to hear what would make it more useful for you.

---

## License & Usage

This tool was built for the CPA firm's AI seminar series. Feel free to use, modify, and share within the organization.

---

## Credits

Built with:
- [marked.js](https://marked.js.org/) - Markdown parser and compiler
- Lots of iteration and refinement with Claude Code

---

**Questions or suggestions?** Reach out to Sara!
