# Learning [Photopea](https://www.photopea.com)

Basically Photoshop, except free, and legal, and in your browser: [photopea.com](https://www.photopea.com)

Just one of the things I'm learning. https://github.com/hchiam/learning

Beginner tutorial video: https://www.youtube.com/watch?v=JIdvvG9ZX7c

Feature requests: https://github.com/photopea/photopea/issues

## Example SVG export from Photopea

```bash
open demo.html
```

## **_One command to rule them all_**:

**Ctrl+F**:
- lets you type command name to search and then hit **Enter** to run it. (It also shows the keyboard shortcut.) This functionality reminds me of Ctrl+Shift+P in VSCode.

## Miscellaneous notes

- https://youtu.be/1UWGoiIYGUw?t=14

- https://www.photopea.com/learn/vg-creating

- "Pen" --> click dots = **polygon**.

- Curves: "Pen" --> click+drag = **path with curves** (Bézier ones).

- You can practice drawing Bézier curves at <https://bezier.method.ac>

- Other things like rotation, selection, blur, layers, subtraction, etc. remind me of GIMP. Except the interface is basically Photoshop.

- This only flips one layer, and doesn't work on SVG layers: Edit > Transform > Flip Horizontally.

- This flips the **_entire_** file/image, and **_works_** on **_SVG_** layers: **_Image_** > Transform > Flip Horizontally.

- ["remove" objects with **content-aware fill**](https://www.youtube.com/watch?v=G-d3y9WMFDg): select object > Edit > Fill... > Content Aware.
  - or use the "spot healing" brush or patch tool: https://www.youtube.com/watch?v=JIdvvG9ZX7c

- to add an outline around the selected shape, right click on its layer > Blending Options > Stroke (click on Stroke, checkbox on, change colour, etc.)

- to generate SVG from image, you can run Image > "Vectorize Bitmap"
