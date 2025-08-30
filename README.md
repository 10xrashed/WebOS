
# WebOS: A Browser-Based Linux-like Desktop Environment

[![GitHub Stars](https://img.shields.io/github/stars/10xrashed/WebOS?style=social)](https://github.com/10xrashed/WebOS/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/10xrashed/WebOS?style=social)](https://github.com/10xrashed/WebOS/network/members)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## Table of Contents

-   [About WebOS](#about-webos)
-   [Features](#features)
    -   [Core OS Experience](#core-os-experience)
    -   [Integrated Applications](#integrated-applications)
    -   [Customization & Utilities](#customization--utilities)
-   [Getting Started](#getting-started)
-   [Usage](#usage)
    -   [Boot & Login](#boot--login)
    -   [Desktop Interaction](#desktop-interaction)
    -   [Terminal Commands](#terminal-commands)
    -   [File System Persistence](#file-system-persistence)
-   [Technical Details](#technical-details)
-   [Future Enhancements (Ideas)](#future-enhancements-ideas)
-   [Contributing](#contributing)
-   [License](#license)
-   [Credits](#credits)

---

## About WebOS

WebOS is an ambitious, single-file web application that brilliantly simulates a full-fledged Linux-like desktop environment directly in your web browser. Built entirely with HTML, CSS, and vanilla JavaScript, it offers a surprisingly rich and interactive user experience, complete with a boot sequence, a login screen, and a wide array of functional, albeit simulated, applications.

Dive into a retro-futuristic desktop experience, explore a virtual file system, execute a vast set of Linux-like commands in the terminal, play classic games, and customize your workspace – all without leaving your browser tab!

## Features

WebOS is packed with a multitude of features designed to mimic a real operating system:

### Core OS Experience

*   **Realistic Boot Sequence:** A dynamic boot screen with progress indicators and text messages.
*   **User Login System:** A simple login screen with default `user`/`password` credentials.
*   **Persistent User Data:** Your file system changes, themes, and high scores are saved locally using `localStorage`.
*   **Desktop Environment:**
    *   Interactive desktop icons with double-click to open applications.
    *   Right-click context menu for quick actions (open terminal, file explorer, refresh, settings, logout).
    *   Dynamic notifications system for system alerts and app feedback.
*   **Window Management:**
    *   Draggable windows with minimize, maximize, and close controls.
    *   Taskbar integration showing active applications and allowing focus switching.
    *   Windows retain position and size (unless maximized).
*   **Start Menu:** A classic-style start menu to launch all available applications.
*   **System Tray:** Displays time, date, and simulated system status indicators (volume, network, battery).

### Integrated Applications

1.  **🐧 WebOS Terminal:**
    *   **40+ Linux-like Commands:** Includes `ls`, `cd`, `pwd`, `cat`, `echo`, `clear`, `whoami`, `date`, `uname`, `mkdir`, `touch`, `rm`, `cp`, `mv`, `history`.
    *   **Advanced Commands:** Simulated `sudo`, `ping`, `ifconfig`, `ps`, `top`, `df`, `free`, `uptime`, `grep`, `find`, `wget`, `curl`, `git`, `python`, `node`, `npm`, `docker`.
    *   **Interactive Utilities:** Simulated `nano`, `vim` (opens in Code Editor for `nano`), `htop` (opens System Monitor).
    *   **Fun Commands:** `neofetch` (displays glorious ASCII art penguin), `cowsay`, `fortune`, `figlet`.
    *   Command history with arrow keys and tab auto-completion.
    *   Full path resolution (`~`, `..`, absolute/relative paths).
    *   Persistent virtual file system.

2.  **📁 File Explorer:**
    *   Browse a simulated hierarchical file system.
    *   Quick access sidebar (Home, Documents, Downloads, Pictures, Music).
    *   Toolbar for navigation (Back, Up, Refresh) and creating new folders.
    *   Double-click to open folders or view files in the Code Editor.

3.  **🌐 Web Browser:**
    *   Simulated browser with address bar and navigation controls.
    *   Internal "web pages" including a WebOS homepage, tech news, search engine, and social hub.
    *   Displays current time and simulated system information.

4.  **📝 Code Editor:**
    *   Basic text editing functionality with a toolbar (New, Open, Save, Format).
    *   Line and character count statistics.
    *   Opens and saves files to the virtual file system (specifically, `/home/user/Documents`).
    *   Simulated language selection.
    *   Supports common keyboard shortcuts (Ctrl+S, Ctrl+O, Ctrl+N).

5.  **📊 System Monitor:**
    *   Visualizes simulated CPU, Memory, and Disk usage with progress bars.
    *   Displays system information (OS, Kernel, Desktop, User, Uptime, Processes, Load Average).
    *   Shows simulated network activity (status, IP, download/upload speeds).

6.  **🎮 Games Hub:**
    *   **Tic-Tac-Toe:** Play against a simple AI with win/lose/tie detection.
    *   **Snake Game:** A classic arcade game with a score counter and persistent high scores. Control with WASD or arrow keys.
    *   **Number Guessing Game:** Guess a number between 1 and 100 with feedback and hints.

7.  **🎵 Music Player:**
    *   Simulated music player with play/pause, previous, and next controls.
    *   Displays "Now Playing" and a placeholder playlist.

8.  **🔢 Calculator:**
    *   Fully functional basic arithmetic calculator (+, -, \*, /).
    *   Includes clear, clear entry, backspace, and decimal functions.

9.  **📧 Email Client:**
    *   Simulated inbox with pre-written emails (WebOS welcome, system updates, feature announcements).
    *   Folders for Sent, Drafts, and Trash.
    *   "Compose New Email" interface (simulated send/save draft).

10. **📅 Calendar:**
    *   Displays a navigable monthly calendar (month change simulated).
    *   Highlights the current day.
    *   Lists "Today's Events" with the ability to "Add Event" (simulated).

11. **⚙️ Settings:**
    *   Comprehensive settings panel with categories:
        *   **Appearance:** Change themes (Dark, Light, Retro, Neon) and wallpapers (5 gradient options). Toggle desktop icon visibility.
        *   **System:** Performance (animations, hardware acceleration), Startup (auto-login, boot screen), detailed System Information.
        *   **Accounts:** User profile management (avatar, password change - simulated), account security options.
        *   **Privacy:** Data collection options, option to clear all local data.
        *   **About WebOS:** Project version, build, features list, and system details.

12. **🗑️ Recycle Bin:**
    *   Simulated list of deleted files/folders.
    *   "Restore All" and "Empty Bin" functionality (simulated).
    *   Option to restore individual items (simulated).

### Customization & Utilities

*   **Themes:** Switch between Dark, Light, Retro, and Neon themes.
*   **Wallpapers:** Choose from 5 different gradient wallpapers.
*   **Keyboard Shortcuts:** Basic shortcuts for copy/paste (Ctrl+C/V) and terminal clear (Ctrl+L).

## Getting Started

To get WebOS up and running, follow these simple steps:

1.  **Save the Code:** Copy the entire HTML, CSS, and JavaScript code block provided and save it into a file named `index.html`.
2.  **Open in Browser:** Open the `index.html` file using any modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3.  **Boot Sequence:** Wait for the simulated boot sequence to complete.
4.  **Login:** Enter the default credentials:
    *   **Username:** `user`
    *   **Password:** `password`
    And click "Sign In".

You will then be greeted by the WebOS desktop!

## Usage

### Boot & Login

Upon opening `index.html`, you'll first see a boot screen. This simulates an OS startup. After a few seconds, the login screen will appear. Use `user` for the username and `password` for the password to access the desktop. Your login choice will affect the user context in the terminal and file system.

### Desktop Interaction

*   **Icons:** Double-click any desktop icon to launch its corresponding application.
*   **Windows:**
    *   Drag windows by their title bar.
    *   Click the `_` button to minimize, `[]` to maximize/restore, and `X` to close.
    *   Click on a window to bring it to the foreground (focus).
*   **Taskbar:** Click on an application icon in the taskbar to focus or restore a minimized window.
*   **Start Menu:** Click the "🐧 Start" button to open the start menu and browse all applications.
*   **Context Menu:** Right-click on the desktop background to open a context menu with quick actions.
*   **Notifications:** Keep an eye on the top-right corner for system notifications.

### Terminal Commands

The WebOS Terminal is a core feature.
*   **Launch:** Open the Terminal from the desktop icon or start menu.
*   **Basic Interaction:** Type commands and press `Enter`.
*   **Help:** Type `help` to see a list of all available commands.
*   **System Info:** Try `neofetch` for a visually appealing system overview.
*   **File System:** Use `ls`, `cd`, `pwd`, `cat`, `mkdir`, `touch`, `rm`, `cp`, `mv` to navigate and manage your virtual files.
*   **Sudo:** Type `sudo` to enter a simulated superuser mode. Type `exit` to leave `sudo` mode.
*   **History:** Use the `Arrow Up` and `Arrow Down` keys to navigate through your command history.
*   **Autocomplete:** Press `Tab` to auto-complete commands.

### File System Persistence

All files and directories you create or modify within the WebOS environment (via the Terminal or File Explorer) are saved in your browser's `localStorage`. This means your virtual file system will persist even if you close and reopen the `index.html` page. The same applies to your chosen theme, wallpaper, and game high scores.

## Technical Details

*   **Single File:** The entire application is contained within a single `index.html` file, making it incredibly easy to deploy and share.
*   **Vanilla Stack:** Built purely with HTML, CSS, and JavaScript, demonstrating powerful web capabilities without frameworks.
*   **Client-Side Persistence:** Utilizes `localStorage` for all data persistence, ensuring a stateless server-side is not required.
*   **Simulated Environment:** All OS functionalities, applications, and system resources are simulated client-side. There is no actual backend or real operating system running.

## Future Enhancements (Ideas)

This project has immense potential for expansion. Here are some ideas for future development:

*   **Advanced File System:** Implement drag-and-drop for files/folders, more robust permissions, and a Recycle Bin that actually holds deleted items.
*   **Multi-user Support:** Expand the login system to support multiple user profiles with independent file systems.
*   **True Web Integration:** Utilize iframes or proxies within the browser app for actual external web browsing.
*   **Real-time System Stats:** Integrate with browser APIs (if available and secure) to show actual (or more sophisticated simulated) system resource usage.
*   **Expand Applications:**
    *   More playable games.
    *   A functional drawing application.
    *   Simple text-based adventure games in the terminal.
    *   More advanced features for existing apps (e.g., calculator memory, music player playlists, calendar event management).
*   **Package Manager Simulation:** A more interactive `apt` or `dnf` simulation for installing "new" applications or tools.
*   **Customization:** Allow users to upload their own wallpapers or custom themes.
*   **Networking:** Simulate a local network with other "WebOS" instances or services.
*   **Mobile Responsiveness:** Adapt the desktop environment for smaller screens and touch interactions.

## Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add new feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

Please ensure your code adheres to the existing style and conventions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Credits

*   **Original Author:** [10xrashed](https://github.com/10xrashed)
