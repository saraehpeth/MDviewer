---
title: Markdown Viewer - Project Overview
created: 2025.11.10
purpose: Demo package for senior partners, IT & CS
type: Project Documentation
---

# Markdown Viewer - What We Built

This document outlines the development and features of the custom Markdown Viewer tool, created as part of our firm's AI seminar initiative.

---

## Project Background

**Goal**: Create a professional, user-friendly tool for viewing and comparing markdown documents - particularly useful for reviewing AI seminar materials, documentation, and collaborative content.

**Approach**: Built collaboratively with AI assistance (Claude Code), iterating on design and functionality to create a polished, purpose-built solution.

**Timeline**: Developed in a single session through rapid prototyping and refinement.

---

## What It Does

The Markdown Viewer is a standalone web application that allows users to:

1. **View markdown documents** with professional formatting and styling
2. **Compare two documents side-by-side** for content review and version comparison
3. **Paste or upload content** with flexible input options
4. **Customize the reading experience** with themes and typography controls
5. **Export and save** markdown content for reuse

---

## Key Features Built

### Core Functionality
- **Dual view modes**: Side-by-side comparison or single full-width display
- **Multiple input methods**: Paste directly or upload `.md` files
- **Live rendering**: Instant markdown-to-HTML conversion with GitHub Flavored Markdown support
- **Document statistics**: Automatic word count, character count, and read time calculation

### User Experience
- **6 color themes**: Professional, Dark Mode, Warm, Cool, High Contrast, Sepia
- **Typography controls**: Adjustable font size, line height, and paragraph spacing
- **Synchronized scrolling**: Toggle for comparing documents section-by-section
- **Collapsible headers**: Maximize reading space when needed
- **Persistent preferences**: All settings saved automatically via browser storage

### Professional Polish
- **Frontmatter support**: YAML metadata displayed elegantly
- **Sticky controls**: Document headers remain accessible while scrolling
- **Responsive design**: Works on desktop, tablet, and mobile
- **Clean, minimal interface**: Professional aesthetic suitable for firm use
- **Accessibility**: Keyboard navigation and screen-reader friendly

---

## Technical Approach

### Technology Stack
- **Pure HTML/CSS/JavaScript**: No build process, no dependencies to manage
- **marked.js**: Industry-standard markdown parser (loaded via CDN)
- **localStorage API**: For preference persistence
- **Modern CSS**: Custom properties, flexbox, transitions for polish

### Design Principles
1. **Simplicity**: One standalone HTML file - easy to deploy and share
2. **Performance**: Fast loading, smooth interactions, no bloat
3. **Professionalism**: Clean design suitable for client-facing work
4. **Flexibility**: Customizable without being overwhelming

---

## Development Process

This tool was built through **collaborative iteration** with Claude Code:

1. **Started simple**: Basic side-by-side viewer with file upload
2. **Added depth**: Paste functionality, themes, typography controls
3. **Refined UX**: Statistics, collapsible headers, action buttons
4. **Polished details**: Spacing, colors, button sizing, layout adjustments
5. **Tested thoroughly**: Each feature validated and refined based on real use

### Key Decisions Made
- Paste as default input (faster for testing)
- Mode toggles vs action buttons (different colors considered, settled on unified blue)
- Minimal action links (clear/save) vs prominent buttons
- Horizontal control panel for better space usage
- Sticky headers for accessibility while scrolling

---

## Practical Applications

### For the AI Seminar
- Review and compare framework documents
- Test markdown formatting before finalizing materials
- Present content in different themes for different audiences
- Share documents without requiring markdown editors

### For the Firm
- Review collaborative documentation
- Compare draft versions of policies or procedures
- Present technical documentation professionally
- Create quick demos of content formatting

---

## What Makes This Different

Unlike existing markdown viewers, this tool:
- **Purpose-built for our needs**: Not a generic solution
- **Comparison-focused**: Side-by-side is a first-class feature
- **Highly customizable**: But starts with sensible defaults
- **Standalone and portable**: No installation, no accounts, no cloud
- **Professional aesthetic**: Matches our firm's quality standards

---

## Future Possibilities

Currently considering (see README.md for full list):
- Line numbers for reference
- Diff highlighting between documents
- PDF export
- Table of contents generation
- Additional export formats

**Open to suggestions** - this tool can evolve based on actual use cases.

---

## Technical Notes for IT/CS

### Deployment
- Single `index.html` file can be hosted anywhere
- No server-side processing required
- Works from file system (file://) or web server
- No external API calls (except marked.js CDN)

### Security
- All processing happens client-side
- No data transmission to external servers
- localStorage only (user's own browser)
- Safe for sensitive/confidential content

### Maintenance
- Updates are straightforward (edit one file)
- No dependencies to manage (except marked.js)
- No database or backend infrastructure
- Fully self-contained

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- No IE support needed
- Responsive design for mobile devices
- Graceful degradation for older browsers

---

## Try It Yourself

1. Open `index.html` in your browser
2. Try pasting this document into the viewer
3. Load a second document to see side-by-side comparison
4. Experiment with themes and typography
5. Test the collapsible headers and synchronized scrolling

**Pro tip**: Try loading the README.md and this PROJECT-OVERVIEW.md side-by-side to see the comparison feature in action.

---

## Questions?

This tool represents a practical example of:
- Rapid prototyping with AI assistance
- Purpose-built solutions vs off-the-shelf tools
- Iterative design and user experience refinement
- Creating professional tools for internal use

Happy to discuss the development process, technical details, or potential enhancements.

**— Sara**
