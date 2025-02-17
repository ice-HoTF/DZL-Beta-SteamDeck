# DZL - A Simple DayZ Mod Launcher for Linux
\
 **Beta released 16/02/2025**
\
\
By: ice_hotf
\
\
Tested with Debian 12.
\
\
\
**FLATPAK STEAM NOT SUPPORTED!**
This script only works with the official steam package: https://wiki.debian.org/Steam
\
\
\
This script will wait for user input and automatically identify missing mods, download them and launch DayZ with the mods. 
This script will also allow you to delete mods, save shortcut script or an alias in the terminal interface.
Just follow the instructions in the terminal window
\
\
This script supports modded servers and vanilla servers.
\
\
\
\
**How To:**
\
\
\
1: Extract 'DZL-Beta-Linux-main.zip' to your '/home/$USER' Directory.
\
\
2: Install DZL by running 'install_DZL.sh' in the Terminal:
sh /home/$USER/DZL-Beta-Linux-main/install_DZL.sh
\
\
3: Run DZL by Opening the Application Menu Shortcut 'DZL' or By Terminal Command: bash /home/$USER/DZL/DZL.sh
\
\
\
\
Video: How To Setup and Launch DZL:
https://youtu.be/RQ1DCVzzKxw
\
\
\
\
Join Server:
\
\
![join_server_1](https://github.com/user-attachments/assets/6ec5261a-aed7-4f57-ad87-721ffee2bd58)
\
\
Add Favorite:
\
\
![add_favorite](https://github.com/user-attachments/assets/bda435ef-ce73-4eac-9d0e-c721d347d628)
\
\
Join Favorite:
\
\
![join_favorite](https://github.com/user-attachments/assets/419abb14-c5ad-4e40-92d9-0454825296f9)
\
\
Remove Favorite:
\
\
![remove_favorite](https://github.com/user-attachments/assets/30ff3c24-fd89-4919-a65e-d58349de3783)
\
\
Remove From Specific Server:
\
\
![remode_mods_this_server](https://github.com/user-attachments/assets/46a232fd-ed2b-4123-9df6-413d5135fd88)
\
\
Remove All Mods:
\
\
![remove_all_mods](https://github.com/user-attachments/assets/54d2fa7f-20fa-495e-9d99-3ac86cbec6f2)
\
\
\
\
![dzl](https://github.com/user-attachments/assets/24a04856-76ee-494d-a0a3-9f7116fb1f3e)
\
\
Add DZL as a Application Entry and Open it as an Application: 
\
This is automatically done through the 'install_DZL.sh' script, but this is how yoo do it manually:
\
\
1: Copy 'DZL.desktop' to /home/$USER/.local/share/applications/ and in the Terminal like this:
cp /home/$USER/DZL-Beta-Linux-main/DZL.desktop /home/$USER/.local/share/applications/DZL.desktop
\
\
2: Copy the .png-icon to the '/usr/share/icons' folder in the Terminal like this:
sudo cp /home/$USER/DZL-Beta-Linux-main/DZL/dzl.png /usr/share/icons/
\
\
\
\
FAQ:
I can't join the server:
- Restart Steam if you can't join the server and try again. 
- On heavily modded servers, steam once in a while glitches right after downloading the mods and. A steam restart solves it.
\
\
\
\
Dependencies:
\
\
gawk
\
\
curl
\
\
jq
\
\
