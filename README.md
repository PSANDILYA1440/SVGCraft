SVGCraft
A lightweight, browser-based SVG editor for creating and editing simple vector artwork. SVGCraft runs as a standalone HTML file, so there is no build step or server setup required.

Created by PSANDILYA1440
Features
- Shape tools: add rectangles, circles, ellipses, triangles, stars, lines, and text.
- Direct canvas editing: select and drag objects with a mouse or touch input.
- Object resizing: use the selection handles to resize selected objects.
- Properties inspector: edit object names, position, width, height, fill, stroke, stroke width, opacity, rotation, and text content.
- Layers panel: select layers and delete objects.
- Canvas sizing: set the artboard width and height with the dimension fields, or drag the purple handle at the bottom-right of the canvas.
- Zoom: zoom the canvas view in and out.
- Editing actions: undo, redo, duplicate, and delete objects.
- SVG export: export the artwork as an SVG file using the current artboard dimensions.
Getting started
1. Download or clone this project.
2. Open SVGCraft-UPDATED.html in a modern web browser.
3. Select a shape tool from the left toolbar to add an object.
4. Select an object on the canvas to edit its properties in the right-hand inspector.
5. Use Export SVG to save your artwork.
No package manager, compiler, or development server is required.
Using the editor
Add and select objects
Choose a tool from the left toolbar. The object is added to the canvas and becomes selected. Choose Select to return to selection mode.
Move and resize objects
Drag an object directly on the canvas to move it. When selected, its corner handles can be dragged to resize it. You can also enter exact position and size values in the Properties panel.
Change object appearance
With an object selected, use the Properties panel to change its fill, stroke, stroke width, opacity, and rotation. Text objects also expose a text-content field.
Resize the canvas
Edit the W and H fields above the canvas and choose Apply size, or drag the purple resize grip at the canvas's bottom-right corner. These controls change the SVG artboard dimensions, not just the zoom level. The exported SVG uses the updated dimensions.
Undo and redo
Use the Undo and Redo buttons in the top bar. Keyboard shortcuts are also available:
- Ctrl+Z / Cmd+Z: undo
- Ctrl+Y / Cmd+Y: redo
- Ctrl+D / Cmd+D: duplicate the selected object
- Delete or Backspace: delete the selected object
Export
SVGCraft currently exports artwork as SVG. The export contains the artwork and the current SVG canvas dimensions; the editor's selection outline and resize handles are excluded.

PNG export is mentioned in some promotional copy in the current interface, but is not implemented in this version.
Technology
- HTML
- CSS
- Vanilla JavaScript
- SVG
- DM Sans and Manrope web fonts loaded from Google Fonts, with sans-serif fallbacks
Project files
- SVGCraft-UPDATED.html — the standalone editor.
- README.md — project documentation.
- LICENSE — MIT License.
License
This project is licensed under the MIT License. See the LICENSE file for the full text.

The MIT License is a permissive software license: it allows reuse, modification, and redistribution, including in commercial projects, provided the copyright and license notices are retained. Choose it if that freedom is what you want. If you would rather require distributed modified versions to remain open source, consider a copyleft license such as GPL-3.0 instead.

Only apply this license to material you own or are authorized to relicense. Check the terms for any third-party assets or contributions before publishing.
