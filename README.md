if you are plannig on codeing with this for the fyp-vs-studio-addon visit https://github.com/gamminglord2012/fyp-vs-studio-addon

FPY & FCON
Overview
FPY and FCON are custom tools and file formats designed to extend Python functionality for script handling and configuration management.

FPY allows you to create and run .fpy files that integrate seamlessly with Python.

FCON is used for managing custom file extensions and configuration files.

Once installed, these tools make it easier to manage and execute custom Python-like scripts and configuration files with unique extensions.

Features
FPY: Custom Python-like scripting language with the .fpy extension.

FCON: Custom file association tool to manage .fpy and .fcon files.

Easy installation and setup with an executable installer.

Supports managing custom scripts and configurations through fpy and fcon commands.

Installation
1. Download the Installer
FPY and FCON are packaged with an easy-to-use installer.

Download the installer from this repository or from the release section.

2. Run the Installer
Locate and double-click the unins000.exe installer file.

Follow the on-screen instructions to install FPY and FCON on your system.

The installer will automatically configure everything, including:

File associations for .fpy and .fcon files.

Adding the fpy and fcon commands to your system's PATH.

Usage
Running .fpy Scripts
Once installed, you can easily run .fpy scripts with the fpy command:

bash
fpy <path_to_your_file>.fpy
Example:

bash
fpy D:/scripts/example.fpy
This will execute the .fpy script just like running a regular Python file.

Managing File Extensions with FCON
FCON allows you to manage file extensions like .fpy and .fcon, and associate them with specific executables or actions.

File Association
You can configure .fcon files or link them with executables using the following command:

bash
fcon configure <path_to_your_fcon_file>.fcon
Linking File Types
Link a file extension to an executable:

bash
fcon link .fpy fpy_runner.exe
Uninstallation
If you need to uninstall FPY and FCON, you can do so easily with the uninstaller included in the package.

Locate the Uninstaller: The installer also includes an uninstaller named unins000.exe.

Run the Uninstaller:

Navigate to the installation folder and run unins000.exe.

Follow the on-screen prompts to remove FPY and FCON from your system.

Contributing
We welcome contributions! If you'd like to improve FPY and FCON, feel free to submit issues, pull requests, or suggestions.

Fork the repository.

Create a new branch for your feature or bugfix.

Submit a pull request with your changes.

License
This project is licensed under the MIT License.

