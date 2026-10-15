# ADEP

A Windows-based administration utility designed to simplify common IT support, remote troubleshooting, software deployment, and Active Directory tasks through a single graphical interface.

Built with PowerShell and Sapien PowerShell Studio, the tool brings frequently used administrative operations together in one place, reducing the need to remember and run separate commands for everyday support tasks.

### Features

* **Remote Software Deployment** — Deploy EXE, MSI, batch, command, and PowerShell installers to remote Windows computers. Supports predefined installation jobs, custom command-line arguments, secondary commands, progress monitoring, and remote installation output.
* **Centralized Installation Jobs** — Load reusable deployment configurations from CSV files, including installer paths, commands, and job-specific notes.
* **Remote Computer Access** — Check computer connectivity, resolve IP addresses, open administrative file shares, and retrieve system information for troubleshooting.
* **Process Management** — View running processes on remote computers and terminate selected processes when necessary.
* **Remote User Sessions** — Identify active user sessions and initiate remote session shadowing with an interactive confirmation prompt.
* **Active Directory Management** — Review computer or user account group memberships, copy group assignments from another account, and add accounts to specific groups.
* **Remote Administration Tools** — Quickly access remote Event Viewer, Group Policy Editor, and Registry Editor workflows, including enabling the Remote Registry service when needed.
* **User and Profile Utilities** — Access additional tools for reviewing remote users and user profiles.
* **Live Feedback and Logging** — Display command output, remote installer logs, progress indicators, and diagnostic messages directly in the interface.

### Intended Use

Designed for IT administrators working in managed Windows environments, particularly domain-based networks where remote administration and Active Directory integration are available.

Administrative permissions, network connectivity, Windows management services, and applicable PowerShell modules are required for certain operations.
