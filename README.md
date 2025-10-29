# 🎨 My VS Code Themes
just a few personal settings for vs code 

---

## 🌌 Preview

### Theme 1: Dracula Theme and Custom Slider
![Theme 1](./assets/gif/theme-1.gif)

## ⚙️ Installation
1. Download file custom-css-theme.css
2. Open **VS Code**  
3. Go to **Extensions Marketplace**  
4. Search and Install Custom CSS and JS Loader
5. Add the following line to your `settings.json` (choose the correct path for your OS):
  ```jsonc
  // Windows
  "vscode_custom_css.imports": [
    "file:///C:/Users/<username>/Desktop/custom/<custom-css-theme-name.css>"
  ]

  // macOS
  "vscode_custom_css.imports": [
    "file:///Users/<username>/Desktop/custom/<custom-css-theme-name.css>"
  ]

  // Ubuntu / Linux
  "vscode_custom_css.imports": [
    "file:///home/<username>/Desktop/custom/<custom-css-theme-name.css>"
  ]
  // Replace <username> with your actual system username
  ````
6. Save your settings and run "Reload Custom CSS and JS" from the Command Palette (Ctrl+Shift+P on Windows/Linux, Cmd+Shift+P on macOS).

