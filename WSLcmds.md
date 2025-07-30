<br>1. Open Command Prompt: Press Win + R, type cmd, press Enter.

# Start WSL <br>
  <br>bash : $ ```wsl```
  <br>bash : $ ```wsl --version```


  <br>- Update system: ```sudo pacman -Syu```
  <br>- Install package: ```sudo pacman -S <package>```
  <br>- Remove package: ```sudo pacman -R <package>```
  <br>- Remove unused dependencies: ```sudo pacman -Rns $(pacman -Qtdq)```
  <br>- Search for package: ```pacman -Ss <keyword>```
  <br>- List installed packages: ```pacman -Q```
  <br>- Clean package cache: ```sudo pacman -Sc```
  <br>- Check for broken dependencies: ```sudo pacman -Dk```
  <br>- Start service: ```sudo systemctl start <service>```
  <br>- Enable service on boot: ```sudo systemctl enable <service>```
  <br>- Check service status: ```systemctl status <service>```
  <br>- Reboot: ```sudo reboot```
  <br>- Shutdown: ```sudo poweroff```
  <br>- View logs: ```journalctl -xe```
  <br>- Update mirrorlist: ```sudo pacman -Syy```

  **Uninstallation of Linux-Distro**
  <br>-Open PowerShell as Administrator.
  <br>-Run: ```wsl --list``` to view installed distros.
  <br>-Run: ```wsl --unregister <DistroName>``` (replace <DistroName> with the distro, e.g., Ubuntu, archlinux).
  <br>-Open Settings > Apps > Installed Apps.
  <br>-Search for the distro, click it, select Uninstall.
  <br>-Restart computer.
  
  <br>-
  
  
  
