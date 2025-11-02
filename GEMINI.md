# GEMINI.md

## Directory Overview

This directory contains a static, single-page wedding invitation website for Amit & Priyanka. The page is visually rich, featuring animations, background music, and interactive elements.

## Key Files

*   `index.html`: The main and only HTML file, containing the structure, content, styling (inline CSS), and client-side logic (inline JavaScript) for the entire website.
*   `song.mp3`: The background music for the website.
*   `aplogo.png`: The favicon and logo for the couple.
*   `ganpati.png`: An image of Lord Ganesha displayed at the top of the page.
*   `couple1.png`, `couple2.png`, `couple3.png`, `couple4.png`: Images of the couple used in a "polaroid" style photo gallery.
*   `airport.svg`, `mandap.svg`, `taxi.svg`: Icons used in an animated "helpful information" section to show the route to the venue.

## Usage

This is a static website. To view it, simply open the `index.html` file in a web browser. There is no build process or server required.

## Change Log

*   **Venue Section:**
    *   Increased the `min-height` of the venue section on mobile to prevent text from overlapping with the icons.
    *   Adjusted the `endY` position of the taxi animation to be lower on both mobile and desktop.
    *   Centered the text content of the venue card vertically to prevent overlap with the airport icon.
*   **Button Size:** Adjusted the size of the buttons on mobile for better visibility.
*   **SVG Icon Sizes:** Increased the size of the airport, mandap, and taxi icons.
*   **Firework Animation:**
    *   Added a firework animation to the Sangeet section.
    *   The animation is triggered when the section is visible.
    *   The fireworks are particle-based and continuous.
    *   The animation is responsive and uses the website's color palette.
    *   The animation was refined to be more "natural" with varying rocket speeds, burst sizes, and a gravity effect.