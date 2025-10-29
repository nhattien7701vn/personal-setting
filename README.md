# 🎨 My VS Code Themes
just a few personal settings for vs code 

---

## 🌌 Preview

### Dracula Theme and Custom Slider
![Theme 1](./assets/theme-1.gif)

## ⚙️ Installation
1. Download file custom-colors-vscode.css
2. Open **VS Code**  
3. Go to **Extensions Marketplace**  
4. Search and Install Custom CSS and JS Loader
5. Add the following line to your `settings.json` (choose the correct path for your OS):
  ```jsonc
  // Windows
  "vscode_custom_css.imports": [
    "file:///C:/Users/<username>/Desktop/custom/custom-colors-vscode.css"
  ]

  // macOS
  "vscode_custom_css.imports": [
    "file:///Users/<username>/Desktop/custom/custom-colors-vscode.css"
  ]

  // Ubuntu / Linux
  "vscode_custom_css.imports": [
    "file:///home/<username>/Desktop/custom/custom-colors-vscode.css"
  ]
  // Replace <username> with your actual system username
  ````
6. Save your settings and run "Reload Custom CSS and JS" from the Command Palette (Ctrl+Shift+P on Windows/Linux, Cmd+Shift+P on macOS).

