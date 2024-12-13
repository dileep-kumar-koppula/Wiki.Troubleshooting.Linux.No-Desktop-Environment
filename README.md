# No Desktop Environment

## Gnome Desktop Environment

+ fgrge

    ```bash
    sudo systemctl disable gdm3
    sudo systemctl enable gdm3
    sudo systemctl start gdm3
    ```

```bash
sudo apt install --reinstall gdm3 gnome-terminal -y
sudo apt install gnome-shell gnome-shell-extension-manager gdm3* -y
sudo dpkg-reconfigure gdm3
sudo systemctl enable gdm3
sudo systemctl status gdm3
sudo systemctl start gdm3
sudo systemctl status gdm3
sudo /etc/init.d/gdm3 start
sudo apt remove gnome-weather gnome-contacts totem* gnome-maps gnome-mahjongg aisleriot gnome-2048 five-or-more four-in-a-row quadrapassel rhythmbox* tali swell-foop shotwell* hitori gnome-klotski gnome-chess gnome-mines gnome-music lightsoff gnome-robots gnome-nibbles gnome-sudoku gnome-tetravex gnome-taquin iagno* evolution* gdm* -y
sudo apt update ; sudo apt upgrade -y ; sudo apt dist-upgrade -y ; sudo apt autoremove -y ; sudo apt autoclean -y
sudo apt install gnome-session gnome-shell gnome-shell-extension-manager gdm3* -y
```

