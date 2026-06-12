# DTLteach

DTLteach is a simple, self-contained Windows 11 teaching guide for beginners, older adults, and anyone who needs a calm introduction to everyday computer use.

The project is a single HTML page written in French. It explains common Windows 11 concepts with short sections, simple wording, a fixed navigation sidebar, and one local screenshot of the Windows 11 Start menu.

## Contents

The guide covers:

- The Windows 11 Start menu
- The six useful shortcuts in the left column of the Start menu
- How to increase text size and display scaling
- The Windows desktop
- Window controls
- File Explorer
- Internet browsing with Google Chrome
- Email basics
- USB drives
- Wi-Fi connection
- Essential programs
- Basic security habits

## Files

- `DTLteach.html` - the complete teaching guide, including HTML and CSS.
- `menu_Windows_11.png` - screenshot used in the Start menu section.

## How to Use

Open `DTLteach.html` in a web browser.

No installation, server, build step, or external dependency is required. The page works as a local static file as long as `menu_Windows_11.png` stays in the same folder as the HTML file.

## Editing

The page is intentionally lightweight:

- The navigation links are defined in the `.sidebar` section.
- Each lesson is a `<section>` with its own `id`.
- The visual style is embedded in the `<style>` block at the top of `DTLteach.html`.

To add a new chapter, add a new sidebar link and a matching section with the same anchor id.

## Audience

This guide is designed for practical digital literacy sessions where learners may be discovering Windows for the first time. The tone and structure favor reassurance, clarity, and step-by-step learning over technical detail.
