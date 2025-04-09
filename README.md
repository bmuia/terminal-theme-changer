# Terminal Theme Changer 🎨

A simple Bash script for changing your Ubuntu terminal prompt theme. It allows users to easily switch between different color schemes for their terminal prompt, giving their terminal a fresh, personalized look.

## Features

- Easily change your terminal prompt colors using a menu-driven Bash script.
- Four themes available: `ubuntu`, `green`, `matrix`, and `red`.
- The script modifies the `.bashrc` file to save your selected theme.

## Installation

To install the Terminal Theme Changer, follow the steps below:

### Using the `.deb` Package:

1. Download the `.deb` package from the **Releases** section of this GitHub repository.
   
2. Install the package by running:

   ```bash
   sudo dpkg -i terminal-theme-changer-deb.deb
   ```

## After installation, you can run the theme changer script.
### Usage
Once the package is installed, you can change your terminal theme by simply running the following command:

```bash
themechanger
```

You will be presented with a menu to choose the theme. The available themes are:
# Available Themes:
- **ubuntu** → Purple + Blue
- **green** → Green + Yellow
- **matrix** → Hacker-style green text
- **red** → Red + Blue


## Customization
The Terminal Theme Changer updates your PS1 variable in the .bashrc file to apply the theme. If you wish to manually change your theme, you can modify the PS1 variable by following these steps:
1. Open your terminal and edit .bashrc:
```bash
nano ~/.bashrc
```
2. Look for the PS1 variable, and change its value to one of the preset themes. For example:
```bash
export PS1="\[\e[1;32m\]\u@\h:\[\e[1;33m\]\w\$ \[\e[0m\]"
```
3. Save the file, and then run:
```bash
source ~/.bashrc
```
## Uninstalling
If you no longer wish to use the Terminal Theme Changer, you can uninstall it by running:
```bash
sudo dpkg -r terminal-theme-changer
```

## Contribution
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements, bug fixes, or new theme ideas are welcome!