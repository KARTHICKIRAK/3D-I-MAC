# 3D Screen Display Project

This project creates a 3D rotating display of multiple screens with color selection options.

## Files

1. **index.html** - The main HTML file containing the structure
2. **index.css** - The stylesheet with all the 3D styling and animations

## Features

- 16 layered screens creating a 3D depth effect
- Rotating animation (360 degrees over 10 seconds)
- Color selection via radio buttons (7 color options)
- First screen shows MacOS desktop image
- Last screen shows Apple logo
- Stand/base with detailed 3D styling
- Screen glare animation for realism

## Color Options

1. Purple
2. Blue
3. Green
4. Red
5. Orange
6. Yellow
7. Silver

## How It Works

1. The CSS uses CSS variables (`--primary` and `--secondary`) to control the color scheme
2. Radio button selection updates these variables to change the colors
3. The 3D effect is created using CSS transforms and perspective
4. The screens are positioned absolutely with increasing `translateZ` values for depth
5. The entire assembly rotates continuously using CSS animation

## Requirements

- Modern browser with good CSS3 support (Chrome, Firefox, Safari, Edge)
- Internet connection (for loading external images)

## How to Use

1. Open index.html in a browser
2. Click different color radio buttons to change the color scheme
3. Watch the 3D display rotate automatically

## Customization

You can modify:
- Rotation speed by changing the animation duration
- Screen size by adjusting the `--screenSize` variable
- Colors by editing the color values in the CSS
- Images by changing the background-image URLs
