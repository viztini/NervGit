[./eva-title]

# An Evangelion GitHub Theme (Firefox Extension)

A Firefox browser extension that transforms the GitHub interface with a custom theme inspired by Evangelion Unit 01 and the aesthetic of Neon Genesis Evangelion NERV.

## Features

*   **NERV-Styled Color Palette:** Dark backgrounds, prominent red accents, and subtle grey tones.
*   **Curved Corners:** Applies `border-radius` to various GitHub elements for a softer, more modern look.
*   **Enhanced Dashboard Theming:** Specific styling for the GitHub dashboard feed and repository cards.
*   **Custom Background Support:** Easily integrate your favorite Evangelion-themed background image.
*   **Improved Readability:** Carefully chosen colors and contrasts to maintain readability.

## Installation (Temporary Add-on in Firefox)

To install this theme as a temporary add-on in Firefox:

1.  **Open Firefox:** Launch your Firefox browser.
2.  **Access Add-ons Manager:**
    *   Type `about:addons` in the address bar and press Enter.
    *   Alternatively, click the menu button (three horizontal lines) -> "Add-ons and themes" -> "Extensions".
3.  **Enable Debugging Add-ons:**
    *   On the Add-ons Manager page, click the gear icon (⚙️) in the top right corner.
    *   Select "Debug Add-ons".
4.  **Load Temporary Add-on:**
    *   On the Debug Add-ons page, click the "Load Temporary Add-on..." button.
    *   Navigate to the directory where you have the NervGit folder.
    *   Select any file *inside* the folder (e.g., `manifest.json` or `content.js`). Firefox will automatically detect the extension.
5.  **Verify Installation:**
    *   The "Evangelion GitHub Theme" should now appear in your list of temporary add-ons.
6.  **Test the Theme:**
    *   Open a new tab and navigate to `github.com`.
    *   You should see the Evangelion-themed colors and styling applied to the GitHub interface.

**Note:** Temporary add-ons are removed when Firefox is closed. To keep the extension permanently, you would need to install it using Firefox extension store page for NervGit: https://addons.mozilla.org/en-US/firefox/addon/soon-to-be-added-please-fix/.

## Customization: Adding a Background Image

The theme supports a custom background image. To add your own:

1.  **Find Your Image:** Locate a direct URL for the image you wish to use (e.g., ending in `.png`, `.jpg`, `.gif`, etc.).
2.  **Save the Image:** Download the image and save it as `nerv-background.png` inside the icons
3.  **Reload Extension:** Go to `about:debugging#/runtime/this-firefox` in Firefox, find "NervGit", and click "Reload".
4.  **Refresh GitHub:** Refresh any open GitHub pages to see your new background.

## Contributing

Feel free to modify the `evangelion.css` file to further customize the theme to your liking. Experiment with colors, fonts, and element styles!
