# Image Slider Project

## Overview
This project is an image slider/carousel built using HTML, CSS, and JavaScript. The slider displays various wildlife images with corresponding titles, descriptions, and interactive buttons. It includes features like navigation arrows, automatic sliding, and thumbnail previews.

---

## Features

- **Image Slider:** Displays images with accompanying text and buttons.
- **Thumbnails:** Previews of images below the main slider for navigation.
- **Navigation Arrows:** Allows users to manually navigate through the slider.
- **Auto Sliding:** Automatically transitions between slides after a set interval.
- **Responsive Design:** Adjusts layout for smaller screen sizes.

---

## File Structure

```
|-- index.html         # Main HTML file
|-- style.css          # Stylesheet for the project
|-- script.js          # JavaScript functionality
|-- image/             # Folder containing images
    |-- img1.jpg
    |-- img2.jpg
    |-- img3.jpg
    |-- img4.jpg
```

---

## Installation

1. Clone the repository or download the project files.
2. Place all files in the same directory structure as described above.
3. Open `index.html` in your browser to view the project.

---

## Usage

### Navigating Slides
- Use the **left (<)** and **right (>)** arrow buttons to navigate between images manually.

### Automatic Sliding
- The slider automatically transitions to the next slide every 7 seconds.

### Thumbnails
- Click on a thumbnail to view the corresponding image in the main slider.

---

## JavaScript Functionality

### Core Functions

1. **`showSlider(type)`**
   - Displays the next or previous slide based on the `type` parameter (`next` or `prev`).
   - Animates thumbnails and content transitions.

2. **Event Listeners**
   - `nextDom.onclick`: Triggers the `showSlider('next')` function.
   - `prevDom.onclick`: Triggers the `showSlider('prev')` function.

3. **Automatic Transition**
   - Uses `setTimeout` to trigger the `next` button every 7 seconds.

---

## Styling (CSS)

- **Font:** Poppins from Google Fonts.
- **Color Scheme:** Dark theme with a focus on orange (#f1683a) accents.
- **Animations:** Smooth transitions for content appearance, image scaling, and thumbnail effects.

---

## Compatibility

- **Browsers:** Works on all modern browsers like Chrome, Firefox, Edge, and Safari.
- **Devices:** Fully responsive and optimized for mobile and desktop devices.

---

## Future Improvements

- Add swipe gestures for mobile navigation.
- Implement dynamic image loading using an API.
- Enhance accessibility with ARIA attributes.
- Add a progress bar for slide transitions.

---

## Credits

- **Images:** Wildlife images used in the slider.
- **Author:** Ali (Etherman).

---

## License

This project is free to use for educational and non-commercial purposes. For other uses, please contact the author.

