# BSU Esports Broadcaster Hub | Bryce Jensen

A dedicated portfolio and content hub for Bryce Jensen, broadcasting Boise State University Esports. This single-page web application serves as a central location to share broadcast highlights, track current roster statistics, break down game mechanics, and publish weekly post-match analysis.

## Live Broadcasts & Schedule

Catch my live casts and check the upcoming match schedule on the official Boise State Twitch channel:  
📺 **[Boise State Twitch Schedule](https://www.twitch.tv/boisestate/schedule)**

## Features

*   **Broadcast Clips:** Embedded highlight reels seamlessly integrated from Twitch and YouTube.
*   **Player Stats:** A responsive data table tracking key performance metrics for the current roster across multiple titles.
*   **Esports 101:** Beginner-friendly breakdowns of major esports titles (Rocket League, Valorant, Overwatch 2, League of Legends) for new viewers.
*   **Weekly Write-ups:** A dedicated feed for post-game recaps, match breakdowns, and analytical articles.

## Tech Stack

*   **HTML5:** Core structure and semantic layout.
*   **Tailwind CSS (CDN):** Rapid, utility-first styling custom-configured to official Boise State brand colors (Bronco Blue: `#0033A0` and Orange: `#D64309`).

## Getting Started

To view or modify this project locally, follow these steps:

1.  Clone this repository to your local machine:  
    `git clone https://github.com/yourusername/bsu-esports-hub.git`
2.  Navigate into the project directory:  
    `cd bsu-esports-hub`
3.  Open `index.html` in your preferred web browser. No local server, package manager, or build process is required.

## Customization Guide

*   **Adding Videos:** Locate the `[Embed Twitch/YouTube Clip Here]` placeholders in `index.html` and replace them with standard embed `<iframe>` tags from your streaming platform.
*   **Updating Stats:** Edit the HTML `<table>` rows in the "Player Stats" section to reflect the latest roster numbers.
*   **Adding Articles:** Duplicate an `<article>` block in the "Weekly Write-ups" section to publish new posts.

## Deployment

This project is fully static and ready to be hosted for free using [GitHub Pages](https://pages.github.com/). Simply go to your repository **Settings**, navigate to **Pages**, and select your `main` branch as the build source.
