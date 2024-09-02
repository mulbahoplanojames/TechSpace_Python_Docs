---
sidebar_position: 1
---

# Installation

Before we dive into Python programming, it's essential to ensure that Python is installed on your system. This section provides step-by-step instructions for installing Python on Windows, macOS, and Linux. We'll also cover how to verify your installation to ensure everything is set up correctly.

### 2.1 Windows

To install Python on a Windows system, follow these steps:

1. **Visit the Official Python Website**  
   Open your web browser and go to the official Python website: [python.org](https://www.python.org/).

2. **Navigate to the Downloads Section**  
   Once on the website, click on the "Downloads" tab in the navigation bar. The website should automatically detect that you are using Windows and suggest the latest version of Python compatible with your system.

3. **Download the Latest Python Installer**  
   Click the download button to download the latest Python installer for Windows. The installer will be a `.exe` file.

4. **Run the Installer**  
   Locate the downloaded installer file (usually in your "Downloads" folder) and double-click it to run the installer.

5. **Check "Add Python to PATH"**  
   During the installation process, you'll see an option to "Add Python to PATH." **Ensure this box is checked**. This step is crucial as it allows you to run Python from the command line without needing to specify the full path to the Python executable.

6. **Select "Install Now"**  
   Click the "Install Now" button to proceed with the installation. The installer will install Python, along with pip (Python's package manager), and other necessary tools.

7. **Verify Installation**  
   After the installation is complete, you can verify that Python is installed correctly. Open the Command Prompt (you can search for "cmd" in the Start menu) and type:

   ```bash
   python --version
   ```

### 2.2 MacOS

To install Python on a MacOS system, follow these steps:

1. **Visit the Official Python Website**  
   Open Safari or your preferred web browser and go to the official Python website: [python.org](https://www.python.org/).

2. **Navigate to the Downloads Section**  
   Click on the "Downloads" tab. The website should detect that you are using macOS and offer the latest version of Python compatible with your system.

3. **Download the Latest Python Installer**  
   Click the download button to download the latest Python installer for Windows. The installer will be a `.exe` file.

4. **Run the Installer**  
   Click the download button to get the latest Python installer for macOS. The file will be a .pkg file.

5. **Run the Installer Package**  
   Open the downloaded .pkg file to start the installation process. The installer will guide you through the installation steps.

6. **Follow the Installation Wizard**  
   Proceed through the installation wizard by following the on-screen instructions. The installer will take care of placing Python in the appropriate directories and setting up your system.

7. **Verify Installation**  
   To ensure Python is correctly installed, open the Terminal (you can find it in the Applications > Utilities folder) and type:

   ```bash
   python3 --version
   ```

### 2.3 Linux

    Most Linux distributions come with Python pre-installed, but it may not be the latest version. Here's how to check if Python is installed and how to install or upgrade it if necessary.

1. **Check Python Installation**  
    Open a terminal and type:

   ```
   python --version
   ```

   or

   ```
   python3 --version
   ```

This command should return the version number of Python installed on your system. If Python is not installed, or if you need to install Python 3, proceed with the next steps.

2. **Install Python Using Package Manager**  
   To install Python on Ubuntu (or other Debian-based distributions), use the following commands:

```
sudo apt-get update
sudo apt-get install python3
```

For other distributions, use the equivalent package manager commands:

- Fedora:

```
sudo dnf install python3
```

- And for Arch Linux:

```
sudo pacman -S python
```

3. **Verify Installation**  
   After installation, verify that Python is correctly installed by typing:

```
python3 --version
```
