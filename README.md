# Algo-parser for Bejaia Students

This project is intended for students of the University of Bejaia for their "les td" (tutorials). It provides a basic setup for working with the Algo language, including a VS Code extension.

## 1. Installing Python

To run the parser and other tools, you need to have Python installed on your system.

### On Windows

1.  **Download the Python Installer:**
    *   Go to the official Python downloads page: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
    *   Download the latest stable release for Windows.

2.  **Run the Installer:**
    *   Open the downloaded `.exe` file.
    *   **Important:** Check the box that says "Add Python to PATH".
    *   Click "Install Now".

3.  **Verify the Installation:**
    *   Open a Command Prompt and type:
        ```bash
        python --version
        ```
    *   You should see the installed Python version.

### On macOS

The recommended way to install Python on macOS is using [Homebrew](https://brew.sh/), a package manager for macOS.

1.  **Install Homebrew:**
    *   Open the Terminal and run:
        ```bash
        /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
        ```

2.  **Install Python:**
    *   In the Terminal, run:
        ```bash
        brew install python
        ```

3.  **Verify the Installation:**
    *   Open a new Terminal window and type:
        ```bash
        python3 --version
        ```

### On Linux

Most Linux distributions come with Python pre-installed. You can check by opening a terminal and typing `python3 --version`. If it's not installed, you can install it using your distribution's package manager.

*   **For Debian/Ubuntu:**
    ```bash
    sudo apt update
    sudo apt install python3
    ```

*   **For Fedora/CentOS/RHEL:**
    ```bash
    sudo dnf install python3
    ```

## 2. Setting up VS Code

1.  **Install Visual Studio Code:**
    *   Download and install VS Code from the official website: [https://code.visualstudio.com/](https://code.visualstudio.com/)

2.  **Install the Python Extension:**
    *   Open VS Code.
    *   Go to the Extensions view (Ctrl+Shift+X).
    *   Search for "Python" and install the extension published by Microsoft.

3.  **Install the Algo Language Extension:**
    *   The file `algo-language-features-1.0.0.vsix` in this folder is the extension for the Algo language.
    *   In VS Code, go to the Extensions view.
    *   Click on the "..." menu in the top-right corner of the Extensions view.
    *   Select "Install from VSIX..." and choose the `algo-language-features-1.0.0.vsix` file.

Now you are ready to work with Algo files in VS Code!
