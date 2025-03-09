# Zed Editor Configurations

This repository contains my personalized configurations for the [Zed editor](https://zed.dev/). These configurations include core keybindings, themes, settings, and plugins that enhance my workflow and productivity.

Feel free to use, customize, or contribute to these configurations for your own setup!

---

## **Contents**
- [Keybindings](#keybindings)
- [Settings](#settings)
- [Installation](#installation)
- [Contributing](#contributing)

---

## **Keybindings**
Custom keybindings tailored for faster navigation and efficient editing. These are stored in `keymap.json`.

---

## **Settings**
Custom editor settings for a seamless development experience. Settings are stored in:
- `settings.json`: Primary configuration file.
- `settings_backup.json`: Backup of the settings file.

---

## **Installation**
To use these configurations:

1. Clone this repository:
   ```bash
   git clone https://github.com/Zaki-goumri/zed-config.git
   
2. Copy the configuration files to your Zed config directory:
macOS/Linu

       cp -r zed-config/* ~/.config/zed/
Windows:

     xcopy zed-config\* %APPDATA%\Zed /E /H /C /I

3. Restart Zed to apply the configurations.

## **Contributing**
If you have suggestions or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

1. **Fork the repository.**

2. **Create a new branch:**
   ```bash
   git checkout -b feature/your-feature
3.Commit your changes:
         
    git commit -m "Add your feature"
4. Push to the branch:

       git push origin feature/your-feature
 5. Open a pull request.
