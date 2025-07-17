1. Open Command Prompt: Press Win + R, type cmd, press Enter.

Start WSL<br>
  <br>bash : $ wsl
  <br>bash : $ wsl --version
  
Update system: sudo pacman -Syu
Install package: sudo pacman -S <package>
Remove package: sudo pacman -R <package>
Remove unused dependencies: sudo pacman -Rns $(pacman -Qtdq)
Search for package: pacman -Ss <keyword>
List installed packages: pacman -Q
Clean package cache: sudo pacman -Sc
Check for broken dependencies: sudo pacman -Dk
Start service: sudo systemctl start <service>
Enable service on boot: sudo systemctl enable <service>
Check service status: systemctl status <service>
Reboot: sudo reboot
Shutdown: sudo poweroff
View logs: journalctl -xe
Update mirrorlist: sudo pacman -Syy
