# INSTALLATION :-
# For Windows Theme.
(1) Download Windows-Main theme file either by cloning this repository or from release section.

(2) Once downloaded, you will find Windows folder inside it simply copy and paste it to /boot/grub/themes/ directory.

(3) Then edit /etc/default/grub using any text editor or filemanager and add :
GRUB_THEME=/boot/grub/themes/Windows/theme.txt

(4) Then copy paste menu.cfg file present in Windows-Main folder to /boot/grub/

(5) Also copy paste Menu script file present in Windows-Main folder to /etc/grub.d/

(6) Then simply run chmod +x /etc/grub.d/Menu command in terminal

(7) Now simply set env variable using the command :
    sudo grub-editenv - set config_file=menu.cfg 
    
(8) Everything done just simply update grub by :
    sudo update-grub
           or
    sudo grub-mkconfig -o /boot/grub/grub.cfg 

# For other themes
(1) Download your favourite theme either by cloning this repository or from release section.

(2) Copy the downloaded theme folder to /boot/grub/themes/ directory.

(3) Then edit  /etc/default/grub using any text editor or filemanager.

(4) And add : 
    GRUB_THEME=/boot/grub/themes/(theme-name)/theme.txt
            don't forget to replace (theme-name) with your real theme name.
 
(5) Update grub by:  
    sudo update-grub
           or
    sudo grub-mkconfig -o /boot/grub/grub.cfg 

# Minimal
![Minimal](https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/7fab7ba5-9008-4283-8b27-428b7168405c)

# Cool - Aesthetic - Stylish
![cool](https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/85dc9a2d-42a7-4ad3-9f71-c2a0ee57669c)

# WINDOWS - Preview
https://github.com/MrVivekRajan/Grub-Themes/assets/85994908/92712653-e448-4ad5-a4c3-56401d786e7b

<h4> <span>· </span> <a href="https://github.com/MrVivekRajan/Grub-Themes/"> from </a> <span> · </span> <a href="https://github.com/MrVivekRajan/Grub-Themes/issues"> owner </a> </h4>
