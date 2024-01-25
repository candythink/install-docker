# Docker Installation Script for Ubuntu

This repository contains a Bash script for installing Docker on Ubuntu systems. The script automates the process of uninstalling old Docker versions, setting up the Docker repository, and installing the latest version of Docker.

## Prerequisites

- An Ubuntu-based system.
- Sudo privileges.

## Installation

There are two ways to install Docker using this script:

### Method 1: Running the Script Directly from GitHub

1. Open your terminal.

2. Run the following command:
   ```bash
   curl -sSL https://raw.githubusercontent.com/candythink/install-docker/main/install_docker.sh | sudo bash
    ```
    This will download and execute the script directly from GitHub.

### Method 2: Downloading and Running the Script Locally
1. Download the install_docker.sh script from this repository.
2. Make the script executable:
    ```bash
   chmod +x install_docker.sh
    ```
3. Run the script:
    ```bash
    ./install_docker.sh
    ```
After installation, you may need to log out and log back in for the group changes to take effect, or start a new shell session using newgrp docker

## Important Notes

- **Security Warning**: Running scripts directly from the internet with `sudo` can be risky. Always ensure you trust the source and understand the script before executing it.
- Ensure you have `sudo` privileges before running the script.
- The script will prompt for your password when executing commands requiring `sudo` privileges.
- This script is designed specifically for Ubuntu systems. Compatibility with other distributions is not guaranteed.

## License

- **Free**

## Contributing

Contributions to this script are welcome. Please submit pull requests or issues through the repository.

