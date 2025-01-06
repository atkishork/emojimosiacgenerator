# Emoji Mosaic Web Tool

## Project Overview
The Emoji Mosaic Web Tool allows users to upload an image and generate a mosaic made up of various emojis. The tool processes the image by extracting its pixel colors and mapping them to the closest matching emojis. The final result is displayed as a mosaic of emojis that represents the original image in a creative and fun way. Users can also download the generated emoji mosaic as an image.

## Features
- Upload an image to generate an emoji mosaic.
- Wait for the processing of the image, which may take a moment.
- Download the resulting emoji mosaic as an image file.
- Use light gray buttons for interactions, with a sleek, modern interface.
- All images and colors are mapped using the closest matching emojis.

## How It Works
1. **Image Upload**: The user uploads an image via the file input.
2. **Image Processing**: The uploaded image is processed to extract its pixel colors.
3. **Emoji Mapping**: The extracted colors are matched to the closest emoji from a predefined set.
4. **Mosaic Creation**: A mosaic is generated by placing emojis based on the image's color pattern.
5. **Download the Mosaic**: The user can download the emoji mosaic as an image.

## Functions Breakdown

### 1. `loadEmojis()`
This function loads the available emojis from the `emojiColors` array and maps each emoji to its respective image file. It returns a `colorMap` object that associates each color with an emoji image.

#### Example:
```javascript
var emojiMap = loadEmojis();
