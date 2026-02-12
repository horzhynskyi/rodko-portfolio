# Images Folder

This folder is intended to store local images for the portfolio website.

## Usage

Place your image files in this directory. The following image formats are supported:
- PNG (.png)
- JPEG (.jpg, .jpeg)
- SVG (.svg)
- GIF (.gif)

## Current Image References

The `manifest.json` file in the root directory contains references to images that are expected to be in this folder. Currently, these images are hosted externally. To use local images:

1. Download or copy your images to this folder
2. Update the image paths in `manifest.json` and `index.html` if needed to point to local files

## Examples

Images should be referenced relative to the root directory:
```html
<img src="images/your-image.png" alt="Description">
```

Or in CSS:
```css
background-image: url('../images/your-image.png');
```
