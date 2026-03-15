
# Project Blueprint: Krav Maga Awareness Website

## Overview

This project is a modern, single-page website for a Krav Maga school. It is built with HTML, CSS, and JavaScript, following modern web standards to ensure a responsive and accessible user experience. The design is bold and visually engaging, using a dark theme with red accents to convey a sense of strength and urgency.

## Design & Features

### Visual Design

*   **Typography:** The site uses the 'Oswald' font for headings to create a strong, impactful look, and 'Roboto' for body text to ensure readability.
*   **Color Palette:** The primary color scheme is a dark theme with a black background (`#1a1a1a`), white text (`#f5f5f5`), and a vibrant red accent (`#ff3b3f`) for calls to action and important elements.
*   **Background:** The entire page features a full-screen, fixed background image of a Krav Maga training session (`pexel.jpg`) to create an immersive experience. The content sections have a semi-transparent dark background to ensure text is legible.
*   **Layout:** The layout is a single-page design with a sticky header for easy navigation. The content is organized into logical sections, each with a clear heading and well-structured information.

### Features

*   **Header:** A sticky header with a logo and navigation links that smoothly scroll to different sections of the page.
*   **About Section:** An introduction to Krav Maga, its history, and its purpose.
*   **Statistics Section:** A grid of statistics on global assault rates to highlight the importance of self-defense.
*   **News Section:** A collection of recent news articles about assaults to provide real-world context.
*   **Who Should Practice Section:** Information on who can benefit from Krav Maga training, with an inspiring quote.
*   **Trial Class CTA:** A prominent call-to-action button that encourages users to sign up for a trial class.
*   **Schedule Section:** A table displaying the weekly class schedule.
*   **Instructors Section:** A grid of instructor profiles with photos and brief descriptions.
*   **Footer:** A simple footer with copyright information.

## Current Change: Full-Screen Background Image

### Plan

1.  **Set the background image on the `body` element:** The `background-image` property of the `body` will be set to `url('pexel.jpg')`.
2.  **Make the background cover the entire screen:** The `background-size` property will be set to `cover` to ensure the image scales to fill the viewport.
3.  **Fix the background image:** The `background-attachment` property will be set to `fixed` so the image remains in place as the user scrolls.
4.  **Add a semi-transparent background to content sections:** The `section` elements will be given a `background-color` of `rgba(26, 26, 26, 0.85)` to make the text readable against the background image.
5.  **Remove the banner image:** The `<img>` tag for `Master.png` will be removed from the `index.html` file to prevent it from covering the new background.
