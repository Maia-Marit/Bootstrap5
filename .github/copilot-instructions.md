# Copilot Instructions for Bootstrap5 Workspace

## Project Overview
This workspace is a simple static site project using Bootstrap 5. The main entry point is `index.html`, and all assets are stored in the `assets/` directory. There are no build tools, package managers, or backend code present.

## Architecture & Structure
- **Single-page HTML**: All content and layout are managed in `index.html`.
- **Assets**: Images and other static files are located in `assets/`.
- **No external dependencies**: No npm, package.json, or build scripts detected. Bootstrap is likely included via CDN in the HTML.

## Developer Workflows
- **Editing**: Directly modify `index.html` for content and layout changes.
- **Adding assets**: Place new images or files in the `assets/` folder and reference them in `index.html`.
- **Previewing**: Open `index.html` in a browser to view changes. No local server required.

## Project-Specific Conventions
- **File organization**: Keep all images and static files in `assets/`.
- **Referencing assets**: Use relative paths like `assets/ebook-cover.png` in HTML.
- **Bootstrap usage**: Follow Bootstrap 5 conventions for layout and components. Reference the official documentation for grid, utilities, and components.

## Examples
- To add a new image: Place it in `assets/` and use `<img src="assets/new-image.png">` in `index.html`.
- To update the layout: Edit the HTML structure in `index.html` using Bootstrap classes (e.g., `container`, `row`, `col`).

## Key Files
- `index.html`: Main site content and structure.
- `assets/`: All static files (images, etc.).

## Integration Points
- No backend or API integration.
- No custom scripts or external build tools.

## How to Be Productive
- Focus on editing `index.html` and managing assets in `assets/`.
- Use Bootstrap 5 documentation for UI changes.
- No need to run build or test commands; changes are reflected immediately in the browser.

---
For questions or unclear conventions, ask the user for clarification or examples from their workflow.
