# Eaglercraft Launcher

Eaglercraft Launcher is a **browser-based launcher** for accessing, testing, and managing multiple versions and client builds of Eaglercraft (and Minecraft-inspired games) through a clean, interactive web interface. This project is ideal for users who want all their playable builds in one place—no new tabs, no complicated setups, and instant switching.

---

# DMCA Notice

All Eaglercraft versions, clients, and game builds linked or referenced in this launcher were **not created by me**. The source files, resources, and game links used in this project are provided by third-party authors and original developers. Credit and ownership of these builds belong entirely to their respective creators.

If you are a copyright owner and believe your work is featured or linked in this repository without proper authorization, please contact me to request removal or provide clarification in accordance with the Digital Millennium Copyright Act (DMCA) guidelines. I will act promptly and in good faith to address any concerns, correct attribution, or remove material as needed.

This launcher is intended as a **community aggregation point** for browser-accessible Minecraft builds. All links, titles, and resources remain under the trademark, copyright, or open license of their respective owners. No files are hosted or re-distributed by me beyond link aggregation. Please see the full DMCA policy for details on takedown requests and procedures[web:10][web:12].

---

## Purpose

The goal of Eaglercraft Launcher is to provide a central, user-friendly platform for launching and experimenting with different browser-based Minecraft versions, mod clients, and extra builds. Whether seeking nostalgia, speed, PvP enhancements, mod features, or alternative control schemes, this launcher puts everything a click away with rich descriptions and fast session management.

---

## Features

- **Tabbed Navigation:** Quickly switch between “Normal” game versions, Premium Clients, Hacked Clients, and Extras.
- **In-site Game Launch:** All games and clients run inside the site via fullscreen iframes—no popups or redirections.
- **ESC Overlay Management:** Press ESC and hover at the top to pause, resume, or leave sessions instantly.
- **Info Modal:** View usage tips and feature details for each build through card “Info” buttons.
- **Responsive UI:** Designed for both desktop and mobile/touch users, with smooth grid layouts and modern visuals.
- **Session Control:** Overlay lets users quickly leave games or resume, helping manage audio, loops, and focus.
- **Customizable Cards:** Game and client entries described with thumbnails, titles, meta tags, and helpful tooltips.
- **Accessibility:** Keyboard navigation for session and modal closure, gentle UI feedback for missed actions.

---

## How It Works

1. Open the `index.html` file in any modern browser.
2. Browse tabs (“Normal”, “Clients”, “Hacked Clients”, “Extras”) for available builds.
3. Click **Launch** to start a build directly in the site’s main container.
4. Press **ESC + Hover Top** to access pause/leave overlay for session control.
5. Click **Info** to reveal extra details about any game/client.

> **Note:** Links to each game/client will be connected via the `data-src` attribute on the Launch buttons. Please ensure your HTML builds and resources are placed in the `games/` folder as intended.

---

## Technologies

- **HTML5 / CSS3:** Layout, theming, transitions, and grid.
- **Vanilla JavaScript:** Tab switching, launch logic, modals, overlays, accessibility.
- **Google Fonts (Inter):** Modern bundled font for readability.

No special frameworks or server dependencies. Runs as static files.

---

## Customization

- **Adding New Builds:** Copy and edit card `<article>` blocks in the corresponding tab’s section. Set the title, description, and `data-src` link to the appropriate game/client HTML file.
- **Styling:** Edit CSS variables in the `<style>` section to change colors, radii, gradients, or theme accents.
- **Session Management:** You may extend overlay logic for custom actions, additional controls, or new session states.

---

## Project Status

This is an active work in progress. Some launch links are currently placeholders/fake paths until their respective builds are added. Feel free to fork, adjust, or contribute as the launcher and builds are completed.

---

## License

Choose and state your license here (MIT, Apache, etc.).

---

## Credits

- UI and launcher design inspired by browser game portals, community UI/UX feedback, and the Eaglercraft modding scene.
- Thanks to Eaglercraft and client authors for making browser Minecraft possible.

---

## Contact & Contributions

For bug reports, feature suggestions, or collaboration, please open an issue in the repository or message the maintainer.

