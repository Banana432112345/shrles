# Shrles Discord Theme

A custom **Vencord** Discord theme featuring your screenshot as the background image.

## Features

✨ Custom screenshot background  
🎨 Semi-transparent overlays for better readability  
🌙 Dark theme optimized for Discord  

## Installation

### Prerequisites
- [Vencord](https://vencord.dev/) installed on Discord

### Steps

1. **Download the theme file**
   - Clone or download this repository
   - Or copy `shrles.theme.css` directly

2. **Place the theme in your Vencord folder**
   - **Windows**: `%APPDATA%/Vencord/themes/`
   - **Linux**: `~/.config/Vencord/themes/`
   - **macOS**: `~/.config/Vencord/themes/`

3. **Enable the theme in Discord**
   - Open Discord with Vencord
   - Go to **Settings** → **Vencord** → **Themes**
   - Find and toggle **Shrles Theme** on
   - Restart Discord if needed

## Customization

You can edit `shrles.theme.css` to customize:

- **Background opacity**: Change `rgba(0, 0, 0, 0.2)` values (higher = darker)
- **Background image**: Replace the URL in `--background-image`
- **Colors**: Modify the `background-color` values

### Example: Darker Theme
```css
/* Make the overlay darker */
.app-mount {
  background-color: rgba(0, 0, 0, 0.5) !important; /* Increased from 0.2 */
}
```

## Theme Preview

Uses your custom screenshot as the main background with semi-transparent dark overlays for readability.

## Support

If you encounter any issues:
1. Clear Discord cache
2. Restart Discord
3. Check that the theme file is in the correct folder
4. Ensure Vencord is up to date

## License

Feel free to modify and share!

---

**Created with ❤️ for Discord customization**
