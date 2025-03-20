Виконала самостійно Слобожан Софія РПЗ-23А
# СРС_WORK-CASE №4
## Task 1: Definitions of "Package" and "Repository"
# Package

# A package is an archive containing software that may include:
  Executable files
  Libraries
  Configuration files
  Other necessary resources for the program's operation
  
# Packages typically have a specific format, depending on the package manager, e.g.,:
  .deb for Debian/Ubuntu
  .rpm for Red Hat/Fedora
  
# Packages contain metadata describing:
  The program's name and version
  Dependencies
  Other important data

# Repository
  A repository is a centralized storage for packages that:
  Allows users to download and install software
  Can be official (supported by the distribution) or unofficial (created by community or third   parties)
  Provides access to packages, their updates, and dependencies
  
# Package Managers
  # APT (Advanced Package Tool)
    Used in Debian and Ubuntu
    Facilitates easy installation, updating, and removal of packages
   # Key commands:
      apt-get
      apt-cache
      apt

      
# YUM (Yellowdog Updater, Modified)
  Used in Red Hat, CentOS, and Fedora
  Supports automatic dependency management
   # Key commands:
    yum install
    yum update
    yum remove
    DNF (Dandified YUM)

# A newer version of YUM with improved performance and functionality
  Key commands:
  dnf install
  dnf update
  dnf remove
  
# Pacman
    Package manager for Arch Linux
    Supports a simple command syntax and dependency management
    Key commands:
    pacman -S
    pacman -R
    pacman -Sy
    
# Zypper
    Package manager for openSUSE
    Manages repositories and dependencies
    
   ### Key commands:
    zypper install
    zypper remove
    zypper update

 #   Task 2: 
 
  Using APT in Linux Mint
  
#  1. Update the Package List

    Use the command: sudo apt update
    This refreshes the list of available packages and their versions.

![image](https://github.com/user-attachments/assets/59ab8a04-8cd7-4191-ae0a-a3229767a6f4)

# 2. Search for a Package

    You can search for a package using the command: apt search [package_name]
    This will display a list of matching packages.
    
   ![image](https://github.com/user-attachments/assets/221b7bdd-f8d2-4e94-8d95-14281dd253dc)

# 3. Install a Package

    To install a package, use: sudo apt install [package_name]
    This command downloads and installs the specified package.

![image](https://github.com/user-attachments/assets/fbd9a6fe-4148-4419-9fcd-d1206e0d14d5)

# 4. View Package Information

    To view details about a package, use: apt show [package_name]
    This command displays the package description, version, and other metadata.
    
![image](https://github.com/user-attachments/assets/583e1b90-642c-4d19-bc10-b7d61551b739)

# 5. Remove a Package
    To uninstall a package, use: sudo apt remove [package_name]
    This command removes the specified package from your system.
    
# 6. Clean Up Unused Packages
    Use the command: sudo apt autoremove
    This removes packages that were automatically installed to satisfy dependencies for other       packages and are no longer needed 

# 7. Add a New Repository

    To add a repository, you can edit /etc/apt/sources.list or use:
     sudo add-apt-repository [repository_url]

![image](https://github.com/user-attachments/assets/12e6803e-1282-4b21-b072-0be1a575a65b)
  This allows you to install software from additional sources.


# 8. Installing Software via Graphical Interface
  You can use the "Software Manager" in Linux Mint:
    Open "Software Manager"
    Search for the desired program
    Click "Install" to add it to your system..

### TASK 3.

# Installation Instructions

# 1. Installing Python
   Command:
     sudo apt install python3
   
![image](https://github.com/user-attachments/assets/f424975c-92e2-4d4e-8279-8294e8d6f75c)

# 2. Installing GIMP
Command:
   sudo apt install gimp
 
![image](https://github.com/user-attachments/assets/256ebb9c-5204-4207-b977-c7784579c187)

# 3. Installing LibreOffice (Office Suite)
Command:
  sudo apt install libreoffice
![image](https://github.com/user-attachments/assets/f4e77e5e-c4a2-41fc-8671-ac298fed953a)

### TASK 4.

# Installing New Applications via Graphical App Stores

In a graphical environment, you can utilize:

Ubuntu Software Center (for Ubuntu): Open the application, search for the desired package (e.g., VLC or Python), and click "Install."

GNOME Software: A similar store for distributions that use GNOME. You can search for applications, browse categories, and install them with a single click.

# KDE Discover: 
For distributions based on KDE, this tool allows for easy browsing and installation of new software.

# Conclusion
During this work, the fundamental concepts of package management and repositories in Linux were explored. It was established that packages are archives containing the necessary components for software installation, while repositories serve as centralized storage for managing software updates and installations.

The study covered popular package managers such as APT, YUM, DNF, Pacman, and Zypper, along with examples of essential commands for their usage. The practical part focused on using APT in Linux Mint, including updating the package list, searching for packages, installing, viewing package details, removing software, and cleaning up unnecessary dependencies.
