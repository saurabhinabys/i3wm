# i3wm Config personal
Collected from projects; 
https://archbang.org/

https://gitlab.com/dwt1/dotfiles/-/blob/master/.config/polybar/config

Applications needed;
yay -S lightdm lightdm-webkit2-greeter 

yay -S i3-gaps i3lock-fancy lxappearance picom polybar dunst rofi dmenu xfce4-power-manager network-manager-applet kdeconnect transmission-gtk bluberry

Manually add your user to group rfkill for bluetooth toggle to work properly;
sudo usermod -aG rfkill $USER
