WinBrew

Overview

WinBrew is a batch script that provides a command-line menu for performing various system tasks on Windows. It offers options to restart Windows Explorer, execute applications, run commands as SYSTEM, check user details, update the system, manage network settings, and shut down the computer.

Features

Restart Windows Explorer: Refreshes the Windows interface.

Run Applications: Launches specific programs.

Execute as SYSTEM: Runs commands with elevated privileges.

User Check: Displays user-related information.

Update: Triggers an update process.

Network Management: Checks and updates network settings.

Shutdown: Powers off the computer.

GodMode

GodMode is the installer for the WinBrew Custom Firmware (CFW), allowing users to quickly set up and integrate WinBrew on Windows.

How to Install

Installing the GodMode CFW is straightforward and takes approximately 1-5 minutes. Follow these steps to install the Custom Firmware on Windows:

Download the GodMode archive in your preferred language from the download channel or GitHub.

Extract the archive and run the God Mode Installer.bat file.

Follow the on-screen instructions:

Press any key.

Press i, then a random key.

Press c, then a random key.

Press u.

Windows Compatibility Check:

If you have Windows 8.1 or older, you can proceed to the app installation step.

If you have Windows 10 or later, continue with the following steps.

Install Windows Terminal:

If you haven't installed it yet, download and install "Windows Terminal" from the Microsoft Store.

Windows 11 users should have it pre-installed.

Configure Windows Terminal:

Click the downward-facing arrow at the top and select "Settings."

In the sidebar, scroll down and select "Add a New Profile" -> "New Empty Profile."

Set the following options:

Name: Profile 4

Command Line: X:\WinBrew.bat

Startup Directory: X:\

Save the settings.

Set Startup Profile:

In the sidebar, select "Startup" (if it does not appear, restart the program).

Choose Profile 4 as the startup profile.

Restart Windows Terminal:

Close and reopen Windows Terminal to boot directly into WinBrew.

Usage

Run WinBrew.bat by double-clicking the file or executing it in a Command Prompt.

Follow the on-screen menu and enter the corresponding number for the desired action.

Requirements

Windows operating system

Administrative privileges may be required for certain actions

Disclaimer

Use this script at your own risk. Ensure you understand the actions before executing them, especially those requiring elevated privileges.

License

This project is released under an open-source license. Feel free to modify and distribute it as needed.

