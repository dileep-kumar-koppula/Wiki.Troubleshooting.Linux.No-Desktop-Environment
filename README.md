# No Desktop Environment

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

    ```bash
    sudo /etc/init.d/gdm3 start
    ```

## Remove unwanted Apps

    ```bash
    sudo apt remove gnome-weather gnome-contacts totem* gnome-maps gnome-mahjongg aisleriot gnome-2048 five-or-more four-in-a-row quadrapassel rhythmbox* tali swell-foop shotwell* hitori gnome-klotski gnome-chess gnome-mines gnome-music lightsoff gnome-robots gnome-nibbles gnome-sudoku gnome-tetravex gnome-taquin iagno* evolution* gdm* -y
    ```

## System updates

+ Updating, Cleaning system files

    ```bash
    sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
    ```

## Install Gnome

+ Installing

    ```bash
    sudo apt install gnome-session gnome-shell gnome-shell-extension-manager gdm3* -y
    ```
