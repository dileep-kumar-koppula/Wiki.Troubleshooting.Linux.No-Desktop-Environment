# No Desktop Environment / GUI Issue

## System updates

+ Updating, Cleaning system files

    ```bash
    sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
    ```

## Gnome Desktop Environment
    
+ Re-configurate Desktop Manager to Gnome-Desktop-Manager

    ```bash
    sudo dpkg-reconfigure gdm3
    ```

## Services

+ Restarting the Services

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

## Optional - Start Gnome-Desktop-Manager from `tty` Sessions

+ Try this, if you want gnome session from tty session

    ```bash
    sudo /etc/init.d/gdm3 start
    ```

## Install Gnome

+ Installing

    ```bash
    sudo apt install --reinstall gnome-session gnome-shell gdm3* gnome-terminal -y
    ```

## System updates

+ Updating, Cleaning system files

    ```bash
    sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
    ```
