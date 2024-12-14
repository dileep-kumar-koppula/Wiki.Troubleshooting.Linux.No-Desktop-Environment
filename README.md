# No Desktop Environment / GUI Issue

## Gnome Desktop Environment

+ Re-install services

    ```bash
    sudo apt install --reinstall gdm3 gnome-terminal -y
    ```

+ Install required services

    ```bash
    sudo apt install gnome-shell gnome-shell-extension-manager gdm3* -y
    ```

+ Re-configurate Desktop Manager to Gnome-Desktop-Manager

    ```bash
    sudo dpkg-reconfigure gdm3
    ```

+ Services

    ```bash
    sudo systemctl enable gdm3
    ```

    ```bash
    sudo systemctl status gdm3
    ```

    ```bash
    sudo systemctl start gdm3
    ```
    
    ```bash
    sudo systemctl status gdm3
    ```

## Start Gnome-Desktop-Manager from `tty` Sessions

+ Try this, if you want gnome session from tty session

    ```bash
    sudo /etc/init.d/gdm3 start
    ```

## System updates

+ Updating, Cleaning system files

    ```bash
    sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
    ```

## Install Gnome

+ Installing

    ```bash
    sudo apt install gnome-session gnome-shell gnome-shell-extension-manager gdm3* gnome-terminal -y
    ```
